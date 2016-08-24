#### Test 80912877ffdb7be_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-24 10:04:10.568   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=115357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 10:04:11.353  4004  4004 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 10:04:11.358  4004  4004 D AndroidRuntime: CheckJNI is OFF
08-24 10:04:11.401  4004  4004 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 10:04:11.452  4004  4004 I Radio-JNI: register_android_hardware_Radio DONE
08-24 10:04:11.473  4004  4004 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 10:04:11.478   873  1904 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 10:04:11.525  2001  2014 W SearchService: Abort, client detached.
08-24 10:04:11.531  4004  4004 D AndroidRuntime: Shutting down VM
08-24 10:04:11.531  2001  2359 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7f8ee3
08-24 10:04:11.531  2001  2001 I HotwordDetector: Closing mic
08-24 10:04:11.532  2001  2370 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-24 10:04:11.555   873  1615 I ActivityManager: Start proc 4013:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-24 10:04:11.584   375  2372 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-24 10:04:11.585   375  2372 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-24 10:04:11.591   375  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-24 10:04:11.594  2001  2369 I MicroRecognitionRnrImpl: Detection finished
08-24 10:04:11.595  2001  2363 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-24 10:04:11.637  4013  4013 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-24 10:04:11.665  4013  4013 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-24 10:04:11.671  4013  4013 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6458-6461)
08-24 10:04:11.671  4013  4013 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 10:04:11.684  4013  4013 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6dce662}
08-24 10:04:11.685  4013  4013 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 10:04:11.685  4013  4013 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 10:04:11.696  4013  4013 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 10:04:11.698  4013  4013 E SysUtils: ApplicationContext is null in ApplicationStatus
08-24 10:04:11.712  4013  4013 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-24 10:04:11.722  4013  4013 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 10:04:11.722  4013  4013 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 10:04:11.722  4013  4013 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 10:04:11.722  4013  4013 I Adreno  : Build Date                       : 10/20/15
08-24 10:04:11.722  4013  4013 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 10:04:11.722  4013  4013 I Adreno  : Local Branch                     : M14
08-24 10:04:11.722  4013  4013 I Adreno  : Remote Branch                    : 
08-24 10:04:11.722  4013  4013 I Adreno  : Remote Branch                    : 
08-24 10:04:11.722  4013  4013 I Adreno  : Reconstruct Branch               : 
,08-24 10:04:11.776   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@61a253b:true
,08-24 10:04:11.803  4013  4013 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 10:04:11.814  4013  4013 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-24 10:04:11.847  4013  4053 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 10:04:11.853  4013  4039 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-24 10:04:11.895  4013  4053 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 10:04:11.948   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +411ms
,08-24 10:04:11.955  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-24 10:04:12.020  4013  4013 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4013
,08-24 10:04:12.128  4013  4013 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 10:04:12.278  4013  4055 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1681917648
,08-24 10:04:12.283  4013  4055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 10:04:12.283  4013  4055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 10:04:12.283  4013  4055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 10:04:12.283  4013  4055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 10:04:12.283  4013  4055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 10:04:12.283  4013  4055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51c6421 added. We now have 1 listener(s)
,08-24 10:04:12.287  4013  4055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-24 10:04:12.288  4013  4055 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 10:04:12.289  4013  4055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 10:04:12.289  4013  4055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-24 10:04:12.293  4013  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bc2f34 added. We now have 1 listener(s)
08-24 10:04:12.293  4013  4055 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 10:04:12.303   873  1307 D WifiService: New client listening to asynchronous messages
,08-24 10:04:12.304  4013  4055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 10:04:12.304  4013  4055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-24 10:04:12.304  4013  4055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 10:04:12.304  4013  4055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 10:04:12.304  4013  4055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 10:04:12.306  4013  4055 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 10:04:12.306  4013  4055 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-24 10:04:12.311  4013  4055 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 10:04:12.312  4013  4055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 10:04:12.312  4013  4055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 10:04:12.312  4013  4055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 10:04:12.312  4013  4055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 10:04:12.312  4013  4055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 10:04:12.312  4013  4055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 10:04:12.312  4013  4055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 10:04:12.312  4013  4055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 10:04:12.312  4013  4055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 10:04:12.312  4013  4055 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 10:04:12.314  4013  4013 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 10:04:12.315  4013  4013 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 10:04:12.315  4013  4055 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 10:04:12.338   873  1904 I ActivityManager: Killing 3160:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-24 10:04:12.375   873  1904 I ActivityManager: Killing 3384:com.google.android.gm/u0a78 (adj 15): empty #18
,08-24 10:04:12.464  4013  4013 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 10:04:13.237  4013  4061 W jxcore-log: Initializing JXcore engine
08-24 10:04:13.237  4013  4061 W jxcore-log: JXcore engine is ready
,08-24 10:04:13.273  4061  4061 W Thread-377: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8936 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-24 10:04:13.273  4061  4061 W Thread-377: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11897]" dev="sockfs" ino=11897 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-24 10:04:13.276  4061  4061 W Thread-377: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-24 10:04:13.276  4061  4061 W Thread-377: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23537]" dev="sockfs" ino=23537 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-24 10:04:13.288  4013  4061 W jxcore-log: Starting JXcore engine
,08-24 10:04:13.372  4013  4061 W jxcore-log: Platform android
08-24 10:04:13.372  4013  4061 W jxcore-log: 
,08-24 10:04:13.372  4013  4061 W jxcore-log: Process ARCH arm
08-24 10:04:13.372  4013  4061 W jxcore-log: 
,08-24 10:04:13.602  4013  4061 I jxcore-log: JXcore Cordova bridge is ready!
08-24 10:04:13.602  4013  4061 I jxcore-log: 
,08-24 10:04:13.603  4013  4061 W jxcore-log: JXcore engine is started
,08-24 10:04:13.612  4013  4055 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 10:04:13.615  4013  4013 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 10:04:18.198   873  1305 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-24 10:04:21.788  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:04:21.793  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:04:21.794  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:04:21.815  1517  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-24 10:04:21.816  1517  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 10:04:21.816  1517  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:04:21.816  1517  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:04:21.829  3699  3699 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-24 10:04:21.829  3699  3699 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-24 10:04:21.829  3699  3699 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-24 10:04:23.436  4013  4061 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 10:04:23.436  4013  4061 I jxcore-log: 
,08-24 10:04:23.439  4013  4061 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 10:04:23.439  4013  4061 I jxcore-log: 
,08-24 10:04:23.452  4013  4061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 10:04:23.452  4013  4061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 10:04:23.452  4013  4061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 10:04:23.452  4013  4061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 10:04:23.452  4013  4061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 10:04:23.452  4013  4061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 10:04:23.452  4013  4061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 10:04:23.452  4013  4061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 10:04:23.458  4013  4061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 10:04:23.460  4013  4061 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 10:04:23.460  4013  4061 I jxcore-log: 
,08-24 10:04:23.462  4013  4061 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 10:04:23.462  4013  4061 I jxcore-log: 
,08-24 10:04:24.025  4013  4061 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-24 10:04:24.025  4013  4061 I jxcore-log: Failed to execute UT.
08-24 10:04:24.025  4013  4061 I jxcore-log: 
,08-24 10:04:24.027  4013  4061 I jxcore-log: Unit Test app is loaded
08-24 10:04:24.027  4013  4061 I jxcore-log: 
,08-24 10:04:24.039  4013  4013 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-24 10:04:24.043  4013  4061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 10:04:24.043  4013  4061 I jxcore-log: 
,08-24 10:04:24.051  4013  4061 I jxcore-log: My device name is: motorola-Nexus 6
08-24 10:04:24.051  4013  4061 I jxcore-log: 
,08-24 10:04:26.563  1517  2286 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 10:04:26.564  1517  2286 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 10:04:26.564  1517  2286 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 10:04:26.564  1517  2286 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:04:26.581  3737  4076 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 10:04:26.581  3737  4076 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at jdm.a(PG:82)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at jcs.o(PG:406)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at jcn.a(PG:1379)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at jcs.i(PG:143)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at blb.a(PG:3937)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at czp.a(PG:18188)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at czp.a(PG:9081)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at czq.run(PG:1686)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 10:04:26.581  3737  4076 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at jdj.a(PG:4091)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at jdj.a(PG:1125)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at jdm.a(PG:77)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	... 12 more
08-24 10:04:26.581  3737  4076 E HttpOperation: Caused by: faj: BadAuthentication
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at fal.a(PG:38)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	at jdj.a(PG:4089)
08-24 10:04:26.581  3737  4076 E HttpOperation: 	... 14 more
,08-24 10:04:26.641  1517  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 10:04:26.641  1517  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-24 10:04:26.641  1517  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:04:26.641  1517  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:04:26.667  3737  4076 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 10:04:26.667  3737  4076 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at jdm.a(PG:82)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at jcs.o(PG:406)
,08-24 10:04:26.667  3737  4076 E HttpOperation: 	at jcn.a(PG:1379)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at jcs.i(PG:143)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at hec.a(PG:42)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at hee.a(PG:102)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at czr.a(PG:65)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at kka.a(PG:108)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at czp.a(PG:19176)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at czp.a(PG:9081)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at czq.run(PG:1686)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 10:04:26.667  3737  4076 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at jdj.a(PG:4091)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at jdj.a(PG:1125)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at jdm.a(PG:77)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	... 15 more
08-24 10:04:26.667  3737  4076 E HttpOperation: Caused by: faj: BadAuthentication
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at fal.a(PG:38)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	at jdj.a(PG:4089)
08-24 10:04:26.667  3737  4076 E HttpOperation: 	... 17 more
,08-24 10:04:26.667  3737  4076 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 10:04:26.667  3737  4076 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at hec.a(PG:42)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at hee.a(PG:102)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at czr.a(PG:65)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at kka.a(PG:108)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	... 15 more
08-24 10:04:26.667  3737  4076 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at fal.a(PG:38)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 10:04:26.667  3737  4076 E ExperimentLoader: 	... 17 more
,08-24 10:04:26.772   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131087, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-24 10:04:28.115   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 10:04:28.224  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-24 10:04:28.224  4013  4061 I jxcore-log: 
,08-24 10:04:29.132  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-24 10:04:29.132  4013  4061 I jxcore-log: 
,08-24 10:04:29.157  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-24 10:04:29.157  4013  4061 I jxcore-log: 
,08-24 10:04:29.162  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-24 10:04:29.162  4013  4061 I jxcore-log: 
,08-24 10:04:29.179  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-24 10:04:29.179  4013  4061 I jxcore-log: 
,08-24 10:04:29.183  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-24 10:04:29.183  4013  4061 I jxcore-log: 
,08-24 10:04:32.323  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-24 10:04:32.323  4013  4061 I jxcore-log: 
,08-24 10:04:32.335  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-24 10:04:32.335  4013  4061 I jxcore-log: 
,08-24 10:04:32.345  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-24 10:04:32.345  4013  4061 I jxcore-log: 
,08-24 10:04:32.505  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-24 10:04:32.505  4013  4061 I jxcore-log: 
,08-24 10:04:33.326  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-24 10:04:33.326  4013  4061 I jxcore-log: 
,08-24 10:04:33.574  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-24 10:04:33.574  4013  4061 I jxcore-log: 
,08-24 10:04:33.581  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-24 10:04:33.581  4013  4061 I jxcore-log: 
,08-24 10:04:33.772  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-24 10:04:33.772  4013  4061 I jxcore-log: 
,08-24 10:04:33.793  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-24 10:04:33.793  4013  4061 I jxcore-log: 
,08-24 10:04:33.798  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-24 10:04:33.798  4013  4061 I jxcore-log: 
,08-24 10:04:33.804  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-24 10:04:33.804  4013  4061 I jxcore-log: 
,08-24 10:04:33.819  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-24 10:04:33.819  4013  4061 I jxcore-log: 
,08-24 10:04:33.839  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-24 10:04:33.839  4013  4061 I jxcore-log: 
,08-24 10:04:33.920  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-24 10:04:33.920  4013  4061 I jxcore-log: 
,08-24 10:04:33.926  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-24 10:04:33.926  4013  4061 I jxcore-log: 
,08-24 10:04:33.952  4013  4061 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-24 10:04:33.952  4013  4061 I jxcore-log: 
,08-24 10:04:33.964  4013  4061 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-24 10:04:33.967  4013  4061 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-24 10:04:33.967  4013  4061 I jxcore-log: 
,08-24 10:04:39.885  1465  1465 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,08-24 10:04:45.356   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-24 10:04:45.370  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-24 10:04:45.382   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 10:04:45.382   873   893 I Adreno  : Build Date                       : 10/20/15
08-24 10:04:45.382   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 10:04:45.382   873   893 I Adreno  : Local Branch                     : M14
08-24 10:04:45.382   873   893 I Adreno  : Remote Branch                    : 
08-24 10:04:45.382   873   893 I Adreno  : Remote Branch                    : 
08-24 10:04:45.382   873   893 I Adreno  : Reconstruct Branch               : 
,08-24 10:04:45.427   280  1332 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (457 us)
,08-24 10:04:46.083  4013  4013 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 10:04:46.083  4013  4013 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-24 10:04:46.117  4013  4013 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a61bdc8 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2f12ae6, 16908290=android.view.AbsSavedState$1@2f12ae6}, android:focusedViewId=100}]}]
,08-24 10:04:46.117  4013  4013 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-24 10:04:46.117  4013  4013 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 10:04:46.117   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
08-24 10:04:46.117  4013  4013 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-24 10:04:46.137   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-24 10:04:46.143   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-24 10:04:46.145   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-24 10:04:46.145   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-24 10:04:46.155   873   882 I art     : Background partial concurrent mark sweep GC freed 42088(2MB) AllocSpace objects, 19(508KB) LOS objects, 33% free, 29MB/43MB, paused 2.731ms total 102.491ms
,08-24 10:04:46.369   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-24 10:04:46.374   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-24 10:04:46.380   873  1334 D SurfaceControl: Excessive delay in setPowerMode(): 236ms
,08-24 10:04:46.384   873   893 I DreamManagerService: Entering dreamland.
,08-24 10:04:46.385   873   893 I PowerManagerService: Dozing...
,08-24 10:04:46.387   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-24 10:04:46.461   375  1315 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-24 10:04:46.462   375  1315 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-24 10:04:46.467   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 10:04:46.476   873  1305 E native  : do suspend false
,08-24 10:04:46.478  1920  4083 D NfcService: Discovery configuration equal, not updating.
,08-24 10:04:46.494   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-24 10:04:46.514   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 10:04:46.519   873  1305 E native  : do suspend true
,08-24 10:04:46.599   375  1278 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-24 10:04:46.600   375  1278 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-24 10:04:46.972   873  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-24 10:04:50.642  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:04:50.653  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:04:50.656  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:04:50.708  1517  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-24 10:04:50.708  1517  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-24 10:04:50.708  1517  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 10:04:50.709  1517  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:04:50.749  3699  3699 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-24 10:04:50.750  3699  3699 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-24 10:04:50.751  3699  3699 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-24 10:04:54.391  2113  2826 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 10:04:58.214   873  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-24 10:04:59.117  3824  4088 V KeepSync: Connecting to GoogleApiClient
,08-24 10:04:59.117   873  2183 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 10:04:59.157  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:04:59.158  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:04:59.191  1517  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-24 10:04:59.191  1517  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-24 10:04:59.191  1517  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 10:04:59.191  1517  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:04:59.226  1733  4089 V BaseAuthAsyncOperation: access token request failed
,08-24 10:04:59.227  3824  4088 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 10:04:59.293  1517  2270 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-24 10:04:59.293  1517  2270 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-24 10:04:59.293  1517  2270 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:04:59.293  1517  2270 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:04:59.322  3824  4088 E KeepSync: IOException
08-24 10:04:59.322  3824  4088 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 10:04:59.322  3824  4088 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 10:04:59.322  3824  4088 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 10:04:59.322  3824  4088 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 10:04:59.322  3824  4088 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 10:04:59.322  3824  4088 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 10:04:59.322  3824  4088 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 10:04:59.322  3824  4088 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 10:04:59.322  3824  4088 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 10:04:59.322  3824  4088 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 10:04:59.322  3824  4088 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 10:04:59.322  3824  4088 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 10:04:59.322  3824  4088 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 10:04:59.322  3824  4088 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 10:04:59.322  3824  4088 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 10:04:59.322  3824  4088 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 10:04:59.322  3824  4088 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 10:04:59.322  3824  4088 E KeepSync: 	... 10 more
08-24 10:04:59.322  3824  4088 W KeepSync: Sync result 2
,08-24 10:04:59.328   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 163695, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-24 10:05:03.155   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 10:05:16.820  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:05:17.065  1517  4091 I VacuumService: Vacuum at: now=1472025917065 tag=VacuumService
,08-24 10:05:17.315  1517  4092 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-24 10:05:17.318  1517  4092 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-24 10:05:17.347  1517  4092 W Uploader:  no longer exists, so no auth token.
,08-24 10:05:17.903  1517  4096 I SQLiteConnectionPool: The connection pool for /data/user/0/com.google.android.gms/databases/phenotype.db has been closed but there are still 1 connections in use.  They will be closed as they are released back to the pool.
,08-24 10:05:17.904  1517  4096 E ClearcutLoggerIntentService: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
08-24 10:05:17.904  1517  4096 E ClearcutLoggerIntentService: java.lang.IllegalStateException: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
08-24 10:05:17.904  1517  4096 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
08-24 10:05:17.904  1517  4096 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:520)
08-24 10:05:17.904  1517  4096 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:143)
08-24 10:05:17.904  1517  4096 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-24 10:05:17.904  1517  4096 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-24 10:05:17.904  1517  4096 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-24 10:05:17.904  1517  4096 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 10:05:17.904  1517  4096 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 10:05:17.904  1517  4096 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,08-24 10:05:21.213  1517  4092 E Uploader: Failed to get server token: Status{statusCode=TIMEOUT, resolution=null}
,08-24 10:05:21.361  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:05:21.364  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:05:21.402  1517  4092 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-24 10:05:21.402  1517  4092 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-24 10:05:21.403  1517  4092 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:05:21.403  1517  4092 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:05:21.424  1517  4092 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 10:05:21.424  1517  4092 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 10:05:21.424  1517  4092 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 10:05:21.424  1517  4092 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 10:05:21.424  1517  4092 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-24 10:05:21.424  1517  4092 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-24 10:05:21.424  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-24 10:05:21.424  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-24 10:05:21.424  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-24 10:05:21.424  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-24 10:05:21.424  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-24 10:05:21.424  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-24 10:05:21.424  1517  4092 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-24 10:05:21.822   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=186611, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 10:05:21.964  1517  1524 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/user/0/com.google.android.gms/databases/phenotype.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-24 10:05:22.285  1517  4092 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-24 10:05:22.286  1517  4092 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-24 10:05:22.286  1517  4092 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:05:22.286  1517  4092 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:05:22.312  1517  4092 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 10:05:22.312  1517  4092 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 10:05:22.312  1517  4092 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 10:05:22.312  1517  4092 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 10:05:22.312  1517  4092 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-24 10:05:22.312  1517  4092 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-24 10:05:22.312  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-24 10:05:22.312  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-24 10:05:22.312  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-24 10:05:22.312  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-24 10:05:22.312  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-24 10:05:22.312  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-24 10:05:22.312  1517  4092 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-24 10:05:22.797  1517  4092 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-24 10:05:22.797  1517  4092 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-24 10:05:22.797  1517  4092 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 10:05:22.797  1517  4092 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:05:22.820  1517  4092 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 10:05:22.820  1517  4092 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 10:05:22.820  1517  4092 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 10:05:22.820  1517  4092 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 10:05:22.820  1517  4092 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-24 10:05:22.820  1517  4092 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-24 10:05:22.820  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-24 10:05:22.820  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-24 10:05:22.820  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-24 10:05:22.820  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-24 10:05:22.820  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-24 10:05:22.820  1517  4092 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-24 10:05:22.820  1517  4092 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-24 10:05:26.106  1517  2177 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 10:05:29.421  3968  4104 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 10:05:29.454  3968  4105 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 10:05:29.468  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:05:29.470  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:05:29.503  1517  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 10:05:29.503  1517  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-24 10:05:29.503  1517  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:05:29.503  1517  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:05:29.532  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:05:29.534  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:05:29.557  1517  2286 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 10:05:29.557  1517  2286 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 10:05:29.558  1517  2286 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:05:29.558  1517  2286 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:05:29.579  3968  4105 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 10:05:29.580  3968  4104 E BooksSync: Soft error
08-24 10:05:29.580  3968  4104 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 10:05:29.580  3968  4104 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 10:05:29.580  3968  4104 E BooksSync: Sync error
08-24 10:05:29.580  3968  4104 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 10:05:29.580  3968  4104 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 10:05:29.582  3968  4104 I BooksSync: Finished books sync
,08-24 10:05:29.587   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 164884, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 10:05:45.379  1865  1965 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-24 10:05:45.379  1865  1965 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-24 10:05:45.417  1517  1517 I ConfigService: onCreate
,08-24 10:05:50.488  1517  1517 I ConfigService: onDestroy
,08-24 10:05:57.951   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=222740, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 10:06:32.958  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:06:32.959  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:06:32.998  1517  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 10:06:32.998  1517  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 10:06:32.998  1517  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 10:06:32.998  1517  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:06:33.014  3737  4110 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 10:06:33.014  3737  4110 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at jdm.a(PG:82)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at jcs.o(PG:406)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at jcn.a(PG:1379)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at jcs.i(PG:143)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at blb.a(PG:3937)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at czp.a(PG:18188)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at czp.a(PG:9081)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at czq.run(PG:1686)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 10:06:33.014  3737  4110 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at jdj.a(PG:4091)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at jdj.a(PG:1125)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at jdm.a(PG:77)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	... 12 more
08-24 10:06:33.014  3737  4110 E HttpOperation: Caused by: faj: BadAuthentication
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at fal.a(PG:38)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	at jdj.a(PG:4089)
08-24 10:06:33.014  3737  4110 E HttpOperation: 	... 14 more
,08-24 10:06:33.066  1517  2270 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 10:06:33.066  1517  2270 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 10:06:33.066  1517  2270 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 10:06:33.066  1517  2270 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:06:33.099  3737  4110 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 10:06:33.099  3737  4110 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at jdm.a(PG:82)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at jcs.o(PG:406)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at jcn.a(PG:1379)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at jcs.i(PG:143)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at hec.a(PG:42)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at hee.a(PG:102)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at czr.a(PG:65)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at kka.a(PG:108)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at czp.a(PG:19176)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at czp.a(PG:9081)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at czq.run(PG:1686)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 10:06:33.099  3737  4110 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at jdj.a(PG:4091)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at jdj.a(PG:1125)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at jdm.a(PG:77)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	... 15 more
08-24 10:06:33.099  3737  4110 E HttpOperation: Caused by: faj: BadAuthentication
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at fal.a(PG:38)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	at jdj.a(PG:4089)
08-24 10:06:33.099  3737  4110 E HttpOperation: 	... 17 more
,08-24 10:06:33.099  3737  4110 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 10:06:33.099  3737  4110 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at hec.a(PG:42)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at hee.a(PG:102)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at czr.a(PG:65)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at kka.a(PG:108)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	... 15 more
08-24 10:06:33.099  3737  4110 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at fal.a(PG:38)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 10:06:33.099  3737  4110 E ExperimentLoader: 	... 17 more
,08-24 10:06:33.254   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 257302, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-24 10:06:43.715   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 10:07:09.177  3824  4119 V KeepSync: Connecting to GoogleApiClient
08-24 10:07:09.177   873  1904 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 10:07:09.222  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:07:09.224  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:07:09.254  1517  2270 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-24 10:07:09.254  1517  2270 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-24 10:07:09.254  1517  2270 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:07:09.254  1517  2270 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:07:09.277  1733  4120 V BaseAuthAsyncOperation: access token request failed
,08-24 10:07:09.278  3824  4119 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 10:07:09.351  1517  4113 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-24 10:07:09.352  1517  4113 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 10:07:09.352  1517  4113 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:07:09.352  1517  4113 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:07:09.375  3824  4119 E KeepSync: IOException
08-24 10:07:09.375  3824  4119 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 10:07:09.375  3824  4119 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 10:07:09.375  3824  4119 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 10:07:09.375  3824  4119 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 10:07:09.375  3824  4119 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 10:07:09.375  3824  4119 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 10:07:09.375  3824  4119 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 10:07:09.375  3824  4119 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 10:07:09.375  3824  4119 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 10:07:09.375  3824  4119 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 10:07:09.375  3824  4119 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 10:07:09.375  3824  4119 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 10:07:09.375  3824  4119 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 10:07:09.375  3824  4119 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 10:07:09.375  3824  4119 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 10:07:09.375  3824  4119 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 10:07:09.375  3824  4119 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 10:07:09.375  3824  4119 E KeepSync: 	... 10 more
,08-24 10:07:09.375  3824  4119 W KeepSync: Sync result 2
,08-24 10:07:09.391   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 293789, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-24 10:07:18.835   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=303624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 10:07:40.275   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=325064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 10:07:41.600  3968  4122 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 10:07:41.625  3968  4123 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 10:07:41.638  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:07:41.641  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:07:41.668  1517  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 10:07:41.668  1517  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 10:07:41.668  1517  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:07:41.668  1517  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:07:41.706  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:07:41.709  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:07:41.743  1517  2286 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 10:07:41.743  1517  2286 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 10:07:41.743  1517  2286 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:07:41.743  1517  2286 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:07:41.767  3968  4123 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 10:07:41.768  3968  4122 E BooksSync: Soft error
08-24 10:07:41.768  3968  4122 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 10:07:41.768  3968  4122 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-24 10:07:41.768  3968  4122 E BooksSync: Sync error
08-24 10:07:41.768  3968  4122 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 10:07:41.768  3968  4122 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 10:07:41.768  3968  4122 I BooksSync: Finished books sync
,08-24 10:07:41.781   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 326310, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 10:08:00.322  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:08:00.330  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:08:00.335  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:08:00.390  1517  4113 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-24 10:08:00.391  1517  4113 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-24 10:08:00.391  1517  4113 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:08:00.391  1517  4113 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:08:00.430  1517  4113 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 10:08:00.430  1517  4113 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 10:08:00.430  1517  4113 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 10:08:00.430  1517  4113 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-24 10:08:00.430  1517  4113 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-24 10:08:00.430  1517  4113 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-24 10:08:00.430  1517  4113 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-24 10:08:00.440  3699  3728 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 10:08:00.440  3699  3728 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-24 10:08:00.440  3699  3728 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-24 10:08:00.440  3699  3728 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-24 10:08:00.440  3699  3728 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-24 10:08:00.440  3699  3728 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-24 10:08:00.440  3699  3728 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-24 10:08:35.794   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=380584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 10:08:44.168   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=388957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 10:09:19.262   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=424051, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 10:09:28.195   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=432984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 10:10:03.315   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=468104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 10:10:27.995   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=492784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 10:10:45.052  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:10:45.056  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:10:45.127  1517  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 10:10:45.127  1517  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 10:10:45.127  1517  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:10:45.127  1517  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:10:45.168  3737  4137 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 10:10:45.168  3737  4137 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at jdm.a(PG:82)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at jcs.o(PG:406)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at jcn.a(PG:1379)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at jcs.i(PG:143)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at blb.a(PG:3937)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at czp.a(PG:18188)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at czp.a(PG:9081)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at czq.run(PG:1686)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 10:10:45.168  3737  4137 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at jdj.a(PG:4091)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at jdj.a(PG:1125)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at jdm.a(PG:77)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	... 12 more
08-24 10:10:45.168  3737  4137 E HttpOperation: Caused by: faj: BadAuthentication
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at fal.a(PG:38)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	at jdj.a(PG:4089)
08-24 10:10:45.168  3737  4137 E HttpOperation: 	... 14 more
,08-24 10:10:45.252  1517  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 10:10:45.252  1517  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 10:10:45.252  1517  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:10:45.252  1517  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:10:45.281  3737  4137 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 10:10:45.281  3737  4137 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at jdm.a(PG:82)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at jcs.o(PG:406)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at jcn.a(PG:1379)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at jcs.i(PG:143)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at hec.a(PG:42)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at hee.a(PG:102)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at czr.a(PG:65)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at kka.a(PG:108)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at czp.a(PG:19176)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at czp.a(PG:9081)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at czq.run(PG:1686)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 10:10:45.281  3737  4137 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at jdj.a(PG:4091)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at jdj.a(PG:1125)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at jdm.a(PG:77)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	... 15 more
08-24 10:10:45.281  3737  4137 E HttpOperation: Caused by: faj: BadAuthentication
08-24 10:10:45.281  3737  4137 E HttpOperation: 	at fal.a(PG:38)
08-24 10:1,0:45.281  3737  4137 E HttpOperation: 	at jdj.a(PG:4089)
08-24 10:10:45.281  3737  4137 E HttpOperation: 	... 17 more
08-24 10:10:45.282  3737  4137 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 10:10:45.282  3737  4137 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at hec.a(PG:42)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at hee.a(PG:102)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at czr.a(PG:65)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at kka.a(PG:108)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	... 15 more
08-24 10:10:45.282  3737  4137 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at fal.a(PG:38)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 10:10:45.282  3737  4137 E ExperimentLoader: 	... 17 more
,08-24 10:10:45.467   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 509524, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-24 10:11:03.048   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=527837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 10:11:28.868  3824  4141 V KeepSync: Connecting to GoogleApiClient
08-24 10:11:28.868   873  1903 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 10:11:28.926  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:11:28.929  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:11:28.963  1517  4113 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-24 10:11:28.963  1517  4113 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-24 10:11:28.963  1517  4113 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 10:11:28.963  1517  4113 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:11:28.984  1733  4142 V BaseAuthAsyncOperation: access token request failed
,08-24 10:11:28.985  3824  4141 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 10:11:29.033  1517  2286 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-24 10:11:29.033  1517  2286 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 10:11:29.033  1517  2286 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:11:29.033  1517  2286 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:11:29.045  3824  4141 E KeepSync: IOException
08-24 10:11:29.045  3824  4141 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 10:11:29.045  3824  4141 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 10:11:29.045  3824  4141 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 10:11:29.045  3824  4141 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 10:11:29.045  3824  4141 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 10:11:29.045  3824  4141 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 10:11:29.045  3824  4141 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 10:11:29.045  3824  4141 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 10:11:29.045  3824  4141 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 10:11:29.045  3824  4141 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 10:11:29.045  3824  4141 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 10:11:29.045  3824  4141 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 10:11:29.045  3824  4141 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 10:11:29.045  3824  4141 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 10:11:29.045  3824  4141 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 10:11:29.045  3824  4141 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 10:11:29.045  3824  4141 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 10:11:29.045  3824  4141 E KeepSync: 	... 10 more
,08-24 10:11:29.046  3824  4141 W KeepSync: Sync result 2
,08-24 10:11:29.050   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 553525, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-24 10:12:05.772  3968  4144 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 10:12:05.794  3968  4145 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 10:12:05.806  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:12:05.809  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:12:05.837  1517  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-24 10:12:05.837  1517  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-24 10:12:05.837  1517  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:12:05.837  1517  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:12:05.864  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:12:05.867  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:12:05.890  1517  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-24 10:12:05.890  1517  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-24 10:12:05.890  1517  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:12:05.890  1517  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:12:05.901   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=590690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 10:12:05.927  3968  4145 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 10:12:05.928  3968  4144 E BooksSync: Soft error
08-24 10:12:05.928  3968  4144 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 10:12:05.928  3968  4144 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 10:12:05.928  3968  4144 E BooksSync: Sync error
08-24 10:12:05.928  3968  4144 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 10:12:05.928  3968  4144 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 10:12:05.928  3968  4144 I BooksSync: Finished books sync
,08-24 10:12:05.935   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 590434, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 10:12:40.969   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=625758, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 10:13:05.755   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=650544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 10:13:40.808   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=685597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 10:17:45.435   873  2182 I ActivityManager: Start proc 4164:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,08-24 10:17:45.510  4164  4164 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,08-24 10:17:45.537  4164  4164 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-24 10:17:45.537  4164  4164 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 10:17:45.537  4164  4164 I GAv4    :   adb logcat -s GAv4
,08-24 10:17:45.549  4164  4164 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-24 10:17:45.553  4164  4164 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-24 10:17:45.568  4164  4179 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-24 10:17:45.657   873  2028 I ActivityManager: Killing 2868:com.google.android.talk/u0a61 (adj 15): empty #17
,08-24 10:18:46.255   873  1903 I ActivityManager: Start proc 4185:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-24 10:18:46.294  4185  4185 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-24 10:18:46.308  1733  4197 I EventLogService: Opted in for usage reporting
,08-24 10:18:46.311  1733  4197 I EventLogService: Aggregate from 1472024926008 (log), 1472024926008 (data)
,08-24 10:18:46.329  1733  1733 I GCM     : Message from null null
,08-24 10:18:46.329  1733  1733 E GCM     : Dropping message from null
,08-24 10:18:46.412  4185  4198 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-24 10:18:46.521  4185  4198 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-24 10:18:46.589  4185  4198 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-24 10:18:46.643  4185  4185 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-24 10:18:46.663  1733  4197 W EventLogAggregator: Unknown tag: snet_gcore
,08-24 10:18:46.663  1733  4197 W EventLogAggregator: Unknown tag: snet_launch_service
,08-24 10:18:46.816  1733  4197 I ServiceDumpSys: dumping service [account]
,08-24 10:18:46.881  4185  4185 W InstanceID/Rpc: Found 10011
,08-24 10:18:46.966   873  1380 I ActivityManager: Start proc 4257:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,08-24 10:18:47.044  4257  4257 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-24 10:18:47.084  4257  4257 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-24 10:18:47.104  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:18:47.105  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:18:47.133  4257  4286 V GoogleAuthProtoRequest: [377] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 10:18:47.176  4218  4218 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-2023640426.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-2023640426.dex
,08-24 10:18:47.189  1517  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-24 10:18:47.189  1517  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-24 10:18:47.189  1517  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:18:47.189  1517  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:18:47.226  4257  4286 W ExperimentUpdateService: [377] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 10:18:47.226  4257  4286 W ExperimentUpdateService: [377] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 10:18:47.226  4257  4286 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 10:18:47.226  4257  4286 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 10:18:47.226  4257  4286 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 10:18:47.226  4257  4286 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 10:18:47.226  4257  4286 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 10:18:47.226  4257  4286 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 10:18:47.226  4257  4286 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 10:18:47.226  4257  4286 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 10:18:47.226  4257  4286 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 10:18:47.226  4257  4286 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-24 10:18:47.230   873   883 I ActivityManager: Killing 3750:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-24 10:18:47.321  4218  4218 I dex2oat : dex2oat took 145.902ms (threads: 4) arena alloc=208KB java alloc=29KB native alloc=1515KB free=1556KB
,08-24 10:18:47.846   873  1979 I ActivityManager: Killing 3604:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-24 10:18:51.275   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=996064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 10:19:08.221   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1013010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 10:19:18.093  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:19:18.096  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:19:18.116  4257  4299 V GoogleAuthProtoRequest: [378] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 10:19:18.169  1517  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-24 10:19:18.169  1517  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-24 10:19:18.170  1517  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 10:19:18.170  1517  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:19:18.198  4257  4299 W ExperimentUpdateService: [378] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 10:19:18.199  4257  4299 W ExperimentUpdateService: [378] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 10:19:18.199  4257  4299 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 10:19:18.199  4257  4299 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 10:19:18.199  4257  4299 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 10:19:18.199  4257  4299 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 10:19:18.199  4257  4299 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 10:19:18.199  4257  4299 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 10:19:18.199  4257  4299 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 10:19:18.199  4257  4299 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 10:19:18.199  4257  4299 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 10:19:18.199  4257  4299 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-24 10:20:18.377  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:20:18.380  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:20:18.402  4257  4306 V GoogleAuthProtoRequest: [379] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 10:20:18.448  1517  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-24 10:20:18.448  1517  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-24 10:20:18.448  1517  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:20:18.448  1517  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:20:18.471  4257  4306 W ExperimentUpdateService: [379] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-24 10:20:18.472  4257  4306 W ExperimentUpdateService: [379] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 10:20:18.472  4257  4306 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 10:20:18.472  4257  4306 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 10:20:18.472  4257  4306 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 10:20:18.472  4257  4306 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 10:20:18.472  4257  4306 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 10:20:18.472  4257  4306 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 10:20:18.472  4257  4306 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 10:20:18.472  4257  4306 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 10:20:18.472  4257  4306 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 10:20:18.472  4257  4306 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-24 10:21:18.212  1517  2177 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 10:22:33.946   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,08-24 10:22:48.538  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:22:48.540  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:22:48.556  4257  4315 V GoogleAuthProtoRequest: [380] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 10:22:48.583  1517  2270 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-24 10:22:48.583  1517  2270 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-24 10:22:48.583  1517  2270 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:22:48.584  1517  2270 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:22:48.600  4257  4315 W ExperimentUpdateService: [380] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 10:22:48.601  4257  4315 W ExperimentUpdateService: [380] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 10:22:48.601  4257  4315 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 10:22:48.601  4257  4315 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 10:22:48.601  4257  4315 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 10:22:48.601  4257  4315 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 10:22:48.601  4257  4315 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 10:22:48.601  4257  4315 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 10:22:48.601  4257  4315 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 10:22:48.601  4257  4315 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 10:22:48.601  4257  4315 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 10:22:48.601  4257  4315 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-24 10:22:53.061   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1237850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 10:23:08.648   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1253437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 10:23:52.155   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1296944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 10:24:02.995   873  1882 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1307784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 10:26:48.815  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:26:48.816  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 10:26:48.836  4257  4330 V GoogleAuthProtoRequest: [381] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 10:26:48.893  1517  2270 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-24 10:26:48.893  1517  2270 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-24 10:26:48.893  1517  2270 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 10:26:48.893  1517  2270 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 10:26:48.910  4257  4330 W ExperimentUpdateService: [381] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 10:26:48.910  4257  4330 W ExperimentUpdateService: [381] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 10:26:48.910  4257  4330 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 10:26:48.910  4257  4330 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 10:26:48.910  4257  4330 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 10:26:48.910  4257  4330 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 10:26:48.910  4257  4330 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 10:26:48.910  4257  4330 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 10:26:48.910  4257  4330 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 10:26:48.910  4257  4330 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 10:26:48.910  4257  4330 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 10:26:48.910  4257  4330 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,TIME-OUT KILL (timeout was 1400000ms),08-24 10:27:42.402  4333  4333 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 10:27:42.407  4333  4333 D AndroidRuntime: CheckJNI is OFF
08-24 10:27:42.442  4333  4333 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 10:27:42.483  4333  4333 I Radio-JNI: register_android_hardware_Radio DONE
08-24 10:27:42.504  4333  4333 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-24 10:27:42.513   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-24 10:27:42.514   873   886 I ActivityManager: Killing 4013:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-24 10:27:42.625   873  2183 D GraphicsStats: Buffer count: 2
08-24 10:27:42.625   873  2182 I WindowState: WIN DEATH: Window{c5ad32b u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 10:27:42.626   873  1307 D WifiService: Client connection lost with reason: 4
08-24 10:27:42.653   873   896 W PackageSettings: Skipping PackageSetting{3d76039 com.example.hello/10273} due to missing metadata
08-24 10:27:42.676   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-24 10:27:42.676   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-24 10:27:42.677   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-24 10:27:42.677   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-24 10:27:42.677   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 10:27:42.677   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 10:27:42.677   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 10:27:42.677   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 10:27:42.677   873   886 I ActivityManager:   Force finishing activity ActivityRecord{c4e4010 u0 com.test.thalitest/.MainActivity t2}
08-24 10:27:42.678   873   896 I art     : Starting a blocking GC Explicit
08-24 10:27:42.688   873  1979 W ActivityManager: Spurious death for ProcessRecord{9f62598 0:com.test.thalitest/u0a0}, curProc for 4013: null
08-24 10:27:42.719   873   896 I art     : Explicit concurrent mark sweep GC freed 23305(1622KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 710us total 41.189ms
08-24 10:27:42.740   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-24 10:27:42.742  4333  4333 I art     : System.exit called, status: 0
08-24 10:27:42.742  4333  4333 I AndroidRuntime: VM exiting with result code 0.
08-24 10:27:42.747   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-24 10:27:42.756   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-24 10:27:42.761  2640  2640 D BluetoothMapAppObserver: onReceive
08-24 10:27:42.761  2640  2640 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-24 10:27:42.762  2113  2296 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-24 10:27:42.765   873  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-24 10:27:42.775  3856  3856 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-24 10:27:42.776  1865  1865 I Keyboard.Facilitator: resetDictionaries() : en_US
08-24 10:27:42.801  1932  1932 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-24 10:27:42.821  1865  4346 I Keyboard.Facilitator.DecoderInitializer: run()
08-24 10:27:42.828  3682  4348 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-24 10:27:42.835  1517  1517 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-24 10:27:42.835  1517  1517 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
08-24 10:27:42.861   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-24 10:27:42.862  1865  4346 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-24 10:27:42.862  1865  4346 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-24 10:27:42.862  1865  4346 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-24 10:27:42.862  1865  4346 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-24 10:27:42.872  1865  4346 I Decoder : createOrResetDecoder
08-24 10:27:42.874  1948  2031 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-24 10:27:42.877  3682  3696 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj4C50AF97E) - 
08-24 10:27:42.887   873  2027 I ActivityManager: Start proc 4352:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-24 10:27:42.888  1948  2031 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-24 10:27:42.888  1948  2031 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1948
08-24 10:27:42.888  1948  2031 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 10:27:42.888  1948  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 10:27:42.888  1948  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 10:27:42.888  1948  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 10:27:42.888  1948  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 10:27:42.888  1948  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 10:27:42.888  1948  2031 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-24 10:27:42.888  1948  2031 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-24 10:27:42.888  1948  2031 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 10:27:42.888  1948  2031 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 10:27:42.888  1948  2031 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 10:27:42.888  1948  2031 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 10:27:42.891   873  1697 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 10:27:42.892   873  4357 E DropBoxManagerService: Can't write: system_app_crash
08-24 10:27:42.892   873  4357 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
08-24 10:27:42.892   873  4357 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 10:27:42.892   873  4357 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 10:27:42.892   873  4357 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 10:27:42.892   873  4357 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 10:27:42.892   873  4357 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 10:27:42.892   873  4357 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 10:27:42.892   873  4357 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 10:27:42.892   873  4357 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 10:27:42.892   873  4357 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 10:27:42.892   873  4357 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 10:27:42.892   873  4357 E DropBoxManagerService: 	... 5 more
08-24 10:27:42.895  1948  2031 I Process : Sending signal. PID: 1948 SIG: 9
08-24 10:27:42.906  1733  4351 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-24 10:27:42.906  1733  4351 D AccountUtils: Clearing selected account for com.test.thalitest
08-24 10:27:42.913  1517  1517 I ConfigService: onCreate
08-24 10:27:42.918   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-24 10:27:42.918  3682  4348 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-24 10:27:42.918   873   885 E PackageManager: Failed to write settings, restoring backup
08-24 10:27:42.918   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-24 10:27:42.918   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-24 10:27:42.918   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-24 10:27:42.918   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-24 10:27:42.918   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-24 10:27:42.918   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 10:27:42.918   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 10:27:42.918   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 10:27:42.920   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-24 10:27:42.920   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 10:27:42.920   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 10:27:42.920   873   886 E DropBoxManagerService: 	... 13 more
08-24 10:27:42.920  3682  4348 I Process : Sending signal. PID: 3682 SIG: 9
08-24 10:27:42.940  1733  4351 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
08-24 10:27:42.982   278   278 E lowmemorykiller: Error writing /proc/3682/oom_score_adj; errno=22
08-24 10:27:43.018   278   278 E lowmemorykiller: Error writing /proc/3682/oom_score_adj; errno=22
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 10:27:43.025  1733  4351 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-24 10:27:43.025  1733  4351 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 10:27:43.026  1733  4351 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-24 10:27:43.029  1517  4367 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-24 10:27:43.029  1517  4367 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-24 10:27:43.035  1517  4367 W SQLiteOpenHelper: Opened config.db in read-only mode
08-24 10:27:43.068  1865  4346 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-24 10:27:43.070   873  1296 W InputDispatcher: channel 'd5be26a com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-24 10:27:43.070   873  1296 E InputDispatcher: channel 'd5be26a com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
08-24 10:27:43.074   873  1903 I WindowState: WIN DEATH: Window{d5be26a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-24 10:27:43.074   873  1903 W InputDispatcher: Attempted to unregister already unregistered input channel 'd5be26a com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
08-24 10:27:43.074   873  2027 D GraphicsStats: Buffer count: 1
08-24 10:27:43.096   873  1380 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1948) has died
08-24 10:27:43.098   873  1380 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-24 10:27:43.138  1733  4372 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-24 10:27:43.141  1733  1733 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-24 10:27:43.141  1733  1733 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-24 10:27:43.152  1733  4372 E DriveAsyncService: disk I/O error (code 3850)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 10:27:43.152  1733  4372 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
08-24 10:27:43.160  1733  1733 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-24 10:27:43.160  1733  1733 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 10:27:43.174  1733  4373 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-24 10:27:43.175  1733  4373 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 10:27:43.178  1733  1733 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-24 10:27:43.179  1733  2461 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml.bak
08-24 10:27:43.182   873  2027 I BroadcastQueue: Delay finish: com.google.android.googlequicksearchbox/com.google.android.apps.gsa.googlequicksearchbox.GelStubAppWatcher
08-24 10:27:43.183   278   278 E lowmemorykiller: Error writing /proc/3682/oom_score_adj; errno=22
08-24 10:27:43.184   278   278 E lowmemorykiller: Error writing /proc/3682/oom_score_adj; errno=22
08-24 10:27:43.197  1733  1733 I ConfigFetchService: service connected
08-24 10:27:43.187  1733  4377 I GMPM-SVC: App measurement is starting up
08-24 10:27:43.200  1865  4346 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-24 10:27:43.202  1865  4346 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-24 10:27:43.202  1865  4346 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-24 10:27:43.203  1865  4346 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-24 10:27:43.203  1865  4346 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-24 10:27:43.204  1865  4346 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-24 10:27:43.204  1865  4346 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-24 10:27:43.205  1865  4346 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-24 10:27:43.205  1865  4346 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-24 10:27:43.205  1865  4346 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-24 10:27:43.205  1865  4346 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-24 10:27:43.205  1865  4346 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-24 10:27:43.205  1865  4346 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-24 10:27:43.207  2001  4376 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-24 10:27:43.210  1733  4373 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-24 10:27:43.210  1733  4373 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-24 10:27:43.210  1733  4373 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
08-24 10:27:43.211  1733  4373 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
08-24 10:27:43.212  1733  4373 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
08-24 10:27:43.212  1733  4373 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-24 10:27:43.212  1733  4373 E AndroidRuntime: Process: com.google.android.gms, PID: 1733
08-24 10:27:43.212  1733  4373 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-24 10:27:43.212  1733  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 10:27:43.212  1733  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 10:27:43.212  1733  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 10:27:43.212  1733  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 10:27:43.212  1733  4373 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 10:27:43.212  1733  4373 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
08-24 10:27:43.212  1733  4373 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-24 10:27:43.212  1733  4373 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 10:27:43.212  1733  4373 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 10:27:43.212  1733  4373 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 10:27:43.212  1733  4373 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 10:27:43.215   873  4383 E DropBoxManagerService: Can't write: system_app_crash
08-24 10:27:43.215   873  4383 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-24 10:27:43.215   873  4383 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 10:27:43.215   873  4383 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 10:27:43.215   873  4383 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 10:27:43.215   873  4383 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 10:27:43.215   873  4383 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 10:27:43.215   873  4383 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 10:27:43.215   873  4383 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 10:27:43.215   873  4383 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 10:27:43.215   873  4383 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 10:27:43.215   873  4383 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 10:27:43.215   873  4383 E DropBoxManagerService: 	... 5 more
08-24 10:27:43.235  1733  4380 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-24 10:27:43.236  1733  4380 I Process : Sending signal. PID: 1733 SIG: 9

```
