#### Test 83591764f116baa_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-09 17:12:13.020   977   977 I kickstart: STATUS: Received file 'm9kefs2'
09-09 17:12:13.020   977   977 I kickstart: STATUS: 950272 bytes transferred in 0.994622 seconds
09-09 17:12:13.020   977   977 I kickstart: STATUS: Successfully downloaded files from target 
09-09 17:12:13.021   977   977 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,09-09 17:12:13.025   977   977 I kickstart: STATUS: Sahara protocol completed
09-09 17:12:13.423   871  1314 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
09-09 17:12:13.744  3763  3763 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 17:12:13.749  3763  3763 D AndroidRuntime: CheckJNI is OFF
09-09 17:12:13.785  3763  3763 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 17:12:13.828  3763  3763 I Radio-JNI: register_android_hardware_Radio DONE
09-09 17:12:13.850  3763  3763 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 17:12:13.854   871  1964 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 17:12:13.910  2001  2013 W SearchService: Abort, client detached.
09-09 17:12:13.916  3763  3763 D AndroidRuntime: Shutting down VM
09-09 17:12:13.924  2001  2350 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ea925fb
09-09 17:12:13.925  2001  2358 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-09 17:12:13.925  2001  2001 I HotwordDetector: Closing mic
09-09 17:12:13.938   871  1414 I ActivityManager: Start proc 3773:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 17:12:13.972   376  2361 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 17:12:13.973   376  2361 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 17:12:13.981   376  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 17:12:13.983  2001  2355 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-09 17:12:13.984  2001  2357 I MicroRecognitionRnrImpl: Detection finished
09-09 17:12:14.017  3773  3773 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 17:12:14.043  3773  3773 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 17:12:14.062  3773  3773 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2880-2885)
09-09 17:12:14.062  3773  3773 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 17:12:14.080  3773  3773 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2dba8ef}
09-09 17:12:14.080  3773  3773 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 17:12:14.081  3773  3773 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 17:12:14.087  3773  3773 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 17:12:14.089  3773  3773 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 17:12:14.115  3773  3773 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 17:12:14.139  3773  3773 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 17:12:14.139  3773  3773 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 17:12:14.140  3773  3773 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 17:12:14.140  3773  3773 I Adreno  : Build Date                       : 10/20/15
09-09 17:12:14.140  3773  3773 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 17:12:14.140  3773  3773 I Adreno  : Local Branch                     : M14
09-09 17:12:14.140  3773  3773 I Adreno  : Remote Branch                    : 
09-09 17:12:14.140  3773  3773 I Adreno  : Remote Branch                    : 
09-09 17:12:14.140  3773  3773 I Adreno  : Reconstruct Branch               : 
,09-09 17:12:14.219   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@85af036:true
,09-09 17:12:14.291  3773  3773 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 17:12:14.308  3773  3773 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-09 17:12:14.401  3773  3814 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 17:12:14.414  3773  3799 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-09 17:12:14.477  3773  3814 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 17:12:14.561   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +647ms
,09-09 17:12:14.572  1878  1878 I Keyboard.Facilitator: onFinishInput()
,09-09 17:12:14.687  3773  3773 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3773
,09-09 17:12:14.745   871  1687 I ActivityManager: Killing 3215:com.google.android.gm/u0a78 (adj 15): empty #17
,09-09 17:12:14.815   871  1687 I ActivityManager: Killing 3125:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-09 17:12:14.831  3773  3773 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 17:12:15.061  3773  3816 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1700792016
,09-09 17:12:15.074  3773  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 17:12:15.074  3773  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 17:12:15.074  3773  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 17:12:15.074  3773  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 17:12:15.074  3773  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 17:12:15.074  3773  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7299bf2 added. We now have 1 listener(s)
,09-09 17:12:15.078  3773  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-09 17:12:15.078  3773  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 17:12:15.079  3773  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 17:12:15.079  3773  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:15.083  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 17:12:15.083  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 17:12:15.083  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 17:12:15.083  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-09 17:12:15.083  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 17:12:15.083  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 17:12:15.083  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 17:12:15.083  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 17:12:15.083  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 17:12:15.083  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 17:12:15.083  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 17:12:15.083  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 17:12:15.083  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 17:12:15.083  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-09 17:12:15.084  3773  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1f21f9 added. We now have 1 listener(s)
09-09 17:12:15.084  3773  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:12:15.088   871  1315 D WifiService: New client listening to asynchronous messages
,09-09 17:12:15.089  3773  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:12:15.090  3773  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 17:12:15.090  3773  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 17:12:15.090  3773  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 17:12:15.091  3773  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 17:12:15.098  3773  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:12:15.098  3773  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-09 17:12:15.110  3773  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 17:12:15.110  3773  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:15.110  3773  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:15.110  3773  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:15.110  3773  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:15.110  3773  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:15.110  3773  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:15.110  3773  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:15.110  3773  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:12:15.110  3773  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 17:12:15.110  3773  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:12:15.111  3773  3816 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 17:12:15.112  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:15.114  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:15.301  3773  3773 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 17:12:16.172  3773  3824 W jxcore-log: Initializing JXcore engine
09-09 17:12:16.172  3773  3824 W jxcore-log: JXcore engine is ready
09-09 17:12:16.217  3824  3824 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-09 17:12:16.217  3824  3824 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9900]" dev="sockfs" ino=9900 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-09 17:12:16.217  3824  3824 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 17:12:16.217  3824  3824 W Thread-321: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[24457]" dev="sockfs" ino=24457 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-09 17:12:16.233  3773  3824 W jxcore-log: Starting JXcore engine
09-09 17:12:16.329  3773  3824 W jxcore-log: Platform android
09-09 17:12:16.329  3773  3824 W jxcore-log: 
09-09 17:12:16.329  3773  3824 W jxcore-log: Process ARCH arm
09-09 17:12:16.329  3773  3824 W jxcore-log: 
09-09 17:12:16.369  1524  1524 I ConfigService: onDestroy
09-09 17:12:16.540  3773  3824 I jxcore-log: JXcore Cordova bridge is ready!
09-09 17:12:16.540  3773  3824 I jxcore-log: 
09-09 17:12:16.540  3773  3824 W jxcore-log: JXcore engine is started
09-09 17:12:16.551  3773  3816 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-09 17:12:16.556  3773  3773 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-09 17:12:16.598  3500  3511 D Finsky  : [264] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
09-09 17:12:16.614  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 17:12:16.650  1524  2325 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-09 17:12:16.650  1524  2325 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-09 17:12:16.650  1524  2325 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 17:12:16.650  1524  2325 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-09 17:12:16.677  3500  3511 D Finsky  : [264] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-09 17:12:25.312   871   884 I ActivityManager: Waited long enough for: ServiceRecord{1e0db25 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,09-09 17:12:25.763  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 17:12:25.772  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 17:12:25.776  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 17:12:25.827  1524  3171 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 17:12:25.828  1524  3171 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 17:12:25.828  1524  3171 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 17:12:25.828  1524  3171 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 17:12:25.865  3500  3500 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 17:12:25.865  3500  3500 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 17:12:25.866  3500  3500 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-09 17:12:26.412  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 17:12:26.412  3773  3824 I jxcore-log: 
,09-09 17:12:26.415  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 17:12:26.415  3773  3824 I jxcore-log: 
,09-09 17:12:26.428  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:26.428  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:26.428  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:26.428  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:26.428  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:26.428  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:26.428  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:26.428  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:12:26.433  3773  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:12:26.435  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 17:12:26.435  3773  3824 I jxcore-log: 
,09-09 17:12:26.437  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 17:12:26.437  3773  3824 I jxcore-log: 
,09-09 17:12:26.953  3773  3824 D executeNativeTests: Running unit tests
,09-09 17:12:27.011  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 17:12:27.012  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 added. We now have 2 listener(s)
09-09 17:12:27.013  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 17:12:27.013  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:27.013  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:27.013  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:27.013  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 added. We now have 2 listener(s)
09-09 17:12:27.013  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:27.014  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:12:27.024  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:12:27.036  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:27.036  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:27.036  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:27.036  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:27.036  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:27.036  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:27.036  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:27.036  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:12:27.043  3773  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:12:27.044  3773  3824 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:12:27.053  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 17:12:27.055  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:27.057  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 17:12:27.057  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 17:12:27.064  3773  3824 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-09 17:12:27.067  3773  3824 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 17:12:27.067  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 17:12:27.067  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:12:27.068  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:12:27.069  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:12:27.071  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:27.071  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.071  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:12:27.075  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:12:27.075  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.075  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:27.076  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:27.076  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 removed from the list
09-09 17:12:27.076  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.076  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 removed from the list
,09-09 17:12:27.076  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.076  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.077  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.077  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:27.080  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.080  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.080  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.080  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.081  3773  3824 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 17:12:27.081  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.081  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.081  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:27.081  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.081  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.081  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.081  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.081  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.081  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.081  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.082  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.082  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.082  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.082  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:27.083  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.083  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.083  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.083  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 17:12:27.087  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 17:12:27.088  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 17:12:27.088  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 17:12:27.088  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 17:12:27.088  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 17:12:27.088  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-09 17:12:27.088  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 17:12:27.088  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 17:12:27.088  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 17:12:27.088  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 17:12:27.088  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 17:12:27.088  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 17:12:27.088  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.088  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.088  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:27.088  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.088  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.088  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.088  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.088  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.088  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.089  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.089  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.089  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.089  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.089  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.090  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.090  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.090  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.090  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.091  3773  3824 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 17:12:27.091  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:27.101  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:27.101  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:27.101  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:27.101  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:27.101  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:27.101  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:27.101  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:27.101  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:27.107  3773  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:27.107  3773  3824 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:27.107  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:27.107  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:12:27.107  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:12:27.107  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:27.107  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:12:27.120  3773  3824 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 17:12:27.120  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:12:27.121  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:27.131  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:27.132  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:12:27.134  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 17:12:27.135  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 17:12:27.137  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-09 17:12:27.141  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-09 17:12:27.142  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 17:12:27.142  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:12:27.143  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 17:12:27.144  3773  3824 D BluetoothAdapter: STATE_ON
09-09 17:12:27.150  2667  2679 D BtGatt.GattService: registerClient() - UUID=34a34684-65d4-49c3-ba69-8bc0e4484c2e
09-09 17:12:27.151  2667  2700 D BtGatt.GattService: onClientRegistered() - UUID=34a34684-65d4-49c3-ba69-8bc0e4484c2e, clientIf=5
09-09 17:12:27.152  3773  3785 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 17:12:27.153  2667  2678 D BtGatt.GattService: start scan with filters
09-09 17:12:27.157  2667  2703 D BtGatt.ScanManager: handling starting scan
09-09 17:12:27.157  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 17:12:27.158  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:12:27.158  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:12:27.158  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 17:12:27.159  2667  2703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
09-09 17:12:27.162  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:12:27.163  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 17:12:27.163  3773  3773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:12:27.166  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 17:12:27.166  2667  2700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 17:12:27.166  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:27.167  2667  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 17:12:27.171  3773  3824 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 17:12:27.173  2667  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 17:12:27.174  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:27.174  2667  2703 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 17:12:27.174  2667  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 17:12:27.175  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.175  3773  3824 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 17:12:27.175  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.175  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 17:12:27.175  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:12:27.175  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:12:27.176  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 17:12:27.176  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:12:27.176  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 17:12:27.176  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:12:27.177  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:12:27.177  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 17:12:27.177  3773  3824 D BluetoothAdapter: STATE_ON,
09-09 17:12:27.178  2667  2678 D BtGatt.GattService: stopScan() - queue size =1
09-09 17:12:27.178  2667  2801 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 17:12:27.179  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:27.179  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 17:12:27.179  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:12:27.179  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:12:27.179  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 17:12:27.180  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:12:27.180  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:12:27.180  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:12:27.181  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 17:12:27.181  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:27.182  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.182  3773  3773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:12:27.182  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.182  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:27.182  3773  3773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:12:27.182  3773  3773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:12:27.182  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.182  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.182  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.182  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.182  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.183  3773  3824 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 17:12:27.184  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:27.185  2667  2700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 17:12:27.185  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:27.189  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:27.189  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:27.189  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:27.189  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:27.189  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:27.189  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:27.189  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:27.189  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:12:27.191  2667  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 17:12:27.191  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:27.192  3773  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:12:27.192  3773  3824 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:12:27.192  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:27.192  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
,09-09 17:12:27.192  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 17:12:27.192  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:27.193  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 17:12:27.195  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:27.197  3773  3824 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 17:12:27.197  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:12:27.197  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:27.198  2667  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 17:12:27.199  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:27.199  2667  2703 D BtGatt.ScanManager: stopping BLe Batch
,09-09 17:12:27.200  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:12:27.201  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 17:12:27.201  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:12:27.205  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 17:12:27.205  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:12:27.206  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 17:12:27.206  2667  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 17:12:27.206  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:27.206  2667  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 17:12:27.207  3773  3824 D BluetoothAdapter: STATE_ON
,09-09 17:12:27.209  2667  2678 D BtGatt.GattService: registerClient() - UUID=2f46f041-2df3-4247-bcfd-862d5364f815
,09-09 17:12:27.210  2667  2700 D BtGatt.GattService: onClientRegistered() - UUID=2f46f041-2df3-4247-bcfd-862d5364f815, clientIf=5
09-09 17:12:27.210  3773  3785 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 17:12:27.211  2667  2801 D BtGatt.GattService: start scan with filters
,09-09 17:12:27.212  2667  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 17:12:27.212  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:27.214  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 17:12:27.214  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:12:27.214  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:12:27.214  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 17:12:27.214  2667  2703 D BtGatt.ScanManager: handling starting scan
09-09 17:12:27.216  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:12:27.216  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 17:12:27.216  3773  3773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:12:27.217  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 17:12:27.220  3773  3824 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 17:12:27.221  2667  2700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 17:12:27.221  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:27.221  2667  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 17:12:27.222  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.222  3773  3824 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 17:12:27.222  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.222  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 17:12:27.222  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.223  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 17:12:27.223  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:12:27.223  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:12:27.223  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 17:12:27.223  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:12:27.223  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:12:27.223  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 17:12:27.223  3773  3824 D BluetoothAdapter: STATE_ON
09-09 17:12:27.224  2667  2678 D BtGatt.GattService: stopScan() - queue size =1
,09-09 17:12:27.225  2667  2801 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 17:12:27.225  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:27.225  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:12:27.225  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:12:27.225  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:12:27.225  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 17:12:27.226  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:12:27.226  2667  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 17:12:27.226  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:27.226  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:12:27.226  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:12:27.226  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:12:27.226  2667  2703 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:12:27.226  2667  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 17:12:27.226  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:27.227  3773  3773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:12:27.227  3773  3773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:12:27.228  3773  3773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:12:27.228  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.228  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.228  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:27.228  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.228  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.228  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.228  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.228  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.229  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.229  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.229  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.229  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.229  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.230  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
,09-09 17:12:27.230  3773  3824 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 17:12:27.231  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:12:27.235  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:27.235  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:27.235  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:27.235  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:27.235  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:27.235  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:27.235  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:27.235  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:12:27.236  2667  2700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 17:12:27.236  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:27.237  3773  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:27.237  3773  3824 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:27.237  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:27.237  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:12:27.237  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:12:27.238  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:27.238  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:12:27.240  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:27.242  2667  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 17:12:27.242  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:27.242  3773  3824 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 17:12:27.243  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:12:27.243  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:27.246  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:12:27.247  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 17:12:27.247  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 17:12:27.248  2667  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 17:12:27.248  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:27.248  2667  2703 D BtGatt.ScanManager: stopping BLe Batch
,09-09 17:12:27.250  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 17:12:27.250  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:12:27.250  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 17:12:27.251  3773  3824 D BluetoothAdapter: STATE_ON
,09-09 17:12:27.252  2667  2801 D BtGatt.GattService: registerClient() - UUID=c9b95581-ea69-4280-96d3-13504b74fc8e
09-09 17:12:27.253  2667  2700 D BtGatt.GattService: onClientRegistered() - UUID=c9b95581-ea69-4280-96d3-13504b74fc8e, clientIf=5
09-09 17:12:27.253  3773  3785 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 17:12:27.253  2667  2823 D BtGatt.GattService: start scan with filters
09-09 17:12:27.254  2667  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 17:12:27.254  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:27.255  2667  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 17:12:27.256  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 17:12:27.256  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:12:27.256  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:12:27.256  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 17:12:27.258  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:12:27.258  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 17:12:27.259  3773  3773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:12:27.260  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 17:12:27.260  2667  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 17:12:27.260  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:27.262  2667  2703 D BtGatt.ScanManager: handling starting scan
09-09 17:12:27.264  3773  3824 I io.jxcore.node.ConnectionHelper: start: OK
09-09 17:12:27.264  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.264  3773  3824 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 17:12:27.264  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.264  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 17:12:27.264  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.264  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:12:27.264  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:12:27.264  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:12:27.264  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:12:27.264  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:12:27.265  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:12:27.265  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 17:12:27.266  3773  3824 D BluetoothAdapter: STATE_ON
09-09 17:12:27.267  2667  2823 D BtGatt.GattService: stopScan() - queue size =1
09-09 17:12:27.267  2667  2679 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 17:12:27.268  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:27.268  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:12:27.268  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:12:27.268  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:12:27.268  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 17:12:27.269  2667  2700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 17:12:27.269  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:27.269  2667  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 17:12:27.269  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:12:27.270  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:12:27.270  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:12:27.270  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:12:27.271  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:27.272  3773  3773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:12:27.272  3773  3773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:12:27.272  3773  3773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:12:27.272  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.273  3773  3824 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 17:12:27.273  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.273  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:27.273  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.273  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.273  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:27.273  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.273  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.273  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.273  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.274  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.274  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.274  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.275  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.275  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.275  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.276  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.276  3773  3824 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 17:12:27.277  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.277  2667  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 17:12:27.277  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:27.277  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.277  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:27.277  2667  2703 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:12:27.278  2667  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 17:12:27.278  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.278  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.278  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.278  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.278  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.278  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.278  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.278  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.278  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.278  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.279  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.280  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.280  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.280  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.280  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.281  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 17:12:27.281  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.281  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.281  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:27.282  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.282  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.282  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.282  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.282  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.282  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.282  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.282  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.282  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.282  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.282  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.283  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.283  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.283  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.284  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.284  3773  3824 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 17:12:27.284  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.284  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.284  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:12:27.285  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.285  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.285  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.285  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.285  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.285  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.285  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.285  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:12:27.285  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.285  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.286  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.286  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.287  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:12:27.287  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.287  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.287  3773  3824 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 17:12:27.287  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.288  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.288  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:27.288  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.288  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.288  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.288  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.288  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.288  2667  2700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 17:12:27.288  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:27.289  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.289  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.289  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.289  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.289  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.289  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.290  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.290  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.290  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.290  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.291  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 17:12:27.292  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:12:27.292  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 17:12:27.292  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:12:27.293  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 17:12:27.293  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:12:27.293  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.294  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.294  2667  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 17:12:27.294  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:27.295  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:27.295  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.295  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.295  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.295  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.295  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.296  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
,09-09 17:12:27.296  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.296  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.296  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.296  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.296  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.297  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.297  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:12:27.297  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:12:27.297  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.298  3773  3824 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:12:27.299  3773  3824 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-09 17:12:27.299  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 17:12:27.302  2667  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 17:12:27.302  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:27.302  2667  2703 D BtGatt.ScanManager: stopping BLe Batch
,09-09 17:12:27.304  3773  3824 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 17:12:27.304  3773  3824 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 17:12:27.304  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 17:12:27.304  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 17:12:27.305  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 17:12:27.305  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 17:12:27.305  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-09 17:12:27.305  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 17:12:27.305  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 17:12:27.305  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 17:12:27.305  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 17:12:27.305  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 17:12:27.305  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 17:12:27.305  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-09 17:12:27.305  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 17:12:27.305  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 17:12:27.305  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 17:12:27.305  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 17:12:27.306  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-09 17:12:27.306  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 17:12:27.306  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 17:12:27.306  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 17:12:27.306  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 17:12:27.306  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 17:12:27.306  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 17:12:27.306  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 17:12:27.306  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 17:12:27.306  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 17:12:27.306  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 17:12:27.306  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-09 17:12:27.306  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 17:12:27.306  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 17:12:27.307  3773  3824 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 17:12:27.307  3773  3824 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 17:12:27.307  3773  3824 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 17:12:27.307  3773  3824 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:12:27.307  3773  3824 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-09 17:12:27.307  3773  3824 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 17:12:27.307  3773  3824 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:12:27.307  3773  3824 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 17:12:27.307  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 17:12:27.308  2667  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 17:12:27.308  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:27.308  2667  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 17:12:27.311  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-09 17:12:27.311  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 17:12:27.312  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-09 17:12:27.312  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 17:12:27.312  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-09 17:12:27.312  3773  3824 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 17:12:27.312  3773  3824 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:12:27.313  3773  3824 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-09 17:12:27.313  3773  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 386)
09-09 17:12:27.313  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:12:27.313  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.313  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:27.314  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.314  2667  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 17:12:27.314  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:27.314  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.314  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.314  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 17:12:27.315  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.315  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:12:27.315  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.315  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.315  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:12:27.315  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.315  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.316  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.316  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.317  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.316  3773  3836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:12:27.317  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.317  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.317  3773  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 386
09-09 17:12:27.317  3773  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 386)
09-09 17:12:27.317  3773  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 386)
,09-09 17:12:27.317  3773  3824 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 17:12:27.318  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.318  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.318  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:27.318  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.318  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.318  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.319  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
,09-09 17:12:27.319  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.319  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.319  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.319  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.319  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.319  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.319  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:27.320  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.320  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.320  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.321  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.321  3773  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 386)
,09-09 17:12:27.321  3773  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 17:12:27.321  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.322  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.322  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:12:27.322  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.322  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.322  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.322  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.322  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.322  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.322  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.322  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:12:27.322  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.322  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.322  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.323  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.324  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.324  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.324  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
,09-09 17:12:27.324  3773  3824 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 17:12:27.324  3773  3824 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 17:12:27.324  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:12:27.325  3773  3824 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 17:12:27.325  3773  3824 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 17:12:27.325  3773  3824 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 17:12:27.325  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-09 17:12:27.325  3773  3824 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 17:12:27.325  3773  3824 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 17:12:27.325  3773  3824 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 17:12:27.325  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:12:27.325  3773  3824 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 17:12:27.325  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.325  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.325  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:27.326  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.326  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:12:27.326  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.326  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.326  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.326  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.326  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.326  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.326  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.326  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.326  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:27.328  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.328  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:12:27.328  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.328  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.328  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.328  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.329  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.329  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
,09-09 17:12:27.329  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.329  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.329  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.329  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.329  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.329  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.329  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.329  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:12:27.329  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.329  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.329  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.330  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.330  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.330  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:27.330  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:12:27.330  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.330  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.330  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.330  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.330  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.330  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.330  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.330  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.330  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.331  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:27.332  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.332  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.332  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:12:27.332  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
,09-09 17:12:27.333  3773  3824 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 17:12:27.333  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:12:27.334  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 17:12:27.335  3773  3824 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 17:12:27.335  3773  3824 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 17:12:27.335  3773  3773 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 17:12:27.335  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 17:12:27.335  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:12:27.336  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.336  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 17:12:27.336  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 17:12:27.336  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 17:12:27.336  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.336  3773  3824 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-09 17:12:27.336  3773  3773 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 17:12:27.336  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
,09-09 17:12:27.337  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,09-09 17:12:27.337  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:12:27.337  3773  3838 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:12:27.337  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 17:12:27.337  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 17:12:27.337  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.337  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.338  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:12:27.338  3773  3773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:12:27.338  3773  3773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:12:27.338  3773  3773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:12:27.339  3773  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 17:12:27.339  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.339  3773  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 17:12:27.339  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:12:27.339  3773  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 17:12:27.339  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.339  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:12:27.339  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:12:27.339  3773  3773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 17:12:27.339  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:12:27.339  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.340  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
,09-09 17:12:27.340  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.340  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
,09-09 17:12:27.340  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.340  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:12:27.340  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.340  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:12:27.340  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.341  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:12:27.341  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.341  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:12:27.342  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.343  3773  3824 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-09 17:12:27.343  3773  3824 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 17:12:27.343  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 17:12:27.343  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:12:27.343  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:12:27.343  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.343  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:27.344  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:12:27.344  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.344  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:27.344  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.344  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.344  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
,09-09 17:12:27.344  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.344  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 17:12:27.344  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:27.344  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.344  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.346  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-09 17:12:27.346  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.346  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:12:27.346  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.350  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:12:27.350  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.350  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:27.350  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.350  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.350  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:27.350  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.350  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:12:27.350  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.350  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.350  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:12:27.351  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.351  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.351  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:27.352  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.352  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:27.352  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.352  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list,
09-09 17:12:27.352  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:27.352  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:27.353  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:12:27.353  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:27.353  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.353  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:27.353  3773  3824 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4849253 not in the list
09-09 17:12:27.353  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:27.353  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
,09-09 17:12:27.353  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:27.353  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:27.353  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.353  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:12:27.353  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:27.354  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:27.354  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:12:27.354  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:12:27.354  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c790 not in the list
09-09 17:12:27.355  3773  3824 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 17:12:27.355  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:12:27.355  3773  3824 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 17:12:27.355  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:12:27.356  3773  3824 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 17:12:27.356  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-09 17:12:27.357  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 17:12:27.357  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 17:12:27.358  3773  3824 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 17:12:27.358  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 17:12:27.358  3773  3824 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 17:12:27.358  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 17:12:27.358  3773  3824 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 17:12:27.358  3773  3824 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 17:12:27.359  3773  3824 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-09 17:12:27.359  3773  3824 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 17:12:27.359  3773  3824 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 17:12:27.359  3773  3824 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 17:12:27.360  3773  3824 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 17:12:27.360  3773  3824 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 17:12:27.361  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:27.361  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@af80ff2 added. We now have 2 listener(s)
09-09 17:12:27.361  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:27.363  3773  3824 D BluetoothAdapter: enable(): BT is already enabled..!
,09-09 17:12:27.364   871  2036 D WifiService: setWifiEnabled: true pid=3773, uid=10000
09-09 17:12:27.364   871  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 17:12:27.366  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:27.366  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7a6b643 added. We now have 3 listener(s)
09-09 17:12:27.366  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:12:27.373  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:27.373  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@85634c0 added. We now have 4 listener(s)
09-09 17:12:27.373  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:12:27.375  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:12:27.375  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d4725f9 added. We now have 5 listener(s)
09-09 17:12:27.375  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:12:27.377   871  1965 D WifiService: setWifiEnabled: false pid=3773, uid=10000
,09-09 17:12:27.377   871  1965 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:12:27.381  2667  2695 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 17:12:27.381  2667  2695 D BluetoothAdapterProperties: Setting state to 13
,09-09 17:12:27.381  2667  2695 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 17:12:27.381  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:27.381  2667  2695 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 17:12:27.382  2667  2695 I BluetoothAdapterState: Entering PendingCommandState
,09-09 17:12:27.383  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:12:27.383  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:27.383  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:27.383  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:27.383  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:27.383  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:27.383  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:27.383  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:27.383  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:12:27.383  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:27.384  3773  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:12:27.384  3773  3824 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:27.386  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 17:12:27.388  2667  2700 D BluetoothAdapterProperties: Scan Mode:20
,09-09 17:12:27.389  2667  2695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-09 17:12:27.389  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:27.390  2667  2667 D BluetoothMapService: onReceive
09-09 17:12:27.390  2667  2667 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:27.390  2667  2667 D BluetoothMapService: STATE_TURNING_OFF
09-09 17:12:27.390  2667  2667 D BluetoothMapService: MAP Service closeService in
09-09 17:12:27.390  2667  2667 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 17:12:27.391  2667  2667 D ObexServerSockets0: shutdown(block = true)
,09-09 17:12:27.391  2667  2667 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 17:12:27.391  2667  2667 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 17:12:27.391  2667  2798 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 17:12:27.393  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:27.394  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:27.394  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:27.394  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:27.394  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:27.394  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:27.394  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:27.394  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:27.394  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:27.394  2667  2825 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 17:12:27.394  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:27.394  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:27.391  2667  2824 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 17:12:27.396  2667  2667 I BtOppRfcommListener: stopping Accept Thread
,09-09 17:12:27.397  2667  3436 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:12:27.397  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:27.397  2667  3436 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 17:12:27.399  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:27.400  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 17:12:27.401   871  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 17:12:27.401  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:27.401   871  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 17:12:27.402   871  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 17:12:27.402   871  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:12:27.411   871   884 I ActivityManager: Start proc 3841:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-09 17:12:27.414  2667  2667 D HeadsetService: Received stop request...Stopping profile...
09-09 17:12:27.414   871  1890 D DhcpClient: Clearing IP address
09-09 17:12:27.415   372   869 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:12:27.415   871   871 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:27.416  1935  2226 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:27.416   871   871 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:27.417  1354  1370 D BluetoothHeadset: Proxy object disconnected
,09-09 17:12:27.417  1354  1354 D HeadsetProfile: Bluetooth service disconnected
,09-09 17:12:27.417   871   871 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:27.418  2667  2667 D A2dpService: Received stop request...Stopping profile...
09-09 17:12:27.418  2667  2804 D A2dpStateMachine: Exit Disconnected: -1
,09-09 17:12:27.418   372   869 D CommandListener: Setting iface cfg
09-09 17:12:27.421   871  1893 D DhcpClient: Receive thread stopped
09-09 17:12:27.422  1354  1354 D BluetoothA2dp: Proxy object disconnected
09-09 17:12:27.423  1524  2129 V NativeCrypto: Read error: ssl=0xaedd5200: I/O error during system call, Connection timed out
09-09 17:12:27.423  2667  2667 V BluetoothAdapterState: isTurningOff()=true
09-09 17:12:27.423  2667  2667 V BluetoothAdapterState: isTurningOn()=false
,09-09 17:12:27.423   871   871 D BluetoothA2dp: Proxy object disconnected
09-09 17:12:27.424  1524  2129 V NativeCrypto: SSL shutdown failed: ssl=0xaedd5200: I/O error during system call, Broken pipe
09-09 17:12:27.423  2667  2667 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:12:27.424  2667  2667 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:27.426  2667  2667 D HidService: Received stop request...Stopping profile...
09-09 17:12:27.426  2667  2667 D HidService: Stopping Bluetooth HidService
,09-09 17:12:27.426   871  1389 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,09-09 17:12:27.426  1354  1354 D BluetoothInputDevice: Proxy object disconnected
09-09 17:12:27.426  1354  1354 D HidProfile: Bluetooth service disconnected
09-09 17:12:27.427   871  1875 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-09 17:12:27.428  2667  2667 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 17:12:27.428  2667  2667 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:12:27.428  2667  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-09 17:12:27.428  2667  2769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:12:27.429  2667  2769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:12:27.429  2667  2769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:12:27.429  2667  2700 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 17:12:27.430  2667  2667 D HealthService: Received stop request...Stopping profile...
09-09 17:12:27.430   871  1875 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-09 17:12:27.433   871  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-09 17:12:27.433   871  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 17:12:27.436  2667  2667 D PanService: Received stop request...Stopping profile...
09-09 17:12:27.437  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 17:12:27.438  2667  2667 D BluetoothMapService: Received stop request...Stopping profile...
,09-09 17:12:27.438  1354  1354 D PanProfile: Bluetooth service disconnected
09-09 17:12:27.438  2667  2667 D BluetoothMapService: stop()
09-09 17:12:27.438  2667  2667 D BluetoothMapAppObserver: deinitObservers()
09-09 17:12:27.438  2667  2667 D BluetoothMapAppObserver: removeReceiver()
09-09 17:12:27.439  2667  2667 V BluetoothAdapterState: isTurningOff()=true
09-09 17:12:27.439  2667  2667 V BluetoothAdapterState: isTurningOn()=false
09-09 17:12:27.439  2667  2667 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:12:27.439  2667  2667 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:27.439  1354  1354 D BluetoothMap: Proxy object disconnected
09-09 17:12:27.440  1354  1354 D MapProfile: Bluetooth service disconnected
09-09 17:12:27.441  2667  2667 V BluetoothAdapterState: isTurningOff()=true
09-09 17:12:27.441  2667  2667 V BluetoothAdapterState: isTurningOn()=false
09-09 17:12:27.441  2667  2667 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:12:27.441  2667  2667 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:27.441  2667  2667 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 17:12:27.441  2667  2667 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 17:12:27.441  2667  2667 V BluetoothAdapterState: isTurningOff()=true
,09-09 17:12:27.441  2667  2667 V BluetoothAdapterState: isTurningOn()=false
,09-09 17:12:27.441  2667  2667 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:12:27.441  2667  2667 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:12:27.442  2667  2667 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-09 17:12:27.442  2667  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 17:12:27.442  2667  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 17:12:27.442  2667  2769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:12:27.442  2667  2700 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 17:12:27.442  2667  2769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:12:27.442  2667  2769 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:12:27.442  2667  2769 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:12:27.442  2667  2769 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 17:12:27.443  2667  2667 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 17:12:27.443  2667  2769 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:12:27.443  2667  2667 V BluetoothAdapterState: isTurningOff()=true
09-09 17:12:27.443  2667  2667 V BluetoothAdapterState: isTurningOn()=false
09-09 17:12:27.443  2667  2667 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:12:27.443  2667  2667 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:27.444  2667  2667 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 17:12:27.444  2667  2667 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 17:12:27.447   871  1314 D WifiStateMachine: Start Disconnecting Watchdog 1
09-09 17:12:27.450   871  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 17:12:27.450   871  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-09 17:12:27.450   871  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-09 17:12:27.450   400   400 E Parcel  : Reading a NULL string not supported here.
09-09 17:12:27.450  2667  2667 D BluetoothMapService: MAP Service closeService in
09-09 17:12:27.450  2667  2667 V BluetoothAdapterState: isTurningOff()=true
,09-09 17:12:27.450  2667  2667 V BluetoothAdapterState: isTurningOn()=false
09-09 17:12:27.450  2667  2667 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:12:27.450  2667  2667 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:27.451  2667  2695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 17:12:27.451  2667  2695 D BluetoothAdapterProperties: Setting state to 15
09-09 17:12:27.451  2667  2667 D BluetoothMapService: cleanup()
09-09 17:12:27.451  2667  2695 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-09 17:12:27.451  2667  2667 D BluetoothMapService: MAP Service closeService in
09-09 17:12:27.451  2667  2695 I BluetoothAdapterState: Entering BleOnState
09-09 17:12:27.454   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:12:27.455   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:27.455  1354  3772 D BluetoothPan: onBluetoothStateChange on: false
09-09 17:12:27.455  1354  1371 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:12:27.455   871  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-09 17:12:27.456   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:27.456  1935  2227 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:27.457  1354  1370 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 17:12:27.459  1354  3772 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:27.459  1354  1371 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 17:12:27.459   871  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 17:12:27.460  1354  2027 D BluetoothMap: onBluetoothStateChange: up=false
09-09 17:12:27.460   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:27.461  2667  2695 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 17:12:27.461  2667  2695 D BluetoothAdapterProperties: Setting state to 16
09-09 17:12:27.461  2667  2695 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-09 17:12:27.461  2667  2695 D BluetoothAdapterProperties: onBleDisable
09-09 17:12:27.461  2667  2695 I BluetoothAdapterState: Entering PendingCommandState
09-09 17:12:27.462  2667  2696 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 17:12:27.462  2667  2769 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 17:12:27.463  2667  2769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:12:27.466  2667  2700 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:12:27.468  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:27.468  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:27.468  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:27.468  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:27.468  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:27.468  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:27.468  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:27.468  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:27.468  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:12:27.469  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:27.469  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:27.471  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:27.471  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:27.471  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:27.471  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:27.471  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:27.471  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:27.471  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:27.471  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:27.471  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:27.471  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:27.471  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:27.473  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:27.474  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:27.488   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 17:12:27.507  3841  3841 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-09 17:12:27.510   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 17:12:27.510   372   869 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:12:27.511   871  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-09 17:12:27.511   871  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:27.515   871   888 D Tethering: MasterInitialState.processMessage what=3
,09-09 17:12:27.515  3402  3402 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9675243 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-09 17:12:27.517  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:27.519  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:27.523   871  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 17:12:27.526  2175  2320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:12:27.527  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:27.527  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:27.527  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:27.527  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:27.527  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:27.527  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:27.527  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:27.527  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:27.527  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:27.528  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:27.528  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:27.529  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:27.530  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:27.530  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:27.530  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:27.530  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:27.530  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:27.530  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:27.530  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:27.530  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:27.530  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:27.530  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:12:27.535   871  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 17:12:27.550  3841  3841 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:12:27.556   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8df0bfb:true
,09-09 17:12:27.556  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:12:27.569   372   869 E Netd    : netlink response contains error (No such file or directory)
,09-09 17:12:27.570   871  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 17:12:27.572   871  1687 I ActivityManager: Start proc 3862:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-09 17:12:27.600  3841  3841 D LocalBluetoothProfileManager: Adding local MAP profile
,09-09 17:12:27.601  3841  3841 D BluetoothMap: Create BluetoothMap proxy object
,09-09 17:12:27.606  3862  3862 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 17:12:27.617  3841  3841 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 17:12:27.633  3841  3841 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:12:27.637   871  3170 I ActivityManager: Killing 2979:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-09 17:12:27.673  2667  2700 I bt_hci  : shut_down
,09-09 17:12:27.722  2667  2704 D bt_hwcfg: hw_epilog_process
,09-09 17:12:27.723  2667  2704 I bt_vendor: low_power_mode_cb
,09-09 17:12:27.749  2667  2704 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 17:12:27.749  2667  2704 I bt_vendor: epilog_cb
09-09 17:12:27.749  2667  2704 I bt_hci  : epilog_finished_callback
,09-09 17:12:27.755  2667  2700 I bt_hci_h4: hal_close
,09-09 17:12:27.756  2667  2700 I bt_userial_vendor: device fd = 51 close
,09-09 17:12:27.804  3862  3862 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:12:27.804  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:12:27.804  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:12:27.805  3862  3862 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:12:27.805  3862  3862 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:12:27.805  3862  3862 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:12:27.805  3862  3862 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:12:27.805  3862  3862 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:12:27.805  3862  3862 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 17:12:27.805  3862  3862 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707),
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:12:27.805  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:12:27.836  3841  3841 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:12:27.839  3773  3773 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 17:12:27.847  3841  3841 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:12:27.858  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:12:27.864   871  1964 I ActivityManager: Killing 3402:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-09 17:12:27.991  2667  2696 D bt_stack_manager: event_shut_down_stack finished.
,09-09 17:12:27.992  2667  2695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 17:12:27.998  2667  2667 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 17:12:27.999  2667  2667 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 17:12:27.999  2667  2667 D BtGatt.GattService: stop()
09-09 17:12:27.999  2667  2667 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 17:12:27.999  2667  2695 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-09 17:12:28.000  2667  2667 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:12:28.000  2667  2667 V BluetoothAdapterState: isTurningOn()=false
09-09 17:12:28.000  2667  2667 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:12:28.000  2667  2667 V BluetoothAdapterState: isBleTurningOff()=true
09-09 17:12:28.001  2667  2695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 17:12:28.001  2667  2695 D BluetoothAdapterProperties: Setting state to 10
09-09 17:12:28.001  2667  2695 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-09 17:12:28.002  2667  2695 I BluetoothAdapterState: Entering OffState
09-09 17:12:28.003  1747  1747 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 17:12:28.006   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-09 17:12:28.008  1747  1747 D SystemUpdateService: onCreate
,09-09 17:12:28.011  1747  1747 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 17:12:28.015  1747  3896 I SystemUpdateService: active receiver: enabled
,09-09 17:12:28.017  2667  2667 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 17:12:28.019  2667  2667 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 17:12:28.019  2667  2696 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-09 17:12:28.021  1747  3896 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 17:12:28.021  2667  2696 D bt_stack_manager: event_clean_up_stack finished.
09-09 17:12:28.019  2667  2667 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 17:12:28.023  1747  3896 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 17:12:28.023  1747  3896 I SystemUpdateService: now status is 0 (complete)
09-09 17:12:28.023  1747  3896 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 17:12:28.023  1747  3896 I SystemUpdateService: file has been verified
09-09 17:12:28.023  1747  3896 I SystemUpdateService: OTA package size = 12249756
,09-09 17:12:28.025  1747  3896 I SystemUpdateService: showing system update notification
,09-09 17:12:28.025  2667  2667 I art     : System.exit called, status: 0
09-09 17:12:28.025  2667  2667 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 17:12:28.039  1747  1747 D SystemUpdateService: onDestroy
,09-09 17:12:28.042  1747  1747 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 17:12:28.046  1747  1747 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 17:12:28.047  1747  1747 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 17:12:28.050  1747  2432 I iu.UploadsManager: num queued entries: 0
09-09 17:12:28.050  1747  2432 I iu.UploadsManager: num updated entries: 0
09-09 17:12:28.051  1747  2432 I iu.SyncManager: NEXT; no task
,09-09 17:12:28.058   871  2036 I ActivityManager: Start proc 3899:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
09-09 17:12:28.059  3862  3889 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 17:12:28.060   871  1965 I ActivityManager: Process com.android.bluetooth (pid 2667) has died
,09-09 17:12:28.084   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28d22b7:true
,09-09 17:12:28.098  3899  3899 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-09 17:12:28.101  3899  3899 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:28.107  3899  3899 D SprintDMHelper: simOperator: 
09-09 17:12:28.107  3899  3899 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 17:12:28.122   871  1965 I ActivityManager: Start proc 3911:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 17:12:28.244   871   881 I ActivityManager: Start proc 3926:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 17:12:28.249  3058  3925 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 17:12:28.255   871   882 I ActivityManager: Killing 3460:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-09 17:12:28.327  3926  3926 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-09 17:12:28.375  3926  3926 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 17:12:28.375  3926  3926 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 17:12:28.375  3926  3926 I GAv4    :   adb logcat -s GAv4
,09-09 17:12:28.403  3926  3926 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 17:12:28.408  3926  3926 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 17:12:28.436  3926  3944 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 17:12:28.528  3926  3926 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 17:12:28.578  3926  3926 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 17:12:28.585  3926  3926 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7406-7408)
,09-09 17:12:28.585  3926  3926 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 17:12:28.598  3926  3926 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3715233}
,09-09 17:12:28.598  3926  3926 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 17:12:28.599  3926  3926 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 17:12:28.606  3926  3926 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 17:12:28.607  3926  3926 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 17:12:28.626  3926  3926 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 17:12:28.640  3926  3926 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 17:12:28.640  3926  3926 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 17:12:28.640  3926  3926 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 17:12:28.640  3926  3926 I Adreno  : Build Date                       : 10/20/15
09-09 17:12:28.640  3926  3926 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 17:12:28.640  3926  3926 I Adreno  : Local Branch                     : M14
09-09 17:12:28.640  3926  3926 I Adreno  : Remote Branch                    : 
09-09 17:12:28.640  3926  3926 I Adreno  : Remote Branch                    : 
09-09 17:12:28.640  3926  3926 I Adreno  : Reconstruct Branch               : 
,09-09 17:12:28.693  3926  3926 I NSApplication: Starting up...
,09-09 17:12:28.714  3926  3972 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 17:12:28.718   871  3170 I ActivityManager: Start proc 3977:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-09 17:12:28.719   871  3170 I ActivityManager: Killing 3041:com.google.android.keep/u0a79 (adj 15): empty #17
,09-09 17:12:28.815  3977  3977 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 17:12:28.986   871  3170 I ActivityManager: Killing 3618:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-09 17:12:29.081   871  2036 I ActivityManager: Start proc 3991:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 17:12:29.172  3991  3991 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 17:12:29.219  3991  3991 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-09 17:12:29.239   871  1965 I ActivityManager: Start proc 4014:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,09-09 17:12:29.240   871  1965 I ActivityManager: Killing 1674:android.process.acore/u0a5 (adj 15): empty #17
,09-09 17:12:29.316  4014  4014 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,09-09 17:12:29.532   871   882 I ActivityManager: Killing 3661:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 17:12:30.386   871  1965 D WifiService: setWifiEnabled: true pid=3773, uid=10000
,09-09 17:12:30.387   871  1965 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:12:30.400   871  1314 D WifiConfigStore: Loading config and enabling all networks 
,09-09 17:12:30.409  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:12:30.409  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:30.409  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:30.409  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:30.409  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:30.409  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:30.409  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:30.409  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:30.409  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:30.410  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:30.410  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:30.413  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:12:30.413  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:30.413  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:30.413  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:30.413  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:30.413  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:30.413  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:30.413  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:30.413  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:30.414  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:30.414  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:12:30.439   871  1314 D WifiConfigStore: loaded 0 passpoint configs
,09-09 17:12:30.440   871  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 17:12:30.441   871  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000,
,09-09 17:12:30.442   871  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 17:12:30.442   871  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-09 17:12:30.442   871  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-09 17:12:30.442   871  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 17:12:30.469   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 17:12:30.469   871  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.00 rxSuccessRate=18.25 delta 1000 -> 994
,09-09 17:12:30.472   372   869 D CommandListener: Setting iface cfg
,09-09 17:12:30.474   871  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-09 17:12:30.474   871  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 17:12:30.481   871  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-09 17:12:30.481   871  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:12:30.489   871  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 17:12:30.529   871  1313 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 17:12:30.531   871  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 17:12:30.586   871  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 17:12:30.592  1474  1474 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 17:12:31.029  1474  1474 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 17:12:31.070  1474  1474 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 17:12:31.070  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 17:12:31.075   871  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 17:12:31.084   871  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 17:12:31.085   871  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:12:31.085   871  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 17:12:31.110   871  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:12:31.126   372   869 D CommandListener: Setting iface cfg
,09-09 17:12:31.127   871  1314 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 17:12:31.146   871  1316 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-09 17:12:31.149   871  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 17:12:31.164   871  4045 D DhcpClient: Receive thread started
,09-09 17:12:31.246   871  1314 E native  : do suspend false
,09-09 17:12:31.265   871  1890 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 17:12:31.281   871  4045 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172702, domain null
,09-09 17:12:31.282   871  1890 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172702 seconds
,09-09 17:12:31.285   871  1890 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 17:12:31.300   871  4045 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 17:12:31.302   871  1890 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 17:12:31.307   372   869 D CommandListener: Setting iface cfg
,09-09 17:12:31.319   871  1890 D DhcpClient: Scheduling renewal in 86399s
,09-09 17:12:31.323   871  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 17:12:31.340   871  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 17:12:31.343   871  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 17:12:31.343   871  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 17:12:31.345   871  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 17:12:31.349   871  1316 D ConnectivityService: Adding iface wlan0 to network 101
,09-09 17:12:31.365   871  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 17:12:31.400   871  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 17:12:31.401   871  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-09 17:12:31.403   871  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-09 17:12:31.405   871  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-09 17:12:31.406   871  1316 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-09 17:12:31.417   871  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 17:12:31.421   871  1316 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-09 17:12:31.422   871  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-09 17:12:31.422   871  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-09 17:12:31.422   871  1316 D ConnectivityService:    accepting network in place of null
09-09 17:12:31.422   871  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-09 17:12:31.422   871  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 17:12:31.424   871  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 17:12:31.479   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 17:12:31.514   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 17:12:31.524   871  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 17:12:31.526   871  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:31.535   871  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-09 17:12:31.537   871   888 D Tethering: MasterInitialState.processMessage what=3
,09-09 17:12:31.556  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:31.556  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:31.556  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:31.556  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:31.556  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:31.556  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:31.556  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:31.556  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:31.556  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:12:31.556  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:31.556  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:12:31.562  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:31.562  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:31.562  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:31.562  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:31.562  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:31.562  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:31.562  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:31.562  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:31.562  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:12:31.562  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:31.562  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:12:31.568  1747  1747 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 17:12:31.571  1747  1747 D SystemUpdateService: onCreate
,09-09 17:12:31.574  1747  1747 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 17:12:31.578  1747  4055 I SystemUpdateService: active receiver: enabled
,09-09 17:12:31.585  1747  4055 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 17:12:31.587  1747  4055 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 17:12:31.587  1747  4055 I SystemUpdateService: now status is 0 (complete)
,09-09 17:12:31.587  1747  4055 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 17:12:31.587  1747  4055 I SystemUpdateService: file has been verified
,09-09 17:12:31.587  1747  4055 I SystemUpdateService: OTA package size = 12249756
,09-09 17:12:31.594  1747  4055 I SystemUpdateService: showing system update notification
,09-09 17:12:31.598  1747  1747 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 17:12:31.599  1747  2432 I iu.UploadsManager: num queued entries: 0
,09-09 17:12:31.600  1747  2432 I iu.UploadsManager: num updated entries: 0
,09-09 17:12:31.600  1747  2432 I iu.SyncManager: NEXT; no task
,09-09 17:12:31.601  1747  4059 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 17:12:31.601  1747  4059 W BaseAppContext: Using Auth Proxy for data requests.
09-09 17:12:31.603  1747  4059 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 17:12:31.603  1747  1747 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-09 17:12:31.605  1747  1747 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 17:12:31.608  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 17:12:31.608  3899  3899 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:31.609  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 17:12:31.611  1747  1747 D SystemUpdateService: onDestroy
09-09 17:12:31.612  3899  3899 D SprintDMHelper: simOperator: 
09-09 17:12:31.612  3899  3899 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 17:12:31.648  1524  2173 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 17:12:31.648  1524  2173 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 17:12:31.648  1524  2173 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 17:12:31.648  1524  2173 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 17:12:31.665  1747  4059 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-09 17:12:32.523   871  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 17:12:33.392   871  1414 D WifiService: setWifiEnabled: false pid=3773, uid=10000
,09-09 17:12:33.393   871  1414 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:12:33.422  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 17:12:33.424   871  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 17:12:33.424   871  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-09 17:12:33.425   871  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 17:12:33.425   871  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:12:33.442   871  1890 D DhcpClient: Clearing IP address
,09-09 17:12:33.443   372   869 D CommandListener: Setting iface cfg
,09-09 17:12:33.445   372   869 D CommandListener: Clearing all IP addresses on wlan0
,09-09 17:12:33.447   871  4045 D DhcpClient: Receive thread stopped
,09-09 17:12:33.460   871  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-09 17:12:33.460   871  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-09 17:12:33.471   871  1314 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-09 17:12:33.475   400   400 E Parcel  : Reading a NULL string not supported here.
,09-09 17:12:33.476   871  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 17:12:33.479   372   869 D CommandListener: Clearing all IP addresses on wlan0
,09-09 17:12:33.484   871  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-09 17:12:33.494  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:12:33.494  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:33.494  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:33.494  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:33.494  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:33.494  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:33.494  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:33.494  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:33.494  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:12:33.494  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:33.494  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:33.495   871  1314 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 17:12:33.495  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:33.495  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:33.495  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:33.495  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:33.495  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:33.495  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:33.495  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:33.495  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:33.495  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:12:33.495  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:33.495  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:33.496  2175  2320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:12:33.509   871  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 17:12:33.523   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 17:12:33.541   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 17:12:33.542   871  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 17:12:33.542   871  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:33.546   871   888 D Tethering: MasterInitialState.processMessage what=3
09-09 17:12:33.547  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:33.548  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:33.555  1747  1747 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 17:12:33.559  1747  1747 D SystemUpdateService: onCreate
,09-09 17:12:33.561  1747  1747 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 17:12:33.572  1747  1747 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 17:12:33.574  1747  2432 I iu.UploadsManager: num queued entries: 0
09-09 17:12:33.574  1747  2432 I iu.UploadsManager: num updated entries: 0
09-09 17:12:33.575  1747  2432 I iu.SyncManager: NEXT; no task
,09-09 17:12:33.579  1747  4073 I SystemUpdateService: active receiver: enabled
,09-09 17:12:33.581  1747  1747 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 17:12:33.583  1747  1747 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 17:12:33.584  3899  3899 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:33.589  3899  3899 D SprintDMHelper: simOperator: 
,09-09 17:12:33.589  3899  3899 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 17:12:33.596  1747  4073 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 17:12:33.599  1747  4073 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 17:12:33.600  1747  4073 I SystemUpdateService: now status is 0 (complete)
09-09 17:12:33.600  1747  4073 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 17:12:33.600  1747  4073 I SystemUpdateService: file has been verified
09-09 17:12:33.600  1747  4073 I SystemUpdateService: OTA package size = 12249756
,09-09 17:12:33.623  1747  4073 I SystemUpdateService: showing system update notification
,09-09 17:12:33.656   372   869 E Netd    : netlink response contains error (No such file or directory)
,09-09 17:12:33.658  1747  1747 D SystemUpdateService: onDestroy
,09-09 17:12:34.378  4014  4021 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@e5b5caf)
,09-09 17:12:36.434   871  4043 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-09 17:12:36.435   871  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 17:12:36.444   871   888 I ActivityManager: Start proc 4080:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 17:12:36.537  4080  4080 D AdapterServiceConfig: Adding HeadsetService
,09-09 17:12:36.537  4080  4080 D AdapterServiceConfig: Adding A2dpService
,09-09 17:12:36.538  4080  4080 D AdapterServiceConfig: Adding HidService
09-09 17:12:36.538  4080  4080 D AdapterServiceConfig: Adding HealthService
09-09 17:12:36.538  4080  4080 D AdapterServiceConfig: Adding PanService
09-09 17:12:36.538  4080  4080 D AdapterServiceConfig: Adding GattService
09-09 17:12:36.538  4080  4080 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 17:12:36.552   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@749142d:true
09-09 17:12:36.552  4080  4080 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 17:12:36.557  4080  4080 I bt_bluedroid: init
,09-09 17:12:36.559  4080  4092 I BluetoothAdapterState: Entering OffState
,09-09 17:12:36.564  4080  4093 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 17:12:36.565  4080  4093 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 17:12:36.565  4080  4093 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 17:12:36.565  4080  4093 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 17:12:36.567  4080  4080 I bt_bluedroid: get_profile_interface socket
,09-09 17:12:36.569  4080  4080 I bt_bluedroid: get_profile_interface sdp
,09-09 17:12:36.573  4080  4096 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 17:12:36.573  4080  4091 I bt_bluedroid: config_hci_snoop_log
09-09 17:12:36.576  4080  4096 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 17:12:36.576   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 17:12:36.585  4080  4092 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 17:12:36.585  4080  4092 D BluetoothAdapterProperties: Setting state to 14
,09-09 17:12:36.586  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 17:12:36.590  4080  4092 D BluetoothBondStateMachine: make
,09-09 17:12:36.596  4080  4097 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 17:12:36.603  4080  4092 I BluetoothAdapterState: Entering PendingCommandState
,09-09 17:12:36.605  4080  4080 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 17:12:36.611  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
09-09 17:12:36.612  4080  4080 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 17:12:36.613  4080  4080 D BtGatt.GattService: Received start request. Starting profile...
,09-09 17:12:36.613  4080  4080 D BtGatt.GattService: start()
09-09 17:12:36.613  4080  4080 I bt_bluedroid: get_profile_interface gatt
09-09 17:12:36.614  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
,09-09 17:12:36.614  4080  4080 D BtGatt.AdvertiseManager: advertise manager created
,09-09 17:12:36.625  4080  4080 V BluetoothAdapterState: isTurningOff()=false
09-09 17:12:36.626  4080  4080 V BluetoothAdapterState: isTurningOn()=false
,09-09 17:12:36.626  4080  4080 V BluetoothAdapterState: isBleTurningOn()=true
09-09 17:12:36.626  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:36.627  4080  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-09 17:12:36.627  4080  4092 I bt_bluedroid: enable
,09-09 17:12:36.628  4080  4093 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 17:12:36.629  4080  4093 I bt_hci  : start_up
,09-09 17:12:36.645  4080  4093 I bt_vendor: alloc value 0xb39dc189
,09-09 17:12:36.645  4080  4093 I bt_vendor: init
09-09 17:12:36.646  4080  4093 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-09 17:12:36.646  4080  4093 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 17:12:36.650  3058  4062 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-09 17:12:36.650  3058  4062 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 17:12:36.652  3058  4062 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-09 17:12:36.654   871  1414 I ActivityManager: Killing 3676:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 17:12:36.754  4080  4093 D bt_hci  : start_up starting async portion
09-09 17:12:36.755  4080  4100 I bt_hci  : event_finish_startup
,09-09 17:12:36.755  4080  4100 I bt_hci_h4: hal_open
09-09 17:12:36.755  4080  4100 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 17:12:36.764  4080  4100 I bt_userial_vendor: device fd = 51 open
,09-09 17:12:36.797  4080  4100 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 17:12:36.829  4080  4100 D bt_hwcfg: Chipset BCM4354A2
,09-09 17:12:36.829  4080  4100 D bt_hwcfg: Target name = [BCM4354A2]
,09-09 17:12:36.830  4080  4100 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 17:12:37.496  4080  4100 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 17:12:37.497  4080  4100 D bt_hwcfg: Settlement delay -- 100 ms
,09-09 17:12:37.498  4080  4100 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 17:12:37.615  4080  4100 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 17:12:37.617  4080  4100 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 17:12:37.645  4080  4100 I bt_hwcfg: vendor lib fwcfg completed
,09-09 17:12:37.645  4080  4100 I bt_vendor: firmware callback
09-09 17:12:37.645  4080  4100 I bt_hci  : firmware_config_callback
,09-09 17:12:37.658  4080  4103 I bt_btu  : btu_task pending for preload complete event
,09-09 17:12:37.658  4080  4103 I bt_btu_task: Bluetooth chip preload is complete
09-09 17:12:37.658  4080  4103 I bt_btu  : btu_task received preload complete event
,09-09 17:12:37.671  4080  4103 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 17:12:37.671  4080  4103 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 17:12:37.672  4080  4103 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 17:12:37.672  4080  4103 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 17:12:37.672  4080  4103 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 17:12:37.673  4080  4103 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 17:12:37.673  4080  4103 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 17:12:37.673  4080  4103 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 17:12:37.674  4080  4103 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 17:12:37.674  4080  4103 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 17:12:37.674  4080  4103 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 17:12:37.674  4080  4103 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 17:12:37.675  4080  4103 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 17:12:37.675  4080  4103 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 17:12:37.675  4080  4103 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 17:12:37.808  4080  4103 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3959d9d
,09-09 17:12:37.808  4080  4103 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3959d9d 
,09-09 17:12:37.824  4080  4096 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 17:12:37.827  4080  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 17:12:37.828  4080  4096 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 17:12:37.832  4080  4096 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 17:12:37.836  4080  4096 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:12:37.836  4080  4096 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 17:12:37.837  4080  4096 D bt_hci  : do_postload posting postload work item
,09-09 17:12:37.837  4080  4100 I bt_hci  : event_postload
,09-09 17:12:37.837  4080  4100 I bt_vendor: sco_config_cb
,09-09 17:12:37.837  4080  4100 I bt_hci  : sco_config_callback postload finished.
,09-09 17:12:37.840  4080  4096 D bt_bte_conf: Device ID record 1 : primary
,09-09 17:12:37.840  4080  4096 D bt_bte_conf:   vendorId            = 000f
,09-09 17:12:37.841  4080  4096 D bt_bte_conf:   vendorIdSource      = 0001
,09-09 17:12:37.841  4080  4096 D bt_bte_conf:   product             = 1200
09-09 17:12:37.841  4080  4096 D bt_bte_conf:   version             = 1436
,09-09 17:12:37.841  4080  4096 D bt_bte_conf:   clientExecutableURL = 
,09-09 17:12:37.841  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:37.841  4080  4096 D bt_bte_conf:   serviceDescription  = 
,09-09 17:12:37.842  4080  4096 D bt_bte_conf:   documentationURL    = 
09-09 17:12:37.842  4080  4096 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-09 17:12:37.842  4080  4093 D bt_stack_manager: event_start_up_stack finished
,09-09 17:12:37.844  4080  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 17:12:37.845  4080  4100 I bt_vendor: low_power_mode_cb
,09-09 17:12:37.845  4080  4092 D BluetoothAdapterProperties: Setting state to 15
09-09 17:12:37.845  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:37.845  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-09 17:12:37.846  4080  4092 I BluetoothAdapterState: Entering BleOnState
,09-09 17:12:37.852  4080  4092 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-09 17:12:37.853  4080  4092 D BluetoothAdapterProperties: Setting state to 11
09-09 17:12:37.853  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 17:12:37.862  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
09-09 17:12:37.867  4080  4080 D HeadsetService: Received start request. Starting profile...
,09-09 17:12:37.869  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:37.871  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:37.872  4080  4080 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 17:12:37.872  4080  4080 D HeadsetStateMachine: make
09-09 17:12:37.880  4080  4092 I BluetoothAdapterState: Entering PendingCommandState
,09-09 17:12:37.882  4080  4080 D HeadsetStateMachine: max_hf_connections = 1
,09-09 17:12:37.883  4080  4080 I bt_bluedroid: get_profile_interface handsfree
09-09 17:12:37.883  4080  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 17:12:37.883  4080  4096 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 17:12:37.886  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
,09-09 17:12:37.887  4080  4080 D A2dpService: Received start request. Starting profile...
09-09 17:12:37.887  4080  4080 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 17:12:37.888  4080  4080 I bt_bluedroid: get_profile_interface avrcp
,09-09 17:12:37.895  4080  4080 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 17:12:37.895  4080  4080 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 17:12:37.895  4080  4080 D A2dpStateMachine: make
09-09 17:12:37.896  4080  4080 I bt_bluedroid: get_profile_interface a2dp
,09-09 17:12:37.897  4080  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 17:12:37.897  4080  4112 D A2dpStateMachine: Enter Disconnected: -2
09-09 17:12:37.898  4080  4080 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 17:12:37.899  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
09-09 17:12:37.900  4080  4080 D HidService: Received start request. Starting profile...
09-09 17:12:37.900  4080  4080 I bt_bluedroid: get_profile_interface hidhost
,09-09 17:12:37.900  4080  4080 D HidService: setHidService(): set to: null
09-09 17:12:37.900  4080  4096 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb393b3e5
09-09 17:12:37.900  4080  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 17:12:37.901  4080  4080 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 17:12:37.902  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
09-09 17:12:37.902  4080  4080 D HealthService: Received start request. Starting profile...
,09-09 17:12:37.905  3841  3841 D BluetoothInputDevice: Proxy object connected
,09-09 17:12:37.905  3841  3841 D HidProfile: Bluetooth service connected
,09-09 17:12:37.907  4080  4080 I bt_bluedroid: get_profile_interface health
,09-09 17:12:37.908  4080  4080 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 17:12:37.909  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
,09-09 17:12:37.910  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:12:37.912  3841  3841 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 17:12:37.912  4080  4080 D PanService: Received start request. Starting profile...
,09-09 17:12:37.912  4080  4080 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 17:12:37.912  4080  4080 I bt_bluedroid: get_profile_interface pan
09-09 17:12:37.912  4080  4096 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 17:12:37.914  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
,09-09 17:12:37.916  4080  4080 D BluetoothMapService: Received start request. Starting profile...
,09-09 17:12:37.916  4080  4080 D BluetoothMapService: start()
,09-09 17:12:37.918  4080  4080 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 17:12:37.918  4080  4080 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-09 17:12:37.918  4080  4080 D BluetoothMapAppObserver: createReceiver()
,09-09 17:12:37.919  4080  4080 D BluetoothMapAppObserver: initObservers()
09-09 17:12:37.919  4080  4080 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 17:12:37.920  3841  3841 D PanProfile: Bluetooth service connected
,09-09 17:12:37.920  3841  3841 D BluetoothMap: Proxy object connected
09-09 17:12:37.921  3841  3841 D MapProfile: Bluetooth service connected
09-09 17:12:37.921  3841  3841 D BluetoothMap: getConnectedDevices()
09-09 17:12:37.921  3841  3841 D BluetoothMap: Bluetooth is Not enabled
,09-09 17:12:37.926  4080  4080 V BluetoothAdapterState: isTurningOff()=false
09-09 17:12:37.926  4080  4080 V BluetoothAdapterState: isTurningOn()=true
09-09 17:12:37.926  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:12:37.926  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:12:37.928  4080  4080 V BluetoothAdapterState: isTurningOff()=false
09-09 17:12:37.928  4080  4080 V BluetoothAdapterState: isTurningOn()=true
,09-09 17:12:37.928  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:12:37.928  4080  4110 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 17:12:37.928  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:37.928  4080  4080 V BluetoothAdapterState: isTurningOff()=false
09-09 17:12:37.928  4080  4080 V BluetoothAdapterState: isTurningOn()=true
,09-09 17:12:37.928  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:12:37.928  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:12:37.928  4080  4080 V BluetoothAdapterState: isTurningOff()=false
09-09 17:12:37.928  4080  4080 V BluetoothAdapterState: isTurningOn()=true
,09-09 17:12:37.928  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:12:37.928  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:37.929  4080  4080 V BluetoothAdapterState: isTurningOff()=false
09-09 17:12:37.929  4080  4080 V BluetoothAdapterState: isTurningOn()=true
09-09 17:12:37.929  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:12:37.929  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:12:37.930  4080  4080 V BluetoothAdapterState: isTurningOff()=false
09-09 17:12:37.930  4080  4080 V BluetoothAdapterState: isTurningOn()=true
09-09 17:12:37.930  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:12:37.930  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:37.930  4080  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 17:12:37.930  4080  4092 D BluetoothAdapterProperties: ScanMode =  20
09-09 17:12:37.931  4080  4092 D BluetoothAdapterProperties: State =  11
09-09 17:12:37.931  4080  4092 D BluetoothAdapterProperties: Setting state to 12
09-09 17:12:37.931  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 17:12:37.931   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 17:12:37.932  4080  4096 D BluetoothAdapterProperties: Scan Mode:21
09-09 17:12:37.932  4080  4092 I BluetoothAdapterState: Entering OnState
09-09 17:12:37.932  4080  4096 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:12:37.934   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:37.934  3841  3852 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 17:12:37.935   871   871 D BluetoothA2dp: Proxy object connected
09-09 17:12:37.935  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:37.935  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:37.935  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:37.935  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:37.935  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:37.935  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:37.935  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:37.935  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:37.937  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:12:37.938  1354  3772 D BluetoothPan: onBluetoothStateChange on: true
,09-09 17:12:37.940  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:37.940  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:37.940  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:37.940  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:37.940  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:37.940  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:37.940  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:37.940  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:12:37.941  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:12:37.941  1354  1354 D PanProfile: Bluetooth service connected
09-09 17:12:37.941  1354  1370 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 17:12:37.942  1354  1354 D BluetoothA2dp: Proxy object connected
,09-09 17:12:37.942  3841  3854 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 17:12:37.943  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:37.943   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:37.943  1935  2114 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:37.943  3841  3852 D BluetoothPan: onBluetoothStateChange on: true
09-09 17:12:37.944  1354  2027 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 17:12:37.945  1354  3772 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:37.945  1354  1371 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 17:12:37.946  4080  4080 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 17:12:37.946  4080  4080 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-09 17:12:37.947  1354  1354 D BluetoothInputDevice: Proxy object connected
09-09 17:12:37.947  1354  1354 D HidProfile: Bluetooth service connected
09-09 17:12:37.947  1354  3772 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 17:12:37.948  4080  4080 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:12:37.948  3841  3854 D BluetoothMap: onBluetoothStateChange: up=true
09-09 17:12:37.949  1354  1354 D BluetoothMap: Proxy object connected
09-09 17:12:37.949  1354  1354 D MapProfile: Bluetooth service connected
09-09 17:12:37.949  1354  1354 D BluetoothMap: getConnectedDevices()
,09-09 17:12:37.949   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:37.950   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 17:12:37.953  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:37.955  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:37.955  4080  4080 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:12:37.956  4080  4080 D ObexServerSockets: Succeed to create listening sockets 
,09-09 17:12:37.955  3841  3841 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 17:12:37.956  4080  4080 D ObexServerSockets0: startAccept()
,09-09 17:12:37.956  4080  4080 D ObexServerSockets0: prepareForNewConnect()
09-09 17:12:37.958  4080  4080 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 17:12:37.958  4080  4080 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 17:12:37.958  4080  4120 D ObexServerSockets0: Accepting socket connection...
09-09 17:12:37.958  4080  4080 D BluetoothMapService: onReceive
09-09 17:12:37.958  4080  4080 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:12:37.959  4080  4080 D BluetoothMapService: STATE_ON
09-09 17:12:37.959  4080  4121 D ObexServerSockets0: Accepting socket connection...
09-09 17:12:37.960  3841  3841 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-09 17:12:37.966  3841  3841 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:12:37.969  3841  3841 D BluetoothA2dp: Proxy object connected
,09-09 17:12:37.973  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:12:37.975  3841  3841 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:12:37.986  3841  3841 D BluetoothPbap: Proxy object connected
,09-09 17:12:37.986  1354  1354 D BluetoothPbap: Proxy object connected
09-09 17:12:37.986  1354  1354 D PbapServerProfile: Bluetooth service connected
,09-09 17:12:37.987  3841  3841 D PbapServerProfile: Bluetooth service connected
,09-09 17:12:37.991  4080  4080 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 17:12:37.991  4080  4080 D ObexServerSockets0: prepareForNewConnect()
,09-09 17:12:37.996  4080  4125 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:12:38.008  4080  4129 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:12:38.010  4080  4129 I BtOppRfcommListener: Accept thread started.
,09-09 17:12:38.035   871   871 D BluetoothHeadset: Proxy object connected
,09-09 17:12:38.036  1935  1953 D BluetoothHeadset: Proxy object connected
,09-09 17:12:38.036   871   871 D BluetoothHeadset: Proxy object connected
,09-09 17:12:38.037  1354  1370 D BluetoothHeadset: Proxy object connected
,09-09 17:12:38.037  1354  1354 D HeadsetProfile: Bluetooth service connected
09-09 17:12:38.040   871   871 D BluetoothHeadset: Proxy object connected
09-09 17:12:38.043   871   888 D BluetoothHeadset: Proxy object connected
,09-09 17:12:38.044  1935  1963 D BluetoothHeadset: Proxy object connected
,09-09 17:12:38.046  1354  2027 D BluetoothHeadset: Proxy object connected
,09-09 17:12:38.047  1354  1354 D HeadsetProfile: Bluetooth service connected
,09-09 17:12:38.049   871   888 D BluetoothHeadset: Proxy object connected
,09-09 17:12:38.062  3841  3854 D BluetoothHeadset: Proxy object connected
,09-09 17:12:38.063  3841  3841 D HeadsetProfile: Bluetooth service connected
,09-09 17:12:39.409  4080  4092 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 17:12:39.410  4080  4092 D BluetoothAdapterProperties: Setting state to 13
09-09 17:12:39.410  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 17:12:39.412  4080  4092 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 17:12:39.417  4080  4092 I BluetoothAdapterState: Entering PendingCommandState
,09-09 17:12:39.424  4080  4080 D BluetoothMapService: onReceive
,09-09 17:12:39.425  4080  4080 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:12:39.425  4080  4080 D BluetoothMapService: STATE_TURNING_OFF
09-09 17:12:39.425   871  1316 D ConnectivityService: handlePromptUnvalidated 101
09-09 17:12:39.425  4080  4080 D BluetoothMapService: MAP Service closeService in
09-09 17:12:39.426  4080  4080 D BluetoothMapMasInstance0: MAP Service shutdown
,09-09 17:12:39.426  4080  4080 D ObexServerSockets0: shutdown(block = true)
09-09 17:12:39.427  4080  4080 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 17:12:39.428  4080  4106 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 17:12:39.428  4080  4080 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-09 17:12:39.428  4080  4121 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 17:12:39.428  4080  4120 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 17:12:39.430  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:39.430  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:39.430  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:39.430  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:39.430  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:39.430  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:39.430  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:39.430  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:39.430  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:12:39.432  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:39.432  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:39.434  4080  4080 I BtOppRfcommListener: stopping Accept Thread
09-09 17:12:39.435  4080  4129 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:12:39.435  4080  4096 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:12:39.436  4080  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-09 17:12:39.437  4080  4129 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 17:12:39.438  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:39.438  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:39.438  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:39.438  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:39.438  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:39.438  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:12:39.438  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:39.438  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:39.438  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:39.440  3773  3773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:12:39.440  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:12:39.440  4080  4080 D HeadsetService: Received stop request...Stopping profile...
09-09 17:12:39.444  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:39.445  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:39.445  3841  3852 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:39.446   871   871 D BluetoothHeadset: Proxy object disconnected
,09-09 17:12:39.446  1935  2227 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:39.446   871   871 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:39.447  1354  2027 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:39.447  1354  1354 D HeadsetProfile: Bluetooth service disconnected
,09-09 17:12:39.447   871   871 D BluetoothHeadset: Proxy object disconnected
09-09 17:12:39.448  4080  4080 D A2dpService: Received stop request...Stopping profile...
09-09 17:12:39.448  4080  4112 D A2dpStateMachine: Exit Disconnected: -1
09-09 17:12:39.450  1354  1354 D BluetoothA2dp: Proxy object disconnected
09-09 17:12:39.450   871   871 D BluetoothA2dp: Proxy object disconnected
,09-09 17:12:39.451  4080  4080 D HidService: Received stop request...Stopping profile...
09-09 17:12:39.451  4080  4080 D HidService: Stopping Bluetooth HidService
09-09 17:12:39.452  1354  1354 D BluetoothInputDevice: Proxy object disconnected
09-09 17:12:39.452  1354  1354 D HidProfile: Bluetooth service disconnected
09-09 17:12:39.453  4080  4080 D HealthService: Received stop request...Stopping profile...
,09-09 17:12:39.453  3841  3841 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:12:39.455  4080  4080 D PanService: Received stop request...Stopping profile...
,09-09 17:12:39.456  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 17:12:39.456  1354  1354 D PanProfile: Bluetooth service disconnected
,09-09 17:12:39.457  4080  4080 V BluetoothAdapterState: isTurningOff()=true
,09-09 17:12:39.458  4080  4080 V BluetoothAdapterState: isTurningOn()=false
09-09 17:12:39.458  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:12:39.458  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:39.459  3841  3841 D HeadsetProfile: Bluetooth service disconnected
09-09 17:12:39.460  3841  3841 D BluetoothA2dp: Proxy object disconnected
,09-09 17:12:39.460  4080  4080 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 17:12:39.460  4080  4080 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:12:39.460  4080  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 17:12:39.460  4080  4103 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 17:12:39.460  4080  4103 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:12:39.460  4080  4103 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 17:12:39.460  4080  4096 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
,09-09 17:12:39.461  3841  3841 D BluetoothInputDevice: Proxy object disconnected
09-09 17:12:39.461  3841  3841 D HidProfile: Bluetooth service disconnected
09-09 17:12:39.462  4080  4080 D BluetoothMapService: Received stop request...Stopping profile...
09-09 17:12:39.462  4080  4080 D BluetoothMapService: stop()
09-09 17:12:39.463  4080  4080 D BluetoothMapAppObserver: deinitObservers()
09-09 17:12:39.463  4080  4080 D BluetoothMapAppObserver: removeReceiver()
,09-09 17:12:39.464  1354  1354 D BluetoothMap: Proxy object disconnected
,09-09 17:12:39.464  1354  1354 D MapProfile: Bluetooth service disconnected
,09-09 17:12:39.464  4080  4080 V BluetoothAdapterState: isTurningOff()=true
09-09 17:12:39.465  3841  3841 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 17:12:39.466  4080  4080 V BluetoothAdapterState: isTurningOn()=false
,09-09 17:12:39.466  3841  3841 D PanProfile: Bluetooth service disconnected
,09-09 17:12:39.466  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:12:39.466  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:39.467  4080  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 17:12:39.467  4080  4103 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 17:12:39.467  4080  4103 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 17:12:39.467  4080  4080 V BluetoothAdapterState: isTurningOff()=true
,09-09 17:12:39.467  4080  4103 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 17:12:39.467  4080  4080 V BluetoothAdapterState: isTurningOn()=false
,09-09 17:12:39.468  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:12:39.468  3841  3841 D DockEventReceiver: finishStartingService: stopping service
09-09 17:12:39.468  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:12:39.468  4080  4103 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:12:39.468  4080  4103 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:12:39.468  4080  4103 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 17:12:39.468  4080  4080 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-09 17:12:39.468  4080  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 17:12:39.468  4080  4080 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object,
09-09 17:12:39.468  3841  3841 D BluetoothMap: Proxy object disconnected
,09-09 17:12:39.468  3841  3841 D MapProfile: Bluetooth service disconnected
09-09 17:12:39.468  4080  4080 V BluetoothAdapterState: isTurningOff()=true
09-09 17:12:39.469  4080  4080 V BluetoothAdapterState: isTurningOn()=false
,09-09 17:12:39.469  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:12:39.469  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:12:39.469  4080  4080 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 17:12:39.469  4080  4096 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 17:12:39.469  4080  4080 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-09 17:12:39.469  4080  4080 V BluetoothAdapterState: isTurningOff()=true
09-09 17:12:39.469  4080  4080 V BluetoothAdapterState: isTurningOn()=false
09-09 17:12:39.470  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:12:39.470  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:39.470  4080  4080 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-09 17:12:39.470  4080  4080 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 17:12:39.472  4080  4080 D BluetoothMapService: MAP Service closeService in
09-09 17:12:39.473  4080  4080 V BluetoothAdapterState: isTurningOff()=true
09-09 17:12:39.473  4080  4080 V BluetoothAdapterState: isTurningOn()=false
09-09 17:12:39.473  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:12:39.473  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:12:39.473  4080  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 17:12:39.473  4080  4092 D BluetoothAdapterProperties: Setting state to 15
,09-09 17:12:39.473  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-09 17:12:39.473  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:12:39.473  4080  4092 I BluetoothAdapterState: Entering BleOnState
09-09 17:12:39.474   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:12:39.474   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:39.474  4080  4080 D BluetoothMapService: cleanup()
,09-09 17:12:39.474  4080  4080 D BluetoothMapService: MAP Service closeService in
09-09 17:12:39.474  3841  3852 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 17:12:39.476  1354  1354 D BluetoothPbap: Proxy object disconnected
09-09 17:12:39.476  1354  1354 D PbapServerProfile: Bluetooth service disconnected
09-09 17:12:39.476  1354  2027 D BluetoothPan: onBluetoothStateChange on: false
09-09 17:12:39.477  1354  1371 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:12:39.481  3841  3854 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 17:12:39.481   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:39.482  1935  2226 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:39.482  3841  4132 D BluetoothPan: onBluetoothStateChange on: false
09-09 17:12:39.482  1354  3772 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 17:12:39.483  1354  1370 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:39.483  1354  2027 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 17:12:39.484  1354  1371 D BluetoothMap: onBluetoothStateChange: up=false
09-09 17:12:39.484  3841  3852 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 17:12:39.485  3841  3854 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 17:12:39.485   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:12:39.485  3841  4132 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:12:39.486  4080  4092 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 17:12:39.486  4080  4092 D BluetoothAdapterProperties: Setting state to 16
09-09 17:12:39.486  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 17:12:39.487  4080  4092 D BluetoothAdapterProperties: onBleDisable
,09-09 17:12:39.487  4080  4092 I BluetoothAdapterState: Entering PendingCommandState
09-09 17:12:39.487  4080  4093 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 17:12:39.488  4080  4103 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 17:12:39.488  4080  4103 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:12:39.489  4080  4096 D BluetoothAdapterProperties: Scan Mode:20
,09-09 17:12:39.490  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:39.491  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:39.491  3841  3841 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 17:12:39.493  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:39.494  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:39.495  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:12:39.499  3841  3841 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:12:39.689  4080  4096 I bt_hci  : shut_down
,09-09 17:12:39.689  4080  4100 D bt_hwcfg: hw_epilog_process
,09-09 17:12:39.692  4080  4100 I bt_vendor: low_power_mode_cb
,09-09 17:12:39.713  4080  4100 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 17:12:39.714  4080  4100 I bt_vendor: epilog_cb
09-09 17:12:39.714  4080  4100 I bt_hci  : epilog_finished_callback
,09-09 17:12:39.723  4080  4096 I bt_hci_h4: hal_close
,09-09 17:12:39.725  4080  4096 I bt_userial_vendor: device fd = 51 close
,09-09 17:12:39.849  4080  4093 D bt_stack_manager: event_shut_down_stack finished.
,09-09 17:12:39.851  4080  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 17:12:39.856  4080  4092 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-09 17:12:39.856  4080  4080 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 17:12:39.858  4080  4080 D BtGatt.GattService: Received stop request...Stopping profile...
,09-09 17:12:39.858  4080  4080 D BtGatt.GattService: stop()
09-09 17:12:39.859  4080  4080 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 17:12:39.863  4080  4080 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:12:39.864  4080  4080 V BluetoothAdapterState: isTurningOn()=false
09-09 17:12:39.864  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:12:39.864  4080  4080 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 17:12:39.865  4080  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-09 17:12:39.866  4080  4092 D BluetoothAdapterProperties: Setting state to 10
09-09 17:12:39.866  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 17:12:39.868  4080  4092 I BluetoothAdapterState: Entering OffState
09-09 17:12:39.869   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 17:12:39.894  4080  4080 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 17:12:39.895  4080  4080 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 17:12:39.895  4080  4093 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 17:12:39.906  4080  4080 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 17:12:39.910  4080  4093 D bt_stack_manager: event_clean_up_stack finished.
,09-09 17:12:39.916  4080  4080 I art     : System.exit called, status: 0
,09-09 17:12:39.916  4080  4080 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 17:12:39.970   871  1964 I ActivityManager: Process com.android.bluetooth (pid 4080) has died
,09-09 17:12:42.406  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:12:42.407  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:45.416  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:12:45.417  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c74739f added. We now have 6 listener(s)
09-09 17:12:45.417  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:12:45.421  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:12:45.422  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c9dcec added. We now have 7 listener(s)
09-09 17:12:45.422  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:45.424  3773  3824 I System.out: IsBluetoothEnabled
,09-09 17:12:45.436  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:45.488   871   888 I ActivityManager: Start proc 4141:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 17:12:45.672  4141  4141 D AdapterServiceConfig: Adding HeadsetService
09-09 17:12:45.672  4141  4141 D AdapterServiceConfig: Adding A2dpService
09-09 17:12:45.672  4141  4141 D AdapterServiceConfig: Adding HidService
09-09 17:12:45.672  4141  4141 D AdapterServiceConfig: Adding HealthService
,09-09 17:12:45.672  4141  4141 D AdapterServiceConfig: Adding PanService
,09-09 17:12:45.672  4141  4141 D AdapterServiceConfig: Adding GattService
09-09 17:12:45.673  4141  4141 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 17:12:45.687  4141  4141 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 17:12:45.686   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@acc0c96:true
,09-09 17:12:45.691  4141  4141 I bt_bluedroid: init
09-09 17:12:45.692  4141  4153 I BluetoothAdapterState: Entering OffState
,09-09 17:12:45.698  4141  4154 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 17:12:45.698  4141  4154 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 17:12:45.698  4141  4154 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 17:12:45.699  4141  4154 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 17:12:45.701  4141  4141 I bt_bluedroid: get_profile_interface socket
,09-09 17:12:45.704  4141  4157 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 17:12:45.706  4141  4157 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 17:12:45.706  4141  4141 I bt_bluedroid: get_profile_interface sdp
,09-09 17:12:45.712  4141  4152 I bt_bluedroid: config_hci_snoop_log
,09-09 17:12:45.715   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 17:12:45.725  4141  4153 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 17:12:45.726  4141  4153 D BluetoothAdapterProperties: Setting state to 14
,09-09 17:12:45.726  4141  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 17:12:45.731  4141  4153 D BluetoothBondStateMachine: make
,09-09 17:12:45.734  4141  4158 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 17:12:45.743  4141  4153 I BluetoothAdapterState: Entering PendingCommandState
,09-09 17:12:45.744  4141  4141 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 17:12:45.752  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
,09-09 17:12:45.753  4141  4141 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 17:12:45.755  4141  4141 D BtGatt.GattService: Received start request. Starting profile...
,09-09 17:12:45.755  4141  4141 D BtGatt.GattService: start()
,09-09 17:12:45.756  4141  4141 I bt_bluedroid: get_profile_interface gatt
,09-09 17:12:45.758  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
,09-09 17:12:45.758  4141  4141 D BtGatt.AdvertiseManager: advertise manager created
,09-09 17:12:45.774  4141  4141 V BluetoothAdapterState: isTurningOff()=false
09-09 17:12:45.774  4141  4141 V BluetoothAdapterState: isTurningOn()=false
,09-09 17:12:45.774  4141  4141 V BluetoothAdapterState: isBleTurningOn()=true
09-09 17:12:45.774  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:45.776  4141  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-09 17:12:45.778  4141  4153 I bt_bluedroid: enable
,09-09 17:12:45.778  4141  4154 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-09 17:12:45.779  4141  4154 I bt_hci  : start_up
,09-09 17:12:45.799  4141  4154 I bt_vendor: alloc value 0xb39dc189
,09-09 17:12:45.799  4141  4154 I bt_vendor: init
,09-09 17:12:45.799  4141  4154 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-09 17:12:45.799  4141  4154 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 17:12:45.908  4141  4154 D bt_hci  : start_up starting async portion
,09-09 17:12:45.909  4141  4161 I bt_hci  : event_finish_startup
09-09 17:12:45.910  4141  4161 I bt_hci_h4: hal_open
,09-09 17:12:45.910  4141  4161 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 17:12:45.922  4141  4161 I bt_userial_vendor: device fd = 51 open
,09-09 17:12:45.953  4141  4161 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 17:12:45.983  4141  4161 D bt_hwcfg: Chipset BCM4354A2
,09-09 17:12:45.983  4141  4161 D bt_hwcfg: Target name = [BCM4354A2]
09-09 17:12:45.984  4141  4161 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 17:12:46.859  4141  4161 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 17:12:46.860  4141  4161 D bt_hwcfg: Settlement delay -- 100 ms
09-09 17:12:46.860  4141  4161 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 17:12:46.978  4141  4161 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 17:12:46.980  4141  4161 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 17:12:47.008  4141  4161 I bt_hwcfg: vendor lib fwcfg completed
,09-09 17:12:47.009  4141  4161 I bt_vendor: firmware callback
,09-09 17:12:47.009  4141  4161 I bt_hci  : firmware_config_callback
,09-09 17:12:47.021  4141  4163 I bt_btu  : btu_task pending for preload complete event
,09-09 17:12:47.021  4141  4163 I bt_btu_task: Bluetooth chip preload is complete
,09-09 17:12:47.021  4141  4163 I bt_btu  : btu_task received preload complete event
,09-09 17:12:47.031  4141  4163 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 17:12:47.031  4141  4163 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 17:12:47.031  4141  4163 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 17:12:47.032  4141  4163 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 17:12:47.032  4141  4163 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 17:12:47.032  4141  4163 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 17:12:47.032  4141  4163 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-09 17:12:47.033  4141  4163 I         : BTE_InitTraceLevels -- TRC_BTM
,09-09 17:12:47.033  4141  4163 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 17:12:47.034  4141  4163 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 17:12:47.034  4141  4163 I         : BTE_InitTraceLevels -- TRC_SDP
,09-09 17:12:47.035  4141  4163 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 17:12:47.036  4141  4163 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 17:12:47.037  4141  4163 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-09 17:12:47.038  4141  4163 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 17:12:47.174  4141  4163 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3959d9d
,09-09 17:12:47.174  4141  4163 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3959d9d 
,09-09 17:12:47.185  4141  4157 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-09 17:12:47.187  4141  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 17:12:47.187  4141  4157 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-09 17:12:47.190  4141  4157 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 17:12:47.193  4141  4157 D BluetoothAdapterProperties: Scan Mode:20
,09-09 17:12:47.194  4141  4157 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:12:47.194  4141  4157 D bt_hci  : do_postload posting postload work item
09-09 17:12:47.195  4141  4161 I bt_hci  : event_postload
,09-09 17:12:47.195  4141  4161 I bt_vendor: sco_config_cb
09-09 17:12:47.195  4141  4161 I bt_hci  : sco_config_callback postload finished.
,09-09 17:12:47.198  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:47.198  4141  4157 D bt_bte_conf: Device ID record 1 : primary
09-09 17:12:47.198  4141  4157 D bt_bte_conf:   vendorId            = 000f
,09-09 17:12:47.198  4141  4157 D bt_bte_conf:   vendorIdSource      = 0001
,09-09 17:12:47.198  4141  4157 D bt_bte_conf:   product             = 1200
09-09 17:12:47.198  4141  4157 D bt_bte_conf:   version             = 1436
09-09 17:12:47.199  4141  4157 D bt_bte_conf:   clientExecutableURL = 
09-09 17:12:47.199  4141  4157 D bt_bte_conf:   serviceDescription  = 
09-09 17:12:47.199  4141  4157 D bt_bte_conf:   documentationURL    = 
09-09 17:12:47.199  4141  4157 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 17:12:47.200  4141  4154 D bt_stack_manager: event_start_up_stack finished
09-09 17:12:47.201  4141  4161 I bt_vendor: low_power_mode_cb
09-09 17:12:47.202  4141  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 17:12:47.202  4141  4153 D BluetoothAdapterProperties: Setting state to 15
,09-09 17:12:47.203  4141  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-09 17:12:47.210  4141  4153 I BluetoothAdapterState: Entering BleOnState
09-09 17:12:47.210  4141  4153 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-09 17:12:47.211  4141  4153 D BluetoothAdapterProperties: Setting state to 11
,09-09 17:12:47.211  4141  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 17:12:47.220  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
,09-09 17:12:47.221  4141  4141 D HeadsetService: Received start request. Starting profile...
,09-09 17:12:47.227  4141  4141 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-09 17:12:47.227  4141  4141 D HeadsetStateMachine: make
,09-09 17:12:47.235  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:47.240  4141  4141 D HeadsetStateMachine: max_hf_connections = 1
,09-09 17:12:47.240  4141  4141 I bt_bluedroid: get_profile_interface handsfree
,09-09 17:12:47.241  4141  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-09 17:12:47.241  4141  4157 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 17:12:47.246  4141  4153 I BluetoothAdapterState: Entering PendingCommandState
09-09 17:12:47.245  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
09-09 17:12:47.247  4141  4141 D A2dpService: Received start request. Starting profile...
09-09 17:12:47.247  4141  4141 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 17:12:47.248  4141  4141 I bt_bluedroid: get_profile_interface avrcp
,09-09 17:12:47.254  4141  4141 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 17:12:47.256  4141  4141 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 17:12:47.256  4141  4141 D A2dpStateMachine: make
,09-09 17:12:47.257  4141  4141 I bt_bluedroid: get_profile_interface a2dp
,09-09 17:12:47.258  4141  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 17:12:47.259  4141  4141 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 17:12:47.260  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
,09-09 17:12:47.261  4141  4141 D HidService: Received start request. Starting profile...
,09-09 17:12:47.261  4141  4141 I bt_bluedroid: get_profile_interface hidhost
,09-09 17:12:47.261  4141  4141 D HidService: setHidService(): set to: null
09-09 17:12:47.262  4141  4157 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb393b3e5,
09-09 17:12:47.262  4141  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-09 17:12:47.262  4141  4171 D A2dpStateMachine: Enter Disconnected: -2
,09-09 17:12:47.264  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:12:47.266  4141  4141 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 17:12:47.267  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
,09-09 17:12:47.268  4141  4141 D HealthService: Received start request. Starting profile...
,09-09 17:12:47.270  4141  4141 I bt_bluedroid: get_profile_interface health
,09-09 17:12:47.271  4141  4141 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 17:12:47.272  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
,09-09 17:12:47.272  4141  4141 D PanService: Received start request. Starting profile...
,09-09 17:12:47.273  4141  4141 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-09 17:12:47.273  4141  4141 I bt_bluedroid: get_profile_interface pan
,09-09 17:12:47.274  4141  4157 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 17:12:47.279  4141  4141 V BluetoothAdapterState: isTurningOff()=false
09-09 17:12:47.279  4141  4141 V BluetoothAdapterState: isTurningOn()=true
09-09 17:12:47.279  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:12:47.279  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:47.279  4141  4169 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 17:12:47.284  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
,09-09 17:12:47.285  4141  4141 D BluetoothMapService: Received start request. Starting profile...
09-09 17:12:47.285  4141  4141 D BluetoothMapService: start()
,09-09 17:12:47.293  4141  4141 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 17:12:47.295  4141  4141 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 17:12:47.295  4141  4141 D BluetoothMapAppObserver: createReceiver()
,09-09 17:12:47.297  4141  4141 D BluetoothMapAppObserver: initObservers()
,09-09 17:12:47.297  4141  4141 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 17:12:47.305  4141  4141 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:12:47.305  4141  4141 V BluetoothAdapterState: isTurningOn()=true
09-09 17:12:47.305  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:12:47.305  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:12:47.306  4141  4141 V BluetoothAdapterState: isTurningOff()=false
09-09 17:12:47.306  4141  4141 V BluetoothAdapterState: isTurningOn()=true
,09-09 17:12:47.306  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:12:47.306  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:47.309  4141  4141 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:12:47.309  4141  4141 V BluetoothAdapterState: isTurningOn()=true
,09-09 17:12:47.309  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:12:47.309  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:12:47.310  4141  4141 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:12:47.310  4141  4141 V BluetoothAdapterState: isTurningOn()=true
,09-09 17:12:47.310  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:12:47.310  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:12:47.310  4141  4141 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:12:47.310  4141  4141 V BluetoothAdapterState: isTurningOn()=true
09-09 17:12:47.310  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:12:47.310  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:12:47.311  4141  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-09 17:12:47.311  4141  4153 D BluetoothAdapterProperties: ScanMode =  20
,09-09 17:12:47.311  4141  4153 D BluetoothAdapterProperties: State =  11
09-09 17:12:47.311  4141  4153 D BluetoothAdapterProperties: Setting state to 12
,09-09 17:12:47.311  4141  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 17:12:47.312   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:12:47.312  4141  4153 I BluetoothAdapterState: Entering OnState
09-09 17:12:47.313  4141  4157 D BluetoothAdapterProperties: Scan Mode:21
09-09 17:12:47.313  4141  4157 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:12:47.314   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 17:12:47.314  3841  4132 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 17:12:47.315   871   871 D BluetoothA2dp: Proxy object connected
09-09 17:12:47.316  1354  2027 D BluetoothPan: onBluetoothStateChange on: true
09-09 17:12:47.318  1354  1371 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:12:47.318  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:47.318  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:47.318  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:47.318  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:47.318  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:47.318  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:47.318  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:47.318  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:12:47.319  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:12:47.319  1354  1354 D PanProfile: Bluetooth service connected
,09-09 17:12:47.320  1354  1354 D BluetoothA2dp: Proxy object connected
09-09 17:12:47.320  3841  3852 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 17:12:47.321  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:12:47.321   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:47.322  1935  2227 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 17:12:47.322  3841  4132 D BluetoothPan: onBluetoothStateChange on: true
09-09 17:12:47.323  3841  3841 D BluetoothInputDevice: Proxy object connected
09-09 17:12:47.324  3841  3841 D HidProfile: Bluetooth service connected
09-09 17:12:47.325  1354  1370 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 17:12:47.325  4141  4141 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 17:12:47.325  4141  4141 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 17:12:47.326  1354  3772 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:47.327  1354  2027 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 17:12:47.328  4141  4141 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:12:47.329  1354  1354 D BluetoothInputDevice: Proxy object connected
09-09 17:12:47.329  1354  1354 D HidProfile: Bluetooth service connected
09-09 17:12:47.329  1354  1370 D BluetoothMap: onBluetoothStateChange: up=true
09-09 17:12:47.331  3841  3841 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:12:47.331  3841  3841 D PanProfile: Bluetooth service connected
09-09 17:12:47.331  3841  3854 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:12:47.332  4141  4141 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:12:47.332  3841  3852 D BluetoothMap: onBluetoothStateChange: up=true
09-09 17:12:47.334  4141  4141 D ObexServerSockets: Succeed to create listening sockets 
09-09 17:12:47.334  4141  4141 D ObexServerSockets0: startAccept()
09-09 17:12:47.334  4141  4141 D ObexServerSockets0: prepareForNewConnect()
09-09 17:12:47.335   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 17:12:47.335  3841  4132 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:12:47.336  4141  4141 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 17:12:47.336  4141  4141 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 17:12:47.338  4141  4179 D ObexServerSockets0: Accepting socket connection...
09-09 17:12:47.338  1354  1354 D BluetoothMap: Proxy object connected
09-09 17:12:47.338  1354  1354 D MapProfile: Bluetooth service connected
09-09 17:12:47.338  1354  1354 D BluetoothMap: getConnectedDevices()
09-09 17:12:47.339  3841  3841 D BluetoothA2dp: Proxy object connected
,09-09 17:12:47.339   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 17:12:47.340  4141  4141 D BluetoothMapService: onReceive
,09-09 17:12:47.340  4141  4141 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:12:47.341  4141  4141 D BluetoothMapService: STATE_ON
,09-09 17:12:47.341  4141  4178 D ObexServerSockets0: Accepting socket connection...
09-09 17:12:47.342  3841  3841 D BluetoothMap: Proxy object connected
09-09 17:12:47.343  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:47.343  3841  3841 D MapProfile: Bluetooth service connected
,09-09 17:12:47.343  3841  3841 D BluetoothMap: getConnectedDevices()
09-09 17:12:47.352  3841  3841 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 17:12:47.361  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:12:47.363  3841  3841 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:12:47.374  1354  1354 D BluetoothPbap: Proxy object connected
09-09 17:12:47.374  3841  3841 D BluetoothPbap: Proxy object connected
09-09 17:12:47.374  1354  1354 D PbapServerProfile: Bluetooth service connected
,09-09 17:12:47.374  3841  3841 D PbapServerProfile: Bluetooth service connected
09-09 17:12:47.375  4141  4141 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 17:12:47.375  4141  4141 D ObexServerSockets0: prepareForNewConnect()
,09-09 17:12:47.382  4141  4185 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:12:47.401  4141  4189 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:12:47.403  4141  4189 I BtOppRfcommListener: Accept thread started.
,09-09 17:12:47.415  3841  3852 D BluetoothHeadset: Proxy object connected
,09-09 17:12:47.415  3841  3841 D HeadsetProfile: Bluetooth service connected
09-09 17:12:47.415   871   871 D BluetoothHeadset: Proxy object connected,
09-09 17:12:47.416  1935  2226 D BluetoothHeadset: Proxy object connected
09-09 17:12:47.416   871   871 D BluetoothHeadset: Proxy object connected
,09-09 17:12:47.416  1354  3772 D BluetoothHeadset: Proxy object connected
09-09 17:12:47.417   871   871 D BluetoothHeadset: Proxy object connected
09-09 17:12:47.417  1354  1354 D HeadsetProfile: Bluetooth service connected
,09-09 17:12:47.422   871   888 D BluetoothHeadset: Proxy object connected,
09-09 17:12:47.422  1935  2114 D BluetoothHeadset: Proxy object connected
,09-09 17:12:47.427  1354  1371 D BluetoothHeadset: Proxy object connected
,09-09 17:12:47.428  1354  1354 D HeadsetProfile: Bluetooth service connected
,09-09 17:12:47.432  3841  3854 D BluetoothHeadset: Proxy object connected
,09-09 17:12:47.432  3841  3841 D HeadsetProfile: Bluetooth service connected
,09-09 17:12:47.434   871   888 D BluetoothHeadset: Proxy object connected
,09-09 17:12:47.454  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:47.454  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:47.454  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:47.454  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:12:47.454  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:47.454  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:47.454  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:47.454  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:12:47.458  3773  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:12:47.459  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:47.459  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5cb28b5 added. We now have 8 listener(s)
09-09 17:12:47.459  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:12:47.461   871  1389 D WifiService: setWifiEnabled: false pid=3773, uid=10000
09-09 17:12:47.462   871  1389 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:12:47.482  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:47.483   871  3894 D WifiService: setWifiEnabled: true pid=3773, uid=10000
09-09 17:12:47.483   871  3894 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:12:47.488   871  1314 D WifiConfigStore: Loading config and enabling all networks 
,09-09 17:12:47.503  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:47.503  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:47.503  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:47.503  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:47.503  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:47.503  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:47.503  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:47.503  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:12:47.505   871  1314 D WifiConfigStore: loaded 0 passpoint configs
09-09 17:12:47.506   871  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-09 17:12:47.506   871  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 17:12:47.507   871  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 17:12:47.507   871  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 17:12:47.507   871  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 17:12:47.507   871  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-09 17:12:47.507  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:47.507  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:47.507  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:47.507  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:47.507  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:47.507  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:47.507  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:47.507  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:12:47.510  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:12:47.519  3773  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:12:47.522  3773  3824 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-09 17:12:47.522  3773  3824 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 17:12:47.524  3773  3824 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b93a13d Bundle[{}]
,09-09 17:12:47.524   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-09 17:12:47.524  3773  3824 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 17:12:47.524  3773  3824 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 17:12:47.525   871  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.51 rxSuccessRate=1.20 delta 1000 -> 1000
,09-09 17:12:47.525  3773  3824 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 17:12:47.525  3773  3824 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 17:12:47.525  3773  3824 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 17:12:47.526  3773  3824 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-09 17:12:47.526   372   869 D CommandListener: Setting iface cfg
,09-09 17:12:47.527   871  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-09 17:12:47.528   871  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 17:12:47.528  3773  3824 I System.out: Running OutgoingSocketThread,
09-09 17:12:47.530  3773  4194 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 416)
09-09 17:12:47.531  3773  4194 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47004
09-09 17:12:47.531  3773  4194 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 17:12:47.533   871  1313 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 17:12:47.540   871  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-09 17:12:47.540   871  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:12:47.540   871  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 17:12:47.549   871  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 17:12:47.639   871  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 17:12:47.641  1474  1474 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 17:12:48.102  1474  1474 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 17:12:48.154  1474  1474 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 17:12:48.157  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 17:12:48.161   871  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 17:12:48.177   871  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 17:12:48.207   871  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:12:48.207   871  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 17:12:48.240   871  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:12:48.264   372   869 D CommandListener: Setting iface cfg
,09-09 17:12:48.265   871  1314 D WifiStateMachine: Start Dhcp Watchdog 3
,09-09 17:12:48.286   871  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 17:12:48.286   871  1316 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-09 17:12:48.294   871  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 17:12:48.325   871  4197 D DhcpClient: Receive thread started
,09-09 17:12:48.406   871  1314 E native  : do suspend false
,09-09 17:12:48.429   871  1890 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 17:12:48.449   871  4197 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-09 17:12:48.450   871  1890 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-09 17:12:48.454   871  1890 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 17:12:48.472   871  4197 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 17:12:48.473   871  1890 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 17:12:48.478   372   869 D CommandListener: Setting iface cfg
,09-09 17:12:48.489   871  1890 D DhcpClient: Scheduling renewal in 86399s
,09-09 17:12:48.490   871  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 17:12:48.510   871  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 17:12:48.514   871  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 17:12:48.515   871  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 17:12:48.517   871  1316 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 17:12:48.535  3773  3824 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 417)
,09-09 17:12:48.535  3773  3824 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 417)
09-09 17:12:48.539   871  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 17:12:48.550  3773  3824 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
,09-09 17:12:48.551  3773  3824 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-09 17:12:48.551  3773  3824 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 423)
,09-09 17:12:48.553  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 17:12:48.553  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee5ab4a added. We now have 2 listener(s)
09-09 17:12:48.555  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 17:12:48.555  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:48.555  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 17:12:48.556  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:48.556  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@736aabb added. We now have 9 listener(s)
09-09 17:12:48.556  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:48.556  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:12:48.559  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:12:48.562  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:48.562  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:48.562  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:48.562  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:48.562  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:48.562  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:48.562  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:48.562  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:12:48.565  3773  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:12:48.565  3773  3824 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:12:48.566  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 17:12:48.566  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c529b31 added. We now have 3 listener(s)
,09-09 17:12:48.567  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:48.569  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:48.571  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 17:12:48.571  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 17:12:48.571  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 17:12:48.571  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:12:48.571  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35b3216 added. We now have 10 listener(s)
,09-09 17:12:48.572  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:48.572  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:12:48.572  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:12:48.572  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:48.573  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,09-09 17:12:48.573  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.573  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:48.573  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:48.573  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee5ab4a removed from the list
,09-09 17:12:48.573  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:48.573  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@736aabb removed from the list
09-09 17:12:48.573  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:48.573  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:48.574  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.574  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:48.575  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:48.575  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:48.575  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:48.575  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@736aabb not in the list
09-09 17:12:48.575  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.575  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:48.576  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:48.576  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:48.576  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:48.576  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35b3216 removed from the list
09-09 17:12:48.576  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:48.576  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.576  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:48.577  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:48.577  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c529b31 removed from the list
09-09 17:12:48.577   871  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 17:12:48.578   871  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-09 17:12:48.578  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:48.578  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1b3797 added. We now have 2 listener(s)
09-09 17:12:48.579   871  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-09 17:12:48.580   871  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-09 17:12:48.581  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 17:12:48.581  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:48.581  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:48.581   871  1316 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-09 17:12:48.582  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:48.582  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e50dd84 added. We now have 9 listener(s)
09-09 17:12:48.582  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:12:48.583  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:12:48.587  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:12:48.588   871  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 17:12:48.591  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:48.591  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:48.591  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:48.591  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:48.591  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:48.591  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:12:48.591  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:12:48.591  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:12:48.593  3773  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:12:48.593   871  1316 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-09 17:12:48.593   871  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-09 17:12:48.593  3773  3824 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:12:48.593   871  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-09 17:12:48.593   871  1316 D ConnectivityService:    accepting network in place of null
09-09 17:12:48.594  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 17:12:48.594  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd059a2 added. We now have 3 listener(s)
,09-09 17:12:48.594   871  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-09 17:12:48.595   871  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 17:12:48.595   871  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 17:12:48.596  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 17:12:48.596  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 17:12:48.596  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 17:12:48.596  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:48.597  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251b633 added. We now have 10 listener(s)
,09-09 17:12:48.597  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:12:48.597  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 17:12:48.597  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:12:48.598  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
09-09 17:12:48.598  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:48.598  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 17:12:48.598  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:48.598  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:48.598  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:48.598  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:48.598  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:48.598  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:48.598  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:48.598  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:12:48.601  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:48.601  3773  3824 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 17:12:48.601  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:12:48.603  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:48.605  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:12:48.606  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 17:12:48.606  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:12:48.610  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 17:12:48.610  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 17:12:48.610  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 17:12:48.611  3773  3824 D BluetoothAdapter: STATE_ON
,09-09 17:12:48.613  4141  4180 D BtGatt.GattService: registerClient() - UUID=a5860133-74ff-4c0b-aae1-5bdcc5424a6e
,09-09 17:12:48.613  4141  4157 D BtGatt.GattService: onClientRegistered() - UUID=a5860133-74ff-4c0b-aae1-5bdcc5424a6e, clientIf=5
09-09 17:12:48.614  3773  3783 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 17:12:48.614  4141  4151 D BtGatt.GattService: start scan with filters
,09-09 17:12:48.617  4141  4160 D BtGatt.ScanManager: handling starting scan
09-09 17:12:48.617  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 17:12:48.617  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:12:48.617  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 17:12:48.617  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 17:12:48.618  4141  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a93a601
,09-09 17:12:48.619  4141  4157 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 17:12:48.619  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.619  4141  4160 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 17:12:48.620  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:12:48.620  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 17:12:48.620  3773  3773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:12:48.621  4141  4157 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 17:12:48.621  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:48.621  4141  4160 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 17:12:48.621  4141  4160 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 17:12:48.622  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 17:12:48.622  4141  4157 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 17:12:48.623  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:48.624  4141  4157 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 17:12:48.624  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:48.624  3773  3824 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 17:12:48.624  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:48.625  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 17:12:48.625  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:12:48.625  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 17:12:48.625  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:12:48.625  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 17:12:48.625  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 17:12:48.625  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:12:48.625  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:12:48.625  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
09-09 17:12:48.626  3773  3824 D BluetoothAdapter: STATE_ON
,09-09 17:12:48.626  4141  4180 D BtGatt.GattService: stopScan() - queue size =1
09-09 17:12:48.627  4141  4151 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 17:12:48.627  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:48.627  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:12:48.627  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:12:48.627  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 17:12:48.627  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:12:48.627  4141  4157 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 17:12:48.628  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.628  4141  4160 D BtGatt.ScanManager: stopping BLe Batch
09-09 17:12:48.628  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:12:48.628  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:12:48.628  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:12:48.628  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 17:12:48.629  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:48.630  3773  3773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:12:48.630  3773  3773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:12:48.630  4141  4157 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 17:12:48.630  3773  3773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:12:48.630  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.630  4141  4160 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 17:12:48.631  4141  4157 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 17:12:48.631  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:48.631  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.632  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:48.632  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:48.632  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:48.632  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.632  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:48.632  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 17:12:48.632  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1b3797 removed from the list
09-09 17:12:48.632  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:48.632  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e50dd84 removed from the list
09-09 17:12:48.632  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:48.632  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:48.633  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.633  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:48.634  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:12:48.634  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:48.634  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:48.634  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e50dd84 not in the list
09-09 17:12:48.634  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.634  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:48.634   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 17:12:48.635  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:48.635  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:12:48.635  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:48.635  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251b633 removed from the list
09-09 17:12:48.635  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:48.635  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.635  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:48.635  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:48.635  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd059a2 removed from the list
09-09 17:12:48.636  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 17:12:48.636  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@667828f added. We now have 2 listener(s)
09-09 17:12:48.637  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 17:12:48.637  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:48.637  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:48.637  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:48.637  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d74591c added. We now have 9 listener(s)
09-09 17:12:48.637  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:48.638  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:12:48.639  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:48.642  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:48.642  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:48.642  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:48.642  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:48.642  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:48.642  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:48.642  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:48.642  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:48.643  3773  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:48.644  3773  3824 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:48.644  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:48.644  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e77afa added. We now have 3 listener(s)
09-09 17:12:48.645  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 17:12:48.645  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:48.645  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:48.645  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:48.646  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e63b8ab added. We now have 10 listener(s)
09-09 17:12:48.646  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:48.646  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:48.646  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:48.646  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:48.646  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:12:48.646  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:12:48.646  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:48.647  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:12:48.648  3773  3824 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 17:12:48.648  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:12:48.649  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:48.652  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:12:48.653  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 17:12:48.653  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 17:12:48.656  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 17:12:48.656  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 17:12:48.656  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 17:12:48.657  3773  3824 D BluetoothAdapter: STATE_ON
09-09 17:12:48.657   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 17:12:48.660  4141  4176 D BtGatt.GattService: registerClient() - UUID=6e6c586a-f988-4a0e-9ffb-4f8fe49a6457
09-09 17:12:48.660   871  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-09 17:12:48.660   871  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:12:48.662  4141  4157 D BtGatt.GattService: onClientRegistered() - UUID=6e6c586a-f988-4a0e-9ffb-4f8fe49a6457, clientIf=5
09-09 17:12:48.662  3773  3785 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 17:12:48.663  4141  4152 D BtGatt.GattService: start scan with filters
09-09 17:12:48.663   871   888 D Tethering: MasterInitialState.processMessage what=3
09-09 17:12:48.665  4141  4160 D BtGatt.ScanManager: handling starting scan
09-09 17:12:48.667   871  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-09 17:12:48.668  4141  4157 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 17:12:48.668  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.668  4141  4160 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 17:12:48.668  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 17:12:48.668  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:12:48.668  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:12:48.669  4141  4157 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 17:12:48.669  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.670  4141  4160 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:12:48.670  4141  4160 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 17:12:48.672  4141  4157 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 17:12:48.672  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.668  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 17:12:48.672  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:12:48.672  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:48.672  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:48.672  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:48.672  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:48.672  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:48.672  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:48.672  3773  3773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:12:48.673  4141  4157 D BtGatt.GattService: onBatchScanS,tartStopped() - clientIf=5, status=0, startStopAction=1
09-09 17:12:48.673  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.675  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:12:48.675  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 17:12:48.676  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 17:12:48.676  3773  3773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:48.678  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:48.678  3773  3824 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 17:12:48.678  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:48.678  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:48.678  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:48.678  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:48.678  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.678  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:12:48.678  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:48.678  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@667828f removed from the list
09-09 17:12:48.678  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:48.678  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d74591c removed from the list
,09-09 17:12:48.683  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:48.683  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:48.683  3773  3773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:12:48.683  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:12:48.684  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.684  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 17:12:48.684  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.684  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:12:48.684  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:12:48.684  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:48.684  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:48.685  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d74591c not in the list
,09-09 17:12:48.685  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:12:48.685  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:12:48.685  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 17:12:48.685  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:12:48.685  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
09-09 17:12:48.685  3773  3824 D BluetoothAdapter: STATE_ON
09-09 17:12:48.686  4141  4176 D BtGatt.GattService: stopScan() - queue size =1
09-09 17:12:48.686  4141  4180 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 17:12:48.686  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:48.686  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 17:12:48.686  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:12:48.686  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:12:48.686  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:12:48.687  4141  4157 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 17:12:48.687  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:12:48.687  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:12:48.687  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.687  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 17:12:48.687  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:12:48.687  4141  4160 D BtGatt.ScanManager: stopping BLe Batch
09-09 17:12:48.689  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:48.690  4141  4157 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 17:12:48.690  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:48.690  4141  4160 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 17:12:48.690  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:48.690  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:48.691  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:48.691  3773  3773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:12:48.691  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e63b8ab removed from the list
,09-09 17:12:48.691  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:48.691  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.691  3773  3773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 17:12:48.691  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:48.691  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:48.691  3773  3773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:12:48.691  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e77afa removed from the list
09-09 17:12:48.691  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:48.691  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a33487 added. We now have 2 listener(s)
,09-09 17:12:48.691  4141  4157 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 17:12:48.691  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.692  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 17:12:48.692  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:48.693  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 17:12:48.693  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:48.693  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e8afb4 added. We now have 9 listener(s)
,09-09 17:12:48.693  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:48.693  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:12:48.693  1747  1747 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 17:12:48.695  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:48.697  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:48.697  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:48.697  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:48.697  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:48.697  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:48.697  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:48.697  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:48.697  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:12:48.699  3773  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:12:48.699  3773  3824 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:12:48.699  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-09 17:12:48.699  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe66f52 added. We now have 3 listener(s)
09-09 17:12:48.700  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 17:12:48.700  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:48.700  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:48.700  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:48.701  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6749223 added. We now have 10 listener(s)
,09-09 17:12:48.701  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:48.701  1747  1747 D SystemUpdateService: onCreate
09-09 17:12:48.701  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:48.701  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 17:12:48.701  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:12:48.701  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:12:48.701  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:48.701  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 17:12:48.703  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:48.704  1747  1747 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 17:12:48.704  3773  3824 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 17:12:48.704  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:12:48.707  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:12:48.707  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 17:12:48.707  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:12:48.710  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 17:12:48.710  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 17:12:48.710  3773  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 17:12:48.711  3773  3824 D BluetoothAdapter: STATE_ON
,09-09 17:12:48.712  4141  4151 D BtGatt.GattService: registerClient() - UUID=79765883-95ed-4e9c-a9f7-5e62b30d2b69
,09-09 17:12:48.713  4141  4157 D BtGatt.GattService: onClientRegistered() - UUID=79765883-95ed-4e9c-a9f7-5e62b30d2b69, clientIf=5
09-09 17:12:48.713  3773  3785 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 17:12:48.713  4141  4152 D BtGatt.GattService: start scan with filters
,09-09 17:12:48.717  4141  4160 D BtGatt.ScanManager: handling starting scan
,09-09 17:12:48.717  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 17:12:48.717  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:12:48.717  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:12:48.717  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 17:12:48.718  4141  4157 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 17:12:48.718  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.718  4141  4160 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 17:12:48.719  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:12:48.719  3773  3773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:12:48.720  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 17:12:48.720  4141  4157 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 17:12:48.720  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.720  4141  4160 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:12:48.721  4141  4160 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 17:12:48.721  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 17:12:48.722  4141  4157 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 17:12:48.722  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.723  4141  4157 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 17:12:48.723  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.725  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:48.725  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:48.725  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:48.725  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:48.725  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.725  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:12:48.725  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:48.725  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a33487 removed from the list
09-09 17:12:48.725  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:48.725  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e8afb4 removed from the list
09-09 17:12:48.725  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:48.725  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:48.725  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.725  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 17:12:48.725  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.725  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:48.726  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:48.726  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:48.726  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:48.726  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e8afb4 not in the list
09-09 17:12:48.726  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:12:48.726  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:12:48.726  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMa,cAddressMode
09-09 17:12:48.726  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:12:48.726  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 17:12:48.727  3773  3824 D BluetoothAdapter: STATE_ON
09-09 17:12:48.727  4141  4152 D BtGatt.GattService: stopScan() - queue size =1
09-09 17:12:48.728  4141  4151 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 17:12:48.728  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:12:48.728  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:12:48.728  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:12:48.728  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:12:48.728  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:12:48.728  4141  4157 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 17:12:48.729  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.729  4141  4160 D BtGatt.ScanManager: stopping BLe Batch
09-09 17:12:48.729  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:12:48.729  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:12:48.729  3773  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:12:48.729  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:12:48.730  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:48.730  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:48.730  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:48.730  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:12:48.731  3773  3773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:12:48.731  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6749223 removed from the list
09-09 17:12:48.731  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:12:48.731  3773  3773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 17:12:48.731  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.731  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:48.731  3773  3773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:12:48.731  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:48.731  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe66f52 removed from the list
09-09 17:12:48.731  4141  4157 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 17:12:48.731  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:12:48.731  4141  4160 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 17:12:48.731  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:48.731  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f742d7f added. We now have 2 listener(s)
09-09 17:12:48.732  4141  4157 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 17:12:48.732  4141  4157 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:12:48.732  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 17:12:48.732  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:48.733  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:48.733  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:48.733  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98e414c added. We now have 9 listener(s)
09-09 17:12:48.733  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:48.733  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:12:48.734  1747  1747 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 17:12:48.735  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:12:48.737  3773  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:12:48.737  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:12:48.737  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:12:48.737  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:12:48.737  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:12:48.737  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:12:48.737  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:12:48.737  3773  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:12:48.739  3773  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:12:48.739  3773  3824 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:12:48.740  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:12:48.740  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9496aa added. We now have 3 listener(s)
,09-09 17:12:48.741  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 17:12:48.742  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:12:48.742  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:12:48.742  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:12:48.742  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:12:48.742  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a8229b added. We now have 10 listener(s)
,09-09 17:12:48.742  3773  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:12:48.742  3773  3824 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:12:48.742  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:12:48.742  3773  3824 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:12:48.742  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:12:48.742  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.742  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:12:48.743  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:48.743  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f742d7f removed from the list
09-09 17:12:48.743  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:48.743  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98e414c removed from the list
09-09 17:12:48.743  3773  3773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:12:48.743  3773  3824 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:12:48.743  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:48.743  1747  4208 I SystemUpdateService: active receiver: enabled
09-09 17:12:48.743  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.743  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:48.744  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:12:48.744  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:48.744  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:48.744  3773  3824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98e414c not in the list
09-09 17:12:48.744  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.745  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:12:48.745  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:12:48.745  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:12:48.745  3773  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:12:48.745  3773  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a8229b removed from the list
09-09 17:12:48.745  3773  3824 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:12:48.745  3773  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:12:48.746  3773  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:12:48.746  3773  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:12:48.746  3773  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9496aa removed from the list
,09-09 17:12:48.747  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 17:12:48.747  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 17:12:48.747  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-09 17:12:48.747  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:12:48.747  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 17:12:48.747  3773  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:12:48.750  1747  1747 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 17:12:48.752  1747  1747 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 17:12:48.753  3773  4214 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: My test thread name)
,09-09 17:12:48.753  3773  4214 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: My test thread name)
09-09 17:12:48.753  3773  4214 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-09 17:12:48.753  3899  3899 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:12:48.755  3773  4215 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: My test thread name)
,09-09 17:12:48.755  3773  4215 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: My test thread name)
09-09 17:12:48.755  3773  4215 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 17:12:48.757  3773  3824 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-09 17:12:48.757  3773  3824 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-09 17:12:48.757  3773  3824 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-09 17:12:48.757  3773  3824 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-09 17:12:48.757  3773  3824 D com.test.thalitest.ThaliTestRunner: Total duration: 21747 ms
,09-09 17:12:48.758  3899  3899 D SprintDMHelper: simOperator: 
09-09 17:12:48.759  3899  3899 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-09 17:12:48.759  3773  3824 I jxcore-log: *Native tests were executed*
09-09 17:12:48.759  3773  3824 I jxcore-log: 
,09-09 17:12:48.759  3773  3824 I jxcore-log: Total number of executed tests:  80
09-09 17:12:48.759  3773  3824 I jxcore-log: 
09-09 17:12:48.759  3773  3824 I jxcore-log: Number of passed tests:  80
09-09 17:12:48.759  3773  3824 I jxcore-log: 
09-09 17:12:48.760  3773  3824 I jxcore-log: Number of failed tests:  0
09-09 17:12:48.760  3773  3824 I jxcore-log: 
09-09 17:12:48.760  3773  3824 I jxcore-log: Number of ignored tests:  0
09-09 17:12:48.760  3773  3824 I jxcore-log: 
,09-09 17:12:48.760  3773  3824 I jxcore-log: Total duration:  21747
09-09 17:12:48.760  3773  3824 I jxcore-log: 
09-09 17:12:48.760  3773  3824 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 17:12:48.760  3773  3824 I jxcore-log: 
,09-09 17:12:48.764  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:48.764  3773  3824 I jxcore-log: 
,09-09 17:12:48.766  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:48.766  3773  3824 I jxcore-log: 
,09-09 17:12:48.767  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:48.767  3773  3824 I jxcore-log: 
09-09 17:12:48.768  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:48.768  3773  3824 I jxcore-log: 
09-09 17:12:48.769  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:48.769  3773  3824 I jxcore-log: 
09-09 17:12:48.770  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:48.770  3773  3824 I jxcore-log: 
09-09 17:12:48.770  3773  3773 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 17:12:48.772  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:48.772  3773  3824 I jxcore-log: 
09-09 17:12:48.773  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:12:48.773  3773  3824 I jxcore-log: 
09-09 17:12:48.774  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:12:48.774  3773  3824 I jxcore-log: 
09-09 17:12:48.775  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:12:48.775  3773  3824 I jxcore-log: 
09-09 17:12:48.775  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:12:48.775  3773  3824 I jxcore-log: 
09-09 17:12:48.776  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:12:48.776  3773  3824 I jxcore-log: 
09-09 17:12:48.777  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:12:48.777  3773  3824 I jxcore-log: 
09-09 17:12:48.777  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:12:48.777  3773  3824 I jxcore-log: 
09-09 17:12:48.778  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:48.778  3773  3824 I jxcore-log: 
,09-09 17:12:48.779  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:48.779  3773  3824 I jxcore-log: 
09-09 17:12:48.781  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:12:48.781  3773  3824 I jxcore-log: 
09-09 17:12:48.781  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:12:48.781  3773  3824 I jxcore-log: 
09-09 17:12:48.782  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:12:48.782  3773  3824 I jxcore-log: 
09-09 17:12:48.782  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:12:48.782  3773  3824 I jxcore-log: 
09-09 17:12:48.783  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:12:48.783  3773  3824 I jxcore-log: 
09-09 17:12:48.783  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:12:48.783  3773  3824 I jxcore-log: 
09-09 17:12:48.784  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:12:48.784  3773  3824 I jxcore-log: 
09-09 17:12:48.785  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:12:48.785  3773  3824 I jxcore-log: 
09-09 17:12:48.785  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:12:48.785  3773  3824 I jxcore-log: 
09-09 17:12:48.786  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:12:48.786  3773  3824 I jxcore-log: 
09-09 17:12:48.787  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:12:48.787  3773  3824 I jxcore-log: 
,09-09 17:12:48.787  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:48.787  3773  3824 I jxcore-log: 
09-09 17:12:48.788  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:12:48.788  3773  3824 I jxcore-log: 
09-09 17:12:48.788  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:48.788  3773  3824 I jxcore-log: 
,09-09 17:12:48.789  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:48.789  3773  3824 I jxcore-log: 
,09-09 17:12:48.789  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:48.789  3773  3824 I jxcore-log: 
09-09 17:12:48.790  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:12:48.790  3773  3824 I jxcore-log: 
,09-09 17:12:48.796  1747  4212 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-09 17:12:48.796  1747  4212 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 17:12:48.798  1747  4212 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 17:12:48.801  1747  2432 I iu.UploadsManager: num queued entries: 0
,09-09 17:12:48.801  1747  2432 I iu.UploadsManager: num updated entries: 0
09-09 17:12:48.801  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 17:12:48.802  1747  2432 I iu.SyncManager: NEXT; no task
,09-09 17:12:48.803  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 17:12:48.822  1524  3171 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-09 17:12:48.822  1524  3171 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 17:12:48.822  1524  3171 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 17:12:48.822  1524  3171 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 17:12:48.839  1747  4212 E MDM     : [182] SitrepService.a: Error sending sitrep.
,09-09 17:12:48.841  1747  4208 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 17:12:48.842  1524  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 17:12:48.842  1524  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 17:12:48.843  1524  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 17:12:48.843  1524  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 17:12:48.850  1747  4208 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 17:12:48.850  1747  4208 I SystemUpdateService: now status is 0 (complete)
09-09 17:12:48.850  1747  4208 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 17:12:48.850  1747  4208 I SystemUpdateService: file has been verified
,09-09 17:12:48.850  1747  4208 I SystemUpdateService: OTA package size = 12249756
,09-09 17:12:48.854  3541  4209 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 17:12:48.854  3541  4209 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at jdm.a(PG:82)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at jcs.o(PG:406)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at jcn.a(PG:1379)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at jcs.i(PG:143)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at blb.a(PG:3937)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at czp.a(PG:18188)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at czp.a(PG:9081)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at czq.run(PG:1686)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 17:12:48.854  3541  4209 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at jdj.a(PG:4091)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at jdj.a(PG:1125)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at jdm.a(PG:77)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	... 12 more
09-09 17:12:48.854  3541  4209 E HttpOperation: Caused by: faj: BadAuthentication
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at fal.a(PG:38)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	at jdj.a(PG:4089)
09-09 17:12:48.854  3541  4209 E HttpOperation: 	... 14 more
,09-09 17:12:48.872  1747  4208 I SystemUpdateService: showing system update notification
,09-09 17:12:48.886  1747  1747 D SystemUpdateService: onDestroy
,09-09 17:12:48.888  1524  3171 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 17:12:48.888  1524  3171 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 17:12:48.888  1524  3171 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 17:12:48.888  1524  3171 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 17:12:48.905  3541  4209 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 17:12:48.905  3541  4209 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at jdm.a(PG:82)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at jcs.o(PG:406)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at jcn.a(PG:1379)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at jcs.i(PG:143)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at hec.a(PG:42)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at hee.a(PG:102)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at czr.a(PG:65)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at kka.a(PG:108)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at czp.a(PG:19176)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at czp.a(PG:9081)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at czq.run(PG:1686)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 17:12:48.905  3541  4209 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at jdj.a(PG:4091)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at jdj.a(PG:1125)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at jdm.a(PG:77)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	... 15 more
09-09 17:12:48.905  3541  4209 E HttpOperation: Caused by: faj: BadAuthentication
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at fal.a(PG:38)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	at jdj.a(PG:4089)
09-09 17:12:48.905  3541  4209 E HttpOperation: 	... 17 more
,09-09 17:12:48.905  3541  4209 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 17:12:48.905  3541  4209 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at hec.a(PG:42)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at hee.a(PG:102)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at czr.a(PG:65)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at kka.a(PG:108)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	... 15 more
09-09 17:12:48.905  3541  4209 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at fal.a(PG:38)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 17:12:48.905  3541  4209 E ExperimentLoader: 	... 17 more
,09-09 17:12:49.003   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 125333, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 17:12:49.131  3773  3773 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 17:12:49.135  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:12:49.135  3773  3824 I jxcore-log: 
,09-09 17:12:49.190  3773  3773 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 17:12:49.195  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:12:49.195  3773  3824 I jxcore-log: 
,09-09 17:12:49.231  3773  3773 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 17:12:49.233  3773  3824 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:12:49.233  3773  3824 I jxcore-log: 
,09-09 17:12:49.334   871  4196 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 17:12:49.349  4218  4218 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-09 17:12:49.354  4218  4218 D AndroidRuntime: CheckJNI is OFF
,09-09 17:12:49.396  4218  4218 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-09 17:12:49.441  4218  4218 I Radio-JNI: register_android_hardware_Radio DONE
,09-09 17:12:49.464  4218  4218 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 17:12:49.473   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-09 17:12:49.474   871   884 I ActivityManager: Killing 3773:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-09 17:12:49.561   871   896 W PackageSettings: Skipping PackageSetting{bf501aa com.example.hello/10273} due to missing metadata
,09-09 17:12:49.589   871   896 I art     : Starting a blocking GC Explicit
,09-09 17:12:49.621   871  1965 I WindowState: WIN DEATH: Window{49dd2e6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 17:12:49.622   871  1685 D GraphicsStats: Buffer count: 2
,09-09 17:12:49.622   871  1315 D WifiService: Client connection lost with reason: 4
,09-09 17:12:49.645   871  4195 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-09 17:12:49.652   871   884 W ActivityManager: Force removing ActivityRecord{ee8384f u0 com.test.thalitest/.MainActivity t4}: app died, no saved state
,09-09 17:12:49.658   871   896 I art     : Explicit concurrent mark sweep GC freed 49384(2MB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 29MB/43MB, paused 1.403ms total 68.530ms
,09-09 17:12:49.660   871  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-09 17:12:49.666   871   881 W ActivityManager: Spurious death for ProcessRecord{558a925 0:com.test.thalitest/u0a0}, curProc for 3773: null
,09-09 17:12:49.671  3058  4216 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 17:12:49.690   871  1965 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3773 uid 10000
,09-09 17:12:49.691  1878  1878 I Keyboard.Facilitator: onFinishInput()
09-09 17:12:49.691   871   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-09 17:12:49.696  4218  4218 I art     : System.exit called, status: 0
,09-09 17:12:49.696  4218  4218 I AndroidRuntime: VM exiting with result code 0.
,09-09 17:12:49.707   871   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-09 17:12:49.719  4141  4141 D BluetoothMapAppObserver: onReceive
,09-09 17:12:49.719  4141  4141 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-09 17:12:49.727  2175  2278 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 17:12:49.728   871  1304 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 17:12:49.729  3647  3647 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-09 17:12:49.730   871  4195 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 15:12:49 GMT], X-Android-Received-Millis=[1473433969729], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473433969694]}
,09-09 17:12:49.735  1878  1878 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-09 17:12:49.741   871  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 17:12:49.742   871  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-09 17:12:49.742   871  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 17:12:49.743   871  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 17:12:49.747  1878  4239 I Keyboard.Facilitator.DecoderInitializer: run()
09-09 17:12:49.753  2001  2001 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,09-09 17:12:49.756  1878  4239 I Decoder : createOrResetDecoder
,09-09 17:12:49.782   871  3170 I ActivityManager: Start proc 4243:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-09 17:12:49.790  1935  1935 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-09 17:12:49.838   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-09 17:12:49.848  2001  4257 I MicroRecognitionRnrImpl: Starting detection.
,09-09 17:12:49.851  2001  4258 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@39b2491
,09-09 17:12:49.852   376  4260 I AudioFlinger: AudioFlinger's thread 0xb3380000 ready to run
,09-09 17:12:49.856   376  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,09-09 17:12:49.857  2001  4258 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@39b2491
,09-09 17:12:49.867   376  4260 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,09-09 17:12:49.867   376  4260 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
09-09 17:12:49.867   376  4260 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,09-09 17:12:49.874   376  4260 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,09-09 17:12:49.877  1524  1524 I ConfigService: onCreate
,09-09 17:12:49.879  4243  4243 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-09 17:12:49.895  1878  4239 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-09 17:12:49.919  1878  4239 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-09 17:12:49.921  1950  2028 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-09 17:12:49.922  1878  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-09 17:12:49.922  1878  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-09 17:12:49.924   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-09 17:12:49.924   871   883 E PackageManager: Failed to write settings, restoring backup
09-09 17:12:49.924   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-09 17:12:49.924   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-09 17:12:49.924   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-09 17:12:49.924   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-09 17:12:49.924   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-09 17:12:49.924   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:49.924   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:49.924   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 17:12:49.926   871   884 E DropBoxManagerService: Can't write: system_server_wtf
09-09 17:12:49.926   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 17:12:49.926   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 17:12:49.926   871   884 E DropBoxManagerService: 	... 13 more
,09-09 17:12:49.936   871  1965 I ActivityManager: Start proc 4264:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-09 17:12:49.936  1950  2028 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 17:12:49.936  1950  2028 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1950
09-09 17:12:49.936  1950  2028 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:12:49.936  1950  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 17:12:49.936  1950  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 17:12:49.936  1950  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 17:12:49.936  1950  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 17:12:49.936  1950  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 17:12:49.936  1950  2028 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-09 17:12:49.936  1950  2028 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-09 17:12:49.936  1950  2028 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:12:49.936  1950  2028 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:12:49.936  1950  2028 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:49.936  1950  2028 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 17:12:49.938   871  2036 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 17:12:49.939  1878  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-09 17:12:49.939  1878  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-09 17:12:49.941   871  4270 E DropBoxManagerService: Can't write: system_app_crash
09-09 17:12:49.941   871  4270 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
09-09 17:12:49.941   871  4270 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 17:12:49.941   871  4270 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:12:49.941   871  4270 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:12:49.941   871  4270 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:12:49.941   871  4270 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 17:12:49.941   871  4270 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 17:12:49.941   871  4270 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:12:49.941   871  4270 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:12:49.941   871  4270 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:12:49.941   871  4270 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 17:12:49.941   871  4270 E DropBoxManagerService: 	... 5 more
09-09 17:12:49.942  1878  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-09 17:12:49.942  1878  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-09 17:12:49.943  2001  2404 W SearchService: Abort, client detached.
09-09 17:12:49.945  2001  2001 I HotwordDetector: Closing mic
09-09 17:12:49.945  2001  2350 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@39b2491
09-09 17:12:49.945  2001  4258 E AudioRecord-JNI: Error -4 during AudioRecord native read
,09-09 17:12:49.951  1878  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-09 17:12:49.952  1878  4239 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-09 17:12:49.952  1878  4239 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-09 17:12:49.952  1878  4239 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-09 17:12:49.953  1878  4239 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-09 17:12:49.953  1878  4239 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-09 17:12:49.954   871  4277 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 17:12:49.964  2001  4279 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,09-09 17:12:49.978  4243  4243 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-09 17:12:49.988  4243  4282 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-09 17:12:49.995   871  4277 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 17:12:49.995   871  4277 I Adreno  : Build Date                       : 10/20/15
09-09 17:12:49.995   871  4277 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 17:12:49.995   871  4277 I Adreno  : Local Branch                     : M14
09-09 17:12:49.995   871  4277 I Adreno  : Remote Branch                    : 
09-09 17:12:49.995   871  4277 I Adreno  : Remote Branch                    : 
09-09 17:12:49.995   871  4277 I Adreno  : Reconstruct Branch               : 
,09-09 17:12:49.996   871  1965 I ActivityManager: Start proc 4283:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-09 17:12:50.004   871  4277 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 17:12:50.013   376  4260 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,09-09 17:12:50.014   376  4260 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 17:12:50.020   376  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 17:12:50.021  2001  4257 I MicroRecognitionRnrImpl: Detection finished
09-09 17:12:50.021  2001  2355 I MicroRecognitionRnrImpl: Stopping hotword detection.
,09-09 17:12:50.052  4283  4283 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-09 17:12:50.074  4243  4280 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:50.074  4243  4280 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.o,penInner(SQLiteDatabase.java:806)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:50.075  4243  4280 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 17:12:50.078  1524  1524 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-09 17:12:50.081  1524  1524 D AndroidRuntime: Shutting down VM
09-09 17:12:50.085  1524  1524 E AndroidRuntime: FATAL EXCEPTION: main
09-09 17:12:50.085  1524  1524 E AndroidRuntime: Process: com.google.process.gapps, PID: 1524
09-09 17:12:50.085  1524  1524 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-09 17:12:50.085  1524  1524 E AndroidRuntime: 	... 8 more
09-09 17:12:50.101   871  4302 E DropBoxManagerService: Can't write: system_app_crash
09-09 17:12:50.101   871  4302 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-09 17:12:50.101   871  4302 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 17:12:50.101   871  4302 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:12:50.101   871  4302 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:12:50.101   871  4302 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:12:50.101   871  4302 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 17:12:50.101   871  4302 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 17:12:50.101   871  4302 E DropBoxManagerService: ,Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:12:50.101   871  4302 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:12:50.101   871  4302 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:12:50.101   871  4302 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 17:12:50.101   871  4302 E DropBoxManagerService: 	... 5 more
09-09 17:12:50.117  1747  4304 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-09 17:12:50.118  1747  4304 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-09 17:12:50.141  4243  4280 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:50.151  4243  4282 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-09 17:12:50.152  4243  4282 E AndroidRuntime: Process: android.process.acore, PID: 4243
09-09 17:12:50.152  4243  4282 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:12:50.152  4243  4282 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:12:50.154   871  4305 E DropBoxManagerService: Can't write: system_app_crash
09-09 17:12:50.154   871  4305 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-09 17:12:50.154   871  4305 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 17:12:50.154   871  4305 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:12:50.154   871  4305 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:12:50.154   871  4305 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:12:50.154   871  4305 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 17:12:50.154   871  4305 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 17:12:50.154   871  4305 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:12:50.154   871  4305 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:12:50.154   871  4305 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:12:50.154   871  4305 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 17:12:50.154   871  4305 E DropBoxManagerService: 	... 5 more
09-09 17:12:50.154  4243  4280 I Process : Sending signal. PID: 4243 SIG: 9
,09-09 17:12:50.213   871  3894 I ActivityManager: Process android.process.acore (pid 4243) has died
09-09 17:12:50.214   871  3894 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-09 17:12:50.249   871   889 W AppOps  : Finishing op nesting under-run: uid 1000 pkg android code 24 time=1465474415550 duration=35 nesting=0
,09-09 17:12:50.311   280   280 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,09-09 17:12:50.312   280   280 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
09-09 17:12:50.312   280   280 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
09-09 17:12:50.312   280   280 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
09-09 17:12:50.312   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
09-09 17:12:50.312   280   280 E qdoverlay: MdpCtrl close error in unset
,09-09 17:12:50.572   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0,
09-09 17:12:50.572   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,09-09 17:12:50.572   280   280 E qdoverlay: MdpCtrl close error in unset

```
