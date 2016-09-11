#### Test 84265062bba4ad4_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
09-11 11:55:49.938   872  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-11 11:55:50.006   872  2066 D NetlinkSocketObserver: NeighborEvent{elapsedMs=113543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
09-11 11:55:50.576  3780  3780 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-11 11:55:50.581  3780  3780 D AndroidRuntime: CheckJNI is OFF
09-11 11:55:50.623  3780  3780 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-11 11:55:50.672  3780  3780 I Radio-JNI: register_android_hardware_Radio DONE
09-11 11:55:50.693  3780  3780 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-11 11:55:50.697   872  2207 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-11 11:55:50.718  2031  2400 W SearchService: Abort, client detached.
09-11 11:55:50.735  3780  3780 D AndroidRuntime: Shutting down VM
09-11 11:55:50.738  2031  2354 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@235bca7
09-11 11:55:50.738  2031  2364 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-11 11:55:50.738  2031  2031 I HotwordDetector: Closing mic
09-11 11:55:50.752   872  2204 I ActivityManager: Start proc 3790:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-11 11:55:50.800   375  2366 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-11 11:55:50.801   375  2366 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-11 11:55:50.806   375  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-11 11:55:50.809  2031  2361 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-11 11:55:50.809  2031  2363 I MicroRecognitionRnrImpl: Detection finished
09-11 11:55:50.831  3790  3790 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-11 11:55:50.853  3790  3790 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-11 11:55:50.860  3790  3790 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4395-4397)
09-11 11:55:50.860  3790  3790 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-11 11:55:50.872  3790  3790 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {58d3c78}
09-11 11:55:50.872  3790  3790 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-11 11:55:50.872  3790  3790 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-11 11:55:50.878  3790  3790 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-11 11:55:50.880  3790  3790 E SysUtils: ApplicationContext is null in ApplicationStatus
09-11 11:55:50.893  3790  3790 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-11 11:55:50.903  3790  3790 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-11 11:55:50.903  3790  3790 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-11 11:55:50.903  3790  3790 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-11 11:55:50.903  3790  3790 I Adreno  : Build Date                       : 10/20/15
09-11 11:55:50.903  3790  3790 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-11 11:55:50.903  3790  3790 I Adreno  : Local Branch                     : M14
09-11 11:55:50.903  3790  3790 I Adreno  : Remote Branch                    : 
09-11 11:55:50.903  3790  3790 I Adreno  : Remote Branch                    : 
09-11 11:55:50.903  3790  3790 I Adreno  : Reconstruct Branch               : 
09-11 11:55:50.958   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@63923ad:true
,09-11 11:55:50.986  3790  3790 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-11 11:55:50.998  3790  3790 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-11 11:55:51.074  3790  3828 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-11 11:55:51.083  3790  3815 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-11 11:55:51.109  3790  3828 I OpenGLRenderer: Initialized EGL, version 1.4,
,09-11 11:55:51.205   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +465ms
,09-11 11:55:51.217  1875  1875 I Keyboard.Facilitator: onFinishInput()
,09-11 11:55:51.309  3790  3790 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3790
,09-11 11:55:51.402  3790  3790 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-11 11:55:51.530   872   882 I ActivityManager: Killing 3217:com.google.android.gm/u0a78 (adj 15): empty #17
,09-11 11:55:51.571  3790  3832 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1681917648
,09-11 11:55:51.573   872   882 I ActivityManager: Killing 3099:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-11 11:55:51.576  3790  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-11 11:55:51.576  3790  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-11 11:55:51.576  3790  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-11 11:55:51.576  3790  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-11 11:55:51.576  3790  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-11 11:55:51.576  3790  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bdcb6f added. We now have 1 listener(s)
,09-11 11:55:51.579  3790  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-11 11:55:51.580  3790  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-11 11:55:51.580  3790  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:55:51.581  3790  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-11 11:55:51.584  3790  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dcd815a added. We now have 1 listener(s)
,09-11 11:55:51.584  3790  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:55:51.588   872  1305 D WifiService: New client listening to asynchronous messages
,09-11 11:55:51.589  3790  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-11 11:55:51.589  3790  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-11 11:55:51.589  3790  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-11 11:55:51.589  3790  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-11 11:55:51.589  3790  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-11 11:55:51.623  3790  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:55:51.623  3790  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-11 11:55:51.630  3790  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-11 11:55:51.630  3790  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:55:51.630  3790  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:55:51.630  3790  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:55:51.630  3790  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:55:51.630  3790  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:55:51.630  3790  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:55:51.630  3790  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:55:51.630  3790  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:55:51.630  3790  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-11 11:55:51.631  3790  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:55:51.631  3790  3832 I io.jxcore.node.LifeCycleMonitor: start: OK
09-11 11:55:51.633  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:55:51.635  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:55:51.832  3790  3790 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-11 11:55:52.443  3790  3841 W jxcore-log: Initializing JXcore engine
,09-11 11:55:52.443  3790  3841 W jxcore-log: JXcore engine is ready
,09-11 11:55:52.481  3841  3841 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-11 11:55:52.481  3841  3841 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12026]" dev="sockfs" ino=12026 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-11 11:55:52.481  3841  3841 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-11 11:55:52.481  3841  3841 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23408]" dev="sockfs" ino=23408 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-11 11:55:52.518  3790  3841 W jxcore-log: Starting JXcore engine
,09-11 11:55:52.620  3790  3841 W jxcore-log: Platform android
09-11 11:55:52.620  3790  3841 W jxcore-log: 
,09-11 11:55:52.620  3790  3841 W jxcore-log: Process ARCH arm
09-11 11:55:52.620  3790  3841 W jxcore-log: 
,09-11 11:55:52.823  3790  3841 I jxcore-log: JXcore Cordova bridge is ready!
09-11 11:55:52.823  3790  3841 I jxcore-log: 
,09-11 11:55:52.824  3790  3841 W jxcore-log: JXcore engine is started
,09-11 11:55:52.834  3790  3832 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-11 11:55:52.837  3790  3790 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-11 11:55:56.632   872  2066 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-11 11:55:59.220   872  1304 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-11 11:56:00.956  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-11 11:56:00.961  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-11 11:56:00.963  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-11 11:56:00.988  1506  2018 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-11 11:56:00.988  1506  2018 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-11 11:56:00.988  1506  2018 I GLSUser : [GLSUser] Extracting token using key: Auth
09-11 11:56:00.988  1506  2018 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-11 11:56:01.005  3517  3517 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-11 11:56:01.005  3517  3517 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-11 11:56:01.006  3517  3517 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-11 11:56:02.037   872  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-11 11:56:02.786  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-11 11:56:02.786  3790  3841 I jxcore-log: 
,09-11 11:56:02.789  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-11 11:56:02.789  3790  3841 I jxcore-log: 
,09-11 11:56:02.800  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:02.800  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:02.800  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:02.800  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:02.800  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:02.800  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:02.800  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:02.800  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:02.809  3790  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:02.816  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-11 11:56:02.816  3790  3841 I jxcore-log: 
,09-11 11:56:02.824  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-11 11:56:02.824  3790  3841 I jxcore-log: 
,09-11 11:56:03.257  3041  3852 V KeepSync: Connecting to GoogleApiClient
,09-11 11:56:03.258   872  1992 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-11 11:56:03.377  3790  3841 D executeNativeTests: Running unit tests
,09-11 11:56:03.414  1506  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-11 11:56:03.414  1506  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-11 11:56:03.415  1506  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-11 11:56:03.415  1506  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-11 11:56:03.436  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-11 11:56:03.436  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c added. We now have 2 listener(s)
09-11 11:56:03.437  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-11 11:56:03.437  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-11 11:56:03.437  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:03.437  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-11 11:56:03.437  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 added. We now have 2 listener(s)
09-11 11:56:03.437  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:03.438  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-11 11:56:03.444  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:03.459  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:03.459  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:03.459  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:03.459  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:03.459  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:03.459  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:03.459  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:03.459  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:03.464  3790  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:03.464  3790  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-11 11:56:03.471  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-11 11:56:03.472  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-11 11:56:03.472  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-11 11:56:03.476  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:03.476  3790  3841 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-11 11:56:03.480  1723  3853 V BaseAuthAsyncOperation: access token request failed
09-11 11:56:03.481  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:03.482  3790  3841 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-11 11:56:03.482  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-11 11:56:03.482  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-11 11:56:03.483  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-11 11:56:03.484  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:03.485  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.485  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-11 11:56:03.486  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.486  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.486  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:03.487  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-11 11:56:03.487  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c removed from the list
09-11 11:56:03.487  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.487  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 removed from the list
09-11 11:56:03.487  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.487  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.487  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.488  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.489  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-11 11:56:03.489  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.489  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.489  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
,09-11 11:56:03.491  3041  3852 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-11 11:56:03.491  3790  3841 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-11 11:56:03.491  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.491  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-11 11:56:03.491  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.492  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-11 11:56:03.492  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.492  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.492  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
,09-11 11:56:03.492  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:03.492  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
,09-11 11:56:03.492  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.492  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:03.492  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.492  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.492  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.493  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-11 11:56:03.493  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.493  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.493  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
,09-11 11:56:03.499  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-11 11:56:03.499  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-11 11:56:03.499  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-11 11:56:03.500  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-11 11:56:03.500  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-11 11:56:03.500  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-11 11:56:03.500  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-11 11:56:03.500  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-11 11:56:03.500  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-11 11:56:03.500  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-11 11:56:03.500  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-11 11:56:03.500  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-11 11:56:03.500  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-11 11:56:03.500  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-11 11:56:03.500  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-11 11:56:03.500  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-11 11:56:03.500  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-11 11:56:03.501  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-11 11:56:03.501  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-11 11:56:03.501  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-11 11:56:03.501  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-11 11:56:03.501  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-11 11:56:03.501  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-11 11:56:03.501  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210],
09-11 11:56:03.501  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-11 11:56:03.501  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-11 11:56:03.501  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-11 11:56:03.501  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-11 11:56:03.501  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-11 11:56:03.501  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-11 11:56:03.501  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-11 11:56:03.501  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.502  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.502  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-11 11:56:03.502  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.502  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.502  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.502  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.502  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.502  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.502  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.502  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.502  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.502  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.502  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.503  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.503  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.503  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.504  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.504  3790  3841 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-11 11:56:03.506  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:03.510  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:03.510  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:03.510  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:03.510  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:03.510  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:03.510  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:03.510  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:03.510  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:03.513  3790  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:03.513  3790  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:03.514  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-11 11:56:03.514  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:03.514  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-11 11:56:03.514  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:03.514  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-11 11:56:03.516  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:03.519  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:03.521  3790  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-11 11:56:03.521  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-11 11:56:03.527  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-11 11:56:03.531  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-11 11:56:03.531  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-11 11:56:03.535  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-11 11:56:03.538  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-11 11:56:03.538  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-11 11:56:03.539  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-11 11:56:03.539  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-11 11:56:03.540  3790  3841 D BluetoothAdapter: STATE_ON
,09-11 11:56:03.546  2701  2713 D BtGatt.GattService: registerClient() - UUID=5207797c-2cbd-4c3e-a13e-a8c394b09ec7
,09-11 11:56:03.547  2701  2723 D BtGatt.GattService: onClientRegistered() - UUID=5207797c-2cbd-4c3e-a13e-a8c394b09ec7, clientIf=5
,09-11 11:56:03.548  3790  3802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-11 11:56:03.550  2701  2878 D BtGatt.GattService: start scan with filters
,09-11 11:56:03.555  2701  2730 D BtGatt.ScanManager: handling starting scan
,09-11 11:56:03.555  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-11 11:56:03.556  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-11 11:56:03.556  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-11 11:56:03.556  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-11 11:56:03.558  2701  2730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
09-11 11:56:03.559  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-11 11:56:03.559  3790  3790 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-11 11:56:03.560  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-11 11:56:03.561  1506  2427 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-11 11:56:03.561  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-11 11:56:03.561  1506  2427 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-11 11:56:03.562  1506  2427 I GLSUser : [GLSUser] Extracting token using key: Auth
09-11 11:56:03.562  1506  2427 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-11 11:56:03.564  3790  3841 I io.jxcore.node.ConnectionHelper: start: OK
,09-11 11:56:03.566  2701  2723 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-11 11:56:03.566  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-11 11:56:03.567  2701  2730 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-11 11:56:03.569  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.569  3790  3841 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-11 11:56:03.569  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-11 11:56:03.569  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-11 11:56:03.569  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.569  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-11 11:56:03.570  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-11 11:56:03.570  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-11 11:56:03.570  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-11 11:56:03.570  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-11 11:56:03.571  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-11 11:56:03.571  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-11 11:56:03.573  3790  3841 D BluetoothAdapter: STATE_ON
09-11 11:56:03.573  2701  2723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-11 11:56:03.573  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.574  2701  2730 D BtGatt.ScanManager: Starting BLE batch scan
,09-11 11:56:03.574  2701  2730 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-11 11:56:03.575  2701  2712 D BtGatt.GattService: stopScan() - queue size =1
09-11 11:56:03.576  2701  2878 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-11 11:56:03.577  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:03.577  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-11 11:56:03.577  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-11 11:56:03.577  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-11 11:56:03.577  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-11 11:56:03.578  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:03.579  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-11 11:56:03.579  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-11 11:56:03.579  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-11 11:56:03.579  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:03.580  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.581  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.581  3790  3790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:03.581  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:03.581  3790  3790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:03.581  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
,09-11 11:56:03.581  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.581  3790  3790 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:03.581  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.581  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
,09-11 11:56:03.581  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.581  3790  3841 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-11 11:56:03.583  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:03.588  2701  2723 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-11 11:56:03.588  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-11 11:56:03.591  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:03.591  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:03.591  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:03.591  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:03.591  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:03.591  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:03.591  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:03.591  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:03.593  3790  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:03.593  3790  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:03.594  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-11 11:56:03.594  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:03.594  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:03.594  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:03.594  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-11 11:56:03.596  2701  2723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-11 11:56:03.596  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.597  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:03.598  3790  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-11 11:56:03.598  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-11 11:56:03.602  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-11 11:56:03.602  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:03.603  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-11 11:56:03.603  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-11 11:56:03.604  2701  2723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-11 11:56:03.604  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.604  2701  2730 D BtGatt.ScanManager: stopping BLe Batch
,09-11 11:56:03.606  3041  3852 E KeepSync: IOException
09-11 11:56:03.606  3041  3852 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-11 11:56:03.606  3041  3852 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-11 11:56:03.606  3041  3852 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-11 11:56:03.606  3041  3852 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-11 11:56:03.606  3041  3852 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-11 11:56:03.606  3041  3852 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-11 11:56:03.606  3041  3852 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-11 11:56:03.606  3041  3852 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-11 11:56:03.606  3041  3852 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-11 11:56:03.606  3041  3852 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-11 11:56:03.606  3041  3852 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-11 11:56:03.606  3041  3852 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-11 11:56:03.606  3041  3852 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-11 11:56:03.606  3041  3852 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-11 11:56:03.606  3041  3852 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-11 11:56:03.606  3041  3852 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-11 11:56:03.606  3041  3852 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-11 11:56:03.606  3041  3852 E KeepSync: 	... 10 more
,09-11 11:56:03.606  3041  3852 W KeepSync: Sync result 2
09-11 11:56:03.607  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-11 11:56:03.607  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-11 11:56:03.607  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-11 11:56:03.608  3790  3841 D BluetoothAdapter: STATE_ON
09-11 11:56:03.610  2701  2723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-11 11:56:03.610  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.610  2701  2712 D BtGatt.GattService: registerClient() - UUID=003bfb36-dcb6-4fb9-8135-20dc4d892ab2
09-11 11:56:03.610  2701  2730 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-11 11:56:03.610  2701  2723 D BtGatt.GattService: onClientRegistered() - UUID=003bfb36-dcb6-4fb9-8135-20dc4d892ab2, clientIf=5
09-11 11:56:03.611  3790  3802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-11 11:56:03.611  2701  2713 D BtGatt.GattService: start scan with filters
09-11 11:56:03.614  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-11 11:56:03.614  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-11 11:56:03.614  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-11 11:56:03.614  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-11 11:56:03.617  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-11 11:56:03.617  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-11 11:56:03.617  3790  3790 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-11 11:56:03.618  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-11 11:56:03.618   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, PERIODIC, currentRunTime 126634, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
09-11 11:56:03.623  2701  2723 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
09-11 11:56:03.623  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.623  2701  2723 D BtGatt.GattService: current time is 127160954603
09-11 11:56:03.623  2701  2723 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -85, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-11 11:56:03.624  2701  2723 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-11 11:56:03.624  3790  3841 I io.jxcore.node.ConnectionHelper: start: OK
09-11 11:56:03.625  2701  2730 D BtGatt.ScanManager: handling starting scan
09-11 11:56:03.627  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.627  3790  3841 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-11 11:56:03.627  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.627  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-11 11:56:03.627  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.627  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-11 11:56:03.627  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-11 11:56:03.627  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-11 11:56:03.627  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-11 11:56:03.627  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-11 11:56:03.627  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-11 11:56:03.628  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-11 11:56:03.628  3790  3841 D BluetoothAdapter: STATE_ON
09-11 11:56:03.628  2701  2713 D BtGatt.GattService: stopScan() - queue size =1
09-11 11:56:03.629  2701  2878 D BtGatt.GattService: unregisterClient() - clientIf=5
09-11 11:56:03.629  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:03.629  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-11 11:56:03.629  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-11 11:56:03.629  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-11 11:56:03.630  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-11 11:56:03.630  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:03.630  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-11 11:56:03.630  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-11 11:56:03.631  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-11 11:56:03.631  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:03.632  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.632  3790  3790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:03.632  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.632  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:03.632  3790  3790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:03.632  2701  2723 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-11 11:56:03.632  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.632  3790  3790 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:03.632  2701  2730 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-11 11:56:03.633  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.633  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.633  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.633  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.633  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.633  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.633  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.634  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.634  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.634  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.634  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.635  3790  3841 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-11 11:56:03.636  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:03.638  2701  2723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-11 11:56:03.638  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.639  2701  2730 D BtGatt.ScanManager: Starting BLE batch scan
09-11 11:56:03.639  2701  2730 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-11 11:56:03.643  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:03.643  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:03.643  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:03.643  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:03.643  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:03.643  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:03.643  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:03.643  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:03.645  3790  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:03.645  3790  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:03.646  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:03.647  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:03.647  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:03.647  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:03.648  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:03.648  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-11 11:56:03.650  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:03.651  2701  2723 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-11 11:56:03.651  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.652  3790  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-11 11:56:03.652  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-11 11:56:03.656  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-11 11:56:03.656  2701  2723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-11 11:56:03.656  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.656  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-11 11:56:03.656  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-11 11:56:03.660  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-11 11:56:03.660  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-11 11:56:03.660  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-11 11:56:03.660  3790  3841 D BluetoothAdapter: STATE_ON
09-11 11:56:03.663  2701  2878 D BtGatt.GattService: registerClient() - UUID=9ab88f6b-10c9-4cc5-93f9-861d1a67f511
09-11 11:56:03.663  2701  2723 D BtGatt.GattService: onClientRegistered() - UUID=9ab88f6b-10c9-4cc5-93f9-861d1a67f511, clientIf=5
09-11 11:56:03.664  3790  3801 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-11 11:56:03.664  2701  2723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-11 11:56:03.664  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.664  2701  2713 D BtGatt.GattService: start scan with filters
09-11 11:56:03.664  2701  2730 D BtGatt.ScanManager: stopping BLe Batch
09-11 11:56:03.668  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-11 11:56:03.668  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-11 11:56:03.668  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-11 11:56:03.668  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-11 11:56:03.671  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-11 11:56:03.671  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-11 11:56:03.671  3790  3790 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-11 11:56:03.671  2701  2723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-11 11:56:03.671  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.672  2701  2730 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-11 11:56:03.673  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-11 11:56:03.675  3790  3841 I io.jxcore.node.ConnectionHelper: start: OK
09-11 11:56:03.676  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.676  3790  3841 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-11 11:56:03.676  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.676  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-11 11:56:03.676  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.676  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-11 11:56:03.676  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-11 11:56:03.676  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-11 11:56:03.676  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-11 11:56:03.676  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-11 11:56:03.676  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-11 11:56:03.676  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-11 11:56:03.677  3790  3841 D BluetoothAdapter: STATE_ON
09-11 11:56:03.678  2701  2878 D BtGatt.GattService: stopScan() - queue size =0
09-11 11:56:03.679  2701  2712 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-11 11:56:03.679  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:03.679  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-11 11:56:03.679  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-11 11:56:03.679  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-11 11:56:03.679  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-11 11:56:03.680  2701  2723 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-11 11:56:03.680  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.681  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:03.681  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-11 11:56:03.681  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-11 11:56:03.682  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-11 11:56:03.682  2701  2730 D BtGatt.ScanManager: handling starting scan
09-11 11:56:03.682  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:03.684  3790  3790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:03.684  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.684  3790  3790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:03.684  3790  3841 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-11 11:56:03.684  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.684  3790  3790 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:03.684  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.684  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.684  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.684  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:03.684  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.685  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.687  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.687  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.687  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.688  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.688  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.689  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.689  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.689  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.689  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.689  3790  3841 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-11 11:56:03.690  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.690  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.690  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.690  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.690  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.690  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.691  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.691  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.691  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.691  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.691  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.691  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.691  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.691  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.692  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.692  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.692  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.692  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.693  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-11 11:56:03.693  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.693  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.693  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.694  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.694  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.694  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.694  2701  2723 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-11 11:56:03.694  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.694  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.694  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.694  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.694  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.694  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.694  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.694  2701  2730 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-11 11:56:03.694  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.694  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.695  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.695  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.695  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.695  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.696  3790  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-11 11:56:03.696  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.696  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.696  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.697  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.697  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.697  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.697  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.697  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.697  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.697  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.697  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.697  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.697  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.697  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.698  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.698  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.698  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.698  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.699  3790  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-11 11:56:03.699  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.699  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.699  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.699  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.699  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.699  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.699  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.699  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.699  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.699  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.700  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.700  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.700  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.700  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.700  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.700  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.701  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.701  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.701  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-11 11:56:03.702  2701  2723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-11 11:56:03.702  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.703  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-11 11:56:03.703  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-11 11:56:03.703  2701  2730 D BtGatt.ScanManager: Starting BLE batch scan
09-11 11:56:03.703  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-11 11:56:03.703  2701  2730 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-11 11:56:03.703  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-11 11:56:03.703  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-11 11:56:03.705  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.705  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.708  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.708  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.708  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.708  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.708  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.708  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.709  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.709  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.709  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.710  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.710  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.710  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.711  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.712  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.712  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.712  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.714  3790  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:03.714  3790  3841 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-11 11:56:03.714  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-11 11:56:03.715  2701  2723 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-11 11:56:03.715  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.719  3790  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:03.720  3790  3841 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-11 11:56:03.720  2701  2723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-11 11:56:03.720  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-11 11:56:03.720  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.720  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-11 11:56:03.720  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-11 11:56:03.720  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-11 11:56:03.720  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-11 11:56:03.720  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-11 11:56:03.720  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-11 11:56:03.720  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-11 11:56:03.720  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-11 11:56:03.720  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-11 11:56:03.720  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-11 11:56:03.721  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-11 11:56:03.721  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-11 11:56:03.721  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-11 11:56:03.721  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-11 11:56:03.721  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-11 11:56:03.721  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-11 11:56:03.721  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-11 11:56:03.721  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-11 11:56:03.721  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-11 11:56:03.721  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-11 11:56:03.721  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-11 11:56:03.721  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-11 11:56:03.721  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-11 11:56:03.721  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-11 11:56:03.722  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-11 11:56:03.722  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-11 11:56:03.722  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-11 11:56:03.722  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-11 11:56:03.722  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-11 11:56:03.722  3790  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-11 11:56:03.722  3790  3841 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-11 11:56:03.722  3790  3841 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-11 11:56:03.723  3790  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:03.723  3790  3841 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-11 11:56:03.723  3790  3841 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-11 11:56:03.723  3790  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:03.723  3790  3841 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-11 11:56:03.723  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-11 11:56:03.727  2701  2723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-11 11:56:03.727  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.727  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-11 11:56:03.727  2701  2730 D BtGatt.ScanManager: stopping BLe Batch
09-11 11:56:03.728  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-11 11:56:03.728  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-11 11:56:03.728  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-11 11:56:03.728  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-11 11:56:03.729  3790  3841 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-11 11:56:03.729  3790  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:03.729  3790  3841 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-11 11:56:03.730  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.730  3790  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 385)
09-11 11:56:03.730  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.730  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.730  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.730  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.730  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.730  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-11 11:56:03.731  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.731  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.732  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.732  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.732  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.732  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.732  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.732  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.733  2701  2723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-11 11:56:03.733  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:03.733  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.733  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.733  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.733  3790  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 385
09-11 11:56:03.733  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.734  3790  3841 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-11 11:56:03.734  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.734  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.734  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.735  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.735  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.735  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.735  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.735  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.735  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.735  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.735  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.735  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.735  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.735  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.735  2701  2730 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-11 11:56:03.736  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.736  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.736  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.736  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.737  3790  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-11 11:56:03.737  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.737  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.738  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.738  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-11 11:56:03.738  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:03.738  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.738  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.738  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.738  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.738  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
,09-11 11:56:03.738  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.738  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.738  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.738  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.739  3790  3854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:03.741  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.741  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-11 11:56:03.741  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.741  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.741  2701  2723 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-11 11:56:03.741  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-11 11:56:03.742  3790  3841 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-11 11:56:03.742  3790  3841 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-11 11:56:03.742  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-11 11:56:03.743  3790  3841 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-11 11:56:03.743  3790  3841 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-11 11:56:03.743  3790  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-11 11:56:03.743  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-11 11:56:03.743  3790  3841 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,09-11 11:56:03.743  3790  3841 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-11 11:56:03.743  3790  3841 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-11 11:56:03.743  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-11 11:56:03.743  3790  3841 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-11 11:56:03.743  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:03.743  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.743  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.744  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.744  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.744  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.744  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.744  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.744  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.744  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.744  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.744  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.744  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.744  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.745  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.745  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.745  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:03.746  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.746  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.746  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.746  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.746  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.746  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:03.746  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.747  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.747  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.747  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.747  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:03.747  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.747  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.747  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.747  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.747  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
,09-11 11:56:03.747  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:03.747  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.747  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.748  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.748  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:03.748  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.748  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.748  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.748  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.748  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
,09-11 11:56:03.748  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.748  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.748  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.748  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.749  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-11 11:56:03.749  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.750  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.750  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.751  3790  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-11 11:56:03.751  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:03.752  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-11 11:56:03.752  3790  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-11 11:56:03.753  3790  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-11 11:56:03.753  3790  3790 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-11 11:56:03.753  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-11 11:56:03.753  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-11 11:56:03.753  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.753  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-11 11:56:03.754  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-11 11:56:03.754  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-11 11:56:03.754  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.754  3790  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-11 11:56:03.754  3790  3856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:03.754  3790  3790 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-11 11:56:03.754  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.754  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:03.754  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-11 11:56:03.754  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-11 11:56:03.754  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-11 11:56:03.755  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.755  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.756  3790  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-11 11:56:03.756  3790  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-11 11:56:03.756  3790  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-11 11:56:03.756  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:03.756  3790  3790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-11 11:56:03.756  3790  3790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:03.756  3790  3790 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:03.756  3790  3790 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-11 11:56:03.756  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.757  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:03.757  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.757  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.757  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.757  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.757  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.757  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.757  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.757  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.757  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.757  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.757  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.757  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.757  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.759  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.759  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.759  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:03.759  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.760  3790  3841 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-11 11:56:03.760  3790  3841 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-11 11:56:03.760  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-11 11:56:03.762  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-11 11:56:03.762  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:03.764  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.765  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.766  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.766  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.766  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.766  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.766  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.766  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.766  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.766  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.766  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.766  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.766  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.767  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-11 11:56:03.767  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-11 11:56:03.767  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.767  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.770  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:03.771  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.771  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:03.771  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.771  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:03.771  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.771  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.771  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:03.771  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.771  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.771  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:03.771  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.771  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:03.771  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.774  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.774  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.774  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:03.774  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.775  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:03.775  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:03.775  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-11 11:56:03.775  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:03.775  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.775  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.775  3790  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@605604c not in the list
09-11 11:56:03.775  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.775  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.775  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:03.776  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.776  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:03.776  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:03.776  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:03.777  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:03.777  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:03.777  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:03.777  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a695895 not in the list
09-11 11:56:03.778  3790  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-11 11:56:03.778  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-11 11:56:03.778  3790  3841 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-11 11:56:03.778  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-11 11:56:03.778  3790  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-11 11:56:03.778  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-11 11:56:03.780  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-11 11:56:03.780  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-11 11:56:03.781  3790  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-11 11:56:03.781  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-11 11:56:03.781  3790  3841 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-11 11:56:03.781  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-11 11:56:03.781  3790  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-11 11:56:03.781  3790  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-11 11:56:03.781  3790  3841 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-11 11:56:03.782  3790  3841 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-11 11:56:03.782  3790  3841 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-11 11:56:03.782  3790  3841 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-11 11:56:03.782  3790  3841 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-11 11:56:03.782  3790  3841 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-11 11:56:03.783  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:03.783  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9b26f6f added. We now have 2 listener(s)
09-11 11:56:03.783  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:03.786  3790  3841 D BluetoothAdapter: enable(): BT is already enabled..!
09-11 11:56:03.786   872  2207 D WifiService: setWifiEnabled: true pid=3790, uid=10000
09-11 11:56:03.786   872  2207 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-11 11:56:03.787  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:03.787  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc7747c added. We now have 3 listener(s)
09-11 11:56:03.787  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:03.797  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-11 11:56:03.797  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7529105 added. We now have 4 listener(s)
09-11 11:56:03.797  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:03.799  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:03.799  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@535755a added. We now have 5 listener(s)
09-11 11:56:03.799  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:03.802   872  1698 D WifiService: setWifiEnabled: false pid=3790, uid=10000
,09-11 11:56:03.802   872  1698 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-11 11:56:03.806  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:03.807  2701  2719 D BluetoothAdapterState: Current state: ON, message: 23
,09-11 11:56:03.807  2701  2719 D BluetoothAdapterProperties: Setting state to 13
,09-11 11:56:03.808  2701  2719 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-11 11:56:03.808  2701  2719 D BluetoothAdapterProperties: onBluetoothDisable()
09-11 11:56:03.810  2701  2719 I BluetoothAdapterState: Entering PendingCommandState
,09-11 11:56:03.810  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:03.810  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:03.810  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:03.810  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:03.810  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:03.810  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:03.810  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:03.810  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:03.810  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:03.811  2701  2723 D BluetoothAdapterProperties: Scan Mode:20
09-11 11:56:03.812  2701  2719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-11 11:56:03.814  2701  2701 D BluetoothMapService: onReceive
,09-11 11:56:03.815  2701  2701 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:03.815  2701  2701 D BluetoothMapService: STATE_TURNING_OFF
,09-11 11:56:03.815  2701  2701 D BluetoothMapService: MAP Service closeService in
09-11 11:56:03.815  2701  2701 D BluetoothMapMasInstance0: MAP Service shutdown
,09-11 11:56:03.816  2701  2701 D ObexServerSockets0: shutdown(block = true)
09-11 11:56:03.816  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:03.816  3790  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:03.816  2701  2701 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-11 11:56:03.816  3790  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:03.816  2701  2701 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-11 11:56:03.816  2701  2904 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-11 11:56:03.817  2701  2905 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-11 11:56:03.817  2701  2874 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-11 11:56:03.817  2701  2701 I BtOppRfcommListener: stopping Accept Thread
09-11 11:56:03.817  2701  3453 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-11 11:56:03.817  2701  3453 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-11 11:56:03.820  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-11 11:56:03.820  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:03.822   872  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-11 11:56:03.822   872  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-11 11:56:03.822   872  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-11 11:56:03.822   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-11 11:56:03.823  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:03.827  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:03.827  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:03.827  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:03.827  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:03.827  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:03.827  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:03.827  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:03.827  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:03.827  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:03.828  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:03.828  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:03.830  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:03.833  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:03.834   872   885 I ActivityManager: Start proc 3860:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-11 11:56:03.839  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:03.840   872  2073 D DhcpClient: Clearing IP address
,09-11 11:56:03.840   371   870 D CommandListener: Clearing all IP addresses on wlan0
,09-11 11:56:03.842  2701  2701 D HeadsetService: Received stop request...Stopping profile...
,09-11 11:56:03.844   371   870 D CommandListener: Setting iface cfg
09-11 11:56:03.844  1948  1963 D BluetoothHeadset: Proxy object disconnected
09-11 11:56:03.845   872   872 D BluetoothHeadset: Proxy object disconnected
,09-11 11:56:03.845  1374  1388 D BluetoothHeadset: Proxy object disconnected
,09-11 11:56:03.846  1374  1374 D HeadsetProfile: Bluetooth service disconnected
09-11 11:56:03.846   872   872 D BluetoothHeadset: Proxy object disconnected
,09-11 11:56:03.846   872   872 D BluetoothHeadset: Proxy object disconnected
,09-11 11:56:03.846  1506  2548 V NativeCrypto: Read error: ssl=0xaee7c400: I/O error during system call, Connection timed out
,09-11 11:56:03.848   872  2095 D DhcpClient: Receive thread stopped
,09-11 11:56:03.848   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-11 11:56:03.848  1506  2548 V NativeCrypto: SSL shutdown failed: ssl=0xaee7c400: I/O error during system call, Broken pipe
09-11 11:56:03.848   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-11 11:56:03.851   872  1304 D WifiStateMachine: Start Disconnecting Watchdog 1
09-11 11:56:03.852  2701  2701 D A2dpService: Received stop request...Stopping profile...
,09-11 11:56:03.853  2701  2884 D A2dpStateMachine: Exit Disconnected: -1
09-11 11:56:03.852   425   425 E Parcel  : Reading a NULL string not supported here.
,09-11 11:56:03.855   872  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-11 11:56:03.856  1374  1374 D BluetoothA2dp: Proxy object disconnected
09-11 11:56:03.856   371   870 D CommandListener: Clearing all IP addresses on wlan0
09-11 11:56:03.857   872   872 D BluetoothA2dp: Proxy object disconnected
09-11 11:56:03.858  2701  2701 D HidService: Received stop request...Stopping profile...
09-11 11:56:03.858  2701  2701 D HidService: Stopping Bluetooth HidService
,09-11 11:56:03.858  1374  1374 D BluetoothInputDevice: Proxy object disconnected
09-11 11:56:03.859  2701  2701 D HealthService: Received stop request...Stopping profile...
09-11 11:56:03.859  1374  1374 D HidProfile: Bluetooth service disconnected
09-11 11:56:03.860   872  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-11 11:56:03.863  2701  2701 D PanService: Received stop request...Stopping profile...
09-11 11:56:03.864  2701  2701 D BluetoothMapService: Received stop request...Stopping profile...
09-11 11:56:03.864  2701  2701 D BluetoothMapService: stop()
09-11 11:56:03.865  2701  2701 D BluetoothMapAppObserver: deinitObservers()
09-11 11:56:03.865  1374  1374 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-11 11:56:03.865  2701  2701 D BluetoothMapAppObserver: removeReceiver()
09-11 11:56:03.865  1374  1374 D PanProfile: Bluetooth service disconnected
09-11 11:56:03.867  2701  2701 V BluetoothAdapterState: isTurningOff()=true
09-11 11:56:03.867   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
09-11 11:56:03.867  2701  2701 V BluetoothAdapterState: isTurningOn()=false
09-11 11:56:03.867  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:03.867  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
09-11 11:56:03.869   872  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-11 11:56:03.870  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:03.870  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:03.870  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:03.870  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:03.870  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:03.870  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:03.870  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:03.870  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:03.870  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:03.870  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:03.870  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:03.872  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:03.872  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:03.872  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:03.872  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:03.872  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:03.872  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:03.872  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:03.872  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:03.872  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:03.872  1902  2333 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:03.872  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:03.872  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:03.872  2701  2701 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-11 11:56:03.872  2701  2701 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-11 11:56:03.873  2701  2701 V BluetoothAdapterState: isTurningOff()=true
,09-11 11:56:03.873  2701  2701 V BluetoothAdapterState: isTurningOn()=false
,09-11 11:56:03.873  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:03.873  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
09-11 11:56:03.873  2701  2852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-11 11:56:03.874  2701  2852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-11 11:56:03.874  2701  2852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-11 11:56:03.874  2701  2723 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-11 11:56:03.874  2701  2723 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-11 11:56:03.874  2701  2701 V BluetoothAdapterState: isTurningOff()=true
09-11 11:56:03.875  2701  2701 V BluetoothAdapterState: isTurningOn()=false
09-11 11:56:03.875  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
,09-11 11:56:03.875  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
,09-11 11:56:03.875  2701  2701 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-11 11:56:03.875  2701  2701 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object,
09-11 11:56:03.875  2701  2701 V BluetoothAdapterState: isTurningOff()=true
,09-11 11:56:03.875  2701  2701 V BluetoothAdapterState: isTurningOn()=false
09-11 11:56:03.875  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:03.875  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
09-11 11:56:03.876  2701  2701 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-11 11:56:03.876  2701  2852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-11 11:56:03.876  2701  2852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-11 11:56:03.876  2701  2852 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-11 11:56:03.876  2701  2852 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-11 11:56:03.876  2701  2852 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-11 11:56:03.876  2701  2852 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:03.876  2701  2723 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-11 11:56:03.877  2701  2723 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-11 11:56:03.877  2701  2723 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-11 11:56:03.878  2701  2701 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-11 11:56:03.878  2701  2701 V BluetoothAdapterState: isTurningOff()=true
09-11 11:56:03.878  2701  2701 V BluetoothAdapterState: isTurningOn()=false
09-11 11:56:03.878  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false,
09-11 11:56:03.878  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
09-11 11:56:03.879  2701  2701 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-11 11:56:03.879  2701  2701 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-11 11:56:03.880  2701  2701 D BluetoothMapService: MAP Service closeService in
09-11 11:56:03.880  2701  2701 V BluetoothAdapterState: isTurningOff()=true
09-11 11:56:03.880  2701  2701 V BluetoothAdapterState: isTurningOn()=false
09-11 11:56:03.880  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:03.881  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
09-11 11:56:03.881  1374  1374 D BluetoothMap: Proxy object disconnected
09-11 11:56:03.881  1374  1374 D MapProfile: Bluetooth service disconnected
,09-11 11:56:03.881  2701  2719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-11 11:56:03.881  2701  2719 D BluetoothAdapterProperties: Setting state to 15
09-11 11:56:03.881  2701  2719 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-11 11:56:03.882  2701  2719 I BluetoothAdapterState: Entering BleOnState
09-11 11:56:03.882  2701  2701 D BluetoothMapService: cleanup()
09-11 11:56:03.882  2701  2701 D BluetoothMapService: MAP Service closeService in
,09-11 11:56:03.883  1374  1388 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-11 11:56:03.885   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:03.885  1948  2201 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:03.885  1374  2059 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:03.886   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:03.886  1374  1387 D BluetoothMap: onBluetoothStateChange: up=false
09-11 11:56:03.886  1374  3789 D BluetoothPbap: onBluetoothStateChange: up=false
09-11 11:56:03.887  1374  1388 D BluetoothA2dp: onBluetoothStateChange: up=false
09-11 11:56:03.890  1374  2059 D BluetoothPan: onBluetoothStateChange on: false
09-11 11:56:03.891   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-11 11:56:03.891   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:03.891  2701  2719 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-11 11:56:03.891  2701  2719 D BluetoothAdapterProperties: Setting state to 16
09-11 11:56:03.891  2701  2719 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-11 11:56:03.892  2701  2719 D BluetoothAdapterProperties: onBleDisable
09-11 11:56:03.892  2701  2719 I BluetoothAdapterState: Entering PendingCommandState
09-11 11:56:03.892  2701  2720 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-11 11:56:03.893  2701  2852 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-11 11:56:03.893  2701  2852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-11 11:56:03.894  3790  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 385)
09-11 11:56:03.894  2701  2723 D BluetoothAdapterProperties: Scan Mode:20
09-11 11:56:03.895  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:03.897  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:03.897  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:03.898  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:03.910   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-11 11:56:03.927   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-11 11:56:03.928   872  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-11 11:56:03.928   872  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:03.930   872   889 D Tethering: MasterInitialState.processMessage what=3
09-11 11:56:03.932  3396  3396 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5a5a07c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) },
09-11 11:56:03.932  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:03.933  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:03.937  3860  3860 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-11 11:56:03.946  3860  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-11 11:56:03.950   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5269a5a:true
,09-11 11:56:03.950  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-11 11:56:03.963   872  1992 I ActivityManager: Start proc 3879:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-11 11:56:03.972  3860  3860 D LocalBluetoothProfileManager: Adding local MAP profile
,09-11 11:56:03.983   371   870 E Netd    : netlink response contains error (No such file or directory)
,09-11 11:56:03.984   872  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-11 11:56:03.987  3860  3860 D BluetoothMap: Create BluetoothMap proxy object
,09-11 11:56:03.996  3860  3860 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-11 11:56:04.002  3879  3879 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-11 11:56:04.006  3860  3860 D DockEventReceiver: finishStartingService: stopping service
,09-11 11:56:04.034   872   883 I ActivityManager: Killing 2983:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-11 11:56:04.098  2701  2723 I bt_hci  : shut_down
09-11 11:56:04.098  2701  2731 D bt_hwcfg: hw_epilog_process
,09-11 11:56:04.111  2701  2731 I bt_vendor: low_power_mode_cb
,09-11 11:56:04.130  2701  2731 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-11 11:56:04.131  2701  2731 I bt_vendor: epilog_cb
09-11 11:56:04.131  2701  2731 I bt_hci  : epilog_finished_callback
,09-11 11:56:04.133  2701  2723 I bt_hci_h4: hal_close
,09-11 11:56:04.134  2701  2723 I bt_userial_vendor: device fd = 51 close
,09-11 11:56:04.202  3879  3879 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.File.exists(File.java:361)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-11 11:56:04.202  3879  3879 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-11 11:56:04.202  3879  3879 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-11 11:56:04.202  3879  3879 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.r.e.b(PG:170)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-11 11:56:04.202  3879  3879 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.r.k.d(PG:583)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.r.e.b(PG:170)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-11 11:56:04.202  3879  3879 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.File.exists(File.java:361)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-11 11:56:04.202  3879  3879 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.File.exists(File.java:361)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-11 11:56:04.202  3879  3879 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-11 11:56:04.202  3879  3879 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-11 11:56:04.226   872  1954 I ActivityManager: Start proc 3910:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-11 11:56:04.228   872  1954 I ActivityManager: Killing 3396:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-11 11:56:04.257  3790  3790 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-11 11:56:04.300  2701  2720 D bt_stack_manager: event_shut_down_stack finished.
,09-11 11:56:04.300  2701  2719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-11 11:56:04.302  2701  2719 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-11 11:56:04.302  2701  2701 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-11 11:56:04.303  2701  2701 D BtGatt.GattService: Received stop request...Stopping profile...
09-11 11:56:04.303  2701  2701 D BtGatt.GattService: stop()
09-11 11:56:04.304  2701  2701 D BtGatt.AdvertiseManager: advertise clients cleared
,09-11 11:56:04.305  2701  2701 V BluetoothAdapterState: isTurningOff()=false
09-11 11:56:04.305  2701  2701 V BluetoothAdapterState: isTurningOn()=false
09-11 11:56:04.305  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false,
09-11 11:56:04.305  2701  2701 V BluetoothAdapterState: isBleTurningOff()=true
,09-11 11:56:04.305  2701  2719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-11 11:56:04.305  2701  2719 D BluetoothAdapterProperties: Setting state to 10
09-11 11:56:04.306  2701  2719 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-11 11:56:04.306  2701  2719 I BluetoothAdapterState: Entering OffState
09-11 11:56:04.308   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-11 11:56:04.311  3910  3910 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-11 11:56:04.315  2701  2701 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-11 11:56:04.315  2701  2701 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-11 11:56:04.316  2701  2701 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-11 11:56:04.316  2701  2720 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-11 11:56:04.318  2701  2720 D bt_stack_manager: event_clean_up_stack finished.
,09-11 11:56:04.323  2701  2701 I art     : System.exit called, status: 0
,09-11 11:56:04.323  2701  2701 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-11 11:56:04.371   872   882 I ActivityManager: Process com.android.bluetooth (pid 2701) has died
,09-11 11:56:04.407  3910  3910 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-11 11:56:04.438  3879  3899 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-11 11:56:04.447  3860  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-11 11:56:04.470   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@540272d:true
,09-11 11:56:04.480   872  2207 I ActivityManager: Start proc 3939:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-11 11:56:04.482  3860  3860 D DockEventReceiver: finishStartingService: stopping service
,09-11 11:56:04.595  3939  3939 D AdapterServiceConfig: Adding HeadsetService
09-11 11:56:04.596  3939  3939 D AdapterServiceConfig: Adding A2dpService
09-11 11:56:04.596  3939  3939 D AdapterServiceConfig: Adding HidService
09-11 11:56:04.596  3939  3939 D AdapterServiceConfig: Adding HealthService
09-11 11:56:04.596  3939  3939 D AdapterServiceConfig: Adding PanService
09-11 11:56:04.596  3939  3939 D AdapterServiceConfig: Adding GattService
09-11 11:56:04.596  3939  3939 D AdapterServiceConfig: Adding BluetoothMapService
,09-11 11:56:04.600   872  2204 I ActivityManager: Killing 3469:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-11 11:56:04.651  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-11 11:56:04.679  1723  1723 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-11 11:56:04.683  1723  1723 D SystemUpdateService: onCreate
,09-11 11:56:04.693  1723  1723 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-11 11:56:04.703  1723  3952 I SystemUpdateService: active receiver: enabled
,09-11 11:56:04.709  1723  3952 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-11 11:56:04.710  1723  3952 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-11 11:56:04.713  1723  3952 I SystemUpdateService: now status is 0 (complete)
09-11 11:56:04.713  1723  3952 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-11 11:56:04.713  1723  3952 I SystemUpdateService: file has been verified
09-11 11:56:04.713  1723  3952 I SystemUpdateService: OTA package size = 12249756
,09-11 11:56:04.716  1723  3952 I SystemUpdateService: showing system update notification
,09-11 11:56:04.728  1723  1723 D SystemUpdateService: onDestroy
,09-11 11:56:04.747  1723  1723 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-11 11:56:04.752  1723  2524 I iu.UploadsManager: num queued entries: 0
09-11 11:56:04.752  1723  2524 I iu.UploadsManager: num updated entries: 0
09-11 11:56:04.753  1723  2524 I iu.SyncManager: NEXT; no task
,09-11 11:56:04.755  1723  1723 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-11 11:56:04.757  1723  1723 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-11 11:56:04.773   872  2001 I ActivityManager: Start proc 3955:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-11 11:56:04.820  3955  3955 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-11 11:56:04.822  3955  3955 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:04.831  3955  3955 D SprintDMHelper: simOperator: 
,09-11 11:56:04.831  3955  3955 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-11 11:56:04.857   872  1983 I ActivityManager: Start proc 3967:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-11 11:56:04.859   872  1983 I ActivityManager: Killing 1702:android.process.acore/u0a5 (adj 15): empty #17
,09-11 11:56:05.016   872  1954 I ActivityManager: Start proc 3982:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-11 11:56:05.019   872  1954 I ActivityManager: Killing 3637:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-11 11:56:05.070  3982  3982 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-11 11:56:05.121  3982  3982 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-11 11:56:05.121  3982  3982 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-11 11:56:05.121  3982  3982 I GAv4    :   adb logcat -s GAv4
,09-11 11:56:05.137  3982  3982 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-11 11:56:05.146  3982  3982 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-11 11:56:05.178  3982  4000 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-11 11:56:05.288  3982  3982 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-11 11:56:05.330  3982  3982 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-11 11:56:05.338  3982  3982 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8873-8876)
09-11 11:56:05.338  3982  3982 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-11 11:56:05.352  3982  3982 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bd020ac}
,09-11 11:56:05.353  3982  3982 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-11 11:56:05.353  3982  3982 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-11 11:56:05.362  3982  3982 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-11 11:56:05.363  3982  3982 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-11 11:56:05.379  3982  3982 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-11 11:56:05.391  3982  3982 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-11 11:56:05.391  3982  3982 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-11 11:56:05.391  3982  3982 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-11 11:56:05.391  3982  3982 I Adreno  : Build Date                       : 10/20/15
09-11 11:56:05.391  3982  3982 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-11 11:56:05.391  3982  3982 I Adreno  : Local Branch                     : M14
09-11 11:56:05.391  3982  3982 I Adreno  : Remote Branch                    : 
09-11 11:56:05.391  3982  3982 I Adreno  : Remote Branch                    : 
09-11 11:56:05.391  3982  3982 I Adreno  : Reconstruct Branch               : 
,09-11 11:56:05.457  3982  3982 I NSApplication: Starting up...
,09-11 11:56:05.469  3982  4028 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-11 11:56:05.497   872  1992 I ActivityManager: Start proc 4033:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-11 11:56:05.498   872  1992 I ActivityManager: Killing 3651:com.android.musicfx/u0a18 (adj 15): empty #17
,09-11 11:56:05.591  4033  4033 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-11 11:56:05.780   872  2001 I ActivityManager: Killing 2144:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-11 11:56:06.821   872  2001 D WifiService: setWifiEnabled: true pid=3790, uid=10000
,09-11 11:56:06.822   872  2001 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-11 11:56:06.839   872  1304 D WifiConfigStore: Loading config and enabling all networks 
,09-11 11:56:06.847  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:06.848  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:06.848  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.848  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:06.848  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:06.848  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:06.848  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:06.848  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:06.848  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:06.848  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.848  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:06.852  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.852  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:06.852  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.852  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:06.852  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:06.852  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:06.852  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:06.852  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:06.852  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:06.852  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.853  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:06.866   872  1304 D WifiConfigStore: loaded 0 passpoint configs
09-11 11:56:06.867   872  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-11 11:56:06.868   872  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-11 11:56:06.869   872  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-11 11:56:06.869   872  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-11 11:56:06.869   872  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-11 11:56:06.869   872  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-11 11:56:06.891   872  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=11.88 rxSuccessRate=16.62 delta 1000 -> 994
09-11 11:56:06.891   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-11 11:56:06.894   371   870 D CommandListener: Setting iface cfg
,09-11 11:56:06.901   872  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-11 11:56:06.901   872  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-11 11:56:06.901   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-11 11:56:06.901   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-11 11:56:06.911   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-11 11:56:06.944   872  1303 D WifiNative-HAL: p2pGetDeviceAddress
,09-11 11:56:06.946   872  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-11 11:56:06.994   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-11 11:56:06.996  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-11 11:56:07.422  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-11 11:56:07.490  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-11 11:56:07.491  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-11 11:56:07.498   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-11 11:56:07.512   872  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-11 11:56:07.513   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-11 11:56:07.514   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-11 11:56:07.540   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-11 11:56:07.558   371   870 D CommandListener: Setting iface cfg
,09-11 11:56:07.561   872  1304 D WifiStateMachine: Start Dhcp Watchdog 2
,09-11 11:56:07.580   872  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-11 11:56:07.584   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-11 11:56:07.588   872  4056 D DhcpClient: Receive thread started
,09-11 11:56:07.681   872  1304 E native  : do suspend false
,09-11 11:56:07.703   872  2073 D DhcpClient: Broadcasting DHCPDISCOVER
,09-11 11:56:07.716   872  4056 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172692, domain null
,09-11 11:56:07.718   872  2073 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172692 seconds
,09-11 11:56:07.722   872  2073 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-11 11:56:07.738   872  4056 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-11 11:56:07.741   872  2073 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-11 11:56:07.746   371   870 D CommandListener: Setting iface cfg
,09-11 11:56:07.758   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-11 11:56:07.758   872  2073 D DhcpClient: Scheduling renewal in 86399s
,09-11 11:56:07.774   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-11 11:56:07.779   872  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-11 11:56:07.779   872  1304 D WifiConfigStore: No blacklist allowed without epno enabled
09-11 11:56:07.781   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-11 11:56:07.783   872  1307 D ConnectivityService: Adding iface wlan0 to network 101
,09-11 11:56:07.798   872  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-11 11:56:07.846   872  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-11 11:56:07.847   872  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-11 11:56:07.850   872  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-11 11:56:07.851   872  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-11 11:56:07.852   872  1307 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-11 11:56:07.861   872  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-11 11:56:07.866   872  1307 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-11 11:56:07.866   872  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-11 11:56:07.866   872  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-11 11:56:07.866   872  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-11 11:56:07.866   872  1307 D ConnectivityService:    accepting network in place of null
,09-11 11:56:07.867   872  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-11 11:56:07.867   872  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-11 11:56:07.884   872  4055 D NetlinkSocketObserver: NeighborEvent{elapsedMs=131421, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-11 11:56:07.925   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-11 11:56:07.966   872  4054 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-11 11:56:07.987   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-11 11:56:07.993   872  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-11 11:56:07.993   872  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:08.003   872  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-11 11:56:08.005   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-11 11:56:08.020  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:08.020  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:08.020  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:08.020  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:08.020  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:08.020  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:08.020  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:08.020  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:08.020  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:08.021  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:08.021  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:08.027  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:08.027  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:08.027  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:08.027  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:08.027  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:08.027  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:08.027  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:08.027  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:08.027  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:56:08.028  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:08.028  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:08.032  1723  1723 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-11 11:56:08.035  1723  1723 D SystemUpdateService: onCreate
,09-11 11:56:08.039  1723  1723 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-11 11:56:08.041   872  4054 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 11 Sep 2016 09:56:08 GMT], X-Android-Received-Millis=[1473587768040], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473587768011]}
09-11 11:56:08.042   872  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-11 11:56:08.042  1723  4067 I SystemUpdateService: active receiver: enabled
09-11 11:56:08.042   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-11 11:56:08.042   872  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-11 11:56:08.045   872  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-11 11:56:08.051  1723  4067 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-11 11:56:08.054  1723  4067 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-11 11:56:08.054  1723  4067 I SystemUpdateService: now status is 0 (complete)
09-11 11:56:08.054  1723  4067 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-11 11:56:08.054  1723  4067 I SystemUpdateService: file has been verified
09-11 11:56:08.054  1723  4067 I SystemUpdateService: OTA package size = 12249756
,09-11 11:56:08.060  1723  4067 I SystemUpdateService: showing system update notification
,09-11 11:56:08.067  1723  1723 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-11 11:56:08.069  1723  2524 I iu.UploadsManager: num queued entries: 0
,09-11 11:56:08.070  1723  2524 I iu.UploadsManager: num updated entries: 0
,09-11 11:56:08.072  1723  4071 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-11 11:56:08.072  1723  4071 W BaseAppContext: Using Auth Proxy for data requests.
09-11 11:56:08.072  1723  2524 I iu.SyncManager: NEXT; no task
,09-11 11:56:08.073  1723  4071 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
09-11 11:56:08.073  1723  1723 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-11 11:56:08.074  1723  1723 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-11 11:56:08.078  3955  3955 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:08.082  1723  1723 D SystemUpdateService: onDestroy
,09-11 11:56:08.088  3955  3955 D SprintDMHelper: simOperator: 
09-11 11:56:08.088  3955  3955 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-11 11:56:08.099  1506  2018 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-11 11:56:08.099  1506  2018 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-11 11:56:08.099  1506  2018 I GLSUser : [GLSUser] Extracting token using key: Auth
09-11 11:56:08.100  1506  2018 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-11 11:56:08.117  1723  4071 E MDM     : [176] SitrepService.a: Error sending sitrep.
,09-11 11:56:08.240  2294  4074 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-11 11:56:08.417  1506  4080 I GCM     : Ack for not saved message 146
,09-11 11:56:08.994   872  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-11 11:56:09.613   872  1699 I ActivityManager: Killing 3676:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-11 11:56:09.832   872  2205 D WifiService: setWifiEnabled: false pid=3790, uid=10000
,09-11 11:56:09.832   872  2205 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-11 11:56:09.873  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-11 11:56:09.880   872  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-11 11:56:09.880   872  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-11 11:56:09.881   872  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-11 11:56:09.881   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-11 11:56:09.905   872  2073 D DhcpClient: Clearing IP address
,09-11 11:56:09.907   371   870 D CommandListener: Setting iface cfg
,09-11 11:56:09.911   371   870 D CommandListener: Clearing all IP addresses on wlan0
09-11 11:56:09.912   872  4056 D DhcpClient: Receive thread stopped
,09-11 11:56:09.924  1506  4080 V NativeCrypto: Read error: ssl=0x9a295800: I/O error during system call, Connection timed out
,09-11 11:56:09.926  1506  4080 V NativeCrypto: SSL shutdown failed: ssl=0x9a295800: I/O error during system call, Broken pipe
,09-11 11:56:09.929   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-11 11:56:09.929   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-11 11:56:09.934   872  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-11 11:56:09.937   425   425 E Parcel  : Reading a NULL string not supported here.
09-11 11:56:09.940   872  1304 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-11 11:56:09.944   872  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-11 11:56:09.974   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-11 11:56:10.002   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-11 11:56:10.002   371   870 D CommandListener: Clearing all IP addresses on wlan0
,09-11 11:56:10.002   872  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-11 11:56:10.003   872  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:10.005   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-11 11:56:10.009  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:10.009  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:10.009  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:10.009  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:10.009  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:10.009  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:10.009  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:10.009  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:10.009  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:10.009  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:10.009  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:10.010  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:10.010  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:10.010  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:10.010  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:10.010  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:10.010  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:10.010  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:10.010  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:10.010  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:10.010  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:10.010  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:10.016   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-11 11:56:10.022  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:10.022  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:10.022  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:10.022  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:10.022  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:10.022  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:10.022  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:10.022  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:10.022  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:10.022  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:10.022  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:10.023   872  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-11 11:56:10.023  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:10.023  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:10.023  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:10.023  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:10.023  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:10.023  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:10.023  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:10.023  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:10.023  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:10.023  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:10.023  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:10.023  1723  1723 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-11 11:56:10.027  1723  1723 D SystemUpdateService: onCreate
,09-11 11:56:10.028  1902  2333 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:10.031  1723  1723 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-11 11:56:10.035  1723  4089 I SystemUpdateService: active receiver: enabled
,09-11 11:56:10.048  1723  1723 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-11 11:56:10.050  1723  2524 I iu.UploadsManager: num queued entries: 0
,09-11 11:56:10.050  1723  2524 I iu.UploadsManager: num updated entries: 0
,09-11 11:56:10.051  1723  2524 I iu.SyncManager: NEXT; no task
,09-11 11:56:10.055  1723  4089 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-11 11:56:10.057  1723  1723 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-11 11:56:10.059  1723  1723 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-11 11:56:10.061  3955  3955 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:10.065  3955  3955 D SprintDMHelper: simOperator: 
,09-11 11:56:10.065  3955  3955 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-11 11:56:10.077  1723  4089 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-11 11:56:10.077  1723  4089 I SystemUpdateService: now status is 0 (complete)
,09-11 11:56:10.077  1723  4089 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-11 11:56:10.077  1723  4089 I SystemUpdateService: file has been verified
,09-11 11:56:10.077  1723  4089 I SystemUpdateService: OTA package size = 12249756
,09-11 11:56:10.110   371   870 E Netd    : netlink response contains error (No such file or directory)
,09-11 11:56:10.112   872  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-11 11:56:10.120  2294  4093 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-11 11:56:10.145  1723  4089 I SystemUpdateService: showing system update notification
,09-11 11:56:10.172  1723  1723 D SystemUpdateService: onDestroy
,09-11 11:56:12.888   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@62a6cce:true
,09-11 11:56:12.888  3939  3939 D BluetoothAdapterState: make() - Creating AdapterState
,09-11 11:56:12.893  3939  3939 I bt_bluedroid: init
,09-11 11:56:12.894  3939  4097 I BluetoothAdapterState: Entering OffState
,09-11 11:56:12.897  3939  4098 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-11 11:56:12.897  3939  4098 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-11 11:56:12.897  3939  4098 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-11 11:56:12.898  3939  4098 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-11 11:56:12.898  3939  3939 I bt_bluedroid: get_profile_interface socket
,09-11 11:56:12.901  3939  3939 I bt_bluedroid: get_profile_interface sdp
,09-11 11:56:12.904  3939  4101 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-11 11:56:12.915  3939  4101 D BluetoothAdapterProperties: Name is: Nexus 6
,09-11 11:56:12.916  3939  3950 I bt_bluedroid: config_hci_snoop_log
,09-11 11:56:12.918   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-11 11:56:12.928  3939  4097 D BluetoothAdapterState: Current state: OFF, message: 0
,09-11 11:56:12.928  3939  4097 D BluetoothAdapterProperties: Setting state to 14
,09-11 11:56:12.929  3939  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-11 11:56:12.933  3939  4097 D BluetoothBondStateMachine: make
,09-11 11:56:12.937  3939  4102 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-11 11:56:12.944  3939  3939 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-11 11:56:12.945  3939  4097 I BluetoothAdapterState: Entering PendingCommandState
,09-11 11:56:12.946  3939  3939 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542,
09-11 11:56:12.946  3939  3939 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-11 11:56:12.947  3939  3939 D BtGatt.GattService: Received start request. Starting profile...
,09-11 11:56:12.947  3939  3939 D BtGatt.GattService: start()
,09-11 11:56:12.947  3939  3939 I bt_bluedroid: get_profile_interface gatt
,09-11 11:56:12.947  3939  3939 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
,09-11 11:56:12.948  3939  3939 D BtGatt.AdvertiseManager: advertise manager created
,09-11 11:56:12.956  3939  3939 V BluetoothAdapterState: isTurningOff()=false
,09-11 11:56:12.956  3939  3939 V BluetoothAdapterState: isTurningOn()=false
,09-11 11:56:12.956  3939  3939 V BluetoothAdapterState: isBleTurningOn()=true
,09-11 11:56:12.956  3939  3939 V BluetoothAdapterState: isBleTurningOff()=false
,09-11 11:56:12.956  3939  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-11 11:56:12.957  3939  4097 I bt_bluedroid: enable,
09-11 11:56:12.957  3939  4098 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-11 11:56:12.959  3939  4098 I bt_hci  : start_up
,09-11 11:56:12.970  3939  4098 I bt_vendor: alloc value 0xb3a5c189
,09-11 11:56:12.970  3939  4098 I bt_vendor: init
,09-11 11:56:12.970  3939  4098 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-11 11:56:12.971  3939  4098 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found,
,09-11 11:56:13.076  3939  4098 D bt_hci  : start_up starting async portion
,09-11 11:56:13.077  3939  4105 I bt_hci  : event_finish_startup
09-11 11:56:13.078  3939  4105 I bt_hci_h4: hal_open
,09-11 11:56:13.078  3939  4105 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-11 11:56:13.090  3939  4105 I bt_userial_vendor: device fd = 51 open
,09-11 11:56:13.120  3939  4105 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-11 11:56:13.151  3939  4105 D bt_hwcfg: Chipset BCM4354A2
,09-11 11:56:13.152  3939  4105 D bt_hwcfg: Target name = [BCM4354A2]
09-11 11:56:13.153  3939  4105 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-11 11:56:13.820  3939  4105 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-11 11:56:13.822  3939  4105 D bt_hwcfg: Settlement delay -- 100 ms
09-11 11:56:13.822  3939  4105 I bt_hwcfg: Setting fw settlement delay to 100 
,09-11 11:56:13.940  3939  4105 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-11 11:56:13.941  3939  4105 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-11 11:56:13.970  3939  4105 I bt_hwcfg: vendor lib fwcfg completed
,09-11 11:56:13.970  3939  4105 I bt_vendor: firmware callback
09-11 11:56:13.970  3939  4105 I bt_hci  : firmware_config_callback
,09-11 11:56:13.982  3939  4108 I bt_btu  : btu_task pending for preload complete event
,09-11 11:56:13.982  3939  4108 I bt_btu_task: Bluetooth chip preload is complete
,09-11 11:56:13.983  3939  4108 I bt_btu  : btu_task received preload complete event
,09-11 11:56:13.993  3939  4108 I         : BTE_InitTraceLevels -- TRC_HCI
09-11 11:56:13.994  3939  4108 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-11 11:56:13.994  3939  4108 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-11 11:56:13.994  3939  4108 I         : BTE_InitTraceLevels -- TRC_AVDT
09-11 11:56:13.994  3939  4108 I         : BTE_InitTraceLevels -- TRC_AVRC
09-11 11:56:13.995  3939  4108 I         : BTE_InitTraceLevels -- TRC_A2D
,09-11 11:56:13.995  3939  4108 I         : BTE_InitTraceLevels -- TRC_BNEP
09-11 11:56:13.996  3939  4108 I         : BTE_InitTraceLevels -- TRC_BTM
09-11 11:56:13.997  3939  4108 I         : BTE_InitTraceLevels -- TRC_GAP
09-11 11:56:13.997  3939  4108 I         : BTE_InitTraceLevels -- TRC_PAN
,09-11 11:56:13.997  3939  4108 I         : BTE_InitTraceLevels -- TRC_SDP
,09-11 11:56:13.998  3939  4108 I         : BTE_InitTraceLevels -- TRC_GATT
09-11 11:56:13.998  3939  4108 I         : BTE_InitTraceLevels -- TRC_SMP
,09-11 11:56:13.998  3939  4108 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-11 11:56:13.998  3939  4108 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-11 11:56:14.133  3939  4108 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d9d9d
,09-11 11:56:14.133  3939  4108 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d9d9d 
,09-11 11:56:14.143  3939  4101 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-11 11:56:14.145  3939  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-11 11:56:14.146  3939  4101 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-11 11:56:14.148  3939  4101 D BluetoothAdapterProperties: Name is: Nexus 6
,09-11 11:56:14.152  3939  4101 D BluetoothAdapterProperties: Scan Mode:20
,09-11 11:56:14.153  3939  4101 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-11 11:56:14.153  3939  4101 D bt_hci  : do_postload posting postload work item
,09-11 11:56:14.153  3939  4105 I bt_hci  : event_postload
,09-11 11:56:14.153  3939  4105 I bt_vendor: sco_config_cb
,09-11 11:56:14.154  3939  4105 I bt_hci  : sco_config_callback postload finished.
,09-11 11:56:14.156  3939  4101 D bt_bte_conf: Device ID record 1 : primary
,09-11 11:56:14.157  3939  4101 D bt_bte_conf:   vendorId            = 000f
,09-11 11:56:14.157  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:14.157  3939  4101 D bt_bte_conf:   vendorIdSource      = 0001
09-11 11:56:14.157  3939  4101 D bt_bte_conf:   product             = 1200
09-11 11:56:14.157  3939  4101 D bt_bte_conf:   version             = 1436
09-11 11:56:14.157  3939  4101 D bt_bte_conf:   clientExecutableURL = 
09-11 11:56:14.158  3939  4101 D bt_bte_conf:   serviceDescription  = 
09-11 11:56:14.158  3939  4101 D bt_bte_conf:   documentationURL    = 
,09-11 11:56:14.158  3939  4101 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-11 11:56:14.158  3939  4098 D bt_stack_manager: event_start_up_stack finished
09-11 11:56:14.160  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:14.162  3939  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-11 11:56:14.163  3939  4097 D BluetoothAdapterProperties: Setting state to 15
09-11 11:56:14.164  3939  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-11 11:56:14.165  3939  4097 I BluetoothAdapterState: Entering BleOnState
09-11 11:56:14.169  3939  4105 I bt_vendor: low_power_mode_cb
09-11 11:56:14.169  3939  4097 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-11 11:56:14.169  3939  4097 D BluetoothAdapterProperties: Setting state to 11
,09-11 11:56:14.170  3939  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-11 11:56:14.177  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:14.179  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:14.185  3939  3939 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
,09-11 11:56:14.186  3939  3939 D HeadsetService: Received start request. Starting profile...
,09-11 11:56:14.191  3939  3939 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-11 11:56:14.191  3939  3939 D HeadsetStateMachine: make
,09-11 11:56:14.200  3939  3939 D HeadsetStateMachine: max_hf_connections = 1
09-11 11:56:14.200  3939  4097 I BluetoothAdapterState: Entering PendingCommandState
09-11 11:56:14.200  3939  3939 I bt_bluedroid: get_profile_interface handsfree
,09-11 11:56:14.200  3939  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-11 11:56:14.202  3939  4101 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-11 11:56:14.207  3939  3939 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
09-11 11:56:14.207  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-11 11:56:14.209  3939  3939 D A2dpService: Received start request. Starting profile...
,09-11 11:56:14.209  3939  3939 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-11 11:56:14.210  3939  3939 I bt_bluedroid: get_profile_interface avrcp
,09-11 11:56:14.215  3939  3939 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-11 11:56:14.216  3939  3939 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-11 11:56:14.216  3939  3939 D A2dpStateMachine: make
09-11 11:56:14.217  3939  3939 I bt_bluedroid: get_profile_interface a2dp
09-11 11:56:14.217  3939  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-11 11:56:14.219  3939  4117 D A2dpStateMachine: Enter Disconnected: -2
,09-11 11:56:14.220  3939  3939 I BluetoothHidServiceJni: classInitNative: succeeds
,09-11 11:56:14.220  3939  3939 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
,09-11 11:56:14.221  3860  3860 D BluetoothInputDevice: Proxy object connected
,09-11 11:56:14.221  3939  3939 D HidService: Received start request. Starting profile...
09-11 11:56:14.222  3939  3939 I bt_bluedroid: get_profile_interface hidhost
09-11 11:56:14.222  3939  4101 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39bb3e5
09-11 11:56:14.222  3939  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-11 11:56:14.222  3939  3939 D HidService: setHidService(): set to: null
09-11 11:56:14.222  3860  3860 D HidProfile: Bluetooth service connected
09-11 11:56:14.223  3939  3939 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-11 11:56:14.223  3939  3939 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
09-11 11:56:14.224  3939  3939 D HealthService: Received start request. Starting profile...
09-11 11:56:14.225  3939  3939 I bt_bluedroid: get_profile_interface health
09-11 11:56:14.225  3939  3939 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-11 11:56:14.226  3939  3939 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
,09-11 11:56:14.227  3860  3860 D BluetoothPan: BluetoothPAN Proxy object connected
,09-11 11:56:14.227  3860  3860 D PanProfile: Bluetooth service connected
09-11 11:56:14.228  3939  3939 D PanService: Received start request. Starting profile...
09-11 11:56:14.228  3939  3939 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-11 11:56:14.228  3939  3939 I bt_bluedroid: get_profile_interface pan
09-11 11:56:14.229  3939  4101 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-11 11:56:14.231  3939  3939 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
,09-11 11:56:14.233  3939  3939 D BluetoothMapService: Received start request. Starting profile...
09-11 11:56:14.233  3939  3939 D BluetoothMapService: start()
09-11 11:56:14.234  3860  3860 D BluetoothMap: Proxy object connected
09-11 11:56:14.235  3860  3860 D MapProfile: Bluetooth service connected
09-11 11:56:14.235  3860  3860 D BluetoothMap: getConnectedDevices()
09-11 11:56:14.235  3939  3939 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-11 11:56:14.236  3860  3860 D BluetoothMap: Bluetooth is Not enabled
09-11 11:56:14.236  3939  3939 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-11 11:56:14.236  3939  3939 D BluetoothMapAppObserver: createReceiver()
,09-11 11:56:14.237  3939  3939 D BluetoothMapAppObserver: initObservers()
09-11 11:56:14.237  3939  3939 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-11 11:56:14.243  3939  4114 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-11 11:56:14.243  3939  3939 V BluetoothAdapterState: isTurningOff()=false
09-11 11:56:14.243  3939  3939 V BluetoothAdapterState: isTurningOn()=true
09-11 11:56:14.243  3939  3939 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:14.243  3939  3939 V BluetoothAdapterState: isBleTurningOff()=false
,09-11 11:56:14.246  3939  3939 V BluetoothAdapterState: isTurningOff()=false
,09-11 11:56:14.246  3939  3939 V BluetoothAdapterState: isTurningOn()=true
09-11 11:56:14.246  3939  3939 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:14.246  3939  3939 V BluetoothAdapterState: isBleTurningOff()=false
09-11 11:56:14.246  3939  3939 V BluetoothAdapterState: isTurningOff()=false
09-11 11:56:14.246  3939  3939 V BluetoothAdapterState: isTurningOn()=true
,09-11 11:56:14.246  3939  3939 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:14.246  3939  3939 V BluetoothAdapterState: isBleTurningOff()=false
09-11 11:56:14.247  3939  3939 V BluetoothAdapterState: isTurningOff()=false
09-11 11:56:14.247  3939  3939 V BluetoothAdapterState: isTurningOn()=true
,09-11 11:56:14.247  3939  3939 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:14.247  3939  3939 V BluetoothAdapterState: isBleTurningOff()=false
,09-11 11:56:14.247  3939  3939 V BluetoothAdapterState: isTurningOff()=false
,09-11 11:56:14.247  3939  3939 V BluetoothAdapterState: isTurningOn()=true
09-11 11:56:14.247  3939  3939 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:14.247  3939  3939 V BluetoothAdapterState: isBleTurningOff()=false
,09-11 11:56:14.247  3939  3939 V BluetoothAdapterState: isTurningOff()=false
,09-11 11:56:14.247  3939  3939 V BluetoothAdapterState: isTurningOn()=true
,09-11 11:56:14.247  3939  3939 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:14.248  3939  3939 V BluetoothAdapterState: isBleTurningOff()=false
09-11 11:56:14.248  3939  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-11 11:56:14.248  3939  4097 D BluetoothAdapterProperties: ScanMode =  20
,09-11 11:56:14.248  3939  4097 D BluetoothAdapterProperties: State =  11
,09-11 11:56:14.248  3939  4097 D BluetoothAdapterProperties: Setting state to 12
09-11 11:56:14.248  3939  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-11 11:56:14.249  1374  3789 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-11 11:56:14.249  3939  4101 D BluetoothAdapterProperties: Scan Mode:21
,09-11 11:56:14.250  3939  4101 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-11 11:56:14.250  3939  4097 I BluetoothAdapterState: Entering OnState
09-11 11:56:14.251  1374  1374 D BluetoothInputDevice: Proxy object connected
,09-11 11:56:14.251   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-11 11:56:14.251  1374  1374 D HidProfile: Bluetooth service connected
,09-11 11:56:14.251  1948  2097 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-11 11:56:14.252  3860  3870 D BluetoothPbap: onBluetoothStateChange: up=true
,09-11 11:56:14.254  1374  1387 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-11 11:56:14.254   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-11 11:56:14.254  1374  1388 D BluetoothMap: onBluetoothStateChange: up=true
09-11 11:56:14.254  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,09-11 11:56:14.254  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:14.254  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:14.254  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:14.254  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:14.254  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:14.254  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:14.254  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:14.255  1374  1374 D BluetoothMap: Proxy object connected
09-11 11:56:14.255  3860  3871 D BluetoothMap: onBluetoothStateChange: up=true
09-11 11:56:14.255  1374  1374 D MapProfile: Bluetooth service connected
09-11 11:56:14.255  1374  1374 D BluetoothMap: getConnectedDevices()
,09-11 11:56:14.256  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:14.256  1374  3789 D BluetoothPbap: onBluetoothStateChange: up=true
09-11 11:56:14.258  1374  1387 D BluetoothA2dp: onBluetoothStateChange: up=true
09-11 11:56:14.259  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:14.259  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:14.259  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:14.259  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:14.259  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:14.259  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:14.259  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:14.259  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:14.260  1374  2059 D BluetoothPan: onBluetoothStateChange on: true
09-11 11:56:14.260  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:14.261  1374  1374 D BluetoothPan: BluetoothPAN Proxy object connected
09-11 11:56:14.261  1374  1374 D PanProfile: Bluetooth service connected
09-11 11:56:14.261  1374  1374 D BluetoothA2dp: Proxy object connected
09-11 11:56:14.261  3939  3939 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-11 11:56:14.262  3860  3870 D BluetoothPan: onBluetoothStateChange on: true
,09-11 11:56:14.262   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-11 11:56:14.262  3939  3939 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-11 11:56:14.262   872   872 D BluetoothA2dp: Proxy object connected
09-11 11:56:14.263  3860  3871 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-11 11:56:14.263  3939  3939 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:14.264   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-11 11:56:14.265   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-11 11:56:14.267  3939  3939 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:14.267  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:14.268  3939  3939 D ObexServerSockets: Succeed to create listening sockets 
09-11 11:56:14.268  3939  3939 D ObexServerSockets0: startAccept()
09-11 11:56:14.268  3939  3939 D ObexServerSockets0: prepareForNewConnect()
09-11 11:56:14.269  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:14.269  3860  3860 D LocalBluetoothProfileManager: Adding local A2DP profile
09-11 11:56:14.270  3939  3939 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-11 11:56:14.270  3939  3939 D BluetoothSdpJni: SDP Create record success - handle: 0
09-11 11:56:14.270  3939  3939 D BluetoothMapService: onReceive
09-11 11:56:14.270  3939  3939 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:14.271  3939  4125 D ObexServerSockets0: Accepting socket connection...
09-11 11:56:14.271  3939  3939 D BluetoothMapService: STATE_ON
09-11 11:56:14.271  3939  4124 D ObexServerSockets0: Accepting socket connection...
09-11 11:56:14.272  3860  3860 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-11 11:56:14.282  3860  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-11 11:56:14.286  3860  3860 D BluetoothA2dp: Proxy object connected
,09-11 11:56:14.289  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-11 11:56:14.294  3860  3860 D DockEventReceiver: finishStartingService: stopping service
,09-11 11:56:14.297  3860  3860 D BluetoothPbap: Proxy object connected
09-11 11:56:14.297  1374  1374 D BluetoothPbap: Proxy object connected
09-11 11:56:14.297  1374  1374 D PbapServerProfile: Bluetooth service connected
09-11 11:56:14.297  3860  3860 D PbapServerProfile: Bluetooth service connected
09-11 11:56:14.298  3939  3939 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-11 11:56:14.298  3939  3939 D ObexServerSockets0: prepareForNewConnect()
,09-11 11:56:14.305  3939  4129 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-11 11:56:14.317  3939  4133 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-11 11:56:14.318  3939  4133 I BtOppRfcommListener: Accept thread started.
,09-11 11:56:14.353  1948  1963 D BluetoothHeadset: Proxy object connected
,09-11 11:56:14.353   872   872 D BluetoothHeadset: Proxy object connected
09-11 11:56:14.353  1374  2059 D BluetoothHeadset: Proxy object connected
09-11 11:56:14.353  1374  1374 D HeadsetProfile: Bluetooth service connected
09-11 11:56:14.354   872   872 D BluetoothHeadset: Proxy object connected
,09-11 11:56:14.354   872   872 D BluetoothHeadset: Proxy object connected
,09-11 11:56:14.354  1374  1387 D BluetoothHeadset: Proxy object connected
,09-11 11:56:14.354   872   889 D BluetoothHeadset: Proxy object connected
09-11 11:56:14.355  1374  1374 D HeadsetProfile: Bluetooth service connected
,09-11 11:56:14.365   872   889 D BluetoothHeadset: Proxy object connected
,09-11 11:56:14.375  3860  3870 D BluetoothHeadset: Proxy object connected
,09-11 11:56:14.376  3860  3860 D HeadsetProfile: Bluetooth service connected
,09-11 11:56:15.852  3939  4097 D BluetoothAdapterState: Current state: ON, message: 23
,09-11 11:56:15.852  3939  4097 D BluetoothAdapterProperties: Setting state to 13
,09-11 11:56:15.853  3939  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-11 11:56:15.855  3939  4097 D BluetoothAdapterProperties: onBluetoothDisable()
,09-11 11:56:15.865  3939  3939 D BluetoothMapService: onReceive
,09-11 11:56:15.866  3939  3939 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:15.866  3939  3939 D BluetoothMapService: STATE_TURNING_OFF
09-11 11:56:15.867  3939  3939 D BluetoothMapService: MAP Service closeService in
,09-11 11:56:15.867  3939  3939 D BluetoothMapMasInstance0: MAP Service shutdown
,09-11 11:56:15.867  3939  4097 I BluetoothAdapterState: Entering PendingCommandState
09-11 11:56:15.867  3939  3939 D ObexServerSockets0: shutdown(block = true)
,09-11 11:56:15.868  3939  4124 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-11 11:56:15.870  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:15.870  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:15.870  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:15.870  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:15.870  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:15.870  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:15.870  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:15.870  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:15.870  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:15.871  3939  3939 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-11 11:56:15.872  3939  3939 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-11 11:56:15.873  3939  4125 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-11 11:56:15.873  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:15.874  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:15.874   872  1307 D ConnectivityService: handlePromptUnvalidated 101
09-11 11:56:15.875  3939  4110 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-11 11:56:15.879  3939  3939 I BtOppRfcommListener: stopping Accept Thread
,09-11 11:56:15.880  3939  4133 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-11 11:56:15.882  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:15.883  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:15.883  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:15.883  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:15.883  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:15.883  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:15.883  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:15.883  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:15.883  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:15.883  3939  4133 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-11 11:56:15.884  3790  3790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:15.884  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:15.884  3939  4101 D BluetoothAdapterProperties: Scan Mode:20,
,09-11 11:56:15.884  3860  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-11 11:56:15.885  3939  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-11 11:56:15.886  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:15.887  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:15.889  3939  3939 D HeadsetService: Received stop request...Stopping profile...
09-11 11:56:15.893  3939  3939 D A2dpService: Received stop request...Stopping profile...
09-11 11:56:15.893  3939  4117 D A2dpStateMachine: Exit Disconnected: -1
,09-11 11:56:15.892  1948  1964 D BluetoothHeadset: Proxy object disconnected
,09-11 11:56:15.896   872   872 D BluetoothHeadset: Proxy object disconnected
09-11 11:56:15.896  3860  3870 D BluetoothHeadset: Proxy object disconnected
09-11 11:56:15.897  1374  3789 D BluetoothHeadset: Proxy object disconnected
,09-11 11:56:15.898  3939  3939 V BluetoothAdapterState: isTurningOff()=true
09-11 11:56:15.898   872   872 D BluetoothHeadset: Proxy object disconnected
09-11 11:56:15.898  3939  3939 V BluetoothAdapterState: isTurningOn()=false
09-11 11:56:15.898   872   872 D BluetoothHeadset: Proxy object disconnected
,09-11 11:56:15.898  3939  3939 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:15.898  3939  3939 V BluetoothAdapterState: isBleTurningOff()=false
09-11 11:56:15.898   872   872 D BluetoothA2dp: Proxy object disconnected
,09-11 11:56:15.899  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-11 11:56:15.900  3939  3939 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-11 11:56:15.900  3939  3939 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-11 11:56:15.900  3939  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-11 11:56:15.900  3939  4108 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-11 11:56:15.900  3939  4108 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-11 11:56:15.901  3939  4108 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-11 11:56:15.901  3939  3939 D HidService: Received stop request...Stopping profile...
09-11 11:56:15.901  3939  3939 D HidService: Stopping Bluetooth HidService
09-11 11:56:15.901  3939  4101 E bt_btif : btif_hf_upstreams_evt: Invalid index 17,
09-11 11:56:15.906  3939  3939 D HealthService: Received stop request...Stopping profile...
09-11 11:56:15.906  1374  1374 D HeadsetProfile: Bluetooth service disconnected
09-11 11:56:15.907  1374  1374 D BluetoothA2dp: Proxy object disconnected
,09-11 11:56:15.907  1374  1374 D BluetoothInputDevice: Proxy object disconnected
09-11 11:56:15.907  1374  1374 D HidProfile: Bluetooth service disconnected
09-11 11:56:15.907  1374  1374 D BluetoothPbap: Proxy object disconnected
09-11 11:56:15.907  1374  1374 D PbapServerProfile: Bluetooth service disconnected
,09-11 11:56:15.908  3939  3939 V BluetoothAdapterState: isTurningOff()=true
09-11 11:56:15.908  3939  3939 V BluetoothAdapterState: isTurningOn()=false
09-11 11:56:15.908  3939  3939 V BluetoothAdapterState: isBleTurningOn()=false
,09-11 11:56:15.908  3939  3939 V BluetoothAdapterState: isBleTurningOff()=false
09-11 11:56:15.909  3939  3939 D PanService: Received stop request...Stopping profile...
,09-11 11:56:15.909  3860  3860 D DockEventReceiver: finishStartingService: stopping service
09-11 11:56:15.909  1374  1374 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-11 11:56:15.909  1374  1374 D PanProfile: Bluetooth service disconnected
,09-11 11:56:15.910  3860  3860 D HeadsetProfile: Bluetooth service disconnected
09-11 11:56:15.910  3860  3860 D BluetoothA2dp: Proxy object disconnected
,09-11 11:56:15.911  3939  4108 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-11 11:56:15.911  3939  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-11 11:56:15.911  3860  3860 D BluetoothInputDevice: Proxy object disconnected
,09-11 11:56:15.911  3860  3860 D HidProfile: Bluetooth service disconnected
,09-11 11:56:15.911  3939  4108 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-11 11:56:15.911  3939  4108 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-11 11:56:15.911  3939  4108 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:15.911  3860  3860 D BluetoothPbap: Proxy object disconnected
,09-11 11:56:15.911  3939  4108 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-11 11:56:15.911  3860  3860 D PbapServerProfile: Bluetooth service disconnected
09-11 11:56:15.911  3939  4108 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:15.912  3939  3939 D BluetoothMapService: Received stop request...Stopping profile...
09-11 11:56:15.912  3939  3939 D BluetoothMapService: stop()
09-11 11:56:15.913  3939  3939 D BluetoothMapAppObserver: deinitObservers()
,09-11 11:56:15.913  3939  3939 D BluetoothMapAppObserver: removeReceiver()
09-11 11:56:15.914  3860  3860 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-11 11:56:15.914  3860  3860 D PanProfile: Bluetooth service disconnected
,09-11 11:56:15.914  3860  3860 D BluetoothMap: Proxy object disconnected
09-11 11:56:15.914  3860  3860 D MapProfile: Bluetooth service disconnected
09-11 11:56:15.915  1374  1374 D BluetoothMap: Proxy object disconnected
09-11 11:56:15.915  1374  1374 D MapProfile: Bluetooth service disconnected
,09-11 11:56:15.915  3939  3939 V BluetoothAdapterState: isTurningOff()=true
,09-11 11:56:15.916  3939  3939 V BluetoothAdapterState: isTurningOn()=false
09-11 11:56:15.916  3939  3939 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:15.916  3939  3939 V BluetoothAdapterState: isBleTurningOff()=false
09-11 11:56:15.917  3939  3939 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-11 11:56:15.917  3939  3939 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-11 11:56:15.917  3939  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-11 11:56:15.917  3939  3939 V BluetoothAdapterState: isTurningOff()=true
09-11 11:56:15.918  3939  3939 V BluetoothAdapterState: isTurningOn()=false
09-11 11:56:15.918  3939  3939 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:15.918  3939  3939 V BluetoothAdapterState: isBleTurningOff()=false
,09-11 11:56:15.918  3939  3939 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-11 11:56:15.918  3939  4101 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-11 11:56:15.918  3939  3939 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-11 11:56:15.918  3939  3939 V BluetoothAdapterState: isTurningOff()=true
,09-11 11:56:15.918  3939  3939 V BluetoothAdapterState: isTurningOn()=false
09-11 11:56:15.918  3939  3939 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:15.919  3939  3939 V BluetoothAdapterState: isBleTurningOff()=false
,09-11 11:56:15.920  3939  3939 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-11 11:56:15.920  3939  3939 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-11 11:56:15.921  3939  3939 D BluetoothMapService: MAP Service closeService in
09-11 11:56:15.921  3939  3939 V BluetoothAdapterState: isTurningOff()=true
,09-11 11:56:15.921  3939  3939 V BluetoothAdapterState: isTurningOn()=false
09-11 11:56:15.921  3939  3939 V BluetoothAdapterState: isBleTurningOn()=false
,09-11 11:56:15.921  3939  3939 V BluetoothAdapterState: isBleTurningOff()=false
,09-11 11:56:15.921  3939  3939 D BluetoothMapService: cleanup()
,09-11 11:56:15.921  3939  3939 D BluetoothMapService: MAP Service closeService in
09-11 11:56:15.921  3939  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-11 11:56:15.922  3939  4097 D BluetoothAdapterProperties: Setting state to 15
09-11 11:56:15.922  3939  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-11 11:56:15.922  3939  4097 I BluetoothAdapterState: Entering BleOnState
09-11 11:56:15.923  1374  1388 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-11 11:56:15.924   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:15.924  1948  2201 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:15.924  3860  3871 D BluetoothA2dp: onBluetoothStateChange: up=false
09-11 11:56:15.925  3860  3870 D BluetoothPbap: onBluetoothStateChange: up=false
09-11 11:56:15.925  1374  1387 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:15.925  3860  3871 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:15.926   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:15.926  1374  3789 D BluetoothMap: onBluetoothStateChange: up=false
09-11 11:56:15.926  3860  3870 D BluetoothMap: onBluetoothStateChange: up=false
09-11 11:56:15.927  1374  2059 D BluetoothPbap: onBluetoothStateChange: up=false
09-11 11:56:15.927  1374  1388 D BluetoothA2dp: onBluetoothStateChange: up=false
09-11 11:56:15.928  1374  1387 D BluetoothPan: onBluetoothStateChange on: false
09-11 11:56:15.930  3860  3871 D BluetoothPan: onBluetoothStateChange on: false
09-11 11:56:15.930   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-11 11:56:15.931  3860  3870 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-11 11:56:15.933   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-11 11:56:15.933  3939  4097 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-11 11:56:15.933  3939  4097 D BluetoothAdapterProperties: Setting state to 16
09-11 11:56:15.933  3939  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-11 11:56:15.934  3939  4097 D BluetoothAdapterProperties: onBleDisable
09-11 11:56:15.935  3939  4097 I BluetoothAdapterState: Entering PendingCommandState
09-11 11:56:15.935  3939  4098 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-11 11:56:15.936  3939  4101 D BluetoothAdapterProperties: Scan Mode:20
09-11 11:56:15.937  3939  4108 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-11 11:56:15.937  3939  4108 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-11 11:56:15.939  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:15.939  3860  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-11 11:56:15.940  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:15.941  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:15.942  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:15.944  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-11 11:56:15.951  3860  3860 D DockEventReceiver: finishStartingService: stopping service
,09-11 11:56:16.138  3939  4101 I bt_hci  : shut_down
09-11 11:56:16.139  3939  4105 D bt_hwcfg: hw_epilog_process
,09-11 11:56:16.140  3939  4105 I bt_vendor: low_power_mode_cb
,09-11 11:56:16.163  3939  4105 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-11 11:56:16.163  3939  4105 I bt_vendor: epilog_cb
09-11 11:56:16.164  3939  4105 I bt_hci  : epilog_finished_callback
,09-11 11:56:16.174  3939  4101 I bt_hci_h4: hal_close
,09-11 11:56:16.176  3939  4101 I bt_userial_vendor: device fd = 51 close
,09-11 11:56:16.310  3939  4098 D bt_stack_manager: event_shut_down_stack finished.
,09-11 11:56:16.311  3939  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-11 11:56:16.317  3939  4097 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-11 11:56:16.317  3939  3939 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-11 11:56:16.319  3939  3939 D BtGatt.GattService: Received stop request...Stopping profile...
,09-11 11:56:16.319  3939  3939 D BtGatt.GattService: stop()
,09-11 11:56:16.320  3939  3939 D BtGatt.AdvertiseManager: advertise clients cleared
,09-11 11:56:16.325  3939  3939 V BluetoothAdapterState: isTurningOff()=false
09-11 11:56:16.325  3939  3939 V BluetoothAdapterState: isTurningOn()=false
,09-11 11:56:16.326  3939  3939 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:16.326  3939  3939 V BluetoothAdapterState: isBleTurningOff()=true
,09-11 11:56:16.328  3939  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-11 11:56:16.328  3939  4097 D BluetoothAdapterProperties: Setting state to 10
09-11 11:56:16.329  3939  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-11 11:56:16.331  3939  4097 I BluetoothAdapterState: Entering OffState
09-11 11:56:16.332   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-11 11:56:16.357  3939  3939 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-11 11:56:16.358  3939  3939 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-11 11:56:16.358  3939  4098 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-11 11:56:16.364  3939  3939 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-11 11:56:16.371  3939  4098 D bt_stack_manager: event_clean_up_stack finished.
,09-11 11:56:16.376  3939  3939 I art     : System.exit called, status: 0
,09-11 11:56:16.377  3939  3939 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-11 11:56:16.440   872  2204 I ActivityManager: Process com.android.bluetooth (pid 3939) has died
,09-11 11:56:18.849  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
,09-11 11:56:18.849  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:21.858  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-11 11:56:21.859  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6555c68 added. We now have 6 listener(s)
,09-11 11:56:21.859  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:21.863  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-11 11:56:21.863  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f03881 added. We now have 7 listener(s)
,09-11 11:56:21.863  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:21.865  3790  3841 I System.out: IsBluetoothEnabled
,09-11 11:56:21.877  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:21.929   872   889 I ActivityManager: Start proc 4144:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-11 11:56:22.058  4144  4144 D AdapterServiceConfig: Adding HeadsetService
09-11 11:56:22.058  4144  4144 D AdapterServiceConfig: Adding A2dpService
,09-11 11:56:22.058  4144  4144 D AdapterServiceConfig: Adding HidService
09-11 11:56:22.058  4144  4144 D AdapterServiceConfig: Adding HealthService
09-11 11:56:22.058  4144  4144 D AdapterServiceConfig: Adding PanService
,09-11 11:56:22.059  4144  4144 D AdapterServiceConfig: Adding GattService
09-11 11:56:22.059  4144  4144 D AdapterServiceConfig: Adding BluetoothMapService
,09-11 11:56:22.075  4144  4144 D BluetoothAdapterState: make() - Creating AdapterState
09-11 11:56:22.075   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@710dd53:true
,09-11 11:56:22.080  4144  4144 I bt_bluedroid: init
,09-11 11:56:22.080  4144  4156 I BluetoothAdapterState: Entering OffState
,09-11 11:56:22.082  4144  4157 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-11 11:56:22.082  4144  4157 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-11 11:56:22.082  4144  4157 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-11 11:56:22.083  4144  4157 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-11 11:56:22.083  4144  4144 I bt_bluedroid: get_profile_interface socket
,09-11 11:56:22.085  4144  4144 I bt_bluedroid: get_profile_interface sdp
,09-11 11:56:22.090  4144  4160 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-11 11:56:22.091  4144  4155 I bt_bluedroid: config_hci_snoop_log
09-11 11:56:22.093  4144  4160 D BluetoothAdapterProperties: Name is: Nexus 6
09-11 11:56:22.095   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-11 11:56:22.105  4144  4156 D BluetoothAdapterState: Current state: OFF, message: 0
09-11 11:56:22.106  4144  4156 D BluetoothAdapterProperties: Setting state to 14
09-11 11:56:22.106  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-11 11:56:22.108  4144  4156 D BluetoothBondStateMachine: make
,09-11 11:56:22.112  4144  4161 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-11 11:56:22.118  4144  4144 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-11 11:56:22.119  4144  4156 I BluetoothAdapterState: Entering PendingCommandState
,09-11 11:56:22.121  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
,09-11 11:56:22.122  4144  4144 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-11 11:56:22.122  4144  4144 D BtGatt.GattService: Received start request. Starting profile...
,09-11 11:56:22.122  4144  4144 D BtGatt.GattService: start()
,09-11 11:56:22.123  4144  4144 I bt_bluedroid: get_profile_interface gatt
,09-11 11:56:22.123  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
09-11 11:56:22.124  4144  4144 D BtGatt.AdvertiseManager: advertise manager created
,09-11 11:56:22.132  4144  4144 V BluetoothAdapterState: isTurningOff()=false
,09-11 11:56:22.133  4144  4144 V BluetoothAdapterState: isTurningOn()=false
,09-11 11:56:22.133  4144  4144 V BluetoothAdapterState: isBleTurningOn()=true
09-11 11:56:22.133  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
,09-11 11:56:22.133  4144  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-11 11:56:22.134  4144  4156 I bt_bluedroid: enable
,09-11 11:56:22.134  4144  4157 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-11 11:56:22.135  4144  4157 I bt_hci  : start_up
,09-11 11:56:22.141  4144  4157 I bt_vendor: alloc value 0xb3a6c189
,09-11 11:56:22.141  4144  4157 I bt_vendor: init
09-11 11:56:22.141  4144  4157 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-11 11:56:22.141  4144  4157 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-11 11:56:22.247  4144  4157 D bt_hci  : start_up starting async portion
09-11 11:56:22.248  4144  4164 I bt_hci  : event_finish_startup
09-11 11:56:22.248  4144  4164 I bt_hci_h4: hal_open
09-11 11:56:22.248  4144  4164 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-11 11:56:22.258  4144  4164 I bt_userial_vendor: device fd = 51 open,
,09-11 11:56:22.290  4144  4164 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-11 11:56:22.321  4144  4164 D bt_hwcfg: Chipset BCM4354A2
,09-11 11:56:22.321  4144  4164 D bt_hwcfg: Target name = [BCM4354A2]
,09-11 11:56:22.323  4144  4164 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-11 11:56:23.005  4144  4164 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-11 11:56:23.007  4144  4164 D bt_hwcfg: Settlement delay -- 100 ms
,09-11 11:56:23.007  4144  4164 I bt_hwcfg: Setting fw settlement delay to 100 ,
,09-11 11:56:23.123  4144  4164 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-11 11:56:23.125  4144  4164 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-11 11:56:23.154  4144  4164 I bt_hwcfg: vendor lib fwcfg completed
,09-11 11:56:23.154  4144  4164 I bt_vendor: firmware callback
09-11 11:56:23.155  4144  4164 I bt_hci  : firmware_config_callback
,09-11 11:56:23.165  4144  4166 I bt_btu  : btu_task pending for preload complete event
09-11 11:56:23.166  4144  4166 I bt_btu_task: Bluetooth chip preload is complete
09-11 11:56:23.166  4144  4166 I bt_btu  : btu_task received preload complete event
,09-11 11:56:23.177  4144  4166 I         : BTE_InitTraceLevels -- TRC_HCI
09-11 11:56:23.177  4144  4166 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-11 11:56:23.177  4144  4166 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-11 11:56:23.178  4144  4166 I         : BTE_InitTraceLevels -- TRC_AVDT
09-11 11:56:23.178  4144  4166 I         : BTE_InitTraceLevels -- TRC_AVRC
09-11 11:56:23.178  4144  4166 I         : BTE_InitTraceLevels -- TRC_A2D
,09-11 11:56:23.179  4144  4166 I         : BTE_InitTraceLevels -- TRC_BNEP
09-11 11:56:23.179  4144  4166 I         : BTE_InitTraceLevels -- TRC_BTM
09-11 11:56:23.179  4144  4166 I         : BTE_InitTraceLevels -- TRC_GAP
,09-11 11:56:23.179  4144  4166 I         : BTE_InitTraceLevels -- TRC_PAN
09-11 11:56:23.180  4144  4166 I         : BTE_InitTraceLevels -- TRC_SDP
,09-11 11:56:23.180  4144  4166 I         : BTE_InitTraceLevels -- TRC_GATT
,09-11 11:56:23.180  4144  4166 I         : BTE_InitTraceLevels -- TRC_SMP
09-11 11:56:23.180  4144  4166 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-11 11:56:23.181  4144  4166 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-11 11:56:23.319  4144  4166 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39e9d9d
,09-11 11:56:23.319  4144  4166 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39e9d9d 
,09-11 11:56:23.328  4144  4160 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-11 11:56:23.331  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-11 11:56:23.333  4144  4160 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-11 11:56:23.336  4144  4160 D BluetoothAdapterProperties: Name is: Nexus 6
,09-11 11:56:23.340  4144  4160 D BluetoothAdapterProperties: Scan Mode:20
,09-11 11:56:23.340  4144  4160 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-11 11:56:23.341  4144  4160 D bt_hci  : do_postload posting postload work item
,09-11 11:56:23.343  4144  4164 I bt_hci  : event_postload
,09-11 11:56:23.343  4144  4164 I bt_vendor: sco_config_cb
,09-11 11:56:23.343  4144  4164 I bt_hci  : sco_config_callback postload finished.
,09-11 11:56:23.344  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:23.346  4144  4160 D bt_bte_conf: Device ID record 1 : primary
,09-11 11:56:23.347  4144  4160 D bt_bte_conf:   vendorId            = 000f
09-11 11:56:23.347  4144  4160 D bt_bte_conf:   vendorIdSource      = 0001
,09-11 11:56:23.347  4144  4160 D bt_bte_conf:   product             = 1200
09-11 11:56:23.347  4144  4160 D bt_bte_conf:   version             = 1436
,09-11 11:56:23.347  4144  4160 D bt_bte_conf:   clientExecutableURL = 
,09-11 11:56:23.348  4144  4160 D bt_bte_conf:   serviceDescription  = 
09-11 11:56:23.348  4144  4160 D bt_bte_conf:   documentationURL    = 
09-11 11:56:23.348  4144  4160 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-11 11:56:23.349  4144  4157 D bt_stack_manager: event_start_up_stack finished
09-11 11:56:23.350  4144  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-11 11:56:23.350  4144  4164 I bt_vendor: low_power_mode_cb
09-11 11:56:23.351  4144  4156 D BluetoothAdapterProperties: Setting state to 15,
09-11 11:56:23.351  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-11 11:56:23.352  4144  4156 I BluetoothAdapterState: Entering BleOnState
09-11 11:56:23.357  4144  4156 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-11 11:56:23.357  4144  4156 D BluetoothAdapterProperties: Setting state to 11,
09-11 11:56:23.357  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-11 11:56:23.364  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:23.367  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
,09-11 11:56:23.367  4144  4144 D HeadsetService: Received start request. Starting profile...
09-11 11:56:23.370  4144  4144 I BluetoothHeadsetServiceJni: classInitNative: succeeds,
09-11 11:56:23.370  4144  4144 D HeadsetStateMachine: make
,09-11 11:56:23.375  4144  4156 I BluetoothAdapterState: Entering PendingCommandState
,09-11 11:56:23.378  4144  4144 D HeadsetStateMachine: max_hf_connections = 1
,09-11 11:56:23.378  4144  4144 I bt_bluedroid: get_profile_interface handsfree
,09-11 11:56:23.378  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-11 11:56:23.378  4144  4160 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-11 11:56:23.382  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
,09-11 11:56:23.382  4144  4144 D A2dpService: Received start request. Starting profile...
,09-11 11:56:23.383  4144  4144 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-11 11:56:23.383  4144  4144 I bt_bluedroid: get_profile_interface avrcp
,09-11 11:56:23.390  4144  4144 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-11 11:56:23.390  4144  4144 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-11 11:56:23.390  4144  4144 D A2dpStateMachine: make
,09-11 11:56:23.392  4144  4144 I bt_bluedroid: get_profile_interface a2dp
,09-11 11:56:23.392  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-11 11:56:23.394  4144  4175 D A2dpStateMachine: Enter Disconnected: -2
,09-11 11:56:23.396  4144  4144 I BluetoothHidServiceJni: classInitNative: succeeds
,09-11 11:56:23.398  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
,09-11 11:56:23.396  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-11 11:56:23.399  4144  4144 D HidService: Received start request. Starting profile...
09-11 11:56:23.399  4144  4144 I bt_bluedroid: get_profile_interface hidhost
09-11 11:56:23.399  4144  4144 D HidService: setHidService(): set to: null
09-11 11:56:23.399  4144  4160 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39cb3e5
09-11 11:56:23.399  4144  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-11 11:56:23.400  4144  4144 I BluetoothHealthServiceJni: classInitNative: succeeds
09-11 11:56:23.401  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
09-11 11:56:23.401  4144  4144 D HealthService: Received start request. Starting profile...
,09-11 11:56:23.404  4144  4144 I bt_bluedroid: get_profile_interface health
,09-11 11:56:23.404  4144  4144 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-11 11:56:23.405  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
09-11 11:56:23.406  4144  4144 D PanService: Received start request. Starting profile...
09-11 11:56:23.406  4144  4144 D BluetoothPanServiceJni: initializeNative(L110): pan
09-11 11:56:23.406  4144  4144 I bt_bluedroid: get_profile_interface pan
,09-11 11:56:23.406  4144  4160 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-11 11:56:23.410  4144  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
,09-11 11:56:23.410  4144  4144 D BluetoothMapService: Received start request. Starting profile...
09-11 11:56:23.411  4144  4144 D BluetoothMapService: start()
,09-11 11:56:23.413  4144  4144 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-11 11:56:23.416  4144  4144 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-11 11:56:23.417  4144  4144 D BluetoothMapAppObserver: createReceiver()
09-11 11:56:23.418  4144  4144 D BluetoothMapAppObserver: initObservers()
09-11 11:56:23.418  4144  4144 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-11 11:56:23.427  4144  4144 V BluetoothAdapterState: isTurningOff()=false
,09-11 11:56:23.427  4144  4144 V BluetoothAdapterState: isTurningOn()=true
09-11 11:56:23.427  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:23.428  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
,09-11 11:56:23.430  4144  4144 V BluetoothAdapterState: isTurningOff()=false
09-11 11:56:23.430  4144  4144 V BluetoothAdapterState: isTurningOn()=true
09-11 11:56:23.430  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
,09-11 11:56:23.430  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-11 11:56:23.430  4144  4173 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-11 11:56:23.430  4144  4144 V BluetoothAdapterState: isTurningOff()=false
09-11 11:56:23.430  4144  4144 V BluetoothAdapterState: isTurningOn()=true
09-11 11:56:23.430  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
09-11 11:56:23.430  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
,09-11 11:56:23.433  4144  4144 V BluetoothAdapterState: isTurningOff()=false
,09-11 11:56:23.433  4144  4144 V BluetoothAdapterState: isTurningOn()=true
,09-11 11:56:23.433  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
,09-11 11:56:23.433  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
,09-11 11:56:23.433  4144  4144 V BluetoothAdapterState: isTurningOff()=false
,09-11 11:56:23.434  4144  4144 V BluetoothAdapterState: isTurningOn()=true
09-11 11:56:23.434  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
,09-11 11:56:23.434  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
09-11 11:56:23.434  4144  4144 V BluetoothAdapterState: isTurningOff()=false
09-11 11:56:23.434  4144  4144 V BluetoothAdapterState: isTurningOn()=true
,09-11 11:56:23.434  4144  4144 V BluetoothAdapterState: isBleTurningOn()=false
,09-11 11:56:23.434  4144  4144 V BluetoothAdapterState: isBleTurningOff()=false
,09-11 11:56:23.435  4144  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-11 11:56:23.435  4144  4156 D BluetoothAdapterProperties: ScanMode =  20
,09-11 11:56:23.435  4144  4156 D BluetoothAdapterProperties: State =  11
,09-11 11:56:23.436  4144  4156 D BluetoothAdapterProperties: Setting state to 12
09-11 11:56:23.436  4144  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-11 11:56:23.437  1374  3789 D BluetoothInputDevice: onBluetoothStateChange: up=true,
09-11 11:56:23.437  4144  4160 D BluetoothAdapterProperties: Scan Mode:21
09-11 11:56:23.437  4144  4160 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-11 11:56:23.438  4144  4156 I BluetoothAdapterState: Entering OnState
09-11 11:56:23.440   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-11 11:56:23.440  1374  1374 D BluetoothInputDevice: Proxy object connected
09-11 11:56:23.440  1374  1374 D HidProfile: Bluetooth service connected
,09-11 11:56:23.440  1948  2201 D BluetoothHeadset: onBluetoothStateChange: up=true
09-11 11:56:23.441  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:23.441  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:23.441  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:23.441  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:23.441  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:23.441  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:23.441  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:23.441  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:23.443  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:23.445  4144  4144 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-11 11:56:23.446  4144  4144 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-11 11:56:23.447  4144  4144 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:23.449  3860  3871 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-11 11:56:23.451  4144  4144 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:23.451  3860  3870 D BluetoothPbap: onBluetoothStateChange: up=true
,09-11 11:56:23.452  4144  4144 D ObexServerSockets: Succeed to create listening sockets 
,09-11 11:56:23.453  4144  4144 D ObexServerSockets0: startAccept()
,09-11 11:56:23.453  4144  4144 D ObexServerSockets0: prepareForNewConnect()
09-11 11:56:23.454  1374  1387 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-11 11:56:23.455  4144  4144 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-11 11:56:23.455  4144  4144 D BluetoothSdpJni: SDP Create record success - handle: 0
09-11 11:56:23.455  3860  3871 D BluetoothHeadset: onBluetoothStateChange: up=true
09-11 11:56:23.456   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-11 11:56:23.457  4144  4181 D ObexServerSockets0: Accepting socket connection...
,09-11 11:56:23.457  4144  4182 D ObexServerSockets0: Accepting socket connection...
09-11 11:56:23.458  1374  3789 D BluetoothMap: onBluetoothStateChange: up=true
09-11 11:56:23.458  3860  3860 D BluetoothA2dp: Proxy object connected
,09-11 11:56:23.460  3860  3871 D BluetoothMap: onBluetoothStateChange: up=true
09-11 11:56:23.461  1374  1374 D BluetoothMap: Proxy object connected
09-11 11:56:23.461  1374  1374 D MapProfile: Bluetooth service connected
,09-11 11:56:23.461  1374  1374 D BluetoothMap: getConnectedDevices()
,09-11 11:56:23.462  1374  2059 D BluetoothPbap: onBluetoothStateChange: up=true
,09-11 11:56:23.464  3860  3860 D BluetoothMap: Proxy object connected
09-11 11:56:23.464  3860  3860 D MapProfile: Bluetooth service connected
,09-11 11:56:23.465  3860  3860 D BluetoothMap: getConnectedDevices()
,09-11 11:56:23.466  1374  1387 D BluetoothA2dp: onBluetoothStateChange: up=true
09-11 11:56:23.468  1374  1374 D BluetoothA2dp: Proxy object connected
,09-11 11:56:23.468  1374  1388 D BluetoothPan: onBluetoothStateChange on: true
09-11 11:56:23.470  3860  3870 D BluetoothPan: onBluetoothStateChange on: true
,09-11 11:56:23.471  1374  1374 D BluetoothPan: BluetoothPAN Proxy object connected
09-11 11:56:23.471  1374  1374 D PanProfile: Bluetooth service connected
09-11 11:56:23.472   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-11 11:56:23.472   872   872 D BluetoothA2dp: Proxy object connected
09-11 11:56:23.472  3860  4183 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-11 11:56:23.474   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-11 11:56:23.475  3860  3860 D BluetoothPan: BluetoothPAN Proxy object connected
09-11 11:56:23.476  3860  3860 D PanProfile: Bluetooth service connected
,09-11 11:56:23.476  3860  3860 D BluetoothInputDevice: Proxy object connected
,09-11 11:56:23.476  3860  3860 D HidProfile: Bluetooth service connected
09-11 11:56:23.477   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,09-11 11:56:23.478  4144  4144 D BluetoothMapService: onReceive
,09-11 11:56:23.478  4144  4144 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:23.478  4144  4144 D BluetoothMapService: STATE_ON
09-11 11:56:23.480  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:23.489  3860  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-11 11:56:23.499  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-11 11:56:23.501  3860  3860 D DockEventReceiver: finishStartingService: stopping service
,09-11 11:56:23.507  3860  3860 D BluetoothPbap: Proxy object connected
,09-11 11:56:23.507  1374  1374 D BluetoothPbap: Proxy object connected
09-11 11:56:23.507  3860  3860 D PbapServerProfile: Bluetooth service connected
09-11 11:56:23.507  4144  4144 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-11 11:56:23.507  1374  1374 D PbapServerProfile: Bluetooth service connected
09-11 11:56:23.507  4144  4144 D ObexServerSockets0: prepareForNewConnect()
,09-11 11:56:23.516  4144  4188 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-11 11:56:23.529  4144  4192 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-11 11:56:23.530  4144  4192 I BtOppRfcommListener: Accept thread started.
,09-11 11:56:23.542  1948  2097 D BluetoothHeadset: Proxy object connected
,09-11 11:56:23.542   872   872 D BluetoothHeadset: Proxy object connected
,09-11 11:56:23.542  3860  3871 D BluetoothHeadset: Proxy object connected
,09-11 11:56:23.543  1374  1387 D BluetoothHeadset: Proxy object connected
09-11 11:56:23.543  1374  1374 D HeadsetProfile: Bluetooth service connected
,09-11 11:56:23.543  1948  1963 D BluetoothHeadset: Proxy object connected
,09-11 11:56:23.543   872   872 D BluetoothHeadset: Proxy object connected
09-11 11:56:23.544   872   872 D BluetoothHeadset: Proxy object connected
09-11 11:56:23.544  3860  3860 D HeadsetProfile: Bluetooth service connected
,09-11 11:56:23.555  1374  3789 D BluetoothHeadset: Proxy object connected
,09-11 11:56:23.555  1374  1374 D HeadsetProfile: Bluetooth service connected
,09-11 11:56:23.555  3860  4183 D BluetoothHeadset: Proxy object connected
,09-11 11:56:23.556  3860  3860 D HeadsetProfile: Bluetooth service connected
,09-11 11:56:23.558   872   889 D BluetoothHeadset: Proxy object connected
,09-11 11:56:23.575   872   889 D BluetoothHeadset: Proxy object connected
,09-11 11:56:23.900  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:23.900  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:23.900  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:23.900  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:23.900  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:23.900  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:23.900  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:23.900  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:23.907  3790  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:23.911  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-11 11:56:23.911  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@458d26 added. We now have 8 listener(s)
,09-11 11:56:23.911  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:23.918   872  1699 D WifiService: setWifiEnabled: false pid=3790, uid=10000
,09-11 11:56:23.918   872  1699 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-11 11:56:23.931  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:23.932   872  1954 D WifiService: setWifiEnabled: true pid=3790, uid=10000
09-11 11:56:23.933   872  1954 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-11 11:56:23.946   872  1304 D WifiConfigStore: Loading config and enabling all networks 
,09-11 11:56:23.965  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:23.965  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:23.965  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:23.965  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:23.965  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:23.965  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:23.965  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:23.965  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:23.972  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:23.980   872  1304 D WifiConfigStore: loaded 0 passpoint configs
,09-11 11:56:23.981   872  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-11 11:56:23.982   872  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000,
09-11 11:56:23.983   872  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-11 11:56:23.983   872  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-11 11:56:23.983   872  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-11 11:56:23.984   872  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-11 11:56:24.000   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-11 11:56:24.001   872  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.95 rxSuccessRate=1.23 delta 1000 -> 1000
,09-11 11:56:24.002   371   870 D CommandListener: Setting iface cfg
,09-11 11:56:24.004   872  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-11 11:56:24.004   872  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-11 11:56:24.007   872  1303 D WifiNative-HAL: p2pGetDeviceAddress
,09-11 11:56:24.007   872  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-11 11:56:24.029   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-11 11:56:24.029   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-11 11:56:24.038   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-11 11:56:24.112   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-11 11:56:24.115  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-11 11:56:24.571  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-11 11:56:24.613  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-11 11:56:24.614  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-11 11:56:24.623   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-11 11:56:24.636   872  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-11 11:56:24.636   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-11 11:56:24.636   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-11 11:56:24.658   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-11 11:56:24.670   371   870 D CommandListener: Setting iface cfg
,09-11 11:56:24.670   872  1304 D WifiStateMachine: Start Dhcp Watchdog 3
,09-11 11:56:24.688   872  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-11 11:56:24.689   872  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-11 11:56:24.696   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-11 11:56:24.707   872  4201 D DhcpClient: Receive thread started
,09-11 11:56:24.793   872  1304 E native  : do suspend false
,09-11 11:56:24.815   872  2073 D DhcpClient: Broadcasting DHCPDISCOVER
,09-11 11:56:24.832   872  4201 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-11 11:56:24.833   872  2073 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-11 11:56:24.836   872  2073 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-11 11:56:24.849   872  4201 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-11 11:56:24.850   872  2073 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-11 11:56:24.855   371   870 D CommandListener: Setting iface cfg
,09-11 11:56:24.868   872  2073 D DhcpClient: Scheduling renewal in 86399s
,09-11 11:56:24.869   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-11 11:56:24.879   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-11 11:56:24.881   872  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,09-11 11:56:24.883   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-11 11:56:24.884   872  1307 D ConnectivityService: Adding iface wlan0 to network 102
,09-11 11:56:24.901   872  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-11 11:56:24.950  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:24.950  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:24.950  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:24.950  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:24.950  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:24.950  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:24.950  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:24.950  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:24.950   872  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0,
,09-11 11:56:24.951   872  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-11 11:56:24.952   872  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-11 11:56:24.954   872  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-11 11:56:24.956  3790  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:24.956   872  1307 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-11 11:56:24.969  3790  3841 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-11 11:56:24.970   872  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-11 11:56:24.972  3790  3841 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-11 11:56:24.974  3790  3841 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ac3e38e Bundle[{}]
09-11 11:56:24.975  3790  3841 I io.jxcore.node.LifeCycleMonitor: start: OK
09-11 11:56:24.975   872  1307 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-11 11:56:24.975   872  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-11 11:56:24.975   872  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-11 11:56:24.975   872  1307 D ConnectivityService:    accepting network in place of null
09-11 11:56:24.975  3790  3841 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-11 11:56:24.975   872  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-11 11:56:24.976  3790  3841 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-11 11:56:24.976   872  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-11 11:56:24.977  3790  3841 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-11 11:56:24.977   872  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-11 11:56:24.977  3790  3841 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-11 11:56:24.978  3790  3841 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-11 11:56:24.982  3790  3841 I System.out: Running OutgoingSocketThread
,09-11 11:56:24.984  3790  4206 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 415)
,09-11 11:56:24.984   872  4199 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148522, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
09-11 11:56:24.985  3790  4206 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41426,
09-11 11:56:24.985  3790  4206 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-11 11:56:25.004   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-11 11:56:25.038   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-11 11:56:25.048   872  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-11 11:56:25.048   872  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:25.055   872  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-11 11:56:25.056   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-11 11:56:25.062   872  4198 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-11 11:56:25.083  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:25.083  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:25.083  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:25.083  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:25.083  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:25.083  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:25.083  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:25.083  3790  3790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:25.088  3790  3790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:25.093  1723  1723 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-11 11:56:25.099  1723  1723 D SystemUpdateService: onCreate
,09-11 11:56:25.103  1723  1723 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-11 11:56:25.110  1723  4211 I SystemUpdateService: active receiver: enabled
,09-11 11:56:25.119  1723  4211 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-11 11:56:25.125  1723  1723 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-11 11:56:25.131  1723  2524 I iu.UploadsManager: num queued entries: 0
,09-11 11:56:25.131  1723  2524 I iu.UploadsManager: num updated entries: 0
,09-11 11:56:25.132  1723  4211 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-11 11:56:25.132  1723  4211 I SystemUpdateService: now status is 0 (complete)
09-11 11:56:25.132  1723  4211 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-11 11:56:25.133  1723  4211 I SystemUpdateService: file has been verified
09-11 11:56:25.134  1723  4211 I SystemUpdateService: OTA package size = 12249756
,09-11 11:56:25.139  1723  2524 I iu.SyncManager: NEXT; no task
,09-11 11:56:25.142  1723  4211 I SystemUpdateService: showing system update notification
,09-11 11:56:25.143   872  4198 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 11 Sep 2016 09:56:25 GMT], X-Android-Received-Millis=[1473587785142], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473587785114]}
,09-11 11:56:25.144  1723  1723 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-11 11:56:25.145   872  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-11 11:56:25.145  1723  1723 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-11 11:56:25.145   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-11 11:56:25.146   872  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-11 11:56:25.148  3955  3955 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:25.150   872  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-11 11:56:25.156  1723  4214 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-11 11:56:25.156  1723  4214 W BaseAppContext: Using Auth Proxy for data requests.
,09-11 11:56:25.159  1723  4214 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,09-11 11:56:25.160  3955  3955 D SprintDMHelper: simOperator: 
,09-11 11:56:25.160  3955  3955 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-11 11:56:25.184  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-11 11:56:25.186  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-11 11:56:25.208  1723  1723 D SystemUpdateService: onDestroy
,09-11 11:56:25.231  1506  2427 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-11 11:56:25.231  1506  2427 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-11 11:56:25.231  1506  2427 I GLSUser : [GLSUser] Extracting token using key: Auth
09-11 11:56:25.231  1506  2427 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-11 11:56:25.246  1723  4214 E MDM     : [182] SitrepService.a: Error sending sitrep.
,09-11 11:56:25.299  2294  4217 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-11 11:56:25.452  1506  4221 I GCM     : Ack for not saved message 146
,09-11 11:56:25.985  3790  3841 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 416)
,09-11 11:56:25.986  3790  3841 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 416)
,09-11 11:56:25.996  3790  3841 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 421)
,09-11 11:56:25.998  3790  3841 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-11 11:56:25.998  3790  3841 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422),
,09-11 11:56:26.002  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-11 11:56:26.002  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dd67 added. We now have 2 listener(s)
,09-11 11:56:26.004  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-11 11:56:26.004  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:26.004  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:26.004  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:26.004  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@557d714 added. We now have 9 listener(s)
09-11 11:56:26.004  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:26.005  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-11 11:56:26.008  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:26.017  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:26.017  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:26.017  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:26.017  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:26.017  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:26.017  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:26.017  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:26.017  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:26.022  3790  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:26.022  3790  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:26.022  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:26.023  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eed55b2 added. We now have 3 listener(s)
09-11 11:56:26.024  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-11 11:56:26.024  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-11 11:56:26.024  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:26.025  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:26.025  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d5e903 added. We now have 10 listener(s)
09-11 11:56:26.025  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:26.025  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:26.025  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:26.025  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:26.025  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-11 11:56:26.026  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.026  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-11 11:56:26.026  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-11 11:56:26.026  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dd67 removed from the list
09-11 11:56:26.026  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:26.026  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@557d714 removed from the list
09-11 11:56:26.027  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:26.032  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:26.033  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:26.033  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:26.035  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.035  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:26.038  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:26.038  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:26.038  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:26.038  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@557d714 not in the list
09-11 11:56:26.039  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.039  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:26.041  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-11 11:56:26.042  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:26.042  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:26.042  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d5e903 removed from the list
09-11 11:56:26.043  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:26.043  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.043  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:26.043  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:26.044  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eed55b2 removed from the list
,09-11 11:56:26.046   872  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-11 11:56:26.047  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:26.047  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7655080 added. We now have 2 listener(s)
,09-11 11:56:26.049  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-11 11:56:26.049  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:26.049  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:26.049  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:26.049  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7aa76b9 added. We now have 9 listener(s)
09-11 11:56:26.050  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:26.050  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-11 11:56:26.054  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:26.064  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:26.064  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:26.064  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:26.064  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:26.064  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:26.064  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:26.064  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:26.064  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:26.069  3790  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:26.070  3790  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-11 11:56:26.071  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-11 11:56:26.072  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@744125f added. We now have 3 listener(s)
,09-11 11:56:26.075  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:26.080  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:26.081  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-11 11:56:26.081  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-11 11:56:26.081  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:26.082  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:26.082  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ef4ac added. We now have 10 listener(s)
,09-11 11:56:26.083  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:26.083  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:26.083  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:26.084  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:26.084  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:26.084  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-11 11:56:26.091  3790  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-11 11:56:26.091  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-11 11:56:26.101  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-11 11:56:26.102  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-11 11:56:26.102  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-11 11:56:26.106  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-11 11:56:26.106  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-11 11:56:26.107  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-11 11:56:26.107  3790  3841 D BluetoothAdapter: STATE_ON
,09-11 11:56:26.113  4144  4180 D BtGatt.GattService: registerClient() - UUID=b9831aab-99fc-488a-9993-0802c93ebc28
,09-11 11:56:26.114  4144  4160 D BtGatt.GattService: onClientRegistered() - UUID=b9831aab-99fc-488a-9993-0802c93ebc28, clientIf=5
,09-11 11:56:26.116  3790  3801 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-11 11:56:26.117  4144  4172 D BtGatt.GattService: start scan with filters
,09-11 11:56:26.121  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-11 11:56:26.121  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-11 11:56:26.121  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-11 11:56:26.122  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-11 11:56:26.122  4144  4163 D BtGatt.ScanManager: handling starting scan
,09-11 11:56:26.125  4144  4163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72bb542
,09-11 11:56:26.125  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-11 11:56:26.125  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-11 11:56:26.125  3790  3790 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-11 11:56:26.128  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-11 11:56:26.130  4144  4160 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-11 11:56:26.130  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-11 11:56:26.131  4144  4163 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-11 11:56:26.132  3790  3841 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-11 11:56:26.132  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-11 11:56:26.132  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-11 11:56:26.144  4144  4160 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-11 11:56:26.147  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:26.147  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:26.148  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-11 11:56:26.148  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-11 11:56:26.148  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-11 11:56:26.148  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-11 11:56:26.148  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-11 11:56:26.149  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-11 11:56:26.149  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-11 11:56:26.149  4144  4163 D BtGatt.ScanManager: Starting BLE batch scan
,09-11 11:56:26.150  4144  4163 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-11 11:56:26.150  3790  3841 D BluetoothAdapter: STATE_ON
09-11 11:56:26.152  4144  4180 D BtGatt.GattService: stopScan() - queue size =1
09-11 11:56:26.152  4144  4172 D BtGatt.GattService: unregisterClient() - clientIf=5,
09-11 11:56:26.153  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:26.153  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-11 11:56:26.153  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-11 11:56:26.153  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-11 11:56:26.153  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-11 11:56:26.155  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:26.155  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-11 11:56:26.155  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-11 11:56:26.155  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-11 11:56:26.156  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-11 11:56:26.157  3790  3790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:26.158  3790  3790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:26.158  3790  3790 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-11 11:56:26.161  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:26.161  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-11 11:56:26.161  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:26.161  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-11 11:56:26.162  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.162  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:26.162  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-11 11:56:26.162  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7655080 removed from the list
09-11 11:56:26.162  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:26.162  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7aa76b9 removed from the list
09-11 11:56:26.162  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
,09-11 11:56:26.162  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:26.163  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.163  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:26.164  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-11 11:56:26.164  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:26.164  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:26.164  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7aa76b9 not in the list
09-11 11:56:26.164  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:26.164  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:26.166  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:26.166  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-11 11:56:26.166  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:26.166  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ef4ac removed from the list
09-11 11:56:26.166  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:26.167  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.167  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:26.167  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:26.167  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@744125f removed from the list
,09-11 11:56:26.168  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:26.168  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ccaf98 added. We now have 2 listener(s)
09-11 11:56:26.170  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-11 11:56:26.170  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-11 11:56:26.170  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:26.170  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:26.170  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3743f1 added. We now have 9 listener(s)
09-11 11:56:26.170  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:26.171  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-11 11:56:26.173  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:26.178  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:26.178  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:26.178  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:26.178  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:26.178  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:26.178  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:26.178  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:26.178  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:26.180  3790  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:26.180  3790  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-11 11:56:26.181  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-11 11:56:26.181  4144  4160 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-11 11:56:26.181  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e7ee57 added. We now have 3 listener(s)
,09-11 11:56:26.181  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:26.183  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:26.184  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-11 11:56:26.184  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-11 11:56:26.184  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:26.184  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:26.184  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca92d44 added. We now have 10 listener(s)
,09-11 11:56:26.184  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:26.184  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:26.185  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:26.186  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:26.186  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-11 11:56:26.186  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:26.186  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:26.186  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-11 11:56:26.189  3790  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-11 11:56:26.189  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-11 11:56:26.189  4144  4160 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-11 11:56:26.189  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-11 11:56:26.194  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-11 11:56:26.194  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-11 11:56:26.195  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-11 11:56:26.198  4144  4160 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-11 11:56:26.198  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-11 11:56:26.198  4144  4163 D BtGatt.ScanManager: stopping BLe Batch
09-11 11:56:26.198  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-11 11:56:26.199  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-11 11:56:26.199  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-11 11:56:26.200  3790  3841 D BluetoothAdapter: STATE_ON
,09-11 11:56:26.201  4144  4180 D BtGatt.GattService: registerClient() - UUID=a8c27e08-5b6c-4500-965c-753192b893de
,09-11 11:56:26.202  4144  4160 D BtGatt.GattService: onClientRegistered() - UUID=a8c27e08-5b6c-4500-965c-753192b893de, clientIf=5
09-11 11:56:26.202  3790  3801 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-11 11:56:26.202  4144  4184 D BtGatt.GattService: start scan with filters
,09-11 11:56:26.204  4144  4160 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-11 11:56:26.204  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-11 11:56:26.204  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-11 11:56:26.204  4144  4163 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-11 11:56:26.205  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-11 11:56:26.205  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-11 11:56:26.205  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-11 11:56:26.208  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-11 11:56:26.208  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-11 11:56:26.208  3790  3790 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-11 11:56:26.209  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-11 11:56:26.209  4144  4160 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-11 11:56:26.209  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-11 11:56:26.211  4144  4163 D BtGatt.ScanManager: handling starting scan
,09-11 11:56:26.211  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-11 11:56:26.212  3790  3841 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-11 11:56:26.212  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:26.212  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:26.212  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:26.212  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-11 11:56:26.212  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.212  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-11 11:56:26.212  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-11 11:56:26.212  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ccaf98 removed from the list
09-11 11:56:26.212  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:26.212  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3743f1 removed from the list
09-11 11:56:26.212  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
,09-11 11:56:26.212  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-11 11:56:26.213  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:26.213  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-11 11:56:26.213  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.213  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:26.214  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-11 11:56:26.214  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:26.214  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:26.214  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3743f1 not in the list
09-11 11:56:26.214  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-11 11:56:26.214  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-11 11:56:26.214  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-11 11:56:26.214  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-11 11:56:26.214  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-11 11:56:26.215  3790  3841 D BluetoothAdapter: STATE_ON
09-11 11:56:26.215  4144  4184 D BtGatt.GattService: stopScan() - queue size =1
09-11 11:56:26.216  4144  4172 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-11 11:56:26.216  4144  4160 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-11 11:56:26.216  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:26.216  4144  4163 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-11 11:56:26.216  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-11 11:56:26.219  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-11 11:56:26.219  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-11 11:56:26.219  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-11 11:56:26.219  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-11 11:56:26.220  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-11 11:56:26.220  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-11 11:56:26.220  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-11 11:56:26.220  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-11 11:56:26.220  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:26.221  4144  4160 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-11 11:56:26.221  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:26.221  4144  4163 D BtGatt.ScanManager: Starting BLE batch scan
09-11 11:56:26.221  4144  4163 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-11 11:56:26.221  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:26.222  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-11 11:56:26.222  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:26.222  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca92d44 removed from the list
09-11 11:56:26.222  3790  3790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:26.222  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-11 11:56:26.222  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.222  3790  3790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:26.222  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:26.222  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-11 11:56:26.222  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e7ee57 removed from the list
09-11 11:56:26.222  3790  3790 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:26.223  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-11 11:56:26.223  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2add9b0 added. We now have 2 listener(s)
09-11 11:56:26.224  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-11 11:56:26.224  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:26.224  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-11 11:56:26.224  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:26.225  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a798029 added. We now have 9 listener(s)
09-11 11:56:26.225  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:26.225  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-11 11:56:26.227  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:26.230  4144  4160 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-11 11:56:26.230  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:26.232  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:26.232  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:26.232  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:26.232  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:26.232  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:26.232  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:26.232  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:26.232  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:26.234  3790  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:26.234  3790  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-11 11:56:26.234  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:26.234  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc514f added. We now have 3 listener(s)
09-11 11:56:26.235  4144  4160 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-11 11:56:26.235  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:26.235  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-11 11:56:26.236  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:26.236  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-11 11:56:26.236  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:26.236  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0ee0dc added. We now have 10 listener(s)
,09-11 11:56:26.236  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:26.236  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-11 11:56:26.236  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-11 11:56:26.237  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:26.237  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:26.237  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:26.237  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-11 11:56:26.239  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:26.240  3790  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-11 11:56:26.240  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-11 11:56:26.242  4144  4160 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-11 11:56:26.242  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:26.242  4144  4163 D BtGatt.ScanManager: stopping BLe Batch
09-11 11:56:26.244  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-11 11:56:26.245  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-11 11:56:26.245  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-11 11:56:26.247  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-11 11:56:26.247  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-11 11:56:26.248  3790  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-11 11:56:26.248  4144  4160 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-11 11:56:26.248  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:26.248  4144  4163 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-11 11:56:26.248  3790  3841 D BluetoothAdapter: STATE_ON
09-11 11:56:26.250  4144  4180 D BtGatt.GattService: registerClient() - UUID=c0608d9d-86a9-48bd-86b4-c4dcbde18bc5
,09-11 11:56:26.250  4144  4160 D BtGatt.GattService: onClientRegistered() - UUID=c0608d9d-86a9-48bd-86b4-c4dcbde18bc5, clientIf=5
,09-11 11:56:26.251  3790  3802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-11 11:56:26.251  4144  4184 D BtGatt.GattService: start scan with filters
,09-11 11:56:26.253  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-11 11:56:26.253  4144  4160 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-11 11:56:26.253  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:26.253  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-11 11:56:26.253  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-11 11:56:26.253  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-11 11:56:26.254  4144  4163 D BtGatt.ScanManager: handling starting scan
,09-11 11:56:26.255  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-11 11:56:26.255  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-11 11:56:26.255  3790  3790 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-11 11:56:26.257  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-11 11:56:26.260  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:26.260  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-11 11:56:26.260  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:26.261  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-11 11:56:26.261  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.261  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-11 11:56:26.261  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-11 11:56:26.261  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2add9b0 removed from the list
09-11 11:56:26.261  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:26.261  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a798029 removed from the list
09-11 11:56:26.261  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:26.261  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-11 11:56:26.262  4144  4160 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-11 11:56:26.262  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-11 11:56:26.262  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.262  4144  4163 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
09-11 11:56:26.262  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-11 11:56:26.262  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.262  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-11 11:56:26.263  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:26.263  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:26.264  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:26.264  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a798029 not in the list
,09-11 11:56:26.264  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-11 11:56:26.264  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-11 11:56:26.264  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-11 11:56:26.264  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-11 11:56:26.264  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-11 11:56:26.265  3790  3841 D BluetoothAdapter: STATE_ON
09-11 11:56:26.265  4144  4154 D BtGatt.GattService: stopScan() - queue size =1
,09-11 11:56:26.265  4144  4180 D BtGatt.GattService: unregisterClient() - clientIf=5
09-11 11:56:26.266  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:26.266  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-11 11:56:26.266  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-11 11:56:26.266  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-11 11:56:26.266  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-11 11:56:26.267  4144  4160 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-11 11:56:26.267  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-11 11:56:26.267  4144  4163 D BtGatt.ScanManager: Starting BLE batch scan
09-11 11:56:26.267  4144  4163 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-11 11:56:26.267  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:26.267  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-11 11:56:26.268  3790  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-11 11:56:26.268  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-11 11:56:26.268  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:26.269  3790  3790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-11 11:56:26.269  3790  3790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:26.269  3790  3790 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:26.269  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:26.269  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:26.269  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:26.269  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0ee0dc removed from the list
09-11 11:56:26.270  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:26.270  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.270  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:26.270  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:26.270  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc514f removed from the list
,09-11 11:56:26.270  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:26.270  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3172ec8 added. We now have 2 listener(s)
09-11 11:56:26.272  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-11 11:56:26.272  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:26.272  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-11 11:56:26.272  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:26.272  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d00b61 added. We now have 9 listener(s)
09-11 11:56:26.272  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:26.273  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-11 11:56:26.276  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:26.276  4144  4160 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-11 11:56:26.276  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-11 11:56:26.279  3790  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:26.279  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:26.279  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:26.279  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:26.279  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:26.279  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:26.279  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:26.279  3790  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:26.281  3790  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:26.281  3790  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:26.281  4144  4160 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-11 11:56:26.281  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:26.281  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:26.281  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46b1b47 added. We now have 3 listener(s)
,09-11 11:56:26.283  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-11 11:56:26.283  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-11 11:56:26.283  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:26.283  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:26.283  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d46f74 added. We now have 10 listener(s)
09-11 11:56:26.283  3790  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:26.284  3790  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:26.284  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:26.284  3790  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:26.284  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:26.284  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:26.284  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:26.284  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:26.284  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:26.284  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3172ec8 removed from the list
09-11 11:56:26.284  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:26.284  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d00b61 removed from the list
09-11 11:56:26.286  3790  3790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:26.287  3790  3841 D io.jxcore.node.ConnectivityMonitor: stop
,09-11 11:56:26.287  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:26.287  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.287  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:26.288  4144  4160 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-11 11:56:26.288  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:26.288  4144  4163 D BtGatt.ScanManager: stopping BLe Batch
,09-11 11:56:26.288  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:26.288  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:26.288  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:26.288  3790  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d00b61 not in the list
09-11 11:56:26.288  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:26.289  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:26.289  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:26.289  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:26.289  3790  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:26.290  3790  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d46f74 removed from the list
09-11 11:56:26.290  3790  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-11 11:56:26.290  3790  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:26.290  3790  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:26.290  3790  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:26.290  3790  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46b1b47 removed from the list
09-11 11:56:26.291  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-11 11:56:26.291  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-11 11:56:26.291  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-11 11:56:26.291  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:26.291  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-11 11:56:26.291  3790  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-11 11:56:26.294  4144  4160 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-11 11:56:26.294  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:26.294  4144  4163 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-11 11:56:26.296  3790  4223 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: My test thread name)
,09-11 11:56:26.297  3790  4223 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: My test thread name)
09-11 11:56:26.297  3790  4223 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-11 11:56:26.299  4144  4160 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-11 11:56:26.300  4144  4160 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-11 11:56:26.300  3790  4224 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: My test thread name)
09-11 11:56:26.300  3790  4224 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: My test thread name)
,09-11 11:56:26.300  3790  4224 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-11 11:56:26.303  3790  3841 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-11 11:56:26.303  3790  3841 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-11 11:56:26.303  3790  3841 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-11 11:56:26.303  3790  3841 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-11 11:56:26.303  3790  3841 D com.test.thalitest.ThaliTestRunner: Total duration: 22869 ms
09-11 11:56:26.306  3790  3841 I jxcore-log: *Native tests were executed*
09-11 11:56:26.306  3790  3841 I jxcore-log: 
,09-11 11:56:26.306  3790  3841 I jxcore-log: Total number of executed tests:  80
09-11 11:56:26.306  3790  3841 I jxcore-log: 
,09-11 11:56:26.307  3790  3841 I jxcore-log: Number of passed tests:  80
09-11 11:56:26.307  3790  3841 I jxcore-log: 
,09-11 11:56:26.307  3790  3841 I jxcore-log: Number of failed tests:  0
09-11 11:56:26.307  3790  3841 I jxcore-log: 
09-11 11:56:26.307  3790  3841 I jxcore-log: Number of ignored tests:  0
09-11 11:56:26.307  3790  3841 I jxcore-log: 
09-11 11:56:26.308  3790  3841 I jxcore-log: Total duration:  22869
09-11 11:56:26.308  3790  3841 I jxcore-log: 
09-11 11:56:26.308  3790  3841 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-11 11:56:26.308  3790  3841 I jxcore-log: 
,09-11 11:56:26.312  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.312  3790  3841 I jxcore-log: 
09-11 11:56:26.316  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.316  3790  3841 I jxcore-log: 
09-11 11:56:26.317  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.317  3790  3841 I jxcore-log: 
09-11 11:56:26.318  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.318  3790  3841 I jxcore-log: 
09-11 11:56:26.318  3790  3790 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-11 11:56:26.319  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.319  3790  3841 I jxcore-log: 
09-11 11:56:26.321  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.321  3790  3841 I jxcore-log: 
09-11 11:56:26.323  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.323  3790  3841 I jxcore-log: 
09-11 11:56:26.325  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:26.325  3790  3841 I jxcore-log: 
09-11 11:56:26.326  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:26.326  3790  3841 I jxcore-log: 
09-11 11:56:26.327  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-11 11:56:26.327  3790  3841 I jxcore-log: 
,09-11 11:56:26.328  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-11 11:56:26.328  3790  3841 I jxcore-log: 
,09-11 11:56:26.329  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-11 11:56:26.329  3790  3841 I jxcore-log: 
,09-11 11:56:26.329  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.329  3790  3841 I jxcore-log: 
09-11 11:56:26.330  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.330  3790  3841 I jxcore-log: 
,09-11 11:56:26.331  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-11 11:56:26.331  3790  3841 I jxcore-log: 
,09-11 11:56:26.332  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-11 11:56:26.332  3790  3841 I jxcore-log: 
,09-11 11:56:26.332  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:26.332  3790  3841 I jxcore-log: 
,09-11 11:56:26.333  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:26.333  3790  3841 I jxcore-log: 
09-11 11:56:26.334  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-11 11:56:26.334  3790  3841 I jxcore-log: 
09-11 11:56:26.335  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-11 11:56:26.335  3790  3841 I jxcore-log: 
09-11 11:56:26.335  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:26.335  3790  3841 I jxcore-log: 
,09-11 11:56:26.336  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:26.336  3790  3841 I jxcore-log: 
,09-11 11:56:26.337  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-11 11:56:26.337  3790  3841 I jxcore-log: 
09-11 11:56:26.337  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-11 11:56:26.337  3790  3841 I jxcore-log: 
09-11 11:56:26.338  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-11 11:56:26.338  3790  3841 I jxcore-log: 
09-11 11:56:26.338  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-11 11:56:26.338  3790  3841 I jxcore-log: 
,09-11 11:56:26.339  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.339  3790  3841 I jxcore-log: 
,09-11 11:56:26.340  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.340  3790  3841 I jxcore-log: 
,09-11 11:56:26.341  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.341  3790  3841 I jxcore-log: 
09-11 11:56:26.341  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.341  3790  3841 I jxcore-log: 
09-11 11:56:26.342  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.342  3790  3841 I jxcore-log: 
,09-11 11:56:26.342  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:26.342  3790  3841 I jxcore-log: 
,09-11 11:56:26.474   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-11 11:56:26.479  1875  1875 I Keyboard.Facilitator: onFinishInput()
,09-11 11:56:26.488   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-11 11:56:26.488   872   892 I Adreno  : Build Date                       : 10/20/15
09-11 11:56:26.488   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-11 11:56:26.488   872   892 I Adreno  : Local Branch                     : M14
09-11 11:56:26.488   872   892 I Adreno  : Remote Branch                    : 
09-11 11:56:26.488   872   892 I Adreno  : Remote Branch                    : 
09-11 11:56:26.488   872   892 I Adreno  : Reconstruct Branch               : 
,09-11 11:56:26.512   281  1975 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (195 us)
,09-11 11:56:26.658  3790  3790 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-11 11:56:26.662  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-11 11:56:26.662  3790  3841 I jxcore-log: 
,09-11 11:56:26.723  3790  3790 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-11 11:56:26.727  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-11 11:56:26.727  3790  3841 I jxcore-log: 
,09-11 11:56:26.770  3790  3790 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-11 11:56:26.774  3790  3841 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-11 11:56:26.774  3790  3841 I jxcore-log: 
,09-11 11:56:27.032  4225  4225 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-11 11:56:27.036  4225  4225 D AndroidRuntime: CheckJNI is OFF
,09-11 11:56:27.079  4225  4225 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-11 11:56:27.085  3790  3790 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-11 11:56:27.085  3790  3790 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-11 11:56:27.118  3790  3790 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ac3e38e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@320fc9d, 16908290=android.view.AbsSavedState$1@320fc9d}, android:focusedViewId=100}]}]
,09-11 11:56:27.118  3790  3790 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-11 11:56:27.118  3790  3790 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-11 11:56:27.118  3790  3790 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-11 11:56:27.119   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-11 11:56:27.120  4225  4225 I Radio-JNI: register_android_hardware_Radio DONE
,09-11 11:56:27.123   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-11 11:56:27.127   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-11 11:56:27.127   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
09-11 11:56:27.128   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-11 11:56:27.156  4225  4225 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-11 11:56:27.161   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-11 11:56:27.161   872   885 I ActivityManager: Killing 3790:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-11 11:56:27.247   872  2001 I WindowState: WIN DEATH: Window{b17521d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-11 11:56:27.247   872  1386 D GraphicsStats: Buffer count: 2
09-11 11:56:27.247   872  1305 D WifiService: Client connection lost with reason: 4
,09-11 11:56:27.262   872   896 W PackageSettings: Skipping PackageSetting{171da47 com.example.hello/10273} due to missing metadata
,09-11 11:56:27.293   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-11 11:56:27.293   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-11 11:56:27.294   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-11 11:56:27.294   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-11 11:56:27.294   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:27.294   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:27.294   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-11 11:56:27.294   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-11 11:56:27.295   872   885 I ActivityManager:   Force finishing activity ActivityRecord{a9bacda u0 com.test.thalitest/.MainActivity t4}
,09-11 11:56:27.304   872   896 I art     : Starting a blocking GC Explicit
,09-11 11:56:27.307   872  1992 W ActivityManager: Spurious death for ProcessRecord{e6f4d5b 0:com.test.thalitest/u0a0}, curProc for 3790: null
,09-11 11:56:27.343   872   896 I art     : Explicit concurrent mark sweep GC freed 12859(901KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 742us total 38.131ms
,09-11 11:56:27.357   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-11 11:56:27.359   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-11 11:56:27.360   872  1331 D SurfaceControl: Excessive delay in setPowerMode(): 233ms
,09-11 11:56:27.363   872   892 I DreamManagerService: Entering dreamland.
09-11 11:56:27.363   872   892 I PowerManagerService: Dozing...
09-11 11:56:27.363   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-11 11:56:27.389   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-11 11:56:27.389   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-11 11:56:27.398  1937  4238 D NfcService: Discovery configuration equal, not updating.
,09-11 11:56:27.398   872   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-11 11:56:27.401  4225  4225 I art     : System.exit called, status: 0
09-11 11:56:27.401  4225  4225 I AndroidRuntime: VM exiting with result code 0.
09-11 11:56:27.402   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-11 11:56:27.408   872   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-11 11:56:27.411   872  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-11 11:56:27.423   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-11 11:56:27.425   872  1304 E native  : do suspend false
,09-11 11:56:27.429  4144  4144 D BluetoothMapAppObserver: onReceive
,09-11 11:56:27.429  4144  4144 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-11 11:56:27.430  1902  2310 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-11 11:56:27.431  1875  1875 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-11 11:56:27.435  3623  3623 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-11 11:56:27.442   872  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,09-11 11:56:27.443   872  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-11 11:56:27.445  1875  4242 I Keyboard.Facilitator.DecoderInitializer: run()
,09-11 11:56:27.458  1875  4242 I Decoder : createOrResetDecoder
,09-11 11:56:27.464  1948  1948 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-11 11:56:27.476   872   883 I ActivityManager: Start proc 4245:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-11 11:56:27.491  1506  1506 I ConfigService: onCreate
,09-11 11:56:27.512  1875  4242 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-11 11:56:27.515  4245  4245 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-11 11:56:27.530   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-11 11:56:27.537   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-11 11:56:27.539   872  1304 E native  : do suspend true
,09-11 11:56:27.542   375  1315 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-11 11:56:27.543   375  1315 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-11 11:56:27.544   872   883 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3790 uid 10000
,09-11 11:56:27.547  1875  1875 I Keyboard.Facilitator: onFinishInput()
,09-11 11:56:27.562   872  1332 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,09-11 11:56:27.562   872  1332 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
09-11 11:56:27.562   872  1332 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
09-11 11:56:27.562   872  1332 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
,09-11 11:56:27.562   872  1332 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
09-11 11:56:27.562   872  1332 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
,09-11 11:56:27.562   872  1332 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
09-11 11:56:27.562   872  1332 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
09-11 11:56:27.562   872  1332 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
09-11 11:56:27.562   872  1332 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
,09-11 11:56:27.562   872  1332 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
,09-11 11:56:27.562   872  1332 W System.err: 	... 4 more
09-11 11:56:27.563   872  1332 D skia    : ------- write threw an exception
09-11 11:56:27.568  1875  4242 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-11 11:56:27.570  1875  4242 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-11 11:56:27.570  1875  4242 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-11 11:56:27.575  1875  4242 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-11 11:56:27.577  1875  4242 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-11 11:56:27.577   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-11 11:56:27.578   872   884 E PackageManager: Failed to write settings, restoring backup
09-11 11:56:27.578   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-11 11:56:27.578   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-11 11:56:27.578   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-11 11:56:27.578   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-11 11:56:27.578   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-11 11:56:27.578   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:27.578   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:27.578   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-11 11:56:27.581   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-11 11:56:27.581   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-11 11:56:27.581   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-11 11:56:27.581   872   885 E DropBoxManagerService: 	... 13 more
,09-11 11:56:27.581  1875  4242 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-11 11:56:27.582  1875  4242 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-11 11:56:27.583  1965  2048 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-11 11:56:27.587  1875  4242 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-11 11:56:27.587  1875  4242 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,09-11 11:56:27.587  1875  4242 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-11 11:56:27.588  1875  4242 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-11 11:56:27.588  1875  4242 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-11 11:56:27.588  1875  4242 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-11 11:56:27.589  4245  4245 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-11 11:56:27.596   872  1954 I ActivityManager: Start proc 4264:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-11 11:56:27.596  1965  2048 E AndroidRuntime: FATAL EXCEPTION: launcher-loader,
09-11 11:56:27.596  1965  2048 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1965
09-11 11:56:27.596  1965  2048 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-11 11:56:27.596  1965  2048 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-11 11:56:27.596  1965  2048 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-11 11:56:27.596  1965  2048 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-11 11:56:27.596  1965  2048 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-11 11:56:27.596  1965  2048 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-11 11:56:27.596  1965  2048 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-11 11:56:27.596  1965  2048 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-11 11:56:27.596  1965  2048 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-11 11:56:27.596  1965  2048 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-11 11:56:27.596  1965  2048 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:27.596  1965  2048 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-11 11:56:27.599   872  1992 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-11 11:56:27.599   872  4270 E DropBoxManagerService: Can't write: system_app_crash
09-11 11:56:27.599   872  4270 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-11 11:56:27.599   872  4270 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-11 11:56:27.599   872  4270 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-11 11:56:27.599   872  4270 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-11 11:56:27.599   872  4270 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-11 11:56:27.599   872  4270 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-11 11:56:27.599   872  4270 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-11 11:56:27.599   872  4270 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-11 11:56:27.599   872  4270 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-11 11:56:27.599   872  4270 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-11 11:56:27.599   872  4270 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-11 11:56:27.599   872  4270 E DropBoxManagerService: 	... 5 more
,09-11 11:56:27.610  4245  4260 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:27.610  4245  4260 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:27.610  4245  4260 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-11 11:56:27.615   872  1699 I ActivityManager: Start proc 4279:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-11 11:56:27.616  1965  2048 I Process : Sending signal. PID: 1965 SIG: 9
,09-11 11:56:27.619  4245  4277 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-11 11:56:27.708  4279  4279 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-11 11:56:27.778  1506  1506 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-11 11:56:27.781  1506  1506 D AndroidRuntime: Shutting down VM
,09-11 11:56:27.784   872  1698 D GraphicsStats: Buffer count: 1
,09-11 11:56:27.784   872  2204 I WindowState: WIN DEATH: Window{a9cc423 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-11 11:56:27.786  1506  1506 E AndroidRuntime: FATAL EXCEPTION: main
09-11 11:56:27.786  1506  1506 E AndroidRuntime: Process: com.google.process.gapps, PID: 1506
09-11 11:56:27.786  1506  1506 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-11 11:56:27.786  1506  1506 E AndroidRuntime: 	... 8 more
,09-11 11:56:27.802   872  1698 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1965) has died
09-11 11:56:27.803   872  1698 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-11 11:56:27.805   872  1698 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-11 11:56:27.824   872   885 I ActivityManager: Start proc 4297:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-11 11:56:27.828  1506  1506 I Process : Sending signal. PID: 1506 SIG: 9
09-11 11:56:27.830   872  4303 E DropBoxManagerService: Can't write: system_app_crash
09-11 11:56:27.830   872  4303 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-11 11:56:27.830   872  4303 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-11 11:56:27.830   872  4303 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-11 11:56:27.830   872  4303 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-11 11:56:27.830   872  4303 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-11 11:56:27.830   872  4303 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-11 11:56:27.830   872  4303 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-11 11:56:27.830   872  4303 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-11 11:56:27.830   872  4303 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-11 11:56:27.830   872  4303 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-11 11:56:27.830   872  4303 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-11 11:56:27.830   872  4303 E DropBoxManagerService: 	... 5 more
09-11 11:56:27.846   872  1304 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 15 -> obsolete
09-11 11:56:27.847  1723  4294 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-11 11:56:27.848  1723  4294 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-11 11:56:27.848  4245  4260 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:27.855  4245  4277 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-11 11:56:27.856  4245  4277 E AndroidRuntime: Process: android.process.acore, PID: 4245
09-11 11:56:27.856  4245  4277 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:27.856  4245  4277 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-11 11:56:27.858  4245  4277 I Process : Sending signal. PID: 4245 SIG: 9
09-11 11:56:27.859   872  4310 E DropBoxManagerService: Can't write: system_app_crash
09-11 11:56:27.859   872  4310 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-11 11:56:27.859   872  4310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-11 11:56:27.859   872  4310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-11 11:56:27.859   872  4310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-11 11:56:27.859   872  4310 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-11 11:56:27.859   872  4310 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-11 11:56:27.859   872  4310 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-11 11:56:27.859   872  4310 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-11 11:56:27.859   872  4310 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-11 11:56:27.859   872  4310 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-11 11:56:27.859   872  4310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-11 11:56:27.859   872  4310 E DropBoxManagerService: 	... 5 more
09-11 11:56:27.869   872  1305 D WifiService: Client connection lost with reason: 4
09-11 11:56:27.874   872  2006 I ActivityManager: Process com.google.process.gapps (pid 1506) has died
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-11 11:56:27.874  4297  4297 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-11 11:56:27.874  4297  4297 D AndroidRuntime: Shutting down VM
09-11 11:56:27.874   872  2006 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
09-11 11:56:27.875   872  2006 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
09-11 11:56:27.875   872  2006 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
09-11 11:56:27.875   872  2006 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30999ms
09-11 11:56:27.883  4297  4297 E AndroidRuntime: FATAL EXCEPTION: main
09-11 11:56:27.883  4297  4297 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4297
09-11 11:56:27.883  4297  4297 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-11 11:56:27.883  4297  4297 E AndroidRuntime: 	... 10 more
09-11 11:56:27.884  1723  1723 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-11 11:56:27.888   872  2205 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-11 11:56:27.888  4297  4297 I Process : Sending signal. PID: 4297 SIG: 9
,09-11 11:56:27.889   872  4311 E DropBoxManagerService: Can't write: system_app_crash
09-11 11:56:27.889   872  4311 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-11 11:56:27.889   872  4311 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-11 11:56:27.889   872  4311 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-11 11:56:27.889   872  4311 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-11 11:56:27.889   872  4311 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-11 11:56:27.889   872  4311 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-11 11:56:27.889   872  4311 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-11 11:56:27.889   872  4311 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-11 11:56:27.889   872  4311 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-11 11:56:27.889   872  4311 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-11 11:56:27.889   872  4311 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-11 11:56:27.889   872  4311 E DropBoxManagerService: 	... 5 more
,09-11 11:56:27.902   872   883 I ActivityManager: Start proc 4312:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-11 11:56:27.911   872  1480 I ActivityManager: Process android.process.acore (pid 4245) has died
,09-11 11:56:27.912   872  1480 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40962ms
,09-11 11:56:27.914   872  2001 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4297) has died
,09-11 11:56:27.916   872  2001 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-11 11:56:27.931   872  2006 I ActivityManager: Start proc 4326:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL

```
