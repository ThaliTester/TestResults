#### Test 836273379690449_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-13 14:17:55.357   976   976 I kickstart: STATUS: Received file 'm9kefs2'
09-13 14:17:55.357   976   976 I kickstart: STATUS: 950272 bytes transferred in 0.998299 seconds
09-13 14:17:55.358   976   976 I kickstart: STATUS: Successfully downloaded files from target 
09-13 14:17:55.358   976   976 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
09-13 14:17:55.361   976   976 I kickstart: STATUS: Sahara protocol completed
,09-13 14:17:55.583   871  1302 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
09-13 14:17:56.045  3766  3766 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 14:17:56.050  3766  3766 D AndroidRuntime: CheckJNI is OFF
09-13 14:17:56.095  3766  3766 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 14:17:56.146  3766  3766 I Radio-JNI: register_android_hardware_Radio DONE
09-13 14:17:56.170  3766  3766 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-13 14:17:56.175   871  1984 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 14:17:56.212  2003  2017 W SearchService: Abort, client detached.
09-13 14:17:56.218  3766  3766 D AndroidRuntime: Shutting down VM
09-13 14:17:56.220  2003  2329 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2075a1f
09-13 14:17:56.221  2003  2340 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-13 14:17:56.222  2003  2003 I HotwordDetector: Closing mic
09-13 14:17:56.249   871  1694 I ActivityManager: Start proc 3775:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 14:17:56.278   376  2342 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 14:17:56.279   376  2342 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-13 14:17:56.286   376  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 14:17:56.289  2003  2339 I MicroRecognitionRnrImpl: Detection finished
09-13 14:17:56.289  2003  2334 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-13 14:17:56.326  3775  3775 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 14:17:56.349  3775  3775 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 14:17:56.357  3775  3775 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3197-3200)
09-13 14:17:56.357  3775  3775 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 14:17:56.376  3775  3775 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8def99d}
09-13 14:17:56.377  3775  3775 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 14:17:56.377  3775  3775 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 14:17:56.386  3775  3775 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 14:17:56.387  3775  3775 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 14:17:56.409  3775  3775 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-13 14:17:56.421  3775  3775 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 14:17:56.421  3775  3775 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 14:17:56.422  3775  3775 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 14:17:56.422  3775  3775 I Adreno  : Build Date                       : 10/20/15
09-13 14:17:56.422  3775  3775 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 14:17:56.422  3775  3775 I Adreno  : Local Branch                     : M14
09-13 14:17:56.422  3775  3775 I Adreno  : Remote Branch                    : 
09-13 14:17:56.422  3775  3775 I Adreno  : Remote Branch                    : 
09-13 14:17:56.422  3775  3775 I Adreno  : Reconstruct Branch               : 
,09-13 14:17:56.516   871   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8177e84:true
,09-13 14:17:56.546  3775  3775 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 14:17:56.561  3775  3775 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-13 14:17:56.623  3775  3814 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 14:17:56.631  3775  3800 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-13 14:17:56.675  3775  3814 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 14:17:56.734   871   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +512ms
,09-13 14:17:56.753  1867  1867 I Keyboard.Facilitator: onFinishInput()
,09-13 14:17:56.815  3775  3775 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3775
,09-13 14:17:56.895  3775  3775 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 14:17:57.040   871  1984 I ActivityManager: Killing 2961:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-13 14:17:57.072   871  1984 I ActivityManager: Killing 3183:com.google.android.gm/u0a78 (adj 15): empty #18
,09-13 14:17:57.078  3775  3818 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1672476368
,09-13 14:17:57.087  3775  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 14:17:57.087  3775  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 14:17:57.087  3775  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 14:17:57.087  3775  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 14:17:57.087  3775  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 14:17:57.087  3775  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ed6191 added. We now have 1 listener(s)
,09-13 14:17:57.093  3775  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-13 14:17:57.095  3775  3818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 14:17:57.096  3775  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 14:17:57.097  3775  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-13 14:17:57.106  3775  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4d9f64 added. We now have 1 listener(s)
09-13 14:17:57.106  3775  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 14:17:57.110   871  1303 D WifiService: New client listening to asynchronous messages
,09-13 14:17:57.111  3775  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 14:17:57.111  3775  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 14:17:57.112  3775  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-13 14:17:57.112  3775  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 14:17:57.112  3775  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 14:17:57.151  3775  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:17:57.152  3775  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-13 14:17:57.156  3775  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 14:17:57.156  3775  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:17:57.156  3775  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:17:57.156  3775  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:17:57.156  3775  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:17:57.156  3775  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:17:57.156  3775  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:57.156  3775  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:17:57.156  3775  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:17:57.157  3775  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 14:17:57.157  3775  3818 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 14:17:57.157  3775  3818 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 14:17:57.160  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:17:57.162  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:17:57.183  3775  3775 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 14:17:57.986  3775  3827 W jxcore-log: Initializing JXcore engine
09-13 14:17:57.986  3775  3827 W jxcore-log: JXcore engine is ready
09-13 14:17:58.021  3827  3827 W Thread-331: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-13 14:17:58.021  3827  3827 W Thread-331: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11750]" dev="sockfs" ino=11750 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-13 14:17:58.021  3827  3827 W Thread-331: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 14:17:58.021  3827  3827 W Thread-331: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25952]" dev="sockfs" ino=25952 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-13 14:17:58.037  3775  3827 W jxcore-log: Starting JXcore engine
09-13 14:17:58.119  3775  3827 W jxcore-log: Platform android
09-13 14:17:58.119  3775  3827 W jxcore-log: 
09-13 14:17:58.120  3775  3827 W jxcore-log: Process ARCH arm
09-13 14:17:58.120  3775  3827 W jxcore-log: 
09-13 14:17:58.339  3775  3827 I jxcore-log: JXcore Cordova bridge is ready!
09-13 14:17:58.339  3775  3827 I jxcore-log: 
09-13 14:17:58.343  3775  3827 W jxcore-log: JXcore engine is started
09-13 14:17:58.353  3775  3818 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-13 14:17:58.358  3775  3775 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-13 14:17:58.763  1517  1517 I ConfigService: onDestroy
09-13 14:17:58.844  3496  3571 D Finsky  : [294] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
09-13 14:17:58.862  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 14:17:58.932  1517  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-13 14:17:58.933  1517  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-13 14:17:58.933  1517  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 14:17:58.934  1517  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-13 14:17:58.978  3496  3571 D Finsky  : [294] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-13 14:18:00.140   871  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 14:18:06.209   871  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 14:18:07.762   871   885 I ActivityManager: Waited long enough for: ServiceRecord{9051c82 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,09-13 14:18:08.156  3775  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 14:18:08.156  3775  3827 I jxcore-log: 
,09-13 14:18:08.160  3775  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 14:18:08.160  3775  3827 I jxcore-log: 
,09-13 14:18:08.171  3775  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:08.171  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:08.171  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:08.171  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:08.171  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:08.171  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:08.171  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:08.171  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:08.178  3775  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 14:18:08.181  3775  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 14:18:08.181  3775  3827 I jxcore-log: 
,09-13 14:18:08.183  3775  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 14:18:08.183  3775  3827 I jxcore-log: 
,09-13 14:18:08.726  3775  3827 I jxcore-log: Unit Test app is loaded
09-13 14:18:08.726  3775  3827 I jxcore-log: 
,09-13 14:18:08.737  3775  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:08.737  3775  3827 I jxcore-log: 
,09-13 14:18:08.740  3775  3775 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 14:18:08.745  3775  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 14:18:08.745  3775  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39bd0ed added. We now have 2 listener(s)
,09-13 14:18:08.746  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 14:18:08.746  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 14:18:08.746  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:18:08.746  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:18:08.746  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74e5b22 added. We now have 2 listener(s)
,09-13 14:18:08.746  3775  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 14:18:08.747  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 14:18:08.752  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:08.760  3775  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:08.760  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:08.760  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:08.760  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:08.760  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:08.760  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:08.760  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:08.760  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:08.763  3775  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 14:18:08.763  3775  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:08.764  3775  3827 D ExecuteNativeTests: Running unit tests
09-13 14:18:08.764  3775  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 14:18:08.764  3775  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@555eb70 added. We now have 3 listener(s)
09-13 14:18:08.765  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 14:18:08.765  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:18:08.765  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:18:08.765  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:18:08.765  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf18ee9 added. We now have 3 listener(s)
09-13 14:18:08.765  3775  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 14:18:08.766  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 14:18:08.790  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:08.792  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:08.796  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:08.800  3775  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:08.800  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:08.800  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:08.800  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:08.800  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:08.800  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:08.800  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:08.800  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:08.805  3775  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 14:18:08.806  3775  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 14:18:08.808  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:08.813  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:12.263   871  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 14:18:13.130  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 14:18:13.135  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 14:18:13.137  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 14:18:13.156  1517  2053 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 14:18:13.156  1517  2053 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 14:18:13.156  1517  2053 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 14:18:13.156  1517  2053 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 14:18:13.170  3496  3496 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 14:18:13.171  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 14:18:13.171  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-13 14:18:15.586   871  1302 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 14:18:18.903  3775  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 14:18:18.903  3775  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e added. We now have 4 listener(s)
,09-13 14:18:18.904  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 14:18:18.904  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 14:18:18.904  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 14:18:18.904  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 14:18:18.904  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff added. We now have 4 listener(s)
,09-13 14:18:18.904  3775  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 14:18:18.905  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 14:18:18.908  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:18.923  3775  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:18.923  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:18.923  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:18.923  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:18.923  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:18.923  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:18.923  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:18.923  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:18.928  3775  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:18.928  3775  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 14:18:18.957  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:18.959  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:18.961  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 14:18:18.961  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 14:18:18.961  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 14:18:18.961  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 14:18:18.961  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:18.963  3775  3827 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 14:18:18.964  3775  3827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 14:18:18.964  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 14:18:18.964  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:18.964  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:18.965  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:18.965  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:18.965  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:18.966  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:18.966  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:18.966  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 14:18:18.967  3775  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e removed from the list
09-13 14:18:18.967  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:18.967  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff removed from the list
09-13 14:18:18.968  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:18.968  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:18.970  3775  3827 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 14:18:18.972  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:18.972  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:18.972  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:18.972  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:18.972  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:18.972  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
,09-13 14:18:18.972  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:18.972  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:18.972  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:18.977  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 14:18:18.977  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 14:18:18.977  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 14:18:18.977  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-13 14:18:18.977  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 14:18:18.977  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 14:18:18.977  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-13 14:18:18.977  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 14:18:18.977  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-13 14:18:18.977  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 14:18:18.977  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 14:18:18.977  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-13 14:18:18.977  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 14:18:18.978  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 14:18:18.978  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:18.979  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:18.979  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:18.979  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:18.979  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:18.979  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
,09-13 14:18:18.979  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:18.979  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:18.979  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:18.979  3775  3827 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 14:18:18.981  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:18.987  3775  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:18.987  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:18.987  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:18.987  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:18.987  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:18.987  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,09-13 14:18:18.987  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:18.987  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:18.990  3775  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:18.990  3775  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:18.992  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:18.992  3775  3827 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-13 14:18:18.992  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 14:18:18.993  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:18.993  3775  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 14:18:18.993  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:18:18.993  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:18.995  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 14:18:18.995  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
09-13 14:18:18.996  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 14:18:18.996  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:18.997  3775  3775 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:18:18.996  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:18:18.997  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:18:18.997  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:18.997  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:18:19.007  3775  3840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:18:19.007  3775  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 14:18:19.007  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 14:18:19.009  3775  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 14:18:19.014  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:18:19.017  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 14:18:19.017  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:18:19.020  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 14:18:19.021  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 14:18:19.021  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-13 14:18:19.023  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:19.023  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:19.023  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 14:18:19.024  3775  3827 D BluetoothAdapter: STATE_ON
,09-13 14:18:19.031  2630  2641 D BtGatt.GattService: registerClient() - UUID=d3f15fc6-450d-4802-90e2-42b9ab172828
,09-13 14:18:19.032  2630  2675 D BtGatt.GattService: onClientRegistered() - UUID=d3f15fc6-450d-4802-90e2-42b9ab172828, clientIf=5
09-13 14:18:19.033  3775  3785 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 14:18:19.034  2630  2677 D BtGatt.AdvertiseManager: message : 0
,09-13 14:18:19.040  2630  2677 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 14:18:19.053  2630  2675 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 14:18:19.059  2630  2675 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 14:18:19.060  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:18:19.060  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 14:18:19.062  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:18:19.064  3775  3827 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 14:18:19.064  3775  3775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:19.064  3775  3775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 14:18:19.064  3775  3775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:18:19.064  3775  3775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 14:18:19.064  3775  3775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 14:18:19.065  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-13 14:18:19.066  3775  3775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 14:18:19.067  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:19.486  3009  3842 V KeepSync: Connecting to GoogleApiClient
,09-13 14:18:19.487   871  1375 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 14:18:19.568  3775  3775 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 14:18:19.569  3775  3775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 14:18:19.569  3775  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 14:18:19.569  3775  3775 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 14:18:19.570  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 14:18:19.571  3775  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 14:18:19.571  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:18:19.571  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:18:19.572  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:18:19.574  3775  3840 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:18:19.574  3775  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 14:18:19.574  3775  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 14:18:19.575  3775  3775 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 14:18:19.576  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-13 14:18:19.577  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:18:19.578  3775  3775 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:18:19.578  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 14:18:19.578  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:18:19.579  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:18:19.579  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 14:18:19.580  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 14:18:19.583  3775  3827 D BluetoothAdapter: STATE_ON
09-13 14:18:19.584  3775  3827 D BluetoothLeScanner: could not find callback wrapper
,09-13 14:18:19.584  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:18:19.584  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 14:18:19.587  2630  2677 D BtGatt.AdvertiseManager: message : 1
,09-13 14:18:19.588  2630  2677 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 14:18:19.604  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 14:18:19.605  2630  2675 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-13 14:18:19.605  2630  2675 D BtGatt.GattService: Client app is not null!
,09-13 14:18:19.607  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 14:18:19.607  2630  2754 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 14:18:19.608  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 14:18:19.609  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 14:18:19.610  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 14:18:19.610  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 14:18:19.610  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:18:19.612  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:19.613  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:18:19.613  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 14:18:19.614  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:19.617  3775  3775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 14:18:19.618  3775  3775 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 14:18:19.621  3775  3827 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 14:18:19.621  3775  3827 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 14:18:19.621  3775  3827 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-13 14:18:19.621  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-13 14:18:19.622  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 14:18:19.622  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:19.623  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:18:19.623  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:19.623  3775  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 14:18:19.624  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:18:19.624  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:19.627  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 14:18:19.629  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 14:18:19.629  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:18:19.630  3775  3775 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 14:18:19.630  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:18:19.630  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:18:19.631  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:19.631  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:18:19.633  3775  3845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:18:19.640  3775  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 14:18:19.641  3775  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 14:18:19.642  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 14:18:19.648  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:18:19.649  1517  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-13 14:18:19.649  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:18:19.649  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 14:18:19.649  1517  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-13 14:18:19.649  1517  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 14:18:19.649  1517  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 14:18:19.652  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 14:18:19.652  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 14:18:19.652  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
09-13 14:18:19.652  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:19.653  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 14:18:19.653  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 14:18:19.655  3775  3827 D BluetoothAdapter: STATE_ON
,09-13 14:18:19.659  2630  2754 D BtGatt.GattService: registerClient() - UUID=acd0fb20-b1c4-4d56-90a6-679e38100f1e
,09-13 14:18:19.660  2630  2675 D BtGatt.GattService: onClientRegistered() - UUID=acd0fb20-b1c4-4d56-90a6-679e38100f1e, clientIf=5
09-13 14:18:19.660  3775  3785 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 14:18:19.662  2630  2677 D BtGatt.AdvertiseManager: message : 0
,09-13 14:18:19.666  2630  2677 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 14:18:19.673  1739  3843 V BaseAuthAsyncOperation: access token request failed
,09-13 14:18:19.674  3009  3842 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 14:18:19.682  2630  2675 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 14:18:19.693  2630  2675 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 14:18:19.694  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:18:19.694  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 14:18:19.696  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:18:19.698  3775  3827 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 14:18:19.698  3775  3775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 14:18:19.699  3775  3775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 14:18:19.699  3775  3775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:18:19.699  3775  3775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 14:18:19.699  3775  3775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 14:18:19.700  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 14:18:19.706  3775  3775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 14:18:19.706  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:19.768  1517  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-13 14:18:19.769  1517  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 14:18:19.769  1517  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 14:18:19.770  1517  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 14:18:19.811  3009  3842 E KeepSync: IOException
09-13 14:18:19.811  3009  3842 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 14:18:19.811  3009  3842 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 14:18:19.811  3009  3842 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 14:18:19.811  3009  3842 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 14:18:19.811  3009  3842 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 14:18:19.811  3009  3842 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 14:18:19.811  3009  3842 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 14:18:19.811  3009  3842 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 14:18:19.811  3009  3842 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 14:18:19.811  3009  3842 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 14:18:19.811  3009  3842 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 14:18:19.811  3009  3842 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 14:18:19.811  3009  3842 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 14:18:19.811  3009  3842 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 14:18:19.811  3009  3842 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 14:18:19.811  3009  3842 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 14:18:19.811  3009  3842 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 14:18:19.811  3009  3842 E KeepSync: 	... 10 more
09-13 14:18:19.811  3009  3842 W KeepSync: Sync result 2
,09-13 14:18:19.827   871   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 126143, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 14:18:20.118  1517  2299 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 14:18:20.119  1517  2299 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-13 14:18:20.119  1517  2299 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 14:18:20.120  1517  2299 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 14:18:20.181  3535  3848 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 14:18:20.181  3535  3848 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at jdm.a(PG:82)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at jcs.o(PG:406)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at jcn.a(PG:1379)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at jcs.i(PG:143)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at blb.a(PG:3937)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at czp.a(PG:18188)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at czp.a(PG:9081)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at czq.run(PG:1686)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 14:18:20.181  3535  3848 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at jdj.a(PG:4091)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at jdj.a(PG:1125)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at jdm.a(PG:77)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	... 12 more
09-13 14:18:20.181  3535  3848 E HttpOperation: Caused by: faj: BadAuthentication
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at fal.a(PG:38)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	at jdj.a(PG:4089)
09-13 14:18:20.181  3535  3848 E HttpOperation: 	... 14 more
,09-13 14:18:20.204  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:20.204  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:18:20.205  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:18:20.205  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 14:18:20.206  3775  3845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:18:20.207  3775  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:18:20.207  3775  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 14:18:20.206  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-13 14:18:20.207  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:18:20.208  3775  3775 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 14:18:20.208  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
,09-13 14:18:20.208  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-13 14:18:20.208  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 14:18:20.208  3775  3775 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 14:18:20.208  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 14:18:20.209  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 14:18:20.209  3775  3775 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:18:20.209  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 14:18:20.216  3775  3827 D BluetoothAdapter: STATE_ON
,09-13 14:18:20.216  3775  3827 D BluetoothLeScanner: could not find callback wrapper
,09-13 14:18:20.216  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 14:18:20.217  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 14:18:20.220  2630  2677 D BtGatt.AdvertiseManager: message : 1
,09-13 14:18:20.223  2630  2677 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 14:18:20.239  2630  2675 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-13 14:18:20.239  2630  2675 D BtGatt.GattService: Client app is not null!
09-13 14:18:20.242  2630  2641 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 14:18:20.242  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 14:18:20.243  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 14:18:20.243  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 14:18:20.243  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 14:18:20.243  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:18:20.246  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:20.247  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:18:20.247  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:20.247  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:20.249  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
,09-13 14:18:20.249  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:20.249  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.250  3775  3827 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 14:18:20.251  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:20.251  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:20.251  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:20.251  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:20.255  3775  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:20.255  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:20.255  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:20.255  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:20.255  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:20.255  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:20.255  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:20.255  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:20.257  1517  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-13 14:18:20.257  1517  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 14:18:20.257  1517  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 14:18:20.257  1517  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 14:18:20.257  3775  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 14:18:20.259  3775  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:20.260  3775  3827 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-13 14:18:20.261  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-13 14:18:20.261  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:20.261  3775  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 14:18:20.261  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 14:18:20.261  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:20.263  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 14:18:20.264  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:18:20.264  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:18:20.264  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:18:20.264  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:18:20.264  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:20.264  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:20.264  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:20.267  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:20.267  3775  3775 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:18:20.268  3775  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 14:18:20.268  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 14:18:20.268  3775  3850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:18:20.271  3775  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 14:18:20.272  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:18:20.274  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:18:20.274  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:18:20.276  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 14:18:20.276  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 14:18:20.276  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
09-13 14:18:20.276  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 14:18:20.276  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:20.276  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 14:18:20.278  3535  3848 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 14:18:20.278  3535  3848 E HttpOperation: java.io.IOException: Cannot obtain authentication token,
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at jdm.a(PG:82)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at jcs.o(PG:406)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at jcn.a(PG:1379)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at jcs.i(PG:143)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at hec.a(PG:42)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at hee.a(PG:102)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at czr.a(PG:65)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at kka.a(PG:108)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at czp.a(PG:19176)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at czp.a(PG:9081)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at czq.run(PG:1686)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 14:18:20.278  3535  3848 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at jdj.a(PG:4091)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at jdj.a(PG:1125)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at jdm.a(PG:77)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	... 15 more
09-13 14:18:20.278  3535  3848 E HttpOperation: Caused by: faj: BadAuthentication
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at fal.a(PG:38)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	at jdj.a(PG:4089)
09-13 14:18:20.278  3535  3848 E HttpOperation: 	... 17 more
,09-13 14:18:20.278  3535  3848 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 14:18:20.278  3535  3848 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at hec.a(PG:42)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at hee.a(PG:102)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at czr.a(PG:65)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at kka.a(PG:108)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	... 15 more
09-13 14:18:20.278  3535  3848 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at fal.a(PG:38)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 14:18:20.278  3535  3848 E ExperimentLoader: 	... 17 more
,09-13 14:18:20.279  3775  3827 D BluetoothAdapter: STATE_ON
09-13 14:18:20.283  2630  2642 D BtGatt.GattService: registerClient() - UUID=97619926-87af-40de-a684-07abcf87e376
,09-13 14:18:20.284  2630  2675 D BtGatt.GattService: onClientRegistered() - UUID=97619926-87af-40de-a684-07abcf87e376, clientIf=5
,09-13 14:18:20.284  3775  3787 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-13 14:18:20.285  2630  2677 D BtGatt.AdvertiseManager: message : 0
,09-13 14:18:20.288  2630  2677 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 14:18:20.299  2630  2675 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 14:18:20.305  2630  2675 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 14:18:20.306  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:18:20.306  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 14:18:20.307  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:18:20.308  3775  3775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:20.308  3775  3775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 14:18:20.309  3775  3775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:18:20.309  3775  3775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 14:18:20.309  3775  3775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 14:18:20.309  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-13 14:18:20.309  3775  3827 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 14:18:20.311  3775  3775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:20.312  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:20.313  3775  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 14:18:20.313  3775  3827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 14:18:20.314  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 14:18:20.314  3775  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 14:18:20.314  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:18:20.314  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:18:20.314  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:18:20.314  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-13 14:18:20.314  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 14:18:20.314  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 14:18:20.314  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:18:20.314  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:18:20.314  3775  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:18:20.314  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 14:18:20.314  3775  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:18:20.314  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 14:18:20.314  3775  3775 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:18:20.314  3775  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 14:18:20.315  3775  3827 D BluetoothAdapter: STATE_ON
09-13 14:18:20.315  3775  3827 D BluetoothLeScanner: could not find callback wrapper
09-13 14:18:20.315  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:18:20.315  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 14:18:20.316  2630  2677 D BtGatt.AdvertiseManager: message : 1
09-13 14:18:20.316  2630  2677 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 14:18:20.324  2630  2675 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 14:18:20.324  2630  2675 D BtGatt.GattService: Client app is not null!
09-13 14:18:20.325  2630  2763 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 14:18:20.326  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 14:18:20.326  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 14:18:20.326  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 14:18:20.326  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 14:18:20.326  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:18:20.327  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:18:20.327  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:18:20.327  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 14:18:20.328  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:20.329  3775  3775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 14:18:20.329  3775  3775 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 14:18:20.329  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 14:18:20.329  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:20.329  3775  3775 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 14:18:20.329  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:20.332  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:20.332  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:20.333  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:20.333  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:20.333  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:20.333  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
09-13 14:18:20.333  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:20.334  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:20.336  3775  3827 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 14:18:20.337  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:20.337  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.337  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:20.337  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:20.337  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:20.337  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
09-13 14:18:20.337  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:20.337  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.338  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.338  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 14:18:20.338  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:20.339  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.339  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.339  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:20.339  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:20.339  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
09-13 14:18:20.339  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:20.339  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.339  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.340  3775  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-13 14:18:20.340  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:20.340  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.340  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.340  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:20.340  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:20.340  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
09-13 14:18:20.340  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:20.340  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.340  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.341  3775  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 14:18:20.341  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:20.341  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.341  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.341  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:20.341  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:20.341  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
09-13 14:18:20.341  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:20.342  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.342  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.342  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 14:18:20.342  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:20.342  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:20.343  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:20.343  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 14:18:20.343  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:20.343  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:20.343  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:20.343  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 14:18:20.343  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:20.343  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:20.343  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:20.343  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:20.343  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.344  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.344  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:20.344  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:20.344  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
09-13 14:18:20.344  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:20.344  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.344  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.345  3775  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:20.345  3775  3827 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 14:18:20.345  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 14:18:20.349  3775  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:20.349  3775  3827 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 14:18:20.349  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 14:18:20.350  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 14:18:20.350  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 14:18:20.350  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 14:18:20.350  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 14:18:20.350  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 14:18:20.350  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 14:18:20.350  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 14:18:20.350  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 14:18:20.350  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 14:18:20.350  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 14:18:20.350  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 14:18:20.350  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 14:18:20.350  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 14:18:20.351  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 14:18:20.351  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 14:18:20.351  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 14:18:20.351  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 14:18:20.351  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 14:18:20.351  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 14:18:20.351  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 14:18:20.351  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 14:18:20.351  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 14:18:20.351  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 14:18:20.351  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 14:18:20.352  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 14:18:20.352  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 14:18:20.352  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 14:18:20.352  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 14:18:20.352  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 14:18:20.352  3775  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 14:18:20.352  3775  3827 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 14:18:20.353  3775  3827 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 14:18:20.353  3775  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:20.353  3775  3827 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 14:18:20.353  3775  3827 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 14:18:20.353  3775  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:20.353  3775  3827 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 14:18:20.353  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 14:18:20.356  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 14:18:20.357  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 14:18:20.357  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 14:18:20.358  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 14:18:20.358  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 14:18:20.358  3775  3827 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 14:18:20.358  3775  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:20.358  3775  3827 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 14:18:20.358  3775  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 431)
09-13 14:18:20.359  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:20.359  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.359  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.359  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 14:18:20.360  3775  3853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 14:18:20.360  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:20.360  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:20.360  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
09-13 14:18:20.360  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:20.360  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.360  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.361  3775  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 431
09-13 14:18:20.361  3775  3827 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 14:18:20.361  3775  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 431)
09-13 14:18:20.361  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:20.361  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.362  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.362  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:20.362  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:20.362  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
09-13 14:18:20.362  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:20.362  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.362  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.363  3775  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 14:18:20.361  3775  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 431)
09-13 14:18:20.363  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:20.363  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.363  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.363  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:20.364  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:20.364  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
09-13 14:18:20.364  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:20.364  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.364  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.364  3775  3827 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 14:18:20.365  3775  3827 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 14:18:20.365  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 14:18:20.365  3775  3827 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 14:18:20.365  3775  3827 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 14:18:20.366  3775  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 14:18:20.366  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 14:18:20.366  3775  3827 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 14:18:20.366  3775  3827 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 14:18:20.366  3775  3827 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 14:18:20.366  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 14:18:20.366  3775  3827 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 14:18:20.366  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:20.366  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.366  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.365  3775  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 431)
09-13 14:18:20.366  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:20.367  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:20.367  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
09-13 14:18:20.367  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:20.367  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:20.367  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:20.368  3775  3827 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 14:18:20.370  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:20.374  3775  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:20.374  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:20.374  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:20.374  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:20.374  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:20.374  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:20.374  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:20.374  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:20.376  3775  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:20.376  3775  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:20.376  3775  3827 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-13 14:18:20.376  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-13 14:18:20.378  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:20.379  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:20.379  3775  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 14:18:20.380  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:20.379  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:18:20.380  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:20.381  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 14:18:20.382  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:18:20.382  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:18:20.382  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:18:20.382  3775  3775 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:18:20.382  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:18:20.382  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:20.382  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:20.383  3775  3855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 14:18:20.385  3775  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 14:18:20.385  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 14:18:20.385  3775  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 14:18:20.389  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 14:18:20.390  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:18:20.390  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 14:18:20.391  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 14:18:20.391  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 14:18:20.392  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
09-13 14:18:20.392  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:20.392  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:20.392  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 14:18:20.393  3775  3827 D BluetoothAdapter: STATE_ON
09-13 14:18:20.395  2630  2641 D BtGatt.GattService: registerClient() - UUID=6427c56d-0a52-48eb-91e2-7c638e57c4d4
09-13 14:18:20.395  2630  2675 D BtGatt.GattService: onClientRegistered() - UUID=6427c56d-0a52-48eb-91e2-7c638e57c4d4, clientIf=5
09-13 14:18:20.396  3775  3787 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-13 14:18:20.397  2630  2677 D BtGatt.AdvertiseManager: message : 0
09-13 14:18:20.398  2630  2677 D BtGatt.AdvertiseManager: starting multi advertising
09-13 14:18:20.405   871   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 126679, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
09-13 14:18:20.410  2630  2675 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
09-13 14:18:20.417  2630  2675 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-13 14:18:20.418  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:18:20.418  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 14:18:20.420  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-13 14:18:20.421  3775  3775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:20.421  3775  3775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 14:18:20.421  3775  3775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:18:20.421  3775  3775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 14:18:20.421  3775  3775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 14:18:20.422  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 14:18:20.422  3775  3827 I io.jxcore.node.ConnectionHelper: start: OK
09-13 14:18:20.424  3775  3775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 14:18:20.424  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:20.925  3775  3775 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 14:18:20.926  3775  3775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 14:18:20.926  3775  3775 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 14:18:20.926  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:20.926  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 14:18:20.927  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 14:18:20.927  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:18:20.927  3775  3775 D AndroidRuntime: Shutting down VM
09-13 14:18:20.928  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-13 14:18:20.928  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 14:18:20.928  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:20.929  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:20.929  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
--------- beginning of crash
09-13 14:18:20.930  3775  3775 E AndroidRuntime: FATAL EXCEPTION: main
09-13 14:18:20.930  3775  3775 E AndroidRuntime: Process: com.test.thalitest, PID: 3775
09-13 14:18:20.930  3775  3775 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-13 14:18:20.930  3775  3775 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
09-13 14:18:20.930  3775  3775 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper$2.onFinish(ConnectionHelper.java:487)
09-13 14:18:20.930  3775  3775 E AndroidRuntime: 	at android.os.CountDownTimer$1.handleMessage(CountDownTimer.java:127)
09-13 14:18:20.930  3775  3775 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:20.930  3775  3775 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 14:18:20.930  3775  3775 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 14:18:20.930  3775  3775 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 14:18:20.930  3775  3775 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 14:18:20.930  3775  3775 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 14:18:20.930  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:18:20.930  3775  3855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:18:20.930  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 14:18:20.931  3775  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:18:20.931  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 14:18:20.931  3775  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 14:18:20.934  3775  3827 D BluetoothAdapter: STATE_ON
,09-13 14:18:20.934  3775  3827 D BluetoothLeScanner: could not find callback wrapper
09-13 14:18:20.935  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:18:20.935  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 14:18:20.938  2630  2677 D BtGatt.AdvertiseManager: message : 1
09-13 14:18:20.939  2630  2677 D BtGatt.AdvertiseManager: stop advertise for client 5
09-13 14:18:20.940   871  2049 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
09-13 14:18:20.948   280   359 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (240 us)
,09-13 14:18:21.017   871  3858 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 14:18:21.032  2630  2675 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-13 14:18:21.032  2630  2675 D BtGatt.GattService: Client app is not null!
,09-13 14:18:21.034  2630  2642 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 14:18:21.035  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 14:18:21.035  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 14:18:21.035  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 14:18:21.035  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 14:18:21.035  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:18:21.040  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:21.040  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 14:18:21.040  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 14:18:21.042  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:21.045  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
,09-13 14:18:21.045  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:21.045  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:21.052  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:21.052  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:21.052  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:21.053  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:21.053  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:21.053  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
09-13 14:18:21.053  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:21.053  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:21.054  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:21.057  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 14:18:21.057  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:21.061  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 14:18:21.062  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:18:21.062  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 14:18:21.063  3775  3860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 14:18:21.063  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 14:18:21.063  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 14:18:21.064  3775  3860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 14:18:21.064  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:21.065  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:18:21.065  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:18:21.065  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:18:21.066  3775  3860 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 14:18:21.066  3775  3860 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 14:18:21.069  3775  3860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 14:18:21.066  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:21.069  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:18:21.070  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:21.070  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:21.070  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:18:21.070  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:18:21.070  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 14:18:21.071  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:21.071  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:21.074  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:18:21.074  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
09-13 14:18:21.074  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:21.075  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:21.075  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:21.077  3775  3827 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 14:18:21.077  3775  3827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-13 14:18:21.077  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 14:18:21.077  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:21.077  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:21.077  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:21.077  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:21.078  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:21.078  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:21.078  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
09-13 14:18:21.078  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:21.078  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
,09-13 14:18:21.078  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:21.078  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:21.078  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:21.083  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:21.083  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:21.083  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:21.083  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
,09-13 14:18:21.083  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:21.083  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
09-13 14:18:21.083  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:21.083  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:21.083  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:21.084  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:21.084  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:21.084  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:21.084  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e281e not in the list
,09-13 14:18:21.084  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:21.084  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97468ff not in the list
,09-13 14:18:21.084  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:21.084  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:21.084  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
,09-13 14:18:21.085  3775  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-13 14:18:21.085  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-13 14:18:21.085  3775  3827 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 14:18:21.086  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 14:18:21.086  3775  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-13 14:18:21.086  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 14:18:21.088  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 14:18:21.088  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 14:18:21.089  3775  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-13 14:18:21.090  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 14:18:21.090  3775  3827 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-13 14:18:21.090  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 14:18:21.090  3775  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-13 14:18:21.090   871  3858 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 14:18:21.090   871  3858 I Adreno  : Build Date                       : 10/20/15
09-13 14:18:21.090   871  3858 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 14:18:21.090   871  3858 I Adreno  : Local Branch                     : M14
09-13 14:18:21.090   871  3858 I Adreno  : Remote Branch                    : 
09-13 14:18:21.090   871  3858 I Adreno  : Remote Branch                    : 
09-13 14:18:21.090   871  3858 I Adreno  : Reconstruct Branch               : 
09-13 14:18:21.090  3775  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-13 14:18:21.094  3775  3827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 14:18:21.094  3775  3827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-13 14:18:21.095  3775  3827 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 14:18:21.096  3775  3827 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-13 14:18:21.096  3775  3827 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-13 14:18:21.096  3775  3827 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-13 14:18:21.096   871  3858 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 14:18:21.102  3775  3861 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-13 14:18:21.103  3775  3861 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 14:18:21.494   871   885 W ActivityManager: Activity pause timeout for ActivityRecord{8ca5145 u0 com.test.thalitest/.MainActivity t4 f}
,09-13 14:18:21.531   871   885 I ActivityManager: Killing 3381:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-13 14:18:21.631  3775  3861 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-13 14:18:21.632  3775  3861 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 14:18:21.632  3775  3861 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:21.633  3775  3861 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 14:18:21.633  3775  3861 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 14:18:21.636  3775  3866 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-13 14:18:21.636  3775  3866 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-13 14:18:21.636  3775  3866 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 14:18:21.637  3775  3866 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:21.637  3775  3866 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 14:18:21.648  3775  3870 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 485, name: OutgoingSocketThread/Receiver)
09-13 14:18:21.649  3775  3870 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 485, thread name: OutgoingSocketThread/Receiver)
,09-13 14:18:21.649  3775  3870 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-13 14:18:21.649  3775  3870 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 485, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 14:18:21.654  3775  3869 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 484, name: OutgoingSocketThread/Sender)
,09-13 14:18:21.661  3775  3871 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 486, name: IncomingSocketThread/Sender)
,09-13 14:18:21.662  3775  3872 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 487, name: IncomingSocketThread/Receiver)
,09-13 14:18:21.667  3775  3872 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 487, thread name: IncomingSocketThread/Receiver)
09-13 14:18:21.668  3775  3872 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 14:18:21.668  3775  3872 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 487, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 14:18:22.168  3775  3827 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 14:18:22.171  3775  3827 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 14:18:22.177  3775  3827 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1b25b Bundle[{}]
,09-13 14:18:22.180  3775  3827 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 14:18:22.180  3775  3827 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 14:18:22.183  3775  3827 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 14:18:22.184  3775  3827 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 14:18:22.186  3775  3827 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 14:18:22.188  3775  3827 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 14:18:22.195  3775  3877 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 14:18:22.197  3775  3877 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 14:18:22.222  1941  2176 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,09-13 14:18:22.761  3775  3877 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-13 14:18:22.762  3775  3877 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 14:18:22.762  3775  3877 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:22.763  3775  3877 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:22.763  3775  3877 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 14:18:22.765  3775  3879 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 14:18:22.765  3775  3879 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 14:18:22.765  3775  3879 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:22.766  3775  3879 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:22.766  3775  3879 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 14:18:22.769  3775  3882 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 499, name: OutgoingSocketThread/Receiver)
09-13 14:18:22.770  3775  3882 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 499, thread name: OutgoingSocketThread/Receiver)
,09-13 14:18:22.773  3775  3882 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-13 14:18:22.774  3775  3882 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 499, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 14:18:22.771  3775  3883 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 500, name: IncomingSocketThread/Sender)
,09-13 14:18:22.776  3775  3881 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 498, name: OutgoingSocketThread/Sender)
09-13 14:18:22.778  3775  3884 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 501, name: IncomingSocketThread/Receiver)
09-13 14:18:22.779  3775  3884 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 501, thread name: IncomingSocketThread/Receiver)
,09-13 14:18:22.779  3775  3884 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 14:18:22.779  3775  3884 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 501, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 14:18:23.305  3775  3827 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 510)
,09-13 14:18:23.309  3775  3827 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 14:18:23.309  3775  3827 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 511)
,09-13 14:18:23.312  3775  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 14:18:23.312  3775  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054afc added. We now have 4 listener(s)
,09-13 14:18:23.315  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 14:18:23.315  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 14:18:23.315  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 14:18:23.315  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:18:23.315  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d01e585 added. We now have 4 listener(s)
,09-13 14:18:23.315  3775  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 14:18:23.316  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 14:18:23.320  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:23.320   871   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{21524a6 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{c7a47e8 3775 com.test.thalitest/10000/u0 remote:f5ffd0b}: process crashing
09-13 14:18:23.321   871   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{28f5ee7 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{c7a47e8 3775 com.test.thalitest/10000/u0 remote:f5ffd0b}: process crashing
,09-13 14:18:23.329  3775  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:23.329  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:23.329  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:23.329  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:23.329  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:23.329  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:23.329  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:23.329  3775  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:23.332  3775  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 14:18:23.333  3775  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 14:18:23.339  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:23.339  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:23.339  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:23.339  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 14:18:23.339  3775  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054afc removed from the list
09-13 14:18:23.339  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:23.339  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d01e585 removed from the list
09-13 14:18:23.340  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:23.340  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:23.342  3775  3827 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-13 14:18:23.342  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-13 14:18:23.347  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 14:18:23.347  3775  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 14:18:23.347  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 14:18:23.347  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:23.349  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 14:18:23.350  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 14:18:23.350  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 14:18:23.350  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:18:23.350  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 14:18:23.350  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:23.350  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:23.355   871   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{d690283 u-1 android.net.wifi.p2p.STATE_CHANGED} to ReceiverList{beef93d 3775 com.test.thalitest/10000/u0 remote:39ffa94}: process crashing
09-13 14:18:23.356   871   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{8cc2c00 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{beef93d 3775 com.test.thalitest/10000/u0 remote:39ffa94}: process crashing
09-13 14:18:23.359  3775  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 14:18:23.359  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 14:18:23.363  3775  3885 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:18:23.367  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 14:18:23.368  3775  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 14:18:23.369  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 14:18:23.369  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:18:23.372  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 14:18:23.373  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 14:18:23.373  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
09-13 14:18:23.373  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:23.373  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:23.373  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 14:18:23.374  3775  3827 D BluetoothAdapter: STATE_ON
,09-13 14:18:23.378  2630  2641 D BtGatt.GattService: registerClient() - UUID=0b237428-7702-4a6e-be8c-058707b6ddb7
,09-13 14:18:23.379  2630  2675 D BtGatt.GattService: onClientRegistered() - UUID=0b237428-7702-4a6e-be8c-058707b6ddb7, clientIf=5
09-13 14:18:23.380  3775  3817 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 14:18:23.381  2630  2677 D BtGatt.AdvertiseManager: message : 0
,09-13 14:18:23.385  2630  2677 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 14:18:23.405  2630  2675 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 14:18:23.422  2630  2675 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 14:18:23.423  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:18:23.424  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 14:18:23.428  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:18:24.400   871  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 14:18:25.492  2630  2712 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-13 14:18:25.494  2630  2735 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,09-13 14:18:28.844  3775  3886 E com.test.thalitest.ThaliTestRunner: Discovery manager didn't start after 5s!
,09-13 14:18:31.629   871   885 W ActivityManager: Activity destroy timeout for ActivityRecord{8ca5145 u0 com.test.thalitest/.MainActivity t4 f}
,09-13 14:18:31.888  3775  3827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 14:18:31.889  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 14:18:31.889  3775  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 14:18:31.890  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 14:18:31.890  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:18:31.890  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 14:18:31.900  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:31.900  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 14:18:31.901  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 14:18:31.901  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:31.902  3775  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:18:31.903  3775  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 14:18:31.904  3775  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 14:18:31.908  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:31.913  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:31.914  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:31.914  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:31.914  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054afc not in the list
09-13 14:18:31.914  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:31.914  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d01e585 not in the list
09-13 14:18:31.914  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:31.914  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:31.914  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:31.915  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:31.917  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 14:18:31.917  3775  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:18:31.917  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:18:31.917  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:31.918  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:18:31.923   871   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{dc8082c u-1 android.net.wifi.p2p.STATE_CHANGED} to ReceiverList{a12227e 3775 com.test.thalitest/10000/u0 remote:c56ec39}: process crashing
,09-13 14:18:31.923   871   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{eb112f5 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{a12227e 3775 com.test.thalitest/10000/u0 remote:c56ec39}: process crashing
,09-13 14:18:31.925  3775  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 14:18:31.929  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 14:18:31.937  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-13 14:18:31.937  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 14:18:31.937  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 14:18:31.940  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 14:18:31.941  3775  3827 D BluetoothAdapter: STATE_ON
,09-13 14:18:31.948  2630  2754 D BtGatt.GattService: registerClient() - UUID=29871b5c-a0db-4b42-a817-0a9e753af63a
,09-13 14:18:31.950  2630  2675 D BtGatt.GattService: onClientRegistered() - UUID=29871b5c-a0db-4b42-a817-0a9e753af63a, clientIf=6
,09-13 14:18:31.953  3775  3787 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-13 14:18:31.954  2630  2763 D BtGatt.GattService: start scan with filters
,09-13 14:18:31.961  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 14:18:31.962  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 14:18:31.962  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING, ADVERTISING]
,09-13 14:18:31.962  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING, ADVERTISING]
09-13 14:18:31.962  2630  2678 D BtGatt.ScanManager: handling starting scan
,09-13 14:18:31.967  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,09-13 14:18:31.967  2630  2678 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c0413f
09-13 14:18:31.967  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 14:18:31.969  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:18:31.980  2630  2675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-13 14:18:31.980  2630  2675 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:18:31.982  2630  2678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 14:18:31.999  2630  2675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-13 14:18:31.999  2630  2675 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:18:32.000  2630  2678 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 14:18:32.001  2630  2678 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 14:18:32.036  2630  2675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-13 14:18:32.037  2630  2675 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 14:18:32.060  2630  2675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-13 14:18:32.061  2630  2675 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 14:18:33.487   871  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 14:18:33.491   871  1304 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-13 14:18:33.561  2630  2630 D BtGatt.ScanManager: awakened up at time 140405
,09-13 14:18:33.564  2630  2678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 14:18:33.595  2630  2675 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=4
,09-13 14:18:33.595  2630  2675 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:18:33.596  2630  2675 D BtGatt.GattService: current time is 140439967436
09-13 14:18:33.596  2630  2675 D BtGatt.GattService: Batch record : [0, 12, 83, 61, 110, 116, 1, -128, -57, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96, 0, 35, 97, 126, -92, 22, -56, 1, -128, -84, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, -128, -84, 20, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 14:18:33.597  2630  2675 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96]
09-13 14:18:33.598  2630  2675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-13 14:18:33.598  2630  2675 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,09-13 14:18:33.598  2630  2675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 14:18:35.013  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,09-13 14:18:35.013  3775  3827 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 14:18:35.014  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:35.014  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:35.014  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:35.015  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054afc not in the list
,09-13 14:18:35.016  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:35.017  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:18:35.018  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:18:35.018  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 14:18:35.020  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 14:18:35.020  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 14:18:35.026  3775  3827 D BluetoothAdapter: STATE_ON
,09-13 14:18:35.029  2630  2642 D BtGatt.GattService: stopScan() - queue size =1
,09-13 14:18:35.034  2630  2641 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 14:18:35.034  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:18:35.034  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 14:18:35.034  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 14:18:35.035  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
09-13 14:18:35.035  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,09-13 14:18:35.038  2630  2630 D BtGatt.ScanManager: awakened up at time 141882
09-13 14:18:35.040  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 14:18:35.040  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 14:18:35.041  2630  2677 D BtGatt.AdvertiseManager: message : 1
,09-13 14:18:35.042  2630  2677 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 14:18:35.048  2630  2675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-13 14:18:35.048  2630  2675 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:18:35.048  2630  2678 D BtGatt.ScanManager: stopping BLe Batch,
,09-13 14:18:35.061  2630  2675 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 14:18:35.062  2630  2675 D BtGatt.GattService: Client app is not null!
,09-13 14:18:35.063  2630  2641 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 14:18:35.064  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 14:18:35.064  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
09-13 14:18:35.065  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 14:18:35.065  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 14:18:35.065  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:18:35.067  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:35.067  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 14:18:35.067  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:35.069  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:35.071  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d01e585 not in the list
,09-13 14:18:35.071  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:35.071  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:35.071  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:35.073  3775  3827 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-13 14:18:35.073  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-13 14:18:35.076  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 14:18:35.077  3775  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 14:18:35.077  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:18:35.077  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:35.079  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 14:18:35.080  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 14:18:35.080  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 14:18:35.080  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 14:18:35.081  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:18:35.081  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:35.082  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:18:35.086   871   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{4ce971 u-1 android.net.wifi.p2p.STATE_CHANGED} to ReceiverList{8ee3efb 3775 com.test.thalitest/10000/u0 remote:3a9e88a}: process crashing
09-13 14:18:35.086   871   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{e460356 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{8ee3efb 3775 com.test.thalitest/10000/u0 remote:3a9e88a}: process crashing
,09-13 14:18:35.088  2630  2675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-13 14:18:35.089  2630  2675 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:18:35.089  2630  2678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-13 14:18:35.090  3775  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 14:18:35.090  3775  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 14:18:35.096  3775  3889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:18:35.098  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:18:35.099  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:18:35.099  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:18:35.100  3775  3889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 14:18:35.104  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 14:18:35.104  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 14:18:35.105  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
09-13 14:18:35.105  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:35.105  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 14:18:35.105  3775  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 14:18:35.107  3775  3827 D BluetoothAdapter: STATE_ON
,09-13 14:18:35.110  2630  2754 D BtGatt.GattService: registerClient() - UUID=25ffe39d-bfa1-40f3-9aa4-d36fbe188024
,09-13 14:18:35.111  2630  2675 D BtGatt.GattService: onClientRegistered() - UUID=25ffe39d-bfa1-40f3-9aa4-d36fbe188024, clientIf=5
09-13 14:18:35.111  3775  3785 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 14:18:35.112  2630  2677 D BtGatt.AdvertiseManager: message : 0
,09-13 14:18:35.118  2630  2677 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 14:18:35.133  2630  2675 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 14:18:35.139  2630  2675 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=4
,09-13 14:18:35.140  2630  2675 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 14:18:35.140  2630  2675 D BtGatt.GattService: current time is 141984338788
,09-13 14:18:35.140  2630  2675 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -81, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -90, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -93, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, 4, -94, 18, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-13 14:18:35.141  2630  2675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 14:18:35.141  2630  2675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 14:18:35.141  2630  2675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 14:18:35.142  2630  2675 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-13 14:18:35.145  2630  2675 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 14:18:35.146  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 14:18:35.146  3775  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 14:18:35.148  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:18:36.507   871  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 14:18:36.513   871  1304 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-13 14:18:36.833   871  1833 D NetlinkSocketObserver: NeighborEvent{elapsedMs=143677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 14:18:40.533  3775  3890 E com.test.thalitest.ThaliTestRunner: Discovery manager didn't start after 5s!
,09-13 14:18:42.567   871  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 14:18:43.001   871   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-13 14:18:43.582  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:43.582  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 14:18:43.583  3775  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 14:18:43.583  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 14:18:43.588  3775  3889 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 14:18:43.589  3775  3889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 14:18:43.589  3775  3889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 14:18:43.594  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:43.594  3775  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 14:18:43.595  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054afc not in the list
,09-13 14:18:43.601  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:43.601  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d01e585 not in the list
09-13 14:18:43.601  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:43.602  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:43.602  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:43.605  3775  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:43.605  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:43.605  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:43.605  3775  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f054afc not in the list
09-13 14:18:43.605  3775  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:43.605  3775  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d01e585 not in the list
09-13 14:18:43.606  3775  3827 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:43.606  3775  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:43.606  3775  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:43.607  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 14:18:43.607  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 14:18:43.607  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:43.607  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:43.608  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-13 14:18:43.608  3775  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 14:18:43.620  3775  3894 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 531, name: My test thread name)
,09-13 14:18:43.738   871   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-13 14:18:43.752   871   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-13 14:18:43.760   871   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-13 14:18:43.763   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,09-13 14:18:43.763   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-13 14:18:44.002   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 14:18:44.006   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-13 14:18:44.012   871  1329 D SurfaceControl: Excessive delay in setPowerMode(): 253ms
09-13 14:18:44.018   871   892 I DreamManagerService: Entering dreamland.
09-13 14:18:44.020   871   892 I PowerManagerService: Dozing...
,09-13 14:18:44.021   871   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-13 14:18:44.055   376  1275 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-13 14:18:44.056   376  1275 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-13 14:18:44.061   871  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 14:18:44.067  1913  3897 D NfcService: Discovery configuration equal, not updating.
,09-13 14:18:44.070   871  1302 E native  : do suspend false
,09-13 14:18:44.090   871  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 14:18:44.104   871  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 14:18:44.107   871  1302 E native  : do suspend true
,09-13 14:18:44.199   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-13 14:18:44.200   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-13 14:18:44.565   871  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-13 14:18:45.659  3775  3827 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 531
,09-13 14:18:45.660  3775  3827 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 531, name: My test thread name)
,09-13 14:18:45.666  3775  3894 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 531, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-13 14:18:45.672  3775  3901 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 532, name: My test thread name)
,09-13 14:18:45.672  3775  3901 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 532, thread name: My test thread name)
,09-13 14:18:45.673  3775  3901 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 532, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 14:18:45.679  3775  3827 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 14:18:45.683  3775  3902 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 536, name: My test thread name)
,09-13 14:18:45.683  3775  3902 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 536, thread name: My test thread name): Test exception.
09-13 14:18:45.683  3775  3902 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 536, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 14:18:45.685  3775  3827 E com.test.thalitest.ThaliTestRunner: testExecuteStopOperation(io.jxcore.node.StartStopOperationHandlerTest)
,09-13 14:18:45.685  3775  3827 E com.test.thalitest.ThaliTestRunner: mCurrentOperation should be null
09-13 14:18:45.685  3775  3827 E com.test.thalitest.ThaliTestRunner: Expected: is null
09-13 14:18:45.685  3775  3827 E com.test.thalitest.ThaliTestRunner:      but: was <Stop operation: Should start/stop everything>
,09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: mCurrentOperation should be null
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: Expected: is null
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner:      but: was <Stop operation: Should start/stop everything>
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StartStopOperationHandlerTest.testExecuteStopOperation(StartStopOperationHandlerTest.java:201)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-13 14:18:45.688  3,775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:81)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: testExecuteStartOperation(io.jxcore.node.StartStopOperationHandlerTest)
,09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: mCurrentOperation should be null
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner: Expected: is null
09-13 14:18:45.688  3775  3827 E com.test.thalitest.ThaliTestRunner:      but: was <Start operation: Should start/stop everything>
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: mCurrentOperation should be null
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: Expected: is null
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner:      but: was <Start operation: Should start/stop everything>
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StartStopOperationHandlerTest.testExecuteStartOperation(StartStopOperationHandlerTest.java:154)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildr,en(ParentRunner.java:288)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:81)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
09-13 14:18:45.690  3775  3827 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-13 14:18:45.692  3775  3827 I jxcore-log: Total number of executed tests:  76
09-13 14:18:45.692  3775  3827 I jxcore-log: 
,09-13 14:18:45.693  3775  3827 I jxcore-log: Number of passed tests:  74
09-13 14:18:45.693  3775  3827 I jxcore-log: 
09-13 14:18:45.694  3775  3827 I jxcore-log: Number of failed tests:  2
09-13 14:18:45.694  3775  3827 I jxcore-log: 
09-13 14:18:45.695  3775  3827 I jxcore-log: Number of ignored tests:  0
09-13 14:18:45.695  3775  3827 I jxcore-log: 
,09-13 14:18:45.695  3775  3827 I jxcore-log: Total duration:  26784
09-13 14:18:45.695  3775  3827 I jxcore-log: 
09-13 14:18:45.697  3775  3827 I jxcore-log: Failed to execute UT.
09-13 14:18:45.697  3775  3827 I jxcore-log: 
09-13 14:18:45.697  3775  3827 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-13 14:18:45.697  3775  3827 I jxcore-log: 
,09-13 14:18:45.702  3775  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:45.702  3775  3827 I jxcore-log: 
09-13 14:18:45.704  3775  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:45.704  3775  3827 I jxcore-log: 
09-13 14:18:45.705  3775  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:45.705  3775  3827 I jxcore-log: 
09-13 14:18:45.707  3775  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:45.707  3775  3827 I jxcore-log: 
09-13 14:18:45.709  3775  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 14:18:45.709  3775  3827 I jxcore-log: 
,09-13 14:18:45.712  3775  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 14:18:45.712  3775  3827 I jxcore-log: 
,09-13 14:18:45.714  3775  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:45.714  3775  3827 I jxcore-log: 
09-13 14:18:45.715  3775  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:45.715  3775  3827 I jxcore-log: 
,09-13 14:18:46.360  3903  3903 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-13 14:18:46.365  3903  3903 D AndroidRuntime: CheckJNI is OFF
,09-13 14:18:46.407  3903  3903 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-13 14:18:46.454  3903  3903 I Radio-JNI: register_android_hardware_Radio DONE
,09-13 14:18:46.476  3903  3903 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 14:18:46.485   871   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-13 14:18:46.486   871   885 I ActivityManager: Killing 3775:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,09-13 14:18:46.607  2630  2754 D BtGatt.GattService: Binder is dead - unregistering client (5)!
,09-13 14:18:46.607   871  1375 D GraphicsStats: Buffer count: 3
09-13 14:18:46.608   871  1303 D WifiService: Client connection lost with reason: 4
,09-13 14:18:46.640   871   895 W PackageSettings: Skipping PackageSetting{5e34b30 com.example.hello/10273} due to missing metadata
,09-13 14:18:46.649   871  2052 W ActivityManager: Spurious death for ProcessRecord{fd5883a 0:com.test.thalitest/u0a0}, curProc for 3775: null
,09-13 14:18:46.651   871   886 W AppOps  : Finishing op nesting under-run: uid 1000 pkg android code 24 time=1465474415550 duration=35 nesting=0
,09-13 14:18:46.655   871  1694 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3775 uid 10000
,09-13 14:18:46.660  1867  1867 I Keyboard.Facilitator: onFinishInput()
,09-13 14:18:46.675  2630  2677 D BtGatt.AdvertiseManager: message : 1
,09-13 14:18:46.675  2630  2677 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 14:18:46.678  2630  2677 D BtGatt.AdvertiseManager: app died - unregistering client : 5
,09-13 14:18:46.679  2630  2677 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 14:18:46.680   871   895 I art     : Starting a blocking GC Explicit
,09-13 14:18:46.685  2630  2675 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=255, status=0
,09-13 14:18:46.685  2630  2675 E BtGatt.ContextMap: Context not found for ID 255
,09-13 14:18:46.724   871   895 I art     : Explicit concurrent mark sweep GC freed 33598(2MB) AllocSpace objects, 9(224KB) LOS objects, 33% free, 29MB/43MB, paused 712us total 43.573ms
,09-13 14:18:46.782   871   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-13 14:18:46.789   871   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-13 14:18:46.789  3903  3903 I art     : System.exit called, status: 0
,09-13 14:18:46.790  3903  3903 I AndroidRuntime: VM exiting with result code 0.
,09-13 14:18:46.818  2630  2630 D BluetoothMapAppObserver: onReceive
09-13 14:18:46.818  2630  2630 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-13 14:18:46.823  3650  3650 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-13 14:18:46.829  2138  2288 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 14:18:46.832   871  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 14:18:46.832  1867  1867 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-13 14:18:46.844  1867  3914 I Keyboard.Facilitator.DecoderInitializer: run()
,09-13 14:18:46.864  3480  3917 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-13 14:18:46.866  1922  1922 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-13 14:18:46.868  1867  3914 I Decoder : createOrResetDecoder
,09-13 14:18:46.910  1517  1517 I ConfigService: onCreate
,09-13 14:18:46.921  1517  1517 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-13 14:18:46.921  1517  1517 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-13 14:18:46.927  1867  3914 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-13 14:18:46.935  1739  3921 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-13 14:18:46.936  1739  3921 D AccountUtils: Clearing selected account for com.test.thalitest
,09-13 14:18:46.936   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-13 14:18:46.953  1867  3914 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-13 14:18:46.954  1867  3914 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-13 14:18:46.954  1867  3914 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-13 14:18:46.957  1867  3914 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-13 14:18:46.957  1867  3914 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-13 14:18:46.958  1867  3914 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-13 14:18:46.958  1867  3914 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-13 14:18:46.958  1867  3914 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-13 14:18:46.958  1867  3914 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-13 14:18:46.958  1867  3914 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-13 14:18:46.959  1867  3914 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-13 14:18:46.959  1867  3914 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-13 14:18:46.959  1867  3914 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-13 14:18:46.970  1941  2025 E SQLiteLog: (1546) os_unix.c:29096: (22) ftruncate(/data/user/0/com.google.android.googlequicksearchbox/databases/app_icons.db) - 
,09-13 14:18:46.971  1739  3921 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-13 14:18:46.984   871  1694 I ActivityManager: Start proc 3926:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-13 14:18:46.984  1941  2025 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-13 14:18:46.984  1941  2025 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1941
09-13 14:18:46.984  1941  2025 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 1546)
09-13 14:18:46.984  1941  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 14:18:46.984  1941  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 14:18:46.984  1941  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 14:18:46.984  1941  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 14:18:46.984  1941  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 14:18:46.984  1941  2025 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-13 14:18:46.984  1941  2025 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-13 14:18:46.984  1941  2025 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 14:18:46.984  1941  2025 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 14:18:46.984  1941  2025 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 14:18:46.984  1941  2025 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 14:18:46.986   871  1984 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 14:18:46.986  3480  3917 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
,09-13 14:18:46.987   871  3931 E DropBoxManagerService: Can't write: system_app_crash
09-13 14:18:46.987   871  3931 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
09-13 14:18:46.987   871  3931 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 14:18:46.987   871  3931 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 14:18:46.987   871  3931 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 14:18:46.987   871  3931 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 14:18:46.987   871  3931 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 14:18:46.987   871  3931 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 14:18:46.987   871  3931 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 14:18:46.987   871  3931 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 14:18:46.987   871  3931 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 14:18:46.987   871  3931 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 14:18:46.987   871  3931 E DropBoxManagerService: 	... 5 more
09-13 14:18:46.987  3480  3917 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-13 14:18:46.987  3480  3917 E AndroidRuntime: Process: android.process.acore, PID: 3480
09-13 14:18:46.987  3480  3917 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 14:18:46.987  3480  3917 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 14:18:46.994  1941  2025 I Process : Sending signal. PID: 1941 SIG: 9
,09-13 14:18:46.996   871  3935 E DropBoxManagerService: Can't write: system_app_crash
09-13 14:18:46.996   871  3935 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
09-13 14:18:46.996   871  3935 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 14:18:46.996   871  3935 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 14:18:46.996   871  3935 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 14:18:46.996   871  3935 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 14:18:46.996   871  3935 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 14:18:46.996   871  3935 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 14:18:46.996   871  3935 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 14:18:46.996   871  3935 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 14:18:46.996   871  3935 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 14:18:46.996   871  3935 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 14:18:46.996   871  3935 E DropBoxManagerService: 	... 5 more
,09-13 14:18:47.006  1739  3921 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 14:18:47.006  1739  3921 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-13 14:18:47.006  1739  3921 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 14:18:47.007  3480  3917 I Process : Sending signal. PID: 3480 SIG: 9
09-13 14:18:47.008  1739  3921 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-13 14:18:47.043  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-13 14:18:47.043  1739  1739 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-13 14:18:47.050   278   278 E lowmemorykiller: Error writing /proc/3480/oom_score_adj; errno=22
,09-13 14:18:47.052   278   278 E lowmemorykiller: Error writing /proc/3480/oom_score_adj; errno=22
,09-13 14:18:47.054  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-13 14:18:47.054  1739  1739 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-13 14:18:47.062  1739  3941 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-13 14:18:47.063  1739  3941 E DriveAsyncService: disk I/O error (code 3850)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 14:18:47.063  1739  3941 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,09-13 14:18:47.090   278   278 E lowmemorykiller: Error writing /proc/1941/oom_score_adj; errno=22
09-13 14:18:47.090   278   278 E lowmemorykiller: Error writing /proc/3480/oom_score_adj; errno=22
09-13 14:18:47.090   871   882 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
,09-13 14:18:47.091   871   882 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
09-13 14:18:47.091   871   882 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-13 14:18:47.091   871   882 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 14:18:47.091   871   882 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-13 14:18:47.091   871   882 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-13 14:18:47.091   871   882 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-13 14:18:47.091   871   882 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-13 14:18:47.091   871   882 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
09-13 14:18:47.091   871   882 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-13 14:18:47.091   871   882 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-13 14:18:47.091   871   882 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 14:18:47.099  1739  3947 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-13 14:18:47.102  1739  3942 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 14:18:47.102  1739  3942 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-13 14:18:47.103  1739  3942 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 14:18:47.106  1739  3942 W SQLiteOpenHelper: Opened metrics.db in read-only mode
,09-13 14:18:47.106  1739  3942 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
09-13 14:18:47.106  1739  3942 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
,09-13 14:18:47.110  1739  3942 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,09-13 14:18:47.113  1739  3942 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
,09-13 14:18:47.113  1739  3942 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
09-13 14:18:47.113  1739  3942 E AndroidRuntime: Process: com.google.android.gms, PID: 1739
09-13 14:18:47.113  1739  3942 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
09-13 14:18:47.113  1739  3942 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 14:18:47.113  1739  3942 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 14:18:47.113  1739  3942 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 14:18:47.113  1739  3942 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 14:18:47.113  1739  3942 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 14:18:47.113  1739  3942 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
09-13 14:18:47.113  1739  3942 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
09-13 14:18:47.113  1739  3942 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 14:18:47.113  1739  3942 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:47.113  1739  3942 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 14:18:47.113  1739  3942 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 14:18:47.128   871  1293 W InputDispatcher: channel '7782da4 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,09-13 14:18:47.128   871  1984 D GraphicsStats: Buffer count: 2
09-13 14:18:47.128   871  1293 E InputDispatcher: channel '7782da4 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,09-13 14:18:47.128   871  1984 I WindowState: WIN DEATH: Window{7782da4 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-13 14:18:47.134   871  1984 W InputDispatcher: Attempted to unregister already unregistered input channel '7782da4 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,09-13 14:18:47.146   871   882 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms,
,09-13 14:18:47.160   871   882 I ActivityManager: Start proc 3949:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,09-13 14:18:47.162   871  2050 W ActivityManager: Spurious death for ProcessRecord{352c46a 3949:com.google.android.googlequicksearchbox/u0a28}, curProc for 1941: null
,09-13 14:18:47.163  1739  3942 I Process : Sending signal. PID: 1739 SIG: 9
09-13 14:18:47.163   871   881 I ActivityManager: Process android.process.acore (pid 3480) has died
09-13 14:18:47.163   871   881 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-13 14:18:47.166   278   278 E lowmemorykiller: Error writing /proc/1739/oom_score_adj; errno=22
09-13 14:18:47.167   871  2051 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1768)
09-13 14:18:47.168   871  3954 E DropBoxManagerService: Can't write: system_app_crash
09-13 14:18:47.168   871  3954 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
09-13 14:18:47.168   871  3954 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 14:18:47.168   871  3954 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 14:18:47.168   871  3954 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 14:18:47.168   871  3954 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 14:18:47.168   871  3954 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 14:18:47.168   871  3954 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 14:18:47.168   871  3954 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 14:18:47.168   871  3954 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 14:18:47.168   871  3954 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 14:18:47.168   871  3954 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 14:18:47.168   871  3954 E DropBoxManagerService: 	... 5 more
,09-13 14:18:47.168   871  2051 W ActivityManager: Application dead when creating service ServiceRecord{24b168 u0 com.google.android.gms/.feedback.FeedbackAsyncService}
,09-13 14:18:47.219   871   881 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@c1d6981)
,09-13 14:18:47.219   871  1304 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 14:18:47.220   871  1304 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 14:18:47.226   871  2051 I ActivityManager: Process com.google.android.gms (pid 1739) has died
,09-13 14:18:47.228   871  2051 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
09-13 14:18:47.228   871  2051 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 10999ms
09-13 14:18:47.229   871  2051 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20999ms
,09-13 14:18:47.229   871  2051 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20998ms
09-13 14:18:47.230   871  2051 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20997ms,
09-13 14:18:47.230   871  2051 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20997ms
,09-13 14:18:47.231   871  2051 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20996ms
,09-13 14:18:47.232   871  2051 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackAsyncService in 20996ms
,09-13 14:18:47.235   871  2051 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackAsyncService in 83984ms
,09-13 14:18:47.237   871  2051 W ActivityManager: Exception when starting service com.google.android.gms/.feedback.FeedbackAsyncService
09-13 14:18:47.237   871  2051 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-13 14:18:47.237   871  2051 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 14:18:47.237   871  2051 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
09-13 14:18:47.237   871  2051 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
09-13 14:18:47.237   871  2051 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
09-13 14:18:47.237   871  2051 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
09-13 14:18:47.237   871  2051 W ActivityManager: 	at com.android.server.am.ActiveServices.startServiceInnerLocked(ActiveServices.java:433)
09-13 14:18:47.237   871  2051 W ActivityManager: 	at com.android.server.am.ActiveServices.startServiceLocked(ActiveServices.java:420)
09-13 14:18:47.237   871  2051 W ActivityManager: 	at com.android.server.am.ActivityManagerService.startService(ActivityManagerService.java:15756)
09-13 14:18:47.237   871  2051 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:928)
09-13 14:18:47.237   871  2051 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-13 14:18:47.237   871  2051 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 14:18:47.243  2003  3946 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-13 14:18:47.256   871   882 W ActivityManager: Spurious death for ProcessRecord{7d381ad 0:com.google.android.gms/u0a11}, curProc for 1739: null
,09-13 14:18:47.303  2003  3946 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-13 14:18:47.314  3949  3949 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 14:18:47.314  3949  3949 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 14:18:47.315  3949  3949 D AndroidRuntime: Shutting down VM
,09-13 14:18:47.321  2003  3946 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,09-13 14:18:47.330  2003  3946 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
09-13 14:18:47.330  2003  3946 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2003
09-13 14:18:47.330  2003  3946 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 14:18:47.330  2003  3946 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 14:18:47.338   871  2049 I ActivityManager: Start proc 3963:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService

```
