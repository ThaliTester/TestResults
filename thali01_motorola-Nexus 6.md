#### Test 7975101505baaca_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-10 12:13:37.566   875  2133 D NetlinkSocketObserver: NeighborEvent{elapsedMs=109423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 12:13:37.821  1492  1492 I ConfigService: onDestroy
08-10 12:13:38.224  3706  3706 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 12:13:38.229  3706  3706 D AndroidRuntime: CheckJNI is OFF
08-10 12:13:38.272  3706  3706 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 12:13:38.323  3706  3706 I Radio-JNI: register_android_hardware_Radio DONE
08-10 12:13:38.344  3706  3706 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 12:13:38.349   875  1762 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 12:13:38.418  1839  1851 W SearchService: Abort, client detached.
08-10 12:13:38.421  1839  1839 I HotwordDetector: Closing mic
08-10 12:13:38.421  1839  2163 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@961a82b
08-10 12:13:38.422  1839  2172 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-10 12:13:38.422  3706  3706 D AndroidRuntime: Shutting down VM
08-10 12:13:38.453   875  1763 I ActivityManager: Start proc 3716:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-10 12:13:38.468   377  2174 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-10 12:13:38.469   377  2174 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-10 12:13:38.477   377  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-10 12:13:38.479  1839  2167 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-10 12:13:38.479  1839  2170 I MicroRecognitionRnrImpl: Detection finished
08-10 12:13:38.541  3716  3716 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-10 12:13:38.571  3716  3716 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-10 12:13:38.579  3716  3716 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 433-437)
08-10 12:13:38.579  3716  3716 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 12:13:38.595  3716  3716 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5ebbb3b}
08-10 12:13:38.596  3716  3716 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 12:13:38.596  3716  3716 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 12:13:38.603  3716  3716 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-10 12:13:38.604  3716  3716 E SysUtils: ApplicationContext is null in ApplicationStatus
08-10 12:13:38.626  3716  3716 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-10 12:13:38.654  3716  3716 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 12:13:38.655  3716  3716 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 12:13:38.655  3716  3716 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 12:13:38.655  3716  3716 I Adreno  : Build Date                       : 10/20/15
08-10 12:13:38.655  3716  3716 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 12:13:38.655  3716  3716 I Adreno  : Local Branch                     : M14
08-10 12:13:38.655  3716  3716 I Adreno  : Remote Branch                    : 
08-10 12:13:38.655  3716  3716 I Adreno  : Remote Branch                    : 
08-10 12:13:38.655  3716  3716 I Adreno  : Reconstruct Branch               : 
,08-10 12:13:38.731   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@68bdcbe:true
,08-10 12:13:38.766  3716  3716 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-10 12:13:38.782  3716  3716 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-10 12:13:38.848  3716  3753 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-10 12:13:38.856  3716  3740 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-10 12:13:38.891  3716  3753 I OpenGLRenderer: Initialized EGL, version 1.4
,08-10 12:13:38.952   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +514ms
,08-10 12:13:38.959  1653  1653 I Keyboard.Facilitator: onFinishInput()
,08-10 12:13:39.011  3716  3716 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3716
,08-10 12:13:39.097  3716  3716 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 12:13:39.258   875  1736 I ActivityManager: Killing 2514:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-10 12:13:39.291  3716  3756 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1697449680
,08-10 12:13:39.298  3716  3756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 12:13:39.298  3716  3756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 12:13:39.298  3716  3756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 12:13:39.298  3716  3756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 12:13:39.298  3716  3756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-10 12:13:39.298  3716  3756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@706b32e added. We now have 1 listener(s)
,08-10 12:13:39.300   875  1736 I ActivityManager: Killing 3045:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-10 12:13:39.303  3716  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-10 12:13:39.305  3716  3756 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 12:13:39.305  3716  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 12:13:39.306  3716  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-10 12:13:39.310  3716  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cc9f65 added. We now have 1 listener(s)
08-10 12:13:39.310  3716  3756 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 12:13:39.314   875  1306 D WifiService: New client listening to asynchronous messages
,08-10 12:13:39.315  3716  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 12:13:39.315  3716  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-10 12:13:39.316  3716  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-10 12:13:39.316  3716  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-10 12:13:39.316  3716  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-10 12:13:39.345  3716  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 12:13:39.345  3716  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-10 12:13:39.352  3716  3756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-10 12:13:39.352  3716  3756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 12:13:39.352  3716  3756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:13:39.352  3716  3756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:13:39.352  3716  3756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:13:39.352  3716  3756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:13:39.352  3716  3756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:13:39.352  3716  3756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:13:39.352  3716  3756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 12:13:39.352  3716  3756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 12:13:39.352  3716  3756 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 12:13:39.354  3716  3756 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 12:13:39.354  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:13:39.356  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:13:39.512  3716  3716 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 12:13:40.523  3716  3766 W jxcore-log: Initializing JXcore engine
,08-10 12:13:40.523  3716  3766 W jxcore-log: JXcore engine is ready
,08-10 12:13:40.631  3766  3766 W Thread-342: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8942 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-10 12:13:40.631  3766  3766 W Thread-342: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11095]" dev="sockfs" ino=11095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-10 12:13:40.631  3766  3766 W Thread-342: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-10 12:13:40.631  3766  3766 W Thread-342: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24163]" dev="sockfs" ino=24163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-10 12:13:40.651  3716  3766 W jxcore-log: Starting JXcore engine
,08-10 12:13:40.748  3716  3766 W jxcore-log: Platform android
08-10 12:13:40.748  3716  3766 W jxcore-log: 
,08-10 12:13:40.749  3716  3766 W jxcore-log: Process ARCH arm
08-10 12:13:40.749  3716  3766 W jxcore-log: 
,08-10 12:13:40.967  3716  3766 I jxcore-log: JXcore Cordova bridge is ready!
08-10 12:13:40.967  3716  3766 I jxcore-log: 
,08-10 12:13:40.967  3716  3766 W jxcore-log: JXcore engine is started
,08-10 12:13:40.977  3716  3756 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-10 12:13:40.983  3716  3716 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 12:13:46.877   875   888 I ActivityManager: Waited long enough for: ServiceRecord{423a569 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,08-10 12:13:48.624  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:13:48.628  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:13:48.630  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:13:48.647  1492  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 12:13:48.647  1492  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 12:13:48.647  1492  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:13:48.647  1492  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:13:48.660  3454  3454 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 12:13:48.660  3454  3454 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 12:13:48.661  3454  3454 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-10 12:13:51.008   875  1305 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-10 12:13:53.916  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:13:53.919  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:13:53.972  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:13:53.973  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.,
08-10 12:13:53.973  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:13:53.973  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:13:54.020  2956  3777 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 12:13:54.020  2956  3777 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at blb.a(PG:3937)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at czp.a(PG:18188)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:13:54.020  2956  3777 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	... 12 more
08-10 12:13:54.020  2956  3777 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at fal.a(PG:38)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:13:54.020  2956  3777 E HttpOperation: 	... 14 more
,08-10 12:13:54.086  1492  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:13:54.086  1492  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 12:13:54.086  1492  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:13:54.086  1492  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:13:54.102  2956  3777 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 12:13:54.102  2956  3777 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at hec.a(PG:42)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at hee.a(PG:102)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at czr.a(PG:65)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at kka.a(PG:108)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at czp.a(PG:19176)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:13:54.102  2956  3777 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	... 15 more
08-10 12:13:54.102  2956  3777 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at fal.a(PG:38)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:13:54.102  2956  3777 E HttpOperation: 	... 17 more
,08-10 12:13:54.103  2956  3777 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 12:13:54.103  2956  3777 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at hec.a(PG:42)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at hee.a(PG:102)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at czr.a(PG:65)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at kka.a(PG:108)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	... 15 more
08-10 12:13:54.103  2956  3777 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at fal.a(PG:38)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 12:13:54.103  2956  3777 E ExperimentLoader: 	... 17 more
,08-10 12:13:54.205   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 125486, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:13:57.017  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 12:13:57.017  3716  3766 I jxcore-log: 
,08-10 12:13:57.020  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 12:13:57.020  3716  3766 I jxcore-log: 
,08-10 12:13:57.032  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 12:13:57.032  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:13:57.032  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:13:57.032  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:13:57.032  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:13:57.032  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:13:57.032  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:13:57.032  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 12:13:57.039  3716  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 12:13:57.041  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 12:13:57.041  3716  3766 I jxcore-log: 
,08-10 12:13:57.043  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 12:13:57.043  3716  3766 I jxcore-log: 
,08-10 12:13:57.385  3716  3766 D ExecuteNativeTests: Running unit tests
,08-10 12:13:57.470  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 12:13:57.471  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f added. We now have 2 listener(s)
08-10 12:13:57.472  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 12:13:57.472  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 12:13:57.472  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 12:13:57.472  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 12:13:57.472  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c added. We now have 2 listener(s)
08-10 12:13:57.472  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 12:13:57.473  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 12:13:57.478  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 12:13:57.487  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 12:13:57.487  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:13:57.487  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:13:57.487  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:13:57.487  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:13:57.487  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:13:57.487  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:13:57.487  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 12:13:57.490  3716  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 12:13:57.490  3716  3766 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 12:13:57.493  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-10 12:13:57.493  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 12:13:57.493  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 12:13:57.494  3716  3766 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-10 12:13:57.495  3716  3766 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 12:13:57.495  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 12:13:57.495  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 12:13:57.495  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 12:13:57.496  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.496  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:13:57.496  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.496  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:13:57.496  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.496  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.496  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 12:13:57.496  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 12:13:57.497  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f removed from the list
08-10 12:13:57.497  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.497  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c removed from the list
,08-10 12:13:57.500  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-10 12:13:57.500  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.500  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.500  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.501  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.501  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.501  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.502  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 12:13:57.502  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.503  3716  3766 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-10 12:13:57.504  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.504  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.504  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 12:13:57.504  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.504  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.504  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.504  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.504  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.504  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.504  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 12:13:57.504  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.504  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.504  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.504  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.506  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.507  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.507  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.507  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
,08-10 12:13:57.515  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-10 12:13:57.515  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 12:13:57.515  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 12:13:57.515  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 12:13:57.515  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 12:13:57.515  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 12:13:57.515  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-10 12:13:57.515  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 12:13:57.515  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 12:13:57.515  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 12:13:57.515  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 12:13:57.515  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110],
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810],
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 12:13:57.516  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 12:13:57.516  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.517  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.517  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 12:13:57.517  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.517  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.517  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.517  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.517  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.517  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.517  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.517  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.517  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.517  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.517  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.519  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.519  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 12:13:57.519  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.519  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.520  3716  3766 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 12:13:57.525  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 12:13:57.530  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 12:13:57.530  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:13:57.530  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:13:57.530  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:13:57.530  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:13:57.530  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:13:57.530  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:13:57.530  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 12:13:57.533  3716  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 12:13:57.533  3716  3766 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 12:13:57.533  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 12:13:57.533  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 12:13:57.533  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 12:13:57.533  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 12:13:57.534  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-10 12:13:57.536  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:13:57.538  3716  3766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-10 12:13:57.538  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 12:13:57.540  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:13:57.550  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 12:13:57.553  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-10 12:13:57.554  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 12:13:57.559  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-10 12:13:57.562  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-10 12:13:57.563  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 12:13:57.563  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-10 12:13:57.563  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-10 12:13:57.564  3716  3766 D BluetoothAdapter: STATE_ON
08-10 12:13:57.571  2646  2662 D BtGatt.GattService: registerClient() - UUID=d28b0a1d-6e28-4762-b94b-4618418ebdb5
,08-10 12:13:57.572  2646  2698 D BtGatt.GattService: onClientRegistered() - UUID=d28b0a1d-6e28-4762-b94b-4618418ebdb5, clientIf=5
08-10 12:13:57.573  3716  3762 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-10 12:13:57.574  2646  2833 D BtGatt.GattService: start scan with filters
,08-10 12:13:57.578  2646  2703 D BtGatt.ScanManager: handling starting scan
,08-10 12:13:57.579  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-10 12:13:57.579  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-10 12:13:57.579  2646  2703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
08-10 12:13:57.580  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 12:13:57.580  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 12:13:57.586  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 12:13:57.586  3716  3716 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 12:13:57.587  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 12:13:57.587  2646  2698 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-10 12:13:57.587  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:13:57.587  2646  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-10 12:13:57.591  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 12:13:57.592  2646  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 12:13:57.592  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:13:57.592  2646  2703 D BtGatt.ScanManager: Starting BLE batch scan
08-10 12:13:57.592  2646  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-10 12:13:57.597  3716  3766 I io.jxcore.node.ConnectionHelper: start: OK
,08-10 12:13:57.602  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 12:13:57.602  3716  3766 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-10 12:13:57.602  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-10 12:13:57.602  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 12:13:57.602  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.603  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 12:13:57.603  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 12:13:57.603  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 12:13:57.603  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-10 12:13:57.603  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 12:13:57.603  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 12:13:57.604  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 12:13:57.604  2646  2698 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-10 12:13:57.604  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:13:57.605  3716  3766 D BluetoothAdapter: STATE_ON
,08-10 12:13:57.605  2646  2662 D BtGatt.GattService: stopScan() - queue size =1
08-10 12:13:57.606  2646  2833 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-10 12:13:57.607  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-10 12:13:57.607  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 12:13:57.607  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 12:13:57.607  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 12:13:57.607  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-10 12:13:57.608  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 12:13:57.608  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 12:13:57.609  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 12:13:57.609  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 12:13:57.609  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 12:13:57.610  3716  3716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 12:13:57.611  3716  3716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 12:13:57.611  3716  3716 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 12:13:57.611  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.611  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.611  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 12:13:57.611  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
,08-10 12:13:57.611  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.611  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
,08-10 12:13:57.611  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.612  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.612  3716  3766 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 12:13:57.613  2646  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 12:13:57.613  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:13:57.614  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 12:13:57.618  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 12:13:57.618  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:13:57.618  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:13:57.618  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:13:57.618  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:13:57.618  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:13:57.618  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:13:57.618  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 12:13:57.620  3716  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 12:13:57.620  3716  3766 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 12:13:57.621  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-10 12:13:57.621  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-10 12:13:57.622  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:13:57.624  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-10 12:13:57.624  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:13:57.624  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 12:13:57.624  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 12:13:57.624  2646  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 12:13:57.625  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:13:57.625  2646  2703 D BtGatt.ScanManager: stopping BLe Batch
08-10 12:13:57.628  3716  3766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-10 12:13:57.628  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 12:13:57.631  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-10 12:13:57.632  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-10 12:13:57.632  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 12:13:57.634  2646  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-10 12:13:57.634  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:13:57.634  2646  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 12:13:57.636  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-10 12:13:57.636  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 12:13:57.636  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-10 12:13:57.637  3716  3766 D BluetoothAdapter: STATE_ON
,08-10 12:13:57.639  2646  2661 D BtGatt.GattService: registerClient() - UUID=e1de3cd3-f006-479e-ab4d-de4dbfa66af3
,08-10 12:13:57.640  2646  2698 D BtGatt.GattService: onClientRegistered() - UUID=e1de3cd3-f006-479e-ab4d-de4dbfa66af3, clientIf=5
08-10 12:13:57.640  3716  3762 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-10 12:13:57.640  2646  2662 D BtGatt.GattService: start scan with filters
,08-10 12:13:57.643  2646  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 12:13:57.643  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:13:57.643  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-10 12:13:57.643  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-10 12:13:57.643  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 12:13:57.643  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 12:13:57.644  2646  2703 D BtGatt.ScanManager: handling starting scan
,08-10 12:13:57.646  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 12:13:57.646  3716  3716 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 12:13:57.646  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 12:13:57.647  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 12:13:57.651  2646  2698 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-10 12:13:57.651  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:13:57.651  2646  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-10 12:13:57.652  3716  3766 I io.jxcore.node.ConnectionHelper: start: OK
,08-10 12:13:57.654  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 12:13:57.654  3716  3766 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-10 12:13:57.654  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.654  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 12:13:57.654  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.654  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 12:13:57.654  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 12:13:57.655  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 12:13:57.655  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 12:13:57.655  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 12:13:57.655  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 12:13:57.655  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 12:13:57.656  3716  3766 D BluetoothAdapter: STATE_ON
08-10 12:13:57.656  2646  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
08-10 12:13:57.656  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:13:57.656  2646  2703 D BtGatt.ScanManager: Starting BLE batch scan
08-10 12:13:57.656  2646  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 12:13:57.656  2646  2831 D BtGatt.GattService: stopScan() - queue size =1
08-10 12:13:57.657  2646  2662 D BtGatt.GattService: unregisterClient() - clientIf=5
08-10 12:13:57.657  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-10 12:13:57.658  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 12:13:57.658  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 12:13:57.658  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 12:13:57.658  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-10 12:13:57.659  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 12:13:57.659  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 12:13:57.659  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 12:13:57.659  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 12:13:57.659  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 12:13:57.660  3716  3716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 12:13:57.660  3716  3716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 12:13:57.661  3716  3716 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 12:13:57.661  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 12:13:57.661  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.661  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 12:13:57.661  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.661  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.661  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.661  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 12:13:57.661  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.662  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.662  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.663  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.663  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.663  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.663  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
,08-10 12:13:57.664  3716  3766 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-10 12:13:57.665  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 12:13:57.666  2646  2698 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-10 12:13:57.667  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:13:57.668  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 12:13:57.668  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:13:57.668  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:13:57.668  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:13:57.668  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:13:57.668  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:13:57.668  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:13:57.668  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 12:13:57.670  3716  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 12:13:57.671  3716  3766 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 12:13:57.671  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 12:13:57.671  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 12:13:57.671  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 12:13:57.671  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 12:13:57.671  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 12:13:57.673  2646  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 12:13:57.673  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:13:57.673  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:13:57.674  3716  3766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-10 12:13:57.674  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 12:13:57.677  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:13:57.678  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 12:13:57.679  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-10 12:13:57.679  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 12:13:57.680  2646  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 12:13:57.680  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:13:57.680  2646  2703 D BtGatt.ScanManager: stopping BLe Batch
,08-10 12:13:57.682  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 12:13:57.682  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 12:13:57.682  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-10 12:13:57.683  3716  3766 D BluetoothAdapter: STATE_ON
,08-10 12:13:57.685  2646  2661 D BtGatt.GattService: registerClient() - UUID=adcb3c10-f22f-4f33-8ba6-0ece4743c94e
,08-10 12:13:57.685  2646  2698 D BtGatt.GattService: onClientRegistered() - UUID=adcb3c10-f22f-4f33-8ba6-0ece4743c94e, clientIf=5
,08-10 12:13:57.685  3716  3762 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-10 12:13:57.686  2646  2833 D BtGatt.GattService: start scan with filters
,08-10 12:13:57.686  2646  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-10 12:13:57.686  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:13:57.686  2646  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 12:13:57.689  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-10 12:13:57.689  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-10 12:13:57.689  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-10 12:13:57.689  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 12:13:57.692  2646  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 12:13:57.692  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:13:57.694  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 12:13:57.694  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 12:13:57.694  2646  2703 D BtGatt.ScanManager: handling starting scan
08-10 12:13:57.694  3716  3716 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 12:13:57.695  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 12:13:57.697  3716  3766 I io.jxcore.node.ConnectionHelper: start: OK
,08-10 12:13:57.698  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.698  3716  3766 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-10 12:13:57.698  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.698  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 12:13:57.698  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.698  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 12:13:57.698  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 12:13:57.698  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 12:13:57.698  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 12:13:57.698  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 12:13:57.698  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 12:13:57.699  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-10 12:13:57.699  3716  3766 D BluetoothAdapter: STATE_ON
08-10 12:13:57.700  2646  2833 D BtGatt.GattService: stopScan() - queue size =1
08-10 12:13:57.700  2646  2698 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-10 12:13:57.700  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:13:57.700  2646  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-10 12:13:57.702  2646  2662 D BtGatt.GattService: unregisterClient() - clientIf=5
08-10 12:13:57.702  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-10 12:13:57.702  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 12:13:57.702  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 12:13:57.702  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 12:13:57.702  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-10 12:13:57.704  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 12:13:57.704  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 12:13:57.704  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 12:13:57.704  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 12:13:57.704  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 12:13:57.706  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.706  3716  3766 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-10 12:13:57.706  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.706  2646  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 12:13:57.706  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:13:57.706  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:13:57.706  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.706  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.706  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 12:13:57.706  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.706  2646  2703 D BtGatt.ScanManager: Starting BLE batch scan
,08-10 12:13:57.706  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.706  2646  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 12:13:57.706  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.706  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.706  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.706  3716  3716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 12:13:57.707  3716  3716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 12:13:57.707  3716  3716 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 12:13:57.707  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.707  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.708  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.708  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.708  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.708  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.709  3716  3766 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-10 12:13:57.709  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.709  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.709  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:13:57.710  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.710  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.710  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.710  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.710  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.710  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.710  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.710  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.710  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.710  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.710  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.711  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.711  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.711  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.711  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
,08-10 12:13:57.712  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 12:13:57.712  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.712  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.712  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:13:57.713  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.713  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.713  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.713  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.713  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.713  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.713  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.713  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.713  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.713  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.713  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.714  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.714  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.714  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.714  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
,08-10 12:13:57.715  3716  3766 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-10 12:13:57.715  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.715  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.715  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:13:57.715  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.715  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.715  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.716  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.716  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.716  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.716  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.716  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.716  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.716  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.716  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.717  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.717  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.717  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 12:13:57.717  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.717  2646  2698 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-10 12:13:57.717  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:13:57.718  3716  3766 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-10 12:13:57.718  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.718  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.718  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:13:57.718  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 12:13:57.718  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.718  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.718  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.719  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.719  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.719  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.719  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.719  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.719  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.719  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.720  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.720  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.720  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.720  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
,08-10 12:13:57.721  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-10 12:13:57.722  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 12:13:57.722  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-10 12:13:57.722  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 12:13:57.723  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 12:13:57.723  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 12:13:57.723  2646  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 12:13:57.723  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:13:57.723  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.724  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.724  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:13:57.724  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.724  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.724  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.724  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
,08-10 12:13:57.724  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 12:13:57.724  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
,08-10 12:13:57.724  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.724  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-10 12:13:57.724  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.724  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.724  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.725  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,08-10 12:13:57.725  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 12:13:57.726  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.726  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
,08-10 12:13:57.726  3716  3766 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-10 12:13:57.726  3716  3766 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55,
08-10 12:13:57.726  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
,08-10 12:13:57.728  3716  3766 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-10 12:13:57.729  3716  3766 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-10 12:13:57.729  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-10 12:13:57.730  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-10 12:13:57.730  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-10 12:13:57.730  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-10 12:13:57.730  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 12:13:57.730  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-10 12:13:57.730  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 12:13:57.730  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 12:13:57.730  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-10 12:13:57.730  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 12:13:57.730  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-10 12:13:57.730  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 12:13:57.730  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-10 12:13:57.730  3716  3766 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-10 12:13:57.730  3716  3766 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 12:13:57.730  3716  3766 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-10 12:13:57.731  3716  3766 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
08-10 12:13:57.731  3716  3766 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 12:13:57.731  3716  3766 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-10 12:13:57.731  3716  3766 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-10 12:13:57.731  3716  3766 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 12:13:57.731  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-10 12:13:57.732  2646  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-10 12:13:57.732  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:13:57.732  2646  2703 D BtGatt.ScanManager: stopping BLe Batch
08-10 12:13:57.736  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-10 12:13:57.737  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-10 12:13:57.737  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0,
08-10 12:13:57.737  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-10 12:13:57.737  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-10 12:13:57.738  3716  3766 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-10 12:13:57.738  3716  3766 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-10 12:13:57.738  3716  3766 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-10 12:13:57.738  3716  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 406)
,08-10 12:13:57.738  2646  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-10 12:13:57.738  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:13:57.738  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 12:13:57.739  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 12:13:57.739  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:13:57.739  2646  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,08-10 12:13:57.739  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 12:13:57.739  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.739  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.739  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads,
08-10 12:13:57.740  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
,08-10 12:13:57.740  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.740  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
,08-10 12:13:57.740  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 12:13:57.740  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.740  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.740  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.740  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.740  3716  3780 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 12:13:57.741  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.741  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 12:13:57.741  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.741  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
,08-10 12:13:57.742  3716  3766 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-10 12:13:57.743  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.743  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.743  3716  3781 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 406,
08-10 12:13:57.743  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:13:57.743  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.743  3716  3781 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 406)
08-10 12:13:57.743  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.743  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.743  3716  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 406)
08-10 12:13:57.743  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
,08-10 12:13:57.743  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.743  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.743  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 12:13:57.743  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.743  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.743  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.744  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.744  2646  2828 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-10 12:13:57.745  3716  3781 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 406)
08-10 12:13:57.745  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.745  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.745  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 12:13:57.745  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.745  2646  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 12:13:57.745  2646  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:13:57.747  3716  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-10 12:13:57.747  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.747  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.747  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 12:13:57.747  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.747  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.747  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-10 12:13:57.747  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.747  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 12:13:57.748  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.748  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.748  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.748  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.748  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.748  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.749  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.749  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.749  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-10 12:13:57.749  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.750  3716  3766 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-10 12:13:57.750  3716  3766 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-10 12:13:57.750  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 12:13:57.750  3716  3766 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-10 12:13:57.750  3716  3766 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55,
08-10 12:13:57.750  3716  3766 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-10 12:13:57.750  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 12:13:57.750  3716  3766 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-10 12:13:57.750  3716  3766 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-10 12:13:57.750  3716  3766 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 12:13:57.750  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 12:13:57.750  3716  3766 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-10 12:13:57.750  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.751  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-10 12:13:57.751  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:13:57.751  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 12:13:57.751  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.751  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.751  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
,08-10 12:13:57.751  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.751  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
,08-10 12:13:57.751  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.751  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.751  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.751  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.751  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.753  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-10 12:13:57.753  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.753  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.753  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.754  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 12:13:57.754  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.754  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.754  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
,08-10 12:13:57.754  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.754  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list,
08-10 12:13:57.754  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 12:13:57.754  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.754  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.754  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 12:13:57.754  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.754  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 12:13:57.754  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.754  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.755  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.755  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 12:13:57.755  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.755  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:13:57.755  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.755  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.755  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:13:57.755  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.755  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.755  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.755  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 12:13:57.756  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.756  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.756  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.756  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.756  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.756  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.756  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 12:13:57.757  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.758  3716  3766 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-10 12:13:57.758  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 12:13:57.759  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-10 12:13:57.760  3716  3766 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-10 12:13:57.760  3716  3766 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-10 12:13:57.760  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-10 12:13:57.760  3716  3716 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-10 12:13:57.760  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 12:13:57.760  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.760  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-10 12:13:57.760  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-10 12:13:57.760  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-10 12:13:57.760  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.761  3716  3766 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-10 12:13:57.761  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.761  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 12:13:57.761  3716  3716 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-10 12:13:57.761  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 12:13:57.761  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-10 12:13:57.761  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 12:13:57.761  3716  3782 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 12:13:57.761  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.761  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.762  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 12:13:57.762  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
,08-10 12:13:57.762  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.762  3716  3782 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-10 12:13:57.762  3716  3782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
,08-10 12:13:57.762  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.762  3716  3782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-10 12:13:57.762  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-10 12:13:57.762  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.762  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.762  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.763  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.763  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 12:13:57.763  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
,08-10 12:13:57.763  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.763  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.763  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-10 12:13:57.763  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.763  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.764  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.764  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 12:13:57.764  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.764  3716  3716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 12:13:57.764  3716  3716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 12:13:57.764  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.764  3716  3716 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 12:13:57.765  3716  3716 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-10 12:13:57.765  3716  3766 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-10 12:13:57.766  3716  3766 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 12:13:57.766  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 12:13:57.767  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 12:13:57.767  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 12:13:57.768  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.768  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:13:57.768  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.769  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.769  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.769  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.769  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.769  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.769  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.769  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:13:57.769  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.769  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.769  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.770  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.770  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.771  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.771  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.774  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.774  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.774  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:13:57.774  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.774  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.774  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.774  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.774  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.774  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.774  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.774  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.774  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.774  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.774  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.775  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.775  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.775  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.776  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.776  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:13:57.776  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:13:57.776  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state, already matches the desired outcome of this operation, skipping...
08-10 12:13:57.776  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:13:57.776  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.777  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.777  3716  3766 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dcc18f not in the list
08-10 12:13:57.777  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.777  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.777  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:13:57.777  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.777  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.777  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:13:57.777  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:13:57.778  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:13:57.778  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:13:57.778  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:13:57.778  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f922c1c not in the list
08-10 12:13:57.779  3716  3766 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-10 12:13:57.779  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 12:13:57.779  3716  3766 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-10 12:13:57.779  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 12:13:57.779  3716  3766 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-10 12:13:57.779  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 12:13:57.781  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 12:13:57.781  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-10 12:13:57.781  3716  3766 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-10 12:13:57.782  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 12:13:57.782  3716  3766 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-10 12:13:57.782  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 12:13:57.782  3716  3766 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-10 12:13:57.782  3716  3766 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-10 12:13:57.782  3716  3766 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-10 12:13:57.782  3716  3766 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-10 12:13:57.783  3716  3766 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-10 12:13:57.783  3716  3766 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-10 12:13:57.783  3716  3766 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-10 12:13:57.783  3716  3766 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-10 12:13:57.784  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 12:13:57.784  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5dbc99e added. We now have 2 listener(s)
08-10 12:13:57.784  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 12:13:57.786  3716  3766 D BluetoothAdapter: enable(): BT is already enabled..!
08-10 12:13:57.786   875  1686 D WifiService: setWifiEnabled: true pid=3716, uid=10000
08-10 12:13:57.786   875  1686 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 12:13:57.787  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 12:13:57.787  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4372c7f added. We now have 3 listener(s)
08-10 12:13:57.787  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 12:13:57.793  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 12:13:57.793  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@446d44c added. We now have 4 listener(s)
08-10 12:13:57.793  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 12:13:57.795  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 12:13:57.795  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59fbc95 added. We now have 5 listener(s)
08-10 12:13:57.795  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 12:13:57.798   875  1408 D WifiService: setWifiEnabled: false pid=3716, uid=10000
08-10 12:13:57.798   875  1408 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 12:13:57.805  2646  2694 D BluetoothAdapterState: Current state: ON, message: 23
08-10 12:13:57.805  2646  2694 D BluetoothAdapterProperties: Setting state to 13
08-10 12:13:57.805  2646  2694 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-10 12:13:57.805  2646  2694 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 12:13:57.807  2646  2694 I BluetoothAdapterState: Entering PendingCommandState
08-10 12:13:57.808  2646  2646 D BluetoothMapService: onReceive
08-10 12:13:57.808  2646  2646 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 12:13:57.808  2646  2646 D BluetoothMapService: STATE_TURNING_OFF
08-10 12:13:57.808  2646  2646 D BluetoothMapService: MAP Service closeService in
08-10 12:13:57.808  2646  2646 D BluetoothMapMasInstance0: MAP Service shutdown
08-10 12:13:57.808  2646  2646 D ObexServerSockets0: shutdown(block = true)
08-10 12:13:57.809  2646  2646 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 12:13:57.809  2646  2646 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 12:13:57.809  2646  2852 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-10 12:13:57.809  2646  2828 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-10 12:13:57.809  2646  2853 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-10 12:13:57.810  2646  2646 I BtOppRfcommListener: stopping Accept Thread
08-10 12:13:57.810  2646  3402 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 12:13:57.811  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 12:13:57.811  2646  3402 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 12:13:57.813   875  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 12:13:57.813   875  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-10 12:13:57.813   875  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 12:13:57.813   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 12:13:57.815  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:13:57.815  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:13:57.815  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:13:57.815  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:13:57.815  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:13:57.815  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 12:13:57.815  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:13:57.815  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:13:57.815  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 12:13:57.816  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:13:57.817  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 12:13:57.821   875  2135 D DhcpClient: Clearing IP address
08-10 12:13:57.822   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-10 12:13:57.824   373   873 D CommandListener: Setting iface cfg
08-10 12:13:57.826   875  2136 D DhcpClient: Receive thread stopped
08-10 12:13:57.826   875   888 I ActivityManager: Start proc 3785:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-10 12:13:57.827  2646  2698 D BluetoothAdapterProperties: Scan Mode:20
08-10 12:13:57.827  2646  2694 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-10 12:13:57.827  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 12:13:57.828  1492  2308 V NativeCrypto: Read error: ssl=0x9b55fe00: I/O error during system call, Connection timed out
08-10 12:13:57.830  2646  2646 D HeadsetService: Received stop request...Stopping profile...
08-10 12:13:57.831  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:13:57.832  1492  2308 V NativeCrypto: SSL shutdown failed: ssl=0x9b55fe00: I/O error during system call, Broken pipe
08-10 12:13:57.835   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 12:13:57.835  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:13:57.835  1348  2125 D BluetoothHeadset: Proxy object disconnected
08-10 12:13:57.835  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 12:13:57.835  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:13:57.835  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:13:57.835  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:13:57.835  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 12:13:57.835  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:13:57.835  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:13:57.835  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 12:13:57.836   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 12:13:57.836   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 12:13:57.836  1748  1907 D BluetoothHeadset: Proxy object disconnected
08-10 12:13:57.836  1348  1348 D HeadsetProfile: Bluetooth service disconnected
08-10 12:13:57.838  2646  2646 D A2dpService: Received stop request...Stopping profile...
08-10 12:13:57.838  2646  2835 D A2dpStateMachine: Exit Disconnected: -1
08-10 12:13:57.838  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:13:57.839  3716  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 12:13:57.839  3716  3766 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 12:13:57.840   875  1408 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-10 12:13:57.840   875  2132 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-10 12:13:57.840   875   875 D BluetoothA2dp: Proxy object disconnected
08-10 12:13:57.841  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:13:57.841  2646  2646 D HidService: Received stop request...Stopping profile...
08-10 12:13:57.841  2646  2646 D HidService: Stopping Bluetooth HidService
,08-10 12:13:57.841  1348  1348 D BluetoothA2dp: Proxy object disconnected
08-10 12:13:57.842  1348  1348 D BluetoothInputDevice: Proxy object disconnected
08-10 12:13:57.842  1348  1348 D HidProfile: Bluetooth service disconnected
08-10 12:13:57.842  2646  2646 D HealthService: Received stop request...Stopping profile...
08-10 12:13:57.843   875  2132 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-10 12:13:57.844  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:13:57.844   875  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-10 12:13:57.844   875  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-10 12:13:57.844  2646  2646 D PanService: Received stop request...Stopping profile...
08-10 12:13:57.845   875  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-10 12:13:57.845  1348  1348 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 12:13:57.846  1348  1348 D PanProfile: Bluetooth service disconnected
08-10 12:13:57.846  2646  2646 V BluetoothAdapterState: isTurningOff()=true
08-10 12:13:57.846  2646  2646 V BluetoothAdapterState: isTurningOn()=false
08-10 12:13:57.846  2646  2646 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:13:57.846  2646  2646 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:13:57.848  2646  2646 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 12:13:57.848  2646  2646 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 12:13:57.848  2646  2698 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-10 12:13:57.848  2646  2823 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 12:13:57.848  2646  2823 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 12:13:57.848  2646  2823 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 12:13:57.849  2646  2698 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-10 12:13:57.852   875  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 12:13:57.853   875  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-10 12:13:57.857   875  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
08-10 12:13:57.857   875  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 12:13:57.860   396   396 E Parcel  : Reading a NULL string not supported here.
08-10 12:13:57.862   875  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-10 12:13:57.863   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-10 12:13:57.864  2646  2646 D BluetoothMapService: Received stop request...Stopping profile...
08-10 12:13:57.864  2646  2646 D BluetoothMapService: stop()
08-10 12:13:57.865  2646  2646 D BluetoothMapAppObserver: deinitObservers()
08-10 12:13:57.865  2646  2646 D BluetoothMapAppObserver: removeReceiver()
08-10 12:13:57.866  2646  2646 V BluetoothAdapterState: isTurningOff()=true
08-10 12:13:57.866  2646  2646 V BluetoothAdapterState: isTurningOn()=false
08-10 12:13:57.867  2646  2646 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:13:57.867  2646  2646 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:13:57.867  1348  1348 D BluetoothMap: Proxy object disconnected
08-10 12:13:57.867  1348  1348 D MapProfile: Bluetooth service disconnected
08-10 12:13:57.867  2646  2698 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-10 12:13:57.867  2646  2823 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 12:13:57.868  2646  2823 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 12:13:57.868  2646  2823 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 12:13:57.868  2646  2823 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 12:13:57.868  2646  2823 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 12:13:57.868  2646  2823 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 12:13:57.869  2646  2646 V BluetoothAdapterState: isTurningOff()=true
08-10 12:13:57.869  2646  2646 V BluetoothAdapterState: isTurningOn()=false
08-10 12:13:57.869  2646  2646 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:13:57.870  2646  2646 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:13:57.870  2646  2646 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 12:13:57.870  2646  2698 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 12:13:57.871  2646  2646 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 12:13:57.872  2646  2646 V BluetoothAdapterState: isTurningOff()=true
08-10 12:13:57.872  2646  2646 V BluetoothAdapterState: isTurningOn()=false
08-10 12:13:57.872  2646  2646 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:13:57.872  2646  2646 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:13:57.872  2646  2646 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-10 12:13:57.872  2646  2698 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-10 12:13:57.872  2646  2646 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 12:13:57.872  2646  2646 V BluetoothAdapterState: isTurningOff()=true
08-10 12:13:57.872  2646  2646 V BluetoothAdapterState: isTurningOn()=false
08-10 12:13:57.872  2646  2646 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:13:57.873  2646  2646 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:13:57.873  2646  2646 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 12:13:57.873  2646  2646 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 12:13:57.874  2646  2646 D BluetoothMapService: MAP Service closeService in
08-10 12:13:57.874  2646  2646 V BluetoothAdapterState: isTurningOff()=true
08-10 12:13:57.874  2646  2646 V BluetoothAdapterState: isTurningOn()=false
08-10 12:13:57.874  2646  2646 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:13:57.874  2646  2646 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:13:57.874  2646  2694 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-10 12:13:57.874  2646  2694 D BluetoothAdapterProperties: Setting state to 15
08-10 12:13:57.874  2646  2694 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-10 12:13:57.874  2646  2646 D BluetoothMapService: cleanup()
08-10 12:13:57.874  2646  2646 D BluetoothMapService: MAP Service closeService in
08-10 12:13:57.874  2646  2694 I BluetoothAdapterState: Entering BleOnState
08-10 12:13:57.874  1348  2125 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 12:13:57.875   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 12:13:57.880  1348  1359 D BluetoothPan: onBluetoothStateChange on: false
08-10 12:13:57.881   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 12:13:57.881  1348  1360 D BluetoothMap: onBluetoothStateChange: up=false
08-10 12:13:57.881  1748  1761 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 12:13:57.881   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 12:13:57.881  1348  2125 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 12:13:57.882  1348  1359 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 12:13:57.882  1348  1360 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 12:13:57.883   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 12:13:57.883  2646  2694 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-10 12:13:57.883  2646  2694 D BluetoothAdapterProperties: Setting state to 16
08-10 12:13:57.883  2646  2694 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-10 12:13:57.884  2646  2694 D BluetoothAdapterProperties: onBleDisable
08-10 12:13:57.884  2646  2694 I BluetoothAdapterState: Entering PendingCommandState
08-10 12:13:57.885  2646  2695 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-10 12:13:57.886  2646  2698 D BluetoothAdapterProperties: Scan Mode:20
08-10 12:13:57.886  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:13:57.886  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:13:57.886  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:13:57.886  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:13:57.886  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:13:57.886  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 12:13:57.886  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:13:57.886  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:13:57.886  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 12:13:57.886  2646  2823 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-10 12:13:57.886  2646  2823 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 12:13:57.888  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:13:57.888  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 12:13:57.891  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:13:57.891  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:13:57.891  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:13:57.891  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:13:57.891  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:13:57.891  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 12:13:57.891  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:13:57.891  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:13:57.891  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 12:13:57.905   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 12:13:57.906  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:13:57.906  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 12:13:57.908  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:13:57.910  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:13:57.922  3785  3785 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-10 12:13:57.924   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 12:13:57.925   875  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-10 12:13:57.925   875  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 12:13:57.926   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-10 12:13:57.930  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:13:57.931  3335  3335 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@c067ecf and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-10 12:13:57.931  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:13:57.933   875  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 12:13:57.937  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 12:13:57.937  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:13:57.937  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:13:57.937  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:13:57.937  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 12:13:57.937  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 12:13:57.937  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:13:57.937  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:13:57.937  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 12:13:57.938  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:13:57.938  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 12:13:57.938   875  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 12:13:57.939  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 12:13:57.940  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:13:57.940  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:13:57.940  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:13:57.940  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 12:13:57.940  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 12:13:57.940  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:13:57.940  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:13:57.940  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 12:13:57.941  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:13:57.941  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 12:13:57.942  1810  2060 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 12:13:57.949  3785  3785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 12:13:57.955  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 12:13:57.967   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e97cebf:true
,08-10 12:13:57.968   875  1765 I ActivityManager: Start proc 3804:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-10 12:13:57.995   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-10 12:13:57.996   875  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 12:13:58.000  3785  3785 D LocalBluetoothProfileManager: Adding local MAP profile
,08-10 12:13:58.001  3785  3785 D BluetoothMap: Create BluetoothMap proxy object
,08-10 12:13:58.011  3804  3804 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-10 12:13:58.014  3785  3785 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-10 12:13:58.026  3785  3785 D DockEventReceiver: finishStartingService: stopping service
,08-10 12:13:58.036   875  1762 I ActivityManager: Killing 3144:com.google.android.gm/u0a78 (adj 15): empty #17
,08-10 12:13:58.090  2646  2698 I bt_hci  : shut_down
,08-10 12:13:58.090  2646  2704 D bt_hwcfg: hw_epilog_process
08-10 12:13:58.091  2646  2704 I bt_vendor: low_power_mode_cb
,08-10 12:13:58.116  2646  2704 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-10 12:13:58.116  2646  2704 I bt_vendor: epilog_cb
,08-10 12:13:58.116  2646  2704 I bt_hci  : epilog_finished_callback
,08-10 12:13:58.118  2646  2698 I bt_hci_h4: hal_close
,08-10 12:13:58.119  2646  2698 I bt_userial_vendor: device fd = 51 close
,08-10 12:13:58.189  3804  3804 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 12:13:58.189  3804  3804 D StrictMode: ,	at android.os.Looper.loop(Looper.java:148)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 12:13:58.189  3804  3804 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 12:13:58.189  3804  3804 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 12:13:58.189  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 12:13:58.190  3804  3804 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.r.e.b(PG:170)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 12:13:58.190  3804  3804 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.r.k.d(PG:583)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.r.e.b(PG:170)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 12:13:58.190  3804  3804 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at andr,oid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 12:13:58.190  3804  3804 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 12:13:58.190  3804  3804 D StrictMode,: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 12:13:58.190  3804  3804 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 12:13:58.190  3804  3804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 12:13:58.196  3785  3785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 12:13:58.202  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 12:13:58.210  3785  3785 D DockEventReceiver: finishStartingService: stopping service
08-10 12:13:58.216   875  1702 I ActivityManager: Killing 3335:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-10 12:13:58.266  3716  3716 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 12:13:58.311  2646  2695 D bt_stack_manager: event_shut_down_stack finished.
,08-10 12:13:58.311  2646  2694 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-10 12:13:58.318  2646  2694 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-10 12:13:58.318  2646  2646 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 12:13:58.319  2646  2646 D BtGatt.GattService: Received stop request...Stopping profile...
,08-10 12:13:58.319  2646  2646 D BtGatt.GattService: stop()
,08-10 12:13:58.320  2646  2646 D BtGatt.AdvertiseManager: advertise clients cleared
08-10 12:13:58.320  1778  1778 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 12:13:58.323  2646  2646 V BluetoothAdapterState: isTurningOff()=false
,08-10 12:13:58.323  2646  2646 V BluetoothAdapterState: isTurningOn()=false
,08-10 12:13:58.324  2646  2646 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 12:13:58.324  2646  2646 V BluetoothAdapterState: isBleTurningOff()=true
,08-10 12:13:58.326  2646  2694 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-10 12:13:58.326  2646  2694 D BluetoothAdapterProperties: Setting state to 10
,08-10 12:13:58.326  2646  2694 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-10 12:13:58.330  2646  2694 I BluetoothAdapterState: Entering OffState
08-10 12:13:58.332   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-10 12:13:58.335  1778  1778 D SystemUpdateService: onCreate
,08-10 12:13:58.349  1778  1778 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 12:13:58.359  2646  2646 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-10 12:13:58.359  2646  2646 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-10 12:13:58.359  2646  2695 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-10 12:13:58.359  2646  2646 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-10 12:13:58.363  2646  2695 D bt_stack_manager: event_clean_up_stack finished.
,08-10 12:13:58.365  2646  2646 I art     : System.exit called, status: 0
,08-10 12:13:58.365  2646  2646 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-10 12:13:58.375  1778  1778 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-10 12:13:58.378  1778  2362 I iu.UploadsManager: num queued entries: 0
,08-10 12:13:58.378  1778  2362 I iu.UploadsManager: num updated entries: 0
,08-10 12:13:58.396  1778  2362 I iu.SyncManager: NEXT; no task
,08-10 12:13:58.397  1778  1778 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 12:13:58.400  1778  3837 I SystemUpdateService: active receiver: enabled
,08-10 12:13:58.411  1778  1778 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 12:13:58.426  1778  3837 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 12:13:58.429  1778  3837 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-10 12:13:58.430  1778  3837 I SystemUpdateService: now status is 0 (complete)
08-10 12:13:58.430  1778  3837 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-10 12:13:58.430  1778  3837 I SystemUpdateService: file has been verified
08-10 12:13:58.430  1778  3837 I SystemUpdateService: OTA package size = 12249756
,08-10 12:13:58.437  1778  3837 I SystemUpdateService: showing system update notification
,08-10 12:13:58.443  3804  3823 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-10 12:13:58.449   875   886 I ActivityManager: Start proc 3841:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-10 12:13:58.450   875  1759 I ActivityManager: Process com.android.bluetooth (pid 2646) has died
,08-10 12:13:58.473  1778  1778 D SystemUpdateService: onDestroy
,08-10 12:13:58.508  3841  3841 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-10 12:13:58.509   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d331fbb:true
,08-10 12:13:58.511  3841  3841 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 12:13:58.522  3841  3841 D SprintDMHelper: simOperator: 
,08-10 12:13:58.522  3841  3841 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 12:13:58.536   875   886 I ActivityManager: Start proc 3854:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-10 12:13:58.615  2971  3868 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-10 12:13:58.621   875  1759 I ActivityManager: Start proc 3869:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-10 12:13:58.624   875  1742 I ActivityManager: Killing 3215:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-10 12:13:58.677  3869  3869 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-10 12:13:58.727  3869  3869 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-10 12:13:58.727  3869  3869 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-10 12:13:58.727  3869  3869 I GAv4    :   adb logcat -s GAv4
,08-10 12:13:58.747  3869  3869 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-10 12:13:58.757  3869  3869 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-10 12:13:58.782  3869  3886 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-10 12:13:58.893  3869  3869 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-10 12:13:58.935  3869  3869 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-10 12:13:58.942  3869  3869 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 798-800)
08-10 12:13:58.942  3869  3869 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 12:13:58.953  3869  3869 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5eab9bf}
08-10 12:13:58.953  3869  3869 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 12:13:58.954  3869  3869 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 12:13:58.960  3869  3869 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-10 12:13:58.961  3869  3869 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-10 12:13:58.977  3869  3869 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-10 12:13:58.988  3869  3869 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-10 12:13:58.988  3869  3869 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-10 12:13:58.988  3869  3869 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 12:13:58.988  3869  3869 I Adreno  : Build Date                       : 10/20/15
08-10 12:13:58.988  3869  3869 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 12:13:58.988  3869  3869 I Adreno  : Local Branch                     : M14
08-10 12:13:58.988  3869  3869 I Adreno  : Remote Branch                    : 
08-10 12:13:58.988  3869  3869 I Adreno  : Remote Branch                    : 
08-10 12:13:58.988  3869  3869 I Adreno  : Reconstruct Branch               : 
,08-10 12:13:59.053  3869  3869 I NSApplication: Starting up...
,08-10 12:13:59.064  3869  3915 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-10 12:13:59.084   875  1681 I ActivityManager: Start proc 3920:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-10 12:13:59.085   875  1681 I ActivityManager: Killing 2991:com.google.android.keep/u0a79 (adj 15): empty #17
,08-10 12:13:59.154  3920  3920 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-10 12:13:59.313   875  1742 I ActivityManager: Killing 3553:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-10 12:13:59.403   875   885 I ActivityManager: Start proc 3934:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-10 12:13:59.454  3934  3934 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-10 12:13:59.496  3934  3934 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-10 12:13:59.513   875  1764 I ActivityManager: Start proc 3957:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
08-10 12:13:59.515   875  1764 I ActivityManager: Killing 1687:android.process.acore/u0a5 (adj 15): empty #17
,08-10 12:13:59.600  3957  3957 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,08-10 12:13:59.876   875  1686 I ActivityManager: Killing 3603:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-10 12:14:00.842   875  1765 D WifiService: setWifiEnabled: true pid=3716, uid=10000
,08-10 12:14:00.842   875  1765 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 12:14:00.855   875  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-10 12:14:00.862  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 12:14:00.863  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:00.863  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:00.863  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:00.863  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:14:00.863  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 12:14:00.863  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:14:00.863  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:14:00.863  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 12:14:00.863  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 12:14:00.863  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 12:14:00.866  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 12:14:00.866  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:00.866  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:00.866  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:00.866  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:14:00.866  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 12:14:00.866  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:14:00.866  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:14:00.866  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 12:14:00.866  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 12:14:00.866  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 12:14:00.895   875  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-10 12:14:00.898   875  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-10 12:14:00.901   875  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-10 12:14:00.903   875  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-10 12:14:00.904   875  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-10 12:14:00.905   875  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-10 12:14:00.905   875  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-10 12:14:00.918   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-10 12:14:00.918   875  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.50 rxSuccessRate=11.25 delta 1000 -> 994
,08-10 12:14:00.920   373   873 D CommandListener: Setting iface cfg
,08-10 12:14:00.922   875  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-10 12:14:00.923   875  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-10 12:14:00.928   875  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-10 12:14:00.928   875  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-10 12:14:00.929   875  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-10 12:14:00.929   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 12:14:00.937   875  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-10 12:14:01.002   875  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-10 12:14:01.005  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-10 12:14:01.428  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 12:14:01.475  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-10 12:14:01.477  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-10 12:14:01.484   875  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 12:14:01.498   875  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 12:14:01.498   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 12:14:01.498   875  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-10 12:14:01.526   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 12:14:01.536   373   873 D CommandListener: Setting iface cfg
,08-10 12:14:01.537   875  1305 D WifiStateMachine: Start Dhcp Watchdog 2
,08-10 12:14:01.550   875  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-10 12:14:01.552   875  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-10 12:14:01.572   875  3990 D DhcpClient: Receive thread started
,08-10 12:14:01.655   875  1305 E native  : do suspend false
,08-10 12:14:01.677   875  2135 D DhcpClient: Broadcasting DHCPDISCOVER
,08-10 12:14:01.690   875  3990 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172689, domain null
,08-10 12:14:01.691   875  2135 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172689 seconds
,08-10 12:14:01.695   875  2135 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-10 12:14:01.708   875  3990 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-10 12:14:01.709   875  2135 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-10 12:14:01.714   373   873 D CommandListener: Setting iface cfg
,08-10 12:14:01.726   875  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-10 12:14:01.728   875  2135 D DhcpClient: Scheduling renewal in 86399s
,08-10 12:14:01.747   875  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-10 12:14:01.750   875  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-10 12:14:01.750   875  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-10 12:14:01.751   875  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-10 12:14:01.758   875  1307 D ConnectivityService: Adding iface wlan0 to network 101
,08-10 12:14:01.768   875  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-10 12:14:01.810   875  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-10 12:14:01.810   875  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-10 12:14:01.813   875  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-10 12:14:01.816   875  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-10 12:14:01.819   875  1307 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-10 12:14:01.830   875  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-10 12:14:01.837   875  1307 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-10 12:14:01.837   875  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-10 12:14:01.837   875  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-10 12:14:01.838   875  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 12:14:01.838   875  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-10 12:14:01.838   875  1307 D ConnectivityService:    accepting network in place of null
,08-10 12:14:01.839   875  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 12:14:01.850   875  3989 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133707, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 12:14:01.904   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 12:14:01.934   875  3988 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:401b:801::200e
,08-10 12:14:01.938   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 12:14:01.946   875  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-10 12:14:01.946   875  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 12:14:01.953   875  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-10 12:14:01.956   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-10 12:14:01.969  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:14:01.969  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:01.969  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:01.969  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:01.969  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:14:01.969  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 12:14:01.969  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:14:01.969  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:14:01.969  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 12:14:01.969  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 12:14:01.969  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 12:14:01.971  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:14:01.972  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:01.972  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:01.972  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:01.972  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:14:01.972  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 12:14:01.972  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:14:01.972  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:14:01.972  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 12:14:01.972  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 12:14:01.972  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 12:14:01.985  1778  1778 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 12:14:01.990  1778  1778 D SystemUpdateService: onCreate
,08-10 12:14:01.994  1778  1778 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 12:14:01.997  1778  4000 I SystemUpdateService: active receiver: enabled
,08-10 12:14:02.002  1778  4000 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 12:14:02.006  1778  4000 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-10 12:14:02.006  1778  4000 I SystemUpdateService: now status is 0 (complete)
08-10 12:14:02.006  1778  4000 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-10 12:14:02.006  1778  4000 I SystemUpdateService: file has been verified
,08-10 12:14:02.008  1778  4000 I SystemUpdateService: OTA package size = 12249756
,08-10 12:14:02.015  1778  4000 I SystemUpdateService: showing system update notification
,08-10 12:14:02.023  1778  1778 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-10 12:14:02.024  1778  2362 I iu.UploadsManager: num queued entries: 0
,08-10 12:14:02.025  1778  2362 I iu.UploadsManager: num updated entries: 0
08-10 12:14:02.025  1778  2362 I iu.SyncManager: NEXT; no task
,08-10 12:14:02.031   875  3988 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 10:14:02 GMT], X-Android-Received-Millis=[1470824042030], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470824042001]}
08-10 12:14:02.032  1778  1778 D SystemUpdateService: onDestroy
,08-10 12:14:02.035   875  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 12:14:02.035   875  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-10 12:14:02.035   875  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-10 12:14:02.036   875  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-10 12:14:02.039  1778  1778 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-10 12:14:02.039  1778  4004 I MDM     : [206] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-10 12:14:02.039  1778  4004 W BaseAppContext: Using Auth Proxy for data requests.
,08-10 12:14:02.040  1778  1778 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-10 12:14:02.040  1778  4004 V GoogleAuthProtoRequest: [206] a.<init>: mAccountName set to: thalitester@gmail.com
08-10 12:14:02.042  3841  3841 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 12:14:02.046  3841  3841 D SprintDMHelper: simOperator: 
08-10 12:14:02.046  3841  3841 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 12:14:02.049  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:02.051  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:02.089  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-10 12:14:02.089  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-10 12:14:02.089  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:14:02.089  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:14:02.105  1778  4004 E MDM     : [206] SitrepService.a: Error sending sitrep.
,08-10 12:14:02.167  2971  4007 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-10 12:14:02.945   875  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-10 12:14:03.579   875  1686 I ActivityManager: Killing 3619:com.android.musicfx/u0a18 (adj 15): empty #17
,08-10 12:14:03.849   875  1681 D WifiService: setWifiEnabled: false pid=3716, uid=10000
08-10 12:14:03.849   875  1681 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 12:14:03.887  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-10 12:14:03.894   875  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 12:14:03.895   875  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-10 12:14:03.895   875  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 12:14:03.895   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 12:14:03.935   875  2135 D DhcpClient: Clearing IP address
,08-10 12:14:03.935   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-10 12:14:03.939   373   873 D CommandListener: Setting iface cfg
,08-10 12:14:03.941  1492  4011 V NativeCrypto: Read error: ssl=0x9a502a00: I/O error during system call, Connection timed out
,08-10 12:14:03.942  1492  4011 V NativeCrypto: SSL shutdown failed: ssl=0x9a502a00: I/O error during system call, Broken pipe
,08-10 12:14:03.948   875  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-10 12:14:03.948   875  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-10 12:14:03.949   396   396 E Parcel  : Reading a NULL string not supported here.
08-10 12:14:03.953   875  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-10 12:14:03.954   875  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 12:14:03.957   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-10 12:14:03.958   875  3990 D DhcpClient: Receive thread stopped
08-10 12:14:03.959   875  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-10 12:14:03.969   875  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 12:14:03.972  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:14:03.973  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:03.973  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:03.973  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:03.973  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 12:14:03.973  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 12:14:03.973  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:14:03.973  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:14:03.973  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 12:14:03.973  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:14:03.974  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 12:14:03.975  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:14:03.975  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:03.975  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:03.975  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:03.975  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 12:14:03.975  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 12:14:03.975  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:14:03.975  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:14:03.975  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 12:14:03.975  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:14:03.975  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 12:14:03.975   875  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 12:14:03.978  1810  2060 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 12:14:03.996   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 12:14:04.019   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 12:14:04.020   875  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-10 12:14:04.021   875  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 12:14:04.025  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:04.025   875   892 D Tethering: MasterInitialState.processMessage what=3
08-10 12:14:04.027  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:04.041  1778  1778 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 12:14:04.047  1778  1778 D SystemUpdateService: onCreate
,08-10 12:14:04.051  1778  1778 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 12:14:04.063  1778  1778 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-10 12:14:04.066  1778  2362 I iu.UploadsManager: num queued entries: 0
,08-10 12:14:04.067  1778  2362 I iu.UploadsManager: num updated entries: 0
,08-10 12:14:04.067  1778  2362 I iu.SyncManager: NEXT; no task
,08-10 12:14:04.069  1778  4023 I SystemUpdateService: active receiver: enabled
,08-10 12:14:04.076  1778  1778 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 12:14:04.078  1778  1778 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 12:14:04.082  3841  3841 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 12:14:04.088  3841  3841 D SprintDMHelper: simOperator: 
,08-10 12:14:04.088  3841  3841 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 12:14:04.112   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-10 12:14:04.114   875  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-10 12:14:04.119  1778  4023 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 12:14:04.121  2971  4027 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-10 12:14:04.130  1778  4023 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-10 12:14:04.130  1778  4023 I SystemUpdateService: now status is 0 (complete)
08-10 12:14:04.130  1778  4023 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-10 12:14:04.130  1778  4023 I SystemUpdateService: file has been verified
08-10 12:14:04.130  1778  4023 I SystemUpdateService: OTA package size = 12249756
,08-10 12:14:04.135  1778  4023 I SystemUpdateService: showing system update notification
,08-10 12:14:04.143  1778  1778 D SystemUpdateService: onDestroy
,08-10 12:14:04.678  3957  3964 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@ec9afb)
,08-10 12:14:06.911   875   892 I ActivityManager: Start proc 4030:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-10 12:14:07.034  4030  4030 D AdapterServiceConfig: Adding HeadsetService
,08-10 12:14:07.034  4030  4030 D AdapterServiceConfig: Adding A2dpService
,08-10 12:14:07.034  4030  4030 D AdapterServiceConfig: Adding HidService
08-10 12:14:07.034  4030  4030 D AdapterServiceConfig: Adding HealthService
,08-10 12:14:07.035  4030  4030 D AdapterServiceConfig: Adding PanService
,08-10 12:14:07.035  4030  4030 D AdapterServiceConfig: Adding GattService
08-10 12:14:07.035  4030  4030 D AdapterServiceConfig: Adding BluetoothMapService
,08-10 12:14:07.050  4030  4030 D BluetoothAdapterState: make() - Creating AdapterState
,08-10 12:14:07.049   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@53a0e37:true
,08-10 12:14:07.053  4030  4030 I bt_bluedroid: init
,08-10 12:14:07.054  4030  4042 I BluetoothAdapterState: Entering OffState
,08-10 12:14:07.056  4030  4043 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-10 12:14:07.057  4030  4043 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-10 12:14:07.057  4030  4043 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-10 12:14:07.057  4030  4043 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-10 12:14:07.057  4030  4030 I bt_bluedroid: get_profile_interface socket
,08-10 12:14:07.059  4030  4030 I bt_bluedroid: get_profile_interface sdp
,08-10 12:14:07.062  4030  4041 I bt_bluedroid: config_hci_snoop_log
,08-10 12:14:07.062  4030  4046 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 12:14:07.068   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-10 12:14:07.069  4030  4046 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 12:14:07.074  4030  4042 D BluetoothAdapterState: Current state: OFF, message: 0
,08-10 12:14:07.075  4030  4042 D BluetoothAdapterProperties: Setting state to 14
,08-10 12:14:07.075  4030  4042 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-10 12:14:07.079  4030  4042 D BluetoothBondStateMachine: make
,08-10 12:14:07.083  4030  4047 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-10 12:14:07.089  4030  4042 I BluetoothAdapterState: Entering PendingCommandState
,08-10 12:14:07.089  4030  4030 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-10 12:14:07.091  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
,08-10 12:14:07.092  4030  4030 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 12:14:07.093  4030  4030 D BtGatt.GattService: Received start request. Starting profile...
,08-10 12:14:07.093  4030  4030 D BtGatt.GattService: start()
08-10 12:14:07.093  4030  4030 I bt_bluedroid: get_profile_interface gatt
08-10 12:14:07.094  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
08-10 12:14:07.094  4030  4030 D BtGatt.AdvertiseManager: advertise manager created
,08-10 12:14:07.100  4030  4030 V BluetoothAdapterState: isTurningOff()=false
,08-10 12:14:07.100  4030  4030 V BluetoothAdapterState: isTurningOn()=false
08-10 12:14:07.100  4030  4030 V BluetoothAdapterState: isBleTurningOn()=true
08-10 12:14:07.101  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:14:07.101  4030  4042 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-10 12:14:07.102  4030  4042 I bt_bluedroid: enable
08-10 12:14:07.102  4030  4043 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-10 12:14:07.103  4030  4043 I bt_hci  : start_up
,08-10 12:14:07.108  4030  4043 I bt_vendor: alloc value 0xb399c189
08-10 12:14:07.108  4030  4043 I bt_vendor: init
08-10 12:14:07.108  4030  4043 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-10 12:14:07.108  4030  4043 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-10 12:14:07.217  4030  4043 D bt_hci  : start_up starting async portion
,08-10 12:14:07.218  4030  4050 I bt_hci  : event_finish_startup
08-10 12:14:07.218  4030  4050 I bt_hci_h4: hal_open
,08-10 12:14:07.219  4030  4050 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-10 12:14:07.227  4030  4050 I bt_userial_vendor: device fd = 51 open
,08-10 12:14:07.258  4030  4050 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 12:14:07.291  4030  4050 D bt_hwcfg: Chipset BCM4354A2
,08-10 12:14:07.291  4030  4050 D bt_hwcfg: Target name = [BCM4354A2]
08-10 12:14:07.292  4030  4050 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-10 12:14:07.962  4030  4050 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-10 12:14:07.964  4030  4050 D bt_hwcfg: Settlement delay -- 100 ms
08-10 12:14:07.964  4030  4050 I bt_hwcfg: Setting fw settlement delay to 100 
,08-10 12:14:08.080  4030  4050 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 12:14:08.082  4030  4050 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-10 12:14:08.111  4030  4050 I bt_hwcfg: vendor lib fwcfg completed
,08-10 12:14:08.112  4030  4050 I bt_vendor: firmware callback
08-10 12:14:08.112  4030  4050 I bt_hci  : firmware_config_callback
,08-10 12:14:08.123  4030  4052 I bt_btu  : btu_task pending for preload complete event
,08-10 12:14:08.123  4030  4052 I bt_btu_task: Bluetooth chip preload is complete
08-10 12:14:08.123  4030  4052 I bt_btu  : btu_task received preload complete event
,08-10 12:14:08.133  4030  4052 I         : BTE_InitTraceLevels -- TRC_HCI
08-10 12:14:08.134  4030  4052 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-10 12:14:08.134  4030  4052 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-10 12:14:08.134  4030  4052 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 12:14:08.134  4030  4052 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-10 12:14:08.135  4030  4052 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 12:14:08.135  4030  4052 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 12:14:08.135  4030  4052 I         : BTE_InitTraceLevels -- TRC_BTM
,08-10 12:14:08.136  4030  4052 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 12:14:08.136  4030  4052 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 12:14:08.136  4030  4052 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 12:14:08.136  4030  4052 I         : BTE_InitTraceLevels -- TRC_GATT
,08-10 12:14:08.137  4030  4052 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 12:14:08.137  4030  4052 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 12:14:08.137  4030  4052 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 12:14:08.273  4030  4052 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3919d9d
,08-10 12:14:08.273  4030  4052 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3919d9d 
,08-10 12:14:08.283  4030  4046 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-10 12:14:08.287  4030  4046 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 12:14:08.288  4030  4046 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 12:14:08.292  4030  4046 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 12:14:08.300  4030  4046 D BluetoothAdapterProperties: Scan Mode:20
,08-10 12:14:08.300  4030  4046 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-10 12:14:08.301  4030  4046 D bt_hci  : do_postload posting postload work item
08-10 12:14:08.301  4030  4050 I bt_hci  : event_postload
,08-10 12:14:08.301  4030  4050 I bt_vendor: sco_config_cb
,08-10 12:14:08.301  4030  4050 I bt_hci  : sco_config_callback postload finished.
08-10 12:14:08.304  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:14:08.305  4030  4046 D bt_bte_conf: Device ID record 1 : primary
,08-10 12:14:08.306  4030  4046 D bt_bte_conf:   vendorId            = 000f
08-10 12:14:08.306  4030  4046 D bt_bte_conf:   vendorIdSource      = 0001
08-10 12:14:08.306  4030  4050 I bt_vendor: low_power_mode_cb
,08-10 12:14:08.306  4030  4046 D bt_bte_conf:   product             = 1200
08-10 12:14:08.307  4030  4046 D bt_bte_conf:   version             = 1436
08-10 12:14:08.307  4030  4046 D bt_bte_conf:   clientExecutableURL = 
,08-10 12:14:08.307  4030  4046 D bt_bte_conf:   serviceDescription  = 
08-10 12:14:08.307  4030  4046 D bt_bte_conf:   documentationURL    = 
08-10 12:14:08.307  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:08.308  4030  4046 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-10 12:14:08.308  4030  4043 D bt_stack_manager: event_start_up_stack finished
,08-10 12:14:08.310  4030  4042 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-10 12:14:08.310  4030  4042 D BluetoothAdapterProperties: Setting state to 15
08-10 12:14:08.310  4030  4042 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-10 12:14:08.311  4030  4042 I BluetoothAdapterState: Entering BleOnState
08-10 12:14:08.315  4030  4042 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-10 12:14:08.316  4030  4042 D BluetoothAdapterProperties: Setting state to 11
08-10 12:14:08.316  4030  4042 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-10 12:14:08.322  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
,08-10 12:14:08.326  4030  4030 D HeadsetService: Received start request. Starting profile...
,08-10 12:14:08.334  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:08.336  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:14:08.336  4030  4030 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-10 12:14:08.337  4030  4030 D HeadsetStateMachine: make
08-10 12:14:08.339  4030  4042 I BluetoothAdapterState: Entering PendingCommandState
,08-10 12:14:08.350  4030  4030 D HeadsetStateMachine: max_hf_connections = 1
,08-10 12:14:08.351  4030  4030 I bt_bluedroid: get_profile_interface handsfree
,08-10 12:14:08.351  4030  4046 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-10 12:14:08.352  4030  4046 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-10 12:14:08.359  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
,08-10 12:14:08.360  4030  4030 D A2dpService: Received start request. Starting profile...
,08-10 12:14:08.362  4030  4030 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-10 12:14:08.362  4030  4030 I bt_bluedroid: get_profile_interface avrcp
,08-10 12:14:08.372  4030  4030 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-10 12:14:08.372  4030  4030 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 12:14:08.372  4030  4030 D A2dpStateMachine: make
,08-10 12:14:08.374  4030  4030 I bt_bluedroid: get_profile_interface a2dp
,08-10 12:14:08.375  4030  4046 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-10 12:14:08.378  4030  4061 D A2dpStateMachine: Enter Disconnected: -2
08-10 12:14:08.379  4030  4030 I BluetoothHidServiceJni: classInitNative: succeeds
,08-10 12:14:08.381  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
,08-10 12:14:08.383  3785  3785 D BluetoothInputDevice: Proxy object connected
08-10 12:14:08.384  4030  4030 D HidService: Received start request. Starting profile...
,08-10 12:14:08.384  4030  4030 I bt_bluedroid: get_profile_interface hidhost
08-10 12:14:08.384  3785  3785 D HidProfile: Bluetooth service connected
08-10 12:14:08.384  4030  4046 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fb3e5
08-10 12:14:08.384  4030  4046 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-10 12:14:08.385  4030  4030 D HidService: setHidService(): set to: null
08-10 12:14:08.386  4030  4030 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-10 12:14:08.387  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
,08-10 12:14:08.389  4030  4030 D HealthService: Received start request. Starting profile...
,08-10 12:14:08.392  4030  4030 I bt_bluedroid: get_profile_interface health
,08-10 12:14:08.393  4030  4030 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-10 12:14:08.394  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
,08-10 12:14:08.396  3785  3785 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 12:14:08.396  4030  4030 D PanService: Received start request. Starting profile...
08-10 12:14:08.397  4030  4030 D BluetoothPanServiceJni: initializeNative(L110): pan
08-10 12:14:08.397  4030  4030 I bt_bluedroid: get_profile_interface pan
08-10 12:14:08.397  3785  3785 D PanProfile: Bluetooth service connected
,08-10 12:14:08.398  4030  4046 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-10 12:14:08.409  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 12:14:08.411  4030  4030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
08-10 12:14:08.413  4030  4030 D BluetoothMapService: Received start request. Starting profile...
,08-10 12:14:08.413  4030  4030 D BluetoothMapService: start()
08-10 12:14:08.414  3785  3785 D BluetoothMap: Proxy object connected
,08-10 12:14:08.415  3785  3785 D MapProfile: Bluetooth service connected
,08-10 12:14:08.415  3785  3785 D BluetoothMap: getConnectedDevices()
,08-10 12:14:08.417  4030  4030 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-10 12:14:08.417  3785  3785 D BluetoothMap: Bluetooth is Not enabled
08-10 12:14:08.417  4030  4030 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-10 12:14:08.418  4030  4030 D BluetoothMapAppObserver: createReceiver()
,08-10 12:14:08.419  4030  4030 D BluetoothMapAppObserver: initObservers()
08-10 12:14:08.419  4030  4030 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-10 12:14:08.427  4030  4030 V BluetoothAdapterState: isTurningOff()=false
08-10 12:14:08.427  4030  4030 V BluetoothAdapterState: isTurningOn()=true
,08-10 12:14:08.427  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:14:08.427  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 12:14:08.429  4030  4030 V BluetoothAdapterState: isTurningOff()=false
,08-10 12:14:08.429  4030  4030 V BluetoothAdapterState: isTurningOn()=true
08-10 12:14:08.429  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 12:14:08.429  4030  4059 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-10 12:14:08.429  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:14:08.429  4030  4030 V BluetoothAdapterState: isTurningOff()=false
08-10 12:14:08.429  4030  4030 V BluetoothAdapterState: isTurningOn()=true
,08-10 12:14:08.429  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:14:08.429  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:14:08.430  4030  4030 V BluetoothAdapterState: isTurningOff()=false
08-10 12:14:08.430  4030  4030 V BluetoothAdapterState: isTurningOn()=true
,08-10 12:14:08.430  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 12:14:08.430  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:14:08.430  4030  4030 V BluetoothAdapterState: isTurningOff()=false
08-10 12:14:08.430  4030  4030 V BluetoothAdapterState: isTurningOn()=true
08-10 12:14:08.430  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:14:08.430  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 12:14:08.431  4030  4030 V BluetoothAdapterState: isTurningOff()=false
08-10 12:14:08.431  4030  4030 V BluetoothAdapterState: isTurningOn()=true
08-10 12:14:08.431  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:14:08.431  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:14:08.431  4030  4042 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-10 12:14:08.431  4030  4042 D BluetoothAdapterProperties: ScanMode =  20
08-10 12:14:08.432  4030  4042 D BluetoothAdapterProperties: State =  11
08-10 12:14:08.432  4030  4042 D BluetoothAdapterProperties: Setting state to 12
08-10 12:14:08.432  4030  4042 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 12:14:08.433  4030  4042 I BluetoothAdapterState: Entering OnState
08-10 12:14:08.433  3785  3797 D BluetoothPbap: onBluetoothStateChange: up=true
,08-10 12:14:08.435  4030  4046 D BluetoothAdapterProperties: Scan Mode:21
08-10 12:14:08.435  4030  4046 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 12:14:08.440  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:08.440  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:08.440  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:08.440  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 12:14:08.440  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:14:08.440  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:14:08.440  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:14:08.440  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 12:14:08.441  1348  1360 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 12:14:08.443   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 12:14:08.443  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 12:14:08.443  1348  2125 D BluetoothPan: onBluetoothStateChange on: true
08-10 12:14:08.444   875   875 D BluetoothA2dp: Proxy object connected
08-10 12:14:08.444  1348  1348 D BluetoothA2dp: Proxy object connected
,08-10 12:14:08.449  4030  4030 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 12:14:08.450  4030  4030 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-10 12:14:08.451  1348  1348 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 12:14:08.451  1348  1348 D PanProfile: Bluetooth service connected
08-10 12:14:08.452   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 12:14:08.452  3785  3796 D BluetoothPan: onBluetoothStateChange on: true
,08-10 12:14:08.452  4030  4030 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 12:14:08.453  1348  1360 D BluetoothMap: onBluetoothStateChange: up=true
,08-10 12:14:08.455  1348  1348 D BluetoothMap: Proxy object connected
,08-10 12:14:08.455  1348  1348 D MapProfile: Bluetooth service connected
,08-10 12:14:08.455  1348  1348 D BluetoothMap: getConnectedDevices()
08-10 12:14:08.456  1748  2023 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 12:14:08.456  3785  3797 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 12:14:08.456  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:08.456  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:08.456  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:08.456  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 12:14:08.456  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:14:08.456  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:14:08.456  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:14:08.456  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 12:14:08.457  4030  4030 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 12:14:08.457   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 12:14:08.457  1348  2125 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 12:14:08.458  4030  4030 D ObexServerSockets: Succeed to create listening sockets 
08-10 12:14:08.458  4030  4030 D ObexServerSockets0: startAccept()
,08-10 12:14:08.459  4030  4030 D ObexServerSockets0: prepareForNewConnect()
08-10 12:14:08.459  1348  1359 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 12:14:08.460  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 12:14:08.460  1348  1360 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 12:14:08.461  4030  4030 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-10 12:14:08.461  4030  4030 D BluetoothSdpJni: SDP Create record success - handle: 0
08-10 12:14:08.462  4030  4067 D ObexServerSockets0: Accepting socket connection...
08-10 12:14:08.463  4030  4068 D ObexServerSockets0: Accepting socket connection...
08-10 12:14:08.464   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 12:14:08.464  1348  1348 D BluetoothInputDevice: Proxy object connected
08-10 12:14:08.464  1348  1348 D HidProfile: Bluetooth service connected
,08-10 12:14:08.464  3785  3796 D BluetoothMap: onBluetoothStateChange: up=true
08-10 12:14:08.465   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-10 12:14:08.467  4030  4030 D BluetoothMapService: onReceive
08-10 12:14:08.467  4030  4030 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-10 12:14:08.467  4030  4030 D BluetoothMapService: STATE_ON
08-10 12:14:08.468  3785  3785 D LocalBluetoothProfileManager: Adding local A2DP profile
08-10 12:14:08.469  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:14:08.470  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:14:08.472  3785  3785 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-10 12:14:08.482  3785  3785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 12:14:08.485  3785  3785 D BluetoothA2dp: Proxy object connected
,08-10 12:14:08.488  4030  4030 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-10 12:14:08.488  4030  4030 D ObexServerSockets0: prepareForNewConnect()
,08-10 12:14:08.494  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 12:14:08.496  3785  3785 D DockEventReceiver: finishStartingService: stopping service
,08-10 12:14:08.500  1348  1348 D BluetoothPbap: Proxy object connected
,08-10 12:14:08.500  1348  1348 D PbapServerProfile: Bluetooth service connected
08-10 12:14:08.500  3785  3785 D BluetoothPbap: Proxy object connected
,08-10 12:14:08.501  3785  3785 D PbapServerProfile: Bluetooth service connected
,08-10 12:14:08.509  4030  4073 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 12:14:08.526  4030  4077 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 12:14:08.528  4030  4077 I BtOppRfcommListener: Accept thread started.
,08-10 12:14:08.554   875   875 D BluetoothHeadset: Proxy object connected
,08-10 12:14:08.554  1348  1360 D BluetoothHeadset: Proxy object connected
,08-10 12:14:08.554  1348  1348 D HeadsetProfile: Bluetooth service connected
,08-10 12:14:08.554   875   875 D BluetoothHeadset: Proxy object connected
08-10 12:14:08.555   875   875 D BluetoothHeadset: Proxy object connected
,08-10 12:14:08.555  1748  1761 D BluetoothHeadset: Proxy object connected
08-10 12:14:08.557  1748  1907 D BluetoothHeadset: Proxy object connected
,08-10 12:14:08.557   875   892 D BluetoothHeadset: Proxy object connected
08-10 12:14:08.561  1348  1359 D BluetoothHeadset: Proxy object connected
,08-10 12:14:08.561  1348  1348 D HeadsetProfile: Bluetooth service connected
,08-10 12:14:08.564   875   892 D BluetoothHeadset: Proxy object connected
,08-10 12:14:08.574  3785  3797 D BluetoothHeadset: Proxy object connected
,08-10 12:14:08.576  3785  3785 D HeadsetProfile: Bluetooth service connected
,08-10 12:14:09.843   875  1307 D ConnectivityService: handlePromptUnvalidated 101
,08-10 12:14:09.873  4030  4042 D BluetoothAdapterState: Current state: ON, message: 23
,08-10 12:14:09.873  4030  4042 D BluetoothAdapterProperties: Setting state to 13,
,08-10 12:14:09.874  4030  4042 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-10 12:14:09.876  4030  4042 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 12:14:09.878  4030  4042 I BluetoothAdapterState: Entering PendingCommandState
,08-10 12:14:09.882  4030  4046 D BluetoothAdapterProperties: Scan Mode:20
,08-10 12:14:09.884  4030  4042 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-10 12:14:09.895  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 12:14:09.896  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:09.896  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:09.896  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:09.896  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 12:14:09.896  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 12:14:09.896  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:14:09.896  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:14:09.896  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 12:14:09.895  4030  4030 D BluetoothMapService: onReceive
08-10 12:14:09.896  4030  4030 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 12:14:09.896  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:14:09.896  4030  4030 D BluetoothMapService: STATE_TURNING_OFF
08-10 12:14:09.897  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 12:14:09.899  4030  4030 D HeadsetService: Received stop request...Stopping profile...
08-10 12:14:09.903  3785  3785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 12:14:09.904   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 12:14:09.904  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 12:14:09.904  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:09.904  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:09.904  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:09.904  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 12:14:09.904  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 12:14:09.904  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:14:09.904  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:14:09.904  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 12:14:09.905  4030  4030 D A2dpService: Received stop request...Stopping profile...
08-10 12:14:09.905  4030  4061 D A2dpStateMachine: Exit Disconnected: -1
,08-10 12:14:09.906  3716  3716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 12:14:09.907  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 12:14:09.907  1348  2125 D BluetoothHeadset: Proxy object disconnected
,08-10 12:14:09.908  3785  3796 D BluetoothHeadset: Proxy object disconnected
08-10 12:14:09.910  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:09.911  4030  4030 D BluetoothMapService: MAP Service closeService in
08-10 12:14:09.911  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:14:09.911  4030  4030 D BluetoothMapMasInstance0: MAP Service shutdown
,08-10 12:14:09.911  4030  4030 D ObexServerSockets0: shutdown(block = true)
08-10 12:14:09.911   875   875 D BluetoothHeadset: Proxy object disconnected
,08-10 12:14:09.912   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 12:14:09.912  1748  2023 D BluetoothHeadset: Proxy object disconnected
08-10 12:14:09.912   875   875 D BluetoothA2dp: Proxy object disconnected
08-10 12:14:09.913  4030  4030 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 12:14:09.913  4030  4030 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-10 12:14:09.913  4030  4067 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-10 12:14:09.914  4030  4068 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-10 12:14:09.914  4030  4055 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-10 12:14:09.914  4030  4030 I BtOppRfcommListener: stopping Accept Thread
08-10 12:14:09.915  4030  4077 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 12:14:09.915  4030  4077 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 12:14:09.915  1348  1348 D HeadsetProfile: Bluetooth service disconnected
,08-10 12:14:09.915  1348  1348 D BluetoothA2dp: Proxy object disconnected
08-10 12:14:09.917  4030  4030 D HidService: Received stop request...Stopping profile...
08-10 12:14:09.917  4030  4030 D HidService: Stopping Bluetooth HidService
08-10 12:14:09.918  1348  1348 D BluetoothInputDevice: Proxy object disconnected
08-10 12:14:09.918  1348  1348 D HidProfile: Bluetooth service disconnected
,08-10 12:14:09.919  4030  4030 D HealthService: Received stop request...Stopping profile...
,08-10 12:14:09.921  3785  3785 D HeadsetProfile: Bluetooth service disconnected
08-10 12:14:09.921  4030  4030 V BluetoothAdapterState: isTurningOff()=true
,08-10 12:14:09.921  4030  4030 V BluetoothAdapterState: isTurningOn()=false
,08-10 12:14:09.921  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:14:09.921  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:14:09.923  3785  3785 D DockEventReceiver: finishStartingService: stopping service
,08-10 12:14:09.923  3785  3785 D BluetoothA2dp: Proxy object disconnected
,08-10 12:14:09.924  3785  3785 D BluetoothInputDevice: Proxy object disconnected
,08-10 12:14:09.925  3785  3785 D HidProfile: Bluetooth service disconnected
,08-10 12:14:09.925  4030  4030 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-10 12:14:09.925  4030  4030 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 12:14:09.925  4030  4052 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 12:14:09.925  4030  4052 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 12:14:09.925  4030  4052 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 12:14:09.925  4030  4046 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-10 12:14:09.925  4030  4046 E bt_btif : btif_hf_upstreams_evt: Invalid index 46825
08-10 12:14:09.926  4030  4030 D PanService: Received stop request...Stopping profile...
,08-10 12:14:09.928  1348  1348 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 12:14:09.928  1348  1348 D PanProfile: Bluetooth service disconnected
08-10 12:14:09.930  3785  3785 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 12:14:09.930  3785  3785 D PanProfile: Bluetooth service disconnected
08-10 12:14:09.930  4030  4030 D BluetoothMapService: Received stop request...Stopping profile...
,08-10 12:14:09.930  4030  4030 D BluetoothMapService: stop()
08-10 12:14:09.931  4030  4030 D BluetoothMapAppObserver: deinitObservers()
08-10 12:14:09.931  4030  4030 D BluetoothMapAppObserver: removeReceiver(),
08-10 12:14:09.932  3785  3785 D BluetoothMap: Proxy object disconnected
,08-10 12:14:09.932  1348  1348 D BluetoothMap: Proxy object disconnected
08-10 12:14:09.932  1348  1348 D MapProfile: Bluetooth service disconnected
,08-10 12:14:09.932  3785  3785 D MapProfile: Bluetooth service disconnected
,08-10 12:14:09.932  4030  4030 V BluetoothAdapterState: isTurningOff()=true
,08-10 12:14:09.932  4030  4030 V BluetoothAdapterState: isTurningOn()=false
,08-10 12:14:09.933  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:14:09.933  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:14:09.933  4030  4052 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 12:14:09.934  4030  4052 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 12:14:09.934  4030  4052 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-10 12:14:09.934  4030  4052 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-10 12:14:09.934  4030  4052 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 12:14:09.934  4030  4052 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 12:14:09.934  4030  4046 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-10 12:14:09.936  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 12:14:09.936  4030  4030 V BluetoothAdapterState: isTurningOff()=true
08-10 12:14:09.937  4030  4030 V BluetoothAdapterState: isTurningOn()=false
08-10 12:14:09.937  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:14:09.937  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:14:09.937  4030  4030 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 12:14:09.937  4030  4030 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 12:14:09.937  4030  4046 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 12:14:09.937  4030  4030 V BluetoothAdapterState: isTurningOff()=true
08-10 12:14:09.937  4030  4030 V BluetoothAdapterState: isTurningOn()=false
08-10 12:14:09.937  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:14:09.937  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:14:09.937  4030  4030 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-10 12:14:09.938  4030  4046 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-10 12:14:09.938  4030  4030 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 12:14:09.938  4030  4030 V BluetoothAdapterState: isTurningOff()=true
08-10 12:14:09.938  4030  4030 V BluetoothAdapterState: isTurningOn()=false
,08-10 12:14:09.938  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:14:09.938  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:14:09.939  4030  4030 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 12:14:09.939  4030  4030 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 12:14:09.940  4030  4030 D BluetoothMapService: MAP Service closeService in
08-10 12:14:09.940  4030  4030 V BluetoothAdapterState: isTurningOff()=true
08-10 12:14:09.940  4030  4030 V BluetoothAdapterState: isTurningOn()=false
08-10 12:14:09.940  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:14:09.940  4030  4030 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 12:14:09.940  4030  4042 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-10 12:14:09.940  4030  4042 D BluetoothAdapterProperties: Setting state to 15
08-10 12:14:09.940  4030  4042 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-10 12:14:09.940  4030  4030 D BluetoothMapService: cleanup()
08-10 12:14:09.940  4030  4030 D BluetoothMapService: MAP Service closeService in
08-10 12:14:09.941  4030  4042 I BluetoothAdapterState: Entering BleOnState
08-10 12:14:09.941  1348  1348 D BluetoothPbap: Proxy object disconnected
08-10 12:14:09.942  1348  1348 D PbapServerProfile: Bluetooth service disconnected
,08-10 12:14:09.947  3785  3797 D BluetoothPbap: onBluetoothStateChange: up=false
,08-10 12:14:09.959  1348  2125 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 12:14:09.960  3785  4080 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 12:14:09.961   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 12:14:09.961  1348  1360 D BluetoothPan: onBluetoothStateChange on: false
,08-10 12:14:09.961   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 12:14:09.961  3785  3796 D BluetoothPan: onBluetoothStateChange on: false
,08-10 12:14:09.962  1348  1359 D BluetoothMap: onBluetoothStateChange: up=false
,08-10 12:14:09.963  1748  1761 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 12:14:09.963  3785  3797 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-10 12:14:09.965  3785  4080 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 12:14:09.965   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 12:14:09.965  1348  2125 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 12:14:09.965  1348  1360 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 12:14:09.966  1348  1359 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 12:14:09.966   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 12:14:09.966  3785  3796 D BluetoothMap: onBluetoothStateChange: up=false
,08-10 12:14:09.967  4030  4042 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-10 12:14:09.967  4030  4042 D BluetoothAdapterProperties: Setting state to 16
08-10 12:14:09.967  4030  4042 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-10 12:14:09.967  4030  4042 D BluetoothAdapterProperties: onBleDisable
,08-10 12:14:09.968  4030  4042 I BluetoothAdapterState: Entering PendingCommandState
,08-10 12:14:09.969  4030  4043 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-10 12:14:09.969  4030  4046 D BluetoothAdapterProperties: Scan Mode:20
08-10 12:14:09.969  4030  4052 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-10 12:14:09.969  4030  4052 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 12:14:09.970  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:14:09.970  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:14:09.971  3785  3785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 12:14:09.972  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:09.973  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:14:09.975  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 12:14:09.977  3785  3785 D DockEventReceiver: finishStartingService: stopping service
,08-10 12:14:10.172  4030  4046 I bt_hci  : shut_down
,08-10 12:14:10.180  4030  4050 D bt_hwcfg: hw_epilog_process
08-10 12:14:10.180  4030  4050 I bt_vendor: low_power_mode_cb
,08-10 12:14:10.204  4030  4050 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-10 12:14:10.204  4030  4050 I bt_vendor: epilog_cb
,08-10 12:14:10.205  4030  4050 I bt_hci  : epilog_finished_callback
,08-10 12:14:10.213  4030  4046 I bt_hci_h4: hal_close
,08-10 12:14:10.215  4030  4046 I bt_userial_vendor: device fd = 51 close
,08-10 12:14:10.340  4030  4043 D bt_stack_manager: event_shut_down_stack finished.
,08-10 12:14:10.343  4030  4042 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-10 12:14:10.350  4030  4042 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-10 12:14:10.350  4030  4030 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 12:14:10.352  4030  4030 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 12:14:10.352  4030  4030 D BtGatt.GattService: stop()
08-10 12:14:10.352  4030  4030 D BtGatt.AdvertiseManager: advertise clients cleared
,08-10 12:14:10.357  4030  4030 V BluetoothAdapterState: isTurningOff()=false
08-10 12:14:10.358  4030  4030 V BluetoothAdapterState: isTurningOn()=false
08-10 12:14:10.358  4030  4030 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 12:14:10.359  4030  4030 V BluetoothAdapterState: isBleTurningOff()=true
,08-10 12:14:10.359  4030  4042 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-10 12:14:10.360  4030  4042 D BluetoothAdapterProperties: Setting state to 10
,08-10 12:14:10.361  4030  4042 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-10 12:14:10.362  4030  4042 I BluetoothAdapterState: Entering OffState
08-10 12:14:10.363   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-10 12:14:10.375  4030  4030 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-10 12:14:10.376  4030  4030 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-10 12:14:10.376  4030  4043 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-10 12:14:10.380  4030  4043 D bt_stack_manager: event_clean_up_stack finished.
08-10 12:14:10.380  4030  4030 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-10 12:14:10.382  4030  4030 I art     : System.exit called, status: 0
,08-10 12:14:10.382  4030  4030 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-10 12:14:10.440   875  1385 I ActivityManager: Process com.android.bluetooth (pid 4030) has died
,08-10 12:14:11.305  1492  1987 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-10 12:14:11.330  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:11.341  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:11.345  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:11.381  1492  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 12:14:11.381  1492  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-10 12:14:11.382  1492  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:14:11.382  1492  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:14:11.405  3454  3454 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 12:14:11.406  3454  3454 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 12:14:11.408  3454  3454 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-10 12:14:12.870  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 12:14:12.870  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:14:15.878  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 12:14:15.879  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a1c119b added. We now have 6 listener(s)
,08-10 12:14:15.879  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 12:14:15.883  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 12:14:15.883  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@432e938 added. We now have 7 listener(s)
08-10 12:14:15.884  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 12:14:15.885  3716  3766 I System.out: IsBluetoothEnabled
,08-10 12:14:15.895  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:15.933   875   892 I ActivityManager: Start proc 4088:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-10 12:14:16.095  4088  4088 D AdapterServiceConfig: Adding HeadsetService
,08-10 12:14:16.096  4088  4088 D AdapterServiceConfig: Adding A2dpService
,08-10 12:14:16.097  4088  4088 D AdapterServiceConfig: Adding HidService
,08-10 12:14:16.099  4088  4088 D AdapterServiceConfig: Adding HealthService
,08-10 12:14:16.100  4088  4088 D AdapterServiceConfig: Adding PanService
,08-10 12:14:16.101  4088  4088 D AdapterServiceConfig: Adding GattService
,08-10 12:14:16.102  4088  4088 D AdapterServiceConfig: Adding BluetoothMapService
,08-10 12:14:16.124   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@465d4da:true
08-10 12:14:16.125  4088  4088 D BluetoothAdapterState: make() - Creating AdapterState
,08-10 12:14:16.129  4088  4088 I bt_bluedroid: init
,08-10 12:14:16.129  4088  4100 I BluetoothAdapterState: Entering OffState
,08-10 12:14:16.134  4088  4101 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-10 12:14:16.135  4088  4101 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-10 12:14:16.135  4088  4101 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-10 12:14:16.136  4088  4101 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-10 12:14:16.137  4088  4088 I bt_bluedroid: get_profile_interface socket
,08-10 12:14:16.140  4088  4104 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-10 12:14:16.141  4088  4088 I bt_bluedroid: get_profile_interface sdp
,08-10 12:14:16.142  4088  4104 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 12:14:16.147  4088  4099 I bt_bluedroid: config_hci_snoop_log
,08-10 12:14:16.148   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-10 12:14:16.156  4088  4100 D BluetoothAdapterState: Current state: OFF, message: 0
,08-10 12:14:16.156  4088  4100 D BluetoothAdapterProperties: Setting state to 14
08-10 12:14:16.157  4088  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-10 12:14:16.161  4088  4100 D BluetoothBondStateMachine: make
,08-10 12:14:16.166  4088  4105 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-10 12:14:16.175  4088  4100 I BluetoothAdapterState: Entering PendingCommandState
,08-10 12:14:16.177  4088  4088 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-10 12:14:16.186  4088  4088 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
,08-10 12:14:16.188  4088  4088 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 12:14:16.189  4088  4088 D BtGatt.GattService: Received start request. Starting profile...
08-10 12:14:16.190  4088  4088 D BtGatt.GattService: start()
08-10 12:14:16.190  4088  4088 I bt_bluedroid: get_profile_interface gatt
,08-10 12:14:16.193  4088  4088 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
,08-10 12:14:16.193  4088  4088 D BtGatt.AdvertiseManager: advertise manager created
,08-10 12:14:16.203  4088  4088 V BluetoothAdapterState: isTurningOff()=false
08-10 12:14:16.203  4088  4088 V BluetoothAdapterState: isTurningOn()=false
08-10 12:14:16.203  4088  4088 V BluetoothAdapterState: isBleTurningOn()=true
08-10 12:14:16.203  4088  4088 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:14:16.204  4088  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-10 12:14:16.205  4088  4100 I bt_bluedroid: enable
08-10 12:14:16.205  4088  4101 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-10 12:14:16.206  4088  4101 I bt_hci  : start_up
,08-10 12:14:16.226  4088  4101 I bt_vendor: alloc value 0xb399c189
,08-10 12:14:16.227  4088  4101 I bt_vendor: init
08-10 12:14:16.227  4088  4101 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-10 12:14:16.227  4088  4101 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-10 12:14:16.336  4088  4101 D bt_hci  : start_up starting async portion
,08-10 12:14:16.337  4088  4108 I bt_hci  : event_finish_startup
08-10 12:14:16.337  4088  4108 I bt_hci_h4: hal_open
,08-10 12:14:16.339  4088  4108 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-10 12:14:16.349  4088  4108 I bt_userial_vendor: device fd = 51 open
,08-10 12:14:16.379  4088  4108 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 12:14:16.411  4088  4108 D bt_hwcfg: Chipset BCM4354A2
,08-10 12:14:16.411  4088  4108 D bt_hwcfg: Target name = [BCM4354A2]
08-10 12:14:16.412  4088  4108 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-10 12:14:17.083  4088  4108 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-10 12:14:17.084  4088  4108 D bt_hwcfg: Settlement delay -- 100 ms
08-10 12:14:17.084  4088  4108 I bt_hwcfg: Setting fw settlement delay to 100 
,08-10 12:14:17.201  4088  4108 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 12:14:17.202  4088  4108 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-10 12:14:17.232  4088  4108 I bt_hwcfg: vendor lib fwcfg completed
08-10 12:14:17.232  4088  4108 I bt_vendor: firmware callback
08-10 12:14:17.232  4088  4108 I bt_hci  : firmware_config_callback
,08-10 12:14:17.243  4088  4111 I bt_btu  : btu_task pending for preload complete event
,08-10 12:14:17.243  4088  4111 I bt_btu_task: Bluetooth chip preload is complete
08-10 12:14:17.244  4088  4111 I bt_btu  : btu_task received preload complete event
,08-10 12:14:17.256  4088  4111 I         : BTE_InitTraceLevels -- TRC_HCI
,08-10 12:14:17.256  4088  4111 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-10 12:14:17.256  4088  4111 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-10 12:14:17.257  4088  4111 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 12:14:17.257  4088  4111 I         : BTE_InitTraceLevels -- TRC_AVRC
08-10 12:14:17.257  4088  4111 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 12:14:17.258  4088  4111 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 12:14:17.259  4088  4111 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 12:14:17.259  4088  4111 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 12:14:17.260  4088  4111 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 12:14:17.261  4088  4111 I         : BTE_InitTraceLevels -- TRC_SDP
,08-10 12:14:17.261  4088  4111 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 12:14:17.262  4088  4111 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 12:14:17.262  4088  4111 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-10 12:14:17.263  4088  4111 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 12:14:17.393  4088  4111 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3919d9d
,08-10 12:14:17.394  4088  4111 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3919d9d 
,08-10 12:14:17.404  4088  4104 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-10 12:14:17.407  4088  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 12:14:17.408  4088  4104 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 12:14:17.415  4088  4104 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 12:14:17.418  4088  4104 D BluetoothAdapterProperties: Scan Mode:20
,08-10 12:14:17.419  4088  4104 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 12:14:17.419  4088  4104 D bt_hci  : do_postload posting postload work item
08-10 12:14:17.420  4088  4108 I bt_hci  : event_postload
08-10 12:14:17.420  4088  4108 I bt_vendor: sco_config_cb
08-10 12:14:17.420  4088  4108 I bt_hci  : sco_config_callback postload finished.
08-10 12:14:17.423  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:14:17.424  4088  4104 D bt_bte_conf: Device ID record 1 : primary
,08-10 12:14:17.424  4088  4104 D bt_bte_conf:   vendorId            = 000f
,08-10 12:14:17.425  4088  4104 D bt_bte_conf:   vendorIdSource      = 0001
08-10 12:14:17.425  4088  4104 D bt_bte_conf:   product             = 1200
08-10 12:14:17.426  4088  4104 D bt_bte_conf:   version             = 1436
08-10 12:14:17.426  4088  4104 D bt_bte_conf:   clientExecutableURL = 
,08-10 12:14:17.426  4088  4104 D bt_bte_conf:   serviceDescription  = 
08-10 12:14:17.426  4088  4104 D bt_bte_conf:   documentationURL    = 
08-10 12:14:17.426  4088  4104 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-10 12:14:17.427  4088  4108 I bt_vendor: low_power_mode_cb,
08-10 12:14:17.427  4088  4101 D bt_stack_manager: event_start_up_stack finished
,08-10 12:14:17.428  4088  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-10 12:14:17.428  4088  4100 D BluetoothAdapterProperties: Setting state to 15
08-10 12:14:17.429  4088  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-10 12:14:17.431  4088  4100 I BluetoothAdapterState: Entering BleOnState
,08-10 12:14:17.435  4088  4100 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-10 12:14:17.435  4088  4100 D BluetoothAdapterProperties: Setting state to 11
,08-10 12:14:17.436  4088  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-10 12:14:17.446  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:17.451  4088  4088 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
,08-10 12:14:17.452  4088  4088 D HeadsetService: Received start request. Starting profile...
08-10 12:14:17.455  4088  4088 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 12:14:17.455  4088  4088 D HeadsetStateMachine: make
,08-10 12:14:17.468  4088  4088 D HeadsetStateMachine: max_hf_connections = 1
,08-10 12:14:17.469  4088  4088 I bt_bluedroid: get_profile_interface handsfree
08-10 12:14:17.469  4088  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-10 12:14:17.469  4088  4104 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-10 12:14:17.471  4088  4100 I BluetoothAdapterState: Entering PendingCommandState
,08-10 12:14:17.482  4088  4088 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
,08-10 12:14:17.483  4088  4088 D A2dpService: Received start request. Starting profile...
,08-10 12:14:17.484  4088  4088 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 12:14:17.484  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 12:14:17.484  4088  4088 I bt_bluedroid: get_profile_interface avrcp
,08-10 12:14:17.491  4088  4088 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-10 12:14:17.491  4088  4088 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 12:14:17.491  4088  4088 D A2dpStateMachine: make
,08-10 12:14:17.493  4088  4088 I bt_bluedroid: get_profile_interface a2dp
,08-10 12:14:17.494  4088  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-10 12:14:17.497  4088  4120 D A2dpStateMachine: Enter Disconnected: -2
,08-10 12:14:17.498  4088  4088 I BluetoothHidServiceJni: classInitNative: succeeds
,08-10 12:14:17.499  4088  4088 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
,08-10 12:14:17.500  4088  4088 D HidService: Received start request. Starting profile...
08-10 12:14:17.500  4088  4088 I bt_bluedroid: get_profile_interface hidhost
,08-10 12:14:17.501  4088  4104 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fb3e5
08-10 12:14:17.501  4088  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-10 12:14:17.501  4088  4088 D HidService: setHidService(): set to: null
,08-10 12:14:17.503  4088  4088 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-10 12:14:17.505  4088  4088 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
,08-10 12:14:17.507  4088  4088 D HealthService: Received start request. Starting profile...
,08-10 12:14:17.510  4088  4088 I bt_bluedroid: get_profile_interface health
,08-10 12:14:17.512  4088  4088 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-10 12:14:17.513  4088  4088 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
08-10 12:14:17.514  4088  4088 D PanService: Received start request. Starting profile...
,08-10 12:14:17.515  4088  4088 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-10 12:14:17.515  4088  4088 I bt_bluedroid: get_profile_interface pan
08-10 12:14:17.516  4088  4104 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-10 12:14:17.519  4088  4088 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
08-10 12:14:17.520  4088  4088 D BluetoothMapService: Received start request. Starting profile...
,08-10 12:14:17.521  4088  4088 D BluetoothMapService: start()
,08-10 12:14:17.525  4088  4088 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-10 12:14:17.527  4088  4088 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-10 12:14:17.527  4088  4088 D BluetoothMapAppObserver: createReceiver()
,08-10 12:14:17.529  4088  4088 D BluetoothMapAppObserver: initObservers()
,08-10 12:14:17.530  4088  4088 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-10 12:14:17.546  4088  4088 V BluetoothAdapterState: isTurningOff()=false
,08-10 12:14:17.546  4088  4118 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-10 12:14:17.546  4088  4088 V BluetoothAdapterState: isTurningOn()=true
,08-10 12:14:17.546  4088  4088 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 12:14:17.546  4088  4088 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 12:14:17.552  4088  4088 V BluetoothAdapterState: isTurningOff()=false
,08-10 12:14:17.552  4088  4088 V BluetoothAdapterState: isTurningOn()=true
08-10 12:14:17.552  4088  4088 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 12:14:17.552  4088  4088 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 12:14:17.553  4088  4088 V BluetoothAdapterState: isTurningOff()=false
,08-10 12:14:17.553  4088  4088 V BluetoothAdapterState: isTurningOn()=true
08-10 12:14:17.553  4088  4088 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:14:17.554  4088  4088 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 12:14:17.554  4088  4088 V BluetoothAdapterState: isTurningOff()=false
08-10 12:14:17.554  4088  4088 V BluetoothAdapterState: isTurningOn()=true
,08-10 12:14:17.554  4088  4088 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 12:14:17.555  4088  4088 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:14:17.555  4088  4088 V BluetoothAdapterState: isTurningOff()=false
08-10 12:14:17.555  4088  4088 V BluetoothAdapterState: isTurningOn()=true
08-10 12:14:17.556  4088  4088 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:14:17.556  4088  4088 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:14:17.557  4088  4088 V BluetoothAdapterState: isTurningOff()=false
08-10 12:14:17.557  4088  4088 V BluetoothAdapterState: isTurningOn()=true
08-10 12:14:17.557  4088  4088 V BluetoothAdapterState: isBleTurningOn()=false
08-10 12:14:17.557  4088  4088 V BluetoothAdapterState: isBleTurningOff()=false
08-10 12:14:17.557  4088  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-10 12:14:17.558  4088  4100 D BluetoothAdapterProperties: ScanMode =  20
,08-10 12:14:17.558  4088  4100 D BluetoothAdapterProperties: State =  11
08-10 12:14:17.558  4088  4100 D BluetoothAdapterProperties: Setting state to 12
08-10 12:14:17.558  4088  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 12:14:17.560  4088  4104 D BluetoothAdapterProperties: Scan Mode:21
08-10 12:14:17.560  4088  4104 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 12:14:17.560  4088  4100 I BluetoothAdapterState: Entering OnState
08-10 12:14:17.566  3785  3797 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 12:14:17.566  4088  4088 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-10 12:14:17.567  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:17.567  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:17.567  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:17.567  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 12:14:17.567  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:14:17.567  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:14:17.567  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:14:17.567  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 12:14:17.568  4088  4088 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-10 12:14:17.569  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 12:14:17.569  1348  1359 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 12:14:17.573  3785  4080 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 12:14:17.573  4088  4088 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 12:14:17.576   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 12:14:17.576  4088  4088 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 12:14:17.577  1348  1360 D BluetoothPan: onBluetoothStateChange on: true
,08-10 12:14:17.578  4088  4088 D ObexServerSockets: Succeed to create listening sockets 
08-10 12:14:17.578  4088  4088 D ObexServerSockets0: startAccept()
08-10 12:14:17.578  4088  4088 D ObexServerSockets0: prepareForNewConnect()
,08-10 12:14:17.580   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 12:14:17.581  4088  4088 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-10 12:14:17.581  3785  3796 D BluetoothPan: onBluetoothStateChange on: true
08-10 12:14:17.581  4088  4088 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-10 12:14:17.583   875   875 D BluetoothA2dp: Proxy object connected
08-10 12:14:17.583  4088  4125 D ObexServerSockets0: Accepting socket connection...
,08-10 12:14:17.583  1348  1348 D BluetoothA2dp: Proxy object connected
08-10 12:14:17.584  1348  2125 D BluetoothMap: onBluetoothStateChange: up=true
08-10 12:14:17.585  4088  4126 D ObexServerSockets0: Accepting socket connection...
,08-10 12:14:17.585  1348  1348 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 12:14:17.585  1348  1348 D PanProfile: Bluetooth service connected
08-10 12:14:17.586  1748  1761 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 12:14:17.587  1348  1348 D BluetoothMap: Proxy object connected
,08-10 12:14:17.587  3785  3796 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 12:14:17.587  1348  1348 D MapProfile: Bluetooth service connected
08-10 12:14:17.587  1348  1348 D BluetoothMap: getConnectedDevices()
,08-10 12:14:17.588  3785  3785 D BluetoothA2dp: Proxy object connected
,08-10 12:14:17.589  3785  4080 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 12:14:17.590   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 12:14:17.590  1348  1359 D BluetoothPbap: onBluetoothStateChange: up=true
,08-10 12:14:17.590  3785  3785 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 12:14:17.590  3785  3785 D PanProfile: Bluetooth service connected
,08-10 12:14:17.591  3785  3785 D BluetoothInputDevice: Proxy object connected
,08-10 12:14:17.591  3785  3785 D HidProfile: Bluetooth service connected
,08-10 12:14:17.591  1348  2125 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 12:14:17.592  1348  1360 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 12:14:17.593  1348  1348 D BluetoothInputDevice: Proxy object connected
,08-10 12:14:17.593  1348  1348 D HidProfile: Bluetooth service connected
,08-10 12:14:17.594   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 12:14:17.594  3785  3797 D BluetoothMap: onBluetoothStateChange: up=true
,08-10 12:14:17.597  3785  3785 D BluetoothMap: Proxy object connected
,08-10 12:14:17.597  3785  3785 D MapProfile: Bluetooth service connected
,08-10 12:14:17.597  3785  3785 D BluetoothMap: getConnectedDevices()
08-10 12:14:17.597   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-10 12:14:17.598  4088  4088 D BluetoothMapService: onReceive
08-10 12:14:17.598  4088  4088 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-10 12:14:17.599  4088  4088 D BluetoothMapService: STATE_ON
08-10 12:14:17.601  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:14:17.607  3785  3785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 12:14:17.614  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 12:14:17.622  3785  3785 D DockEventReceiver: finishStartingService: stopping service
,08-10 12:14:17.625  3785  3785 D BluetoothPbap: Proxy object connected
,08-10 12:14:17.625  3785  3785 D PbapServerProfile: Bluetooth service connected
08-10 12:14:17.625  1348  1348 D BluetoothPbap: Proxy object connected
08-10 12:14:17.625  1348  1348 D PbapServerProfile: Bluetooth service connected
,08-10 12:14:17.631  4088  4088 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 12:14:17.631  4088  4088 D ObexServerSockets0: prepareForNewConnect()
,08-10 12:14:17.636  4088  4131 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 12:14:17.653  4088  4135 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 12:14:17.655  4088  4135 I BtOppRfcommListener: Accept thread started.
,08-10 12:14:17.682   875   875 D BluetoothHeadset: Proxy object connected
,08-10 12:14:17.683  1348  1359 D BluetoothHeadset: Proxy object connected
,08-10 12:14:17.683  1348  1348 D HeadsetProfile: Bluetooth service connected
,08-10 12:14:17.683  3785  3797 D BluetoothHeadset: Proxy object connected
,08-10 12:14:17.684  3785  3785 D HeadsetProfile: Bluetooth service connected
08-10 12:14:17.684   875   875 D BluetoothHeadset: Proxy object connected
,08-10 12:14:17.684   875   875 D BluetoothHeadset: Proxy object connected
08-10 12:14:17.684  1748  1907 D BluetoothHeadset: Proxy object connected
08-10 12:14:17.686  1748  1760 D BluetoothHeadset: Proxy object connected
,08-10 12:14:17.689  3785  3796 D BluetoothHeadset: Proxy object connected
,08-10 12:14:17.690   875   892 D BluetoothHeadset: Proxy object connected
08-10 12:14:17.690  3785  3785 D HeadsetProfile: Bluetooth service connected
,08-10 12:14:17.692  1348  1360 D BluetoothHeadset: Proxy object connected
,08-10 12:14:17.692  1348  1348 D HeadsetProfile: Bluetooth service connected
,08-10 12:14:17.694   875   892 D BluetoothHeadset: Proxy object connected
,08-10 12:14:17.915  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:17.915  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:17.915  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:17.915  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 12:14:17.915  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:14:17.915  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:14:17.915  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:14:17.915  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 12:14:17.921  3716  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 12:14:17.926  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 12:14:17.927  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60c8d11 added. We now have 8 listener(s)
08-10 12:14:17.927  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 12:14:17.932   875  1742 D WifiService: setWifiEnabled: false pid=3716, uid=10000
08-10 12:14:17.932   875  1742 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 12:14:17.943  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:17.944   875  1702 D WifiService: setWifiEnabled: true pid=3716, uid=10000
,08-10 12:14:17.944   875  1702 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 12:14:17.963   875  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-10 12:14:17.973  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:17.973  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:17.973  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:17.973  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:14:17.973  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:14:17.973  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 12:14:17.973  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 12:14:17.973  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 12:14:17.979  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 12:14:17.993   875  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-10 12:14:17.994   875  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-10 12:14:17.995   875  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-10 12:14:17.995   875  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-10 12:14:17.996   875  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-10 12:14:17.996   875  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-10 12:14:17.996   875  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-10 12:14:18.009   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-10 12:14:18.010   875  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.75 rxSuccessRate=0.90 delta 1000 -> 1000
08-10 12:14:18.011   373   873 D CommandListener: Setting iface cfg
,08-10 12:14:18.011   875  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,08-10 12:14:18.012   875  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-10 12:14:18.019   875  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-10 12:14:18.019   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 12:14:18.019   875  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-10 12:14:18.026   875  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-10 12:14:18.080   875  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-10 12:14:18.082   875  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-10 12:14:18.085  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-10 12:14:18.356   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-10 12:14:18.365  1653  1653 I Keyboard.Facilitator: onFinishInput()
,08-10 12:14:18.379   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 12:14:18.379   875   895 I Adreno  : Build Date                       : 10/20/15
08-10 12:14:18.379   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 12:14:18.379   875   895 I Adreno  : Local Branch                     : M14
08-10 12:14:18.379   875   895 I Adreno  : Remote Branch                    : 
08-10 12:14:18.379   875   895 I Adreno  : Remote Branch                    : 
08-10 12:14:18.379   875   895 I Adreno  : Reconstruct Branch               : 
,08-10 12:14:18.439   282  1986 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (331 us)
,08-10 12:14:18.541  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 12:14:18.605  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 12:14:18.605  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-10 12:14:18.612   875  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 12:14:18.627   875  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 12:14:18.627   875  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-10 12:14:18.627   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 12:14:18.639   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 12:14:18.649   373   873 D CommandListener: Setting iface cfg
,08-10 12:14:18.649   875  1305 D WifiStateMachine: Start Dhcp Watchdog 3
,08-10 12:14:18.659   875  4145 D DhcpClient: Receive thread started
,08-10 12:14:18.662   875  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-10 12:14:18.662   875  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-10 12:14:18.663   875  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-10 12:14:18.746   875  1305 E native  : do suspend false
,08-10 12:14:18.761   875  2135 D DhcpClient: Broadcasting DHCPDISCOVER
,08-10 12:14:18.773   875  4145 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-10 12:14:18.775   875  2135 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-10 12:14:18.778   875  2135 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-10 12:14:18.790   875  4145 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-10 12:14:18.791   875  2135 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-10 12:14:18.796   373   873 D CommandListener: Setting iface cfg
,08-10 12:14:18.805   875  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-10 12:14:18.808   875  2135 D DhcpClient: Scheduling renewal in 86399s
,08-10 12:14:18.818   875  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-10 12:14:18.820   875  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-10 12:14:18.822   875  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-10 12:14:18.824   875  1307 D ConnectivityService: Adding iface wlan0 to network 102
,08-10 12:14:18.841   875  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-10 12:14:18.878   875  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-10 12:14:18.878   875  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-10 12:14:18.880   875  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-10 12:14:18.884   875  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-10 12:14:18.889   875  1307 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-10 12:14:18.900   875  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-10 12:14:18.904   875  1307 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-10 12:14:18.904   875  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-10 12:14:18.905   875  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-10 12:14:18.905   875  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: [],
08-10 12:14:18.905   875  1307 D ConnectivityService:    accepting network in place of null
08-10 12:14:18.906   875  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 12:14:18.906   875  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 12:14:18.912   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=150770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 12:14:18.951   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 12:14:18.962  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:18.962  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:18.962  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:18.962  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:14:18.962  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:14:18.962  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:14:18.962  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:14:18.962  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 12:14:18.966  3716  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 12:14:18.969  3716  3766 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-10 12:14:18.970  3716  3766 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-10 12:14:18.972  3716  3766 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a3553e9 Bundle[{}]
,08-10 12:14:18.972  3716  3766 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-10 12:14:18.973  3716  3766 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-10 12:14:18.973  3716  3766 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-10 12:14:18.974  3716  3766 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-10 12:14:18.974  3716  3766 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-10 12:14:18.975  3716  3766 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-10 12:14:18.980  3716  3766 I System.out: Running OutgoingSocketThread
,08-10 12:14:18.982  3716  4153 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 436)
08-10 12:14:18.984  3716  4153 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44666
,08-10 12:14:18.984  3716  4153 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...,
,08-10 12:14:18.993   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 12:14:18.999   875  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-10 12:14:19.006   875  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 12:14:19.024  3716  3716 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-10 12:14:19.024  3716  3716 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-10 12:14:19.057   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-10 12:14:19.058   875  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-10 12:14:19.059   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-10 12:14:19.068   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-10 12:14:19.073   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-10 12:14:19.073   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,08-10 12:14:19.073   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-10 12:14:19.089  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 12:14:19.089  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:19.089  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:19.089  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:14:19.089  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:14:19.089  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:14:19.089  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:14:19.089  3716  3716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 12:14:19.091  1778  1778 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-10 12:14:19.091  3716  3716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 12:14:19.093  3716  3716 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a3553e9 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2796e76, 16908290=android.view.AbsSavedState$1@2796e76}, android:focusedViewId=100}]}]
08-10 12:14:19.093  3716  3716 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-10 12:14:19.093  3716  3716 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-10 12:14:19.093  3716  3716 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-10 12:14:19.097  1778  1778 D SystemUpdateService: onCreate
,08-10 12:14:19.100  1778  1778 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 12:14:19.109  1778  4156 I SystemUpdateService: active receiver: enabled
,08-10 12:14:19.114  1778  1778 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-10 12:14:19.117  1778  2362 I iu.UploadsManager: num queued entries: 0
,08-10 12:14:19.118  1778  4156 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 12:14:19.120  1778  1778 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 12:14:19.121  1778  1778 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 12:14:19.123  3841  3841 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 12:14:19.125  1778  4159 I MDM     : [211] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-10 12:14:19.125  1778  4159 W BaseAppContext: Using Auth Proxy for data requests.
,08-10 12:14:19.127  1778  4159 V GoogleAuthProtoRequest: [211] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 12:14:19.128  3841  3841 D SprintDMHelper: simOperator: 
,08-10 12:14:19.128  3841  3841 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 12:14:19.134  1778  4156 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-10 12:14:19.134  1778  4156 I SystemUpdateService: now status is 0 (complete)
08-10 12:14:19.134  1778  4156 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-10 12:14:19.134  1778  4156 I SystemUpdateService: file has been verified
,08-10 12:14:19.139  1778  2362 I iu.UploadsManager: num updated entries: 0
,08-10 12:14:19.143  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:19.145  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:19.151  1778  4156 I SystemUpdateService: OTA package size = 12249756
,08-10 12:14:19.160  1778  2362 I iu.SyncManager: NEXT; no task
,08-10 12:14:19.170  1778  4156 I SystemUpdateService: showing system update notification
,08-10 12:14:19.180  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-10 12:14:19.180  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-10 12:14:19.180  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:14:19.180  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:14:19.185  1778  1778 D SystemUpdateService: onDestroy
,08-10 12:14:19.197  1778  4159 E MDM     : [211] SitrepService.a: Error sending sitrep.
,08-10 12:14:19.296   282   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-10 12:14:19.298   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-10 12:14:19.298   875  1328 D SurfaceControl: Excessive delay in setPowerMode(): 226ms
,08-10 12:14:19.301   875   895 I DreamManagerService: Entering dreamland.
,08-10 12:14:19.302   875   895 I PowerManagerService: Dozing...
,08-10 12:14:19.303   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-10 12:14:19.349   377  1276 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-10 12:14:19.349   377  1276 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-10 12:14:19.356  1735  4166 D NfcService: Discovery configuration equal, not updating.
,08-10 12:14:19.359   875  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 12:14:19.364   875  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-10 12:14:19.367   875  1305 E native  : do suspend false
,08-10 12:14:19.380   875  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-10 12:14:19.388   875  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 12:14:19.390   875  1305 E native  : do suspend true
,08-10 12:14:19.492   377  1458 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-10 12:14:19.492   377  1458 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-10 12:14:19.863   875  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,08-10 12:14:19.983  3716  3766 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 437)
,08-10 12:14:19.983  3716  3766 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 437)
,08-10 12:14:19.992  3716  3766 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 442)
,08-10 12:14:19.994  3716  3766 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-10 12:14:19.995  3716  3766 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 443)
,08-10 12:14:19.999   875  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-10 12:14:20.001  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 12:14:20.001  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a02c77 added. We now have 2 listener(s)
,08-10 12:14:20.003  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 12:14:20.003  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 12:14:20.003  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 12:14:20.003  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 12:14:20.003  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c960e4 added. We now have 9 listener(s)
,08-10 12:14:20.003  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 12:14:20.004  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 12:14:20.008  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 12:14:20.017  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 12:14:20.017  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:20.017  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:20.017  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:14:20.017  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:14:20.017  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:14:20.017  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:14:20.017  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 12:14:20.022  3716  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 12:14:20.022  3716  3766 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 12:14:20.023  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 12:14:20.023  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@905fc02 added. We now have 3 listener(s)
,08-10 12:14:20.026  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 12:14:20.029  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 12:14:20.029  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 12:14:20.029  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 12:14:20.030  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 12:14:20.030  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e11913 added. We now have 10 listener(s)
08-10 12:14:20.030  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 12:14:20.030  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 12:14:20.031  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:14:20.031  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:14:20.031  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:14:20.031  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:20.031  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:14:20.032  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 12:14:20.032  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 12:14:20.032  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a02c77 removed from the list
08-10 12:14:20.032  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:14:20.033  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c960e4 removed from the list
08-10 12:14:20.033  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 12:14:20.033  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:14:20.034  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:14:20.035  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:14:20.037  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:14:20.037  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:14:20.037  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:14:20.038  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c960e4 not in the list
08-10 12:14:20.038  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:14:20.038  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:14:20.040  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 12:14:20.040  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:14:20.040  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:14:20.040  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e11913 removed from the list
,08-10 12:14:20.040  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:14:20.041  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:14:20.041  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:14:20.041  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 12:14:20.041  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@905fc02 removed from the list
08-10 12:14:20.042  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 12:14:20.042  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2da750 added. We now have 2 listener(s)
08-10 12:14:20.044  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 12:14:20.044  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 12:14:20.044  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 12:14:20.044  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 12:14:20.044  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a4acd49 added. We now have 9 listener(s)
,08-10 12:14:20.044  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 12:14:20.045  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 12:14:20.047  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 12:14:20.054  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 12:14:20.054  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:20.054  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:20.054  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:14:20.054  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:14:20.054  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:14:20.054  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:14:20.054  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 12:14:20.057  3716  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 12:14:20.057  3716  3766 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 12:14:20.057  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 12:14:20.057  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63a336f added. We now have 3 listener(s)
,08-10 12:14:20.060  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:20.061  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 12:14:20.061  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 12:14:20.061  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 12:14:20.062  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 12:14:20.062  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94de87c added. We now have 10 listener(s)
08-10 12:14:20.062  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 12:14:20.062  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 12:14:20.062  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-10 12:14:20.062  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 12:14:20.062  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 12:14:20.062  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-10 12:14:20.064  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:20.068  3716  3766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-10 12:14:20.068  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 12:14:20.074  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 12:14:20.075  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-10 12:14:20.075  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 12:14:20.083  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 12:14:20.083  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 12:14:20.083  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-10 12:14:20.085  3716  3766 D BluetoothAdapter: STATE_ON
,08-10 12:14:20.089  4088  4127 D BtGatt.GattService: registerClient() - UUID=44397a87-3eef-43f7-8dd2-48c578884753
,08-10 12:14:20.090  4088  4104 D BtGatt.GattService: onClientRegistered() - UUID=44397a87-3eef-43f7-8dd2-48c578884753, clientIf=5
,08-10 12:14:20.091  3716  3726 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-10 12:14:20.093  4088  4098 D BtGatt.GattService: start scan with filters
,08-10 12:14:20.097  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-10 12:14:20.097  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-10 12:14:20.098  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 12:14:20.098  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 12:14:20.098  4088  4107 D BtGatt.ScanManager: handling starting scan
,08-10 12:14:20.102  4088  4107 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd45ed
,08-10 12:14:20.102  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 12:14:20.102  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 12:14:20.102  3716  3716 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 12:14:20.108  4088  4104 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-10 12:14:20.108  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:14:20.109  4088  4107 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-10 12:14:20.109  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-10 12:14:20.113  3716  3766 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-10 12:14:20.113  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 12:14:20.113  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 12:14:20.114  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:14:20.114  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 12:14:20.114  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 12:14:20.114  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-10 12:14:20.114  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 12:14:20.114  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-10 12:14:20.114  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 12:14:20.114  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 12:14:20.115  3716  3766 D BluetoothAdapter: STATE_ON
,08-10 12:14:20.116  4088  4098 D BtGatt.GattService: stopScan() - queue size =1
08-10 12:14:20.117  4088  4117 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-10 12:14:20.118  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 12:14:20.118  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 12:14:20.118  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 12:14:20.118  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 12:14:20.119  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-10 12:14:20.121  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 12:14:20.121  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-10 12:14:20.121  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 12:14:20.122  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 12:14:20.122  4088  4104 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 12:14:20.123  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:14:20.123  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 12:14:20.123  4088  4107 D BtGatt.ScanManager: Starting BLE batch scan
08-10 12:14:20.123  4088  4107 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-10 12:14:20.126  3716  3716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 12:14:20.126  3716  3716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 12:14:20.126  3716  3716 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 12:14:20.130  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 12:14:20.130  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:14:20.131  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 12:14:20.131  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:14:20.131  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:14:20.132  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 12:14:20.132  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-10 12:14:20.132  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2da750 removed from the list
08-10 12:14:20.132  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:14:20.133  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a4acd49 removed from the list
,08-10 12:14:20.133  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:14:20.133  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:14:20.134  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:14:20.135  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:14:20.137  4088  4104 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-10 12:14:20.137  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:14:20.137  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 12:14:20.137  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:14:20.138  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-10 12:14:20.138  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a4acd49 not in the list
08-10 12:14:20.141  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:14:20.141  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:14:20.143  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 12:14:20.143  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:14:20.143  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:14:20.143  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94de87c removed from the list
08-10 12:14:20.144  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:14:20.144  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:14:20.144  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:14:20.144  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 12:14:20.144  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63a336f removed from the list
,08-10 12:14:20.146  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 12:14:20.146  4088  4104 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 12:14:20.146  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5cf1068 added. We now have 2 listener(s)
08-10 12:14:20.146  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:14:20.152  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 12:14:20.152  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 12:14:20.152  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 12:14:20.152  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 12:14:20.153  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@899dc81 added. We now have 9 listener(s)
08-10 12:14:20.153  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 12:14:20.153  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 12:14:20.156  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 12:14:20.160  4088  4104 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 12:14:20.161  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:14:20.161  4088  4107 D BtGatt.ScanManager: stopping BLe Batch
,08-10 12:14:20.167  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 12:14:20.167  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:20.167  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:20.167  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:14:20.167  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:14:20.167  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:14:20.167  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:14:20.167  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 12:14:20.169  3716  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 12:14:20.169  3716  3766 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 12:14:20.170  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 12:14:20.170  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53f2167 added. We now have 3 listener(s)
08-10 12:14:20.171  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 12:14:20.172  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 12:14:20.172  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 12:14:20.172  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 12:14:20.172  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b8cb14 added. We now have 10 listener(s)
08-10 12:14:20.172  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 12:14:20.172  4088  4104 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-10 12:14:20.172  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:14:20.172  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-10 12:14:20.173  4088  4107 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-10 12:14:20.173  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:20.173  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-10 12:14:20.173  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-10 12:14:20.173  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 12:14:20.174  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 12:14:20.174  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 12:14:20.176  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:20.177  3716  3766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-10 12:14:20.178  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 12:14:20.182  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-10 12:14:20.182  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-10 12:14:20.182  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 12:14:20.183  4088  4104 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-10 12:14:20.183  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:14:20.186  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 12:14:20.186  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-10 12:14:20.186  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-10 12:14:20.187  3716  3766 D BluetoothAdapter: STATE_ON
,08-10 12:14:20.189  4088  4127 D BtGatt.GattService: registerClient() - UUID=3dad7d6b-0635-4bb4-998b-dee06d755b18
,08-10 12:14:20.189  4088  4104 D BtGatt.GattService: onClientRegistered() - UUID=3dad7d6b-0635-4bb4-998b-dee06d755b18, clientIf=5
08-10 12:14:20.190  3716  3726 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-10 12:14:20.190  4088  4099 D BtGatt.GattService: start scan with filters
,08-10 12:14:20.193  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-10 12:14:20.193  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-10 12:14:20.193  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 12:14:20.193  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 12:14:20.193  4088  4107 D BtGatt.ScanManager: handling starting scan
,08-10 12:14:20.196  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 12:14:20.196  3716  3716 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 12:14:20.197  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 12:14:20.198  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 12:14:20.201  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 12:14:20.201  3716  3766 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-10 12:14:20.202  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 12:14:20.202  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 12:14:20.202  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 12:14:20.202  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:14:20.203  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:14:20.203  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 12:14:20.203  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 12:14:20.203  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5cf1068 removed from the list
,08-10 12:14:20.203  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:14:20.203  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@899dc81 removed from the list
,08-10 12:14:20.203  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 12:14:20.203  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 12:14:20.204  4088  4104 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-10 12:14:20.204  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:14:20.204  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:14:20.204  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-10 12:14:20.204  4088  4107 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-10 12:14:20.204  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:14:20.204  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 12:14:20.206  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:14:20.206  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 12:14:20.206  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 12:14:20.206  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@899dc81 not in the list
08-10 12:14:20.206  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-10 12:14:20.206  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 12:14:20.207  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 12:14:20.207  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 12:14:20.207  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 12:14:20.209  3716  3766 D BluetoothAdapter: STATE_ON
,08-10 12:14:20.210  4088  4117 D BtGatt.GattService: stopScan() - queue size =1
08-10 12:14:20.211  4088  4098 D BtGatt.GattService: unregisterClient() - clientIf=5
08-10 12:14:20.212  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 12:14:20.212  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 12:14:20.212  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-10 12:14:20.213  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 12:14:20.213  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-10 12:14:20.214  4088  4104 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-10 12:14:20.214  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:14:20.215  4088  4107 D BtGatt.ScanManager: Starting BLE batch scan
08-10 12:14:20.215  4088  4107 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 12:14:20.215  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 12:14:20.216  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 12:14:20.216  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 12:14:20.216  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 12:14:20.217  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:14:20.219  3716  3716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 12:14:20.219  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 12:14:20.219  3716  3716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 12:14:20.219  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:14:20.219  3716  3716 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 12:14:20.220  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 12:14:20.220  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b8cb14 removed from the list
08-10 12:14:20.220  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:14:20.220  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:14:20.220  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:14:20.220  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 12:14:20.221  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53f2167 removed from the list
,08-10 12:14:20.222  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 12:14:20.222  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de18480 added. We now have 2 listener(s)
,08-10 12:14:20.226  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 12:14:20.227  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 12:14:20.227  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 12:14:20.227  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 12:14:20.228  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a649ab9 added. We now have 9 listener(s)
,08-10 12:14:20.228  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 12:14:20.229  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 12:14:20.232  4088  4104 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-10 12:14:20.232  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:14:20.234  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 12:14:20.240  4088  4104 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-10 12:14:20.240  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:14:20.241  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 12:14:20.241  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:20.241  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:20.241  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:14:20.241  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:14:20.241  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:14:20.241  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:14:20.241  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 12:14:20.244  3716  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 12:14:20.244  3716  3766 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 12:14:20.245  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 12:14:20.245  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@744d65f added. We now have 3 listener(s)
,08-10 12:14:20.246  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 12:14:20.247  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 12:14:20.247  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 12:14:20.247  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 12:14:20.247  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1a68ac added. We now have 10 listener(s)
08-10 12:14:20.247  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 12:14:20.247  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 12:14:20.247  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-10 12:14:20.247  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 12:14:20.247  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 12:14:20.247  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 12:14:20.248  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:20.251  4088  4104 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-10 12:14:20.251  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:14:20.251  4088  4107 D BtGatt.ScanManager: stopping BLe Batch
08-10 12:14:20.252  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:20.253  3716  3766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-10 12:14:20.253  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 12:14:20.257  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 12:14:20.257  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-10 12:14:20.258  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 12:14:20.259  4088  4104 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-10 12:14:20.260  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:14:20.260  4088  4107 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 12:14:20.261  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 12:14:20.261  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 12:14:20.261  3716  3766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-10 12:14:20.262  3716  3766 D BluetoothAdapter: STATE_ON
,08-10 12:14:20.264  4088  4117 D BtGatt.GattService: registerClient() - UUID=b67ed33b-40eb-4baa-b363-76399f5c2f1a
,08-10 12:14:20.264  4088  4104 D BtGatt.GattService: onClientRegistered() - UUID=b67ed33b-40eb-4baa-b363-76399f5c2f1a, clientIf=5
,08-10 12:14:20.265  3716  3762 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-10 12:14:20.265  4088  4099 D BtGatt.GattService: start scan with filters
,08-10 12:14:20.268  4088  4104 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 12:14:20.268  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:14:20.268  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-10 12:14:20.268  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-10 12:14:20.269  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 12:14:20.269  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 12:14:20.270  4088  4107 D BtGatt.ScanManager: handling starting scan
,08-10 12:14:20.271  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 12:14:20.272  3716  3716 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 12:14:20.272  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 12:14:20.273  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 12:14:20.278  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 12:14:20.278  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 12:14:20.278  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 12:14:20.278  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:14:20.278  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:14:20.279  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 12:14:20.279  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 12:14:20.279  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de18480 removed from the list
,08-10 12:14:20.280  4088  4104 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-10 12:14:20.280  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 12:14:20.280  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:14:20.280  4088  4107 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-10 12:14:20.280  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a649ab9 removed from the list
,08-10 12:14:20.280  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
08-10 12:14:20.280  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 12:14:20.282  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:14:20.282  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-10 12:14:20.283  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:14:20.283  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 12:14:20.284  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 12:14:20.284  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:14:20.284  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:14:20.284  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a649ab9 not in the list
,08-10 12:14:20.284  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 12:14:20.284  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 12:14:20.284  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-10 12:14:20.285  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 12:14:20.285  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 12:14:20.286  3716  3766 D BluetoothAdapter: STATE_ON
,08-10 12:14:20.286  4088  4099 D BtGatt.GattService: stopScan() - queue size =1
,08-10 12:14:20.287  4088  4127 D BtGatt.GattService: unregisterClient() - clientIf=5
08-10 12:14:20.287  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-10 12:14:20.288  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 12:14:20.288  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 12:14:20.288  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 12:14:20.288  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-10 12:14:20.288  4088  4104 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 12:14:20.289  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:14:20.289  4088  4107 D BtGatt.ScanManager: Starting BLE batch scan
,08-10 12:14:20.289  4088  4107 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 12:14:20.289  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 12:14:20.289  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-10 12:14:20.289  3716  3766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 12:14:20.289  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 12:14:20.290  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 12:14:20.291  3716  3716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 12:14:20.291  3716  3716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 12:14:20.291  3716  3716 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 12:14:20.291  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 12:14:20.291  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:14:20.291  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:14:20.292  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1a68ac removed from the list
08-10 12:14:20.292  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 12:14:20.292  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:14:20.292  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:14:20.292  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 12:14:20.292  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@744d65f removed from the list
,08-10 12:14:20.293  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 12:14:20.293  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b6398 added. We now have 2 listener(s)
,08-10 12:14:20.295  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 12:14:20.295  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 12:14:20.295  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 12:14:20.295  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 12:14:20.295  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f91e7f1 added. We now have 9 listener(s)
08-10 12:14:20.296  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 12:14:20.296  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 12:14:20.298  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 12:14:20.303  4088  4104 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-10 12:14:20.303  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:14:20.304  3716  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 12:14:20.304  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 12:14:20.304  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 12:14:20.304  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 12:14:20.304  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 12:14:20.304  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 12:14:20.304  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 12:14:20.304  3716  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 12:14:20.307  3716  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 12:14:20.307  3716  3766 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 12:14:20.308  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 12:14:20.310  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bd3257 added. We now have 3 listener(s)
,08-10 12:14:20.310  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:20.311  4088  4104 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-10 12:14:20.312  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 12:14:20.312  3716  3716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 12:14:20.312  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 12:14:20.312  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 12:14:20.313  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-10 12:14:20.313  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 12:14:20.313  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f2144 added. We now have 10 listener(s)
08-10 12:14:20.314  3716  3766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 12:14:20.314  3716  3766 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 12:14:20.314  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 12:14:20.314  3716  3766 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 12:14:20.315  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 12:14:20.315  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 12:14:20.315  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-10 12:14:20.315  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-10 12:14:20.315  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1b6398 removed from the list,
08-10 12:14:20.315  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-10 12:14:20.315  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f91e7f1 removed from the list,
,08-10 12:14:20.316  3716  3766 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 12:14:20.316  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:14:20.316  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:14:20.316  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:14:20.317  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:14:20.318  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:14:20.318  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:14:20.318  3716  3766 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f91e7f1 not in the list
08-10 12:14:20.318  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:14:20.318  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:14:20.319  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 12:14:20.319  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 12:14:20.319  4088  4104 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 12:14:20.319  3716  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 12:14:20.319  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:14:20.319  3716  3766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f2144 removed from the list
08-10 12:14:20.319  3716  3766 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 12:14:20.319  4088  4107 D BtGatt.ScanManager: stopping BLe Batch
08-10 12:14:20.320  3716  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 12:14:20.320  3716  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 12:14:20.320  3716  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 12:14:20.320  3716  3766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bd3257 removed from the list
08-10 12:14:20.321  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-10 12:14:20.321  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-10 12:14:20.321  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-10 12:14:20.321  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 12:14:20.321  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-10 12:14:20.321  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState,: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 12:14:20.326  4088  4104 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-10 12:14:20.326  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:14:20.326  4088  4107 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-10 12:14:20.328  3716  4170 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 450, name: My test thread name)
08-10 12:14:20.329  3716  4170 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 450, thread name: My test thread name)
08-10 12:14:20.329  3716  4170 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 450, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-10 12:14:20.331  3716  4171 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 452, name: My test thread name)
08-10 12:14:20.332  3716  4171 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 452, thread name: My test thread name)
08-10 12:14:20.332  3716  4171 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 452, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-10 12:14:20.334  3716  3766 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-10 12:14:20.334  3716  3766 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-10 12:14:20.334  3716  3766 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-10 12:14:20.334  3716  3766 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-10 12:14:20.334  3716  3766 D com.test.thalitest.ThaliTestRunner: Total duration: 22866 ms
08-10 12:14:20.337  3716  3766 I jxcore-log: Total number of executed tests:  80
08-10 12:14:20.337  3716  3766 I jxcore-log: 
08-10 12:14:20.337  3716  3766 I jxcore-log: Number of passed tests:  80
08-10 12:14:20.337  3716  3766 I jxcore-log: 
08-10 12:14:20.337  3716  3766 I jxcore-log: Number of failed tests:  0
08-10 12:14:20.337  3716  3766 I jxcore-log: 
08-10 12:14:20.337  3716  3766 I jxcore-log: Number of ignored tests:  0
08-10 12:14:20.337  3716  3766 I jxcore-log: 
08-10 12:14:20.338  3716  3766 I jxcore-log: Total duration:  22866
08-10 12:14:20.338  3716  3766 I jxcore-log: 
08-10 12:14:20.338  4088  4104 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-10 12:14:20.338  4088  4104 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 12:14:20.338  4088  4104 D BtGatt.GattService: current time is 152197115222
08-10 12:14:20.339  4088  4104 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-10 12:14:20.340  4088  4104 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-10 12:14:20.341  3716  3766 I jxcore-log: Unit Test app is loaded
08-10 12:14:20.341  3716  3766 I jxcore-log: 
08-10 12:14:20.350  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.350  3716  3766 I jxcore-log: 
08-10 12:14:20.351  3716  3716 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-10 12:14:20.354  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.354  3716  3766 I jxcore-log: 
08-10 12:14:20.355  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.355  3716  3766 I jxcore-log: 
08-10 12:14:20.356  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.356  3716  3766 I jxcore-log: 
08-10 12:14:20.357  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.357  3716  3766 I jxcore-log: 
08-10 12:14:20.358  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.358  3716  3766 I jxcore-log: 
08-10 12:14:20.361  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.361  3716  3766 I jxcore-log: 
08-10 12:14:20.362  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 12:14:20.362  3716  3766 I jxcore-log: 
08-10 12:14:20.363  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 12:14:20.363  3716  3766 I jxcore-log: 
08-10 12:14:20.364  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 12:14:20.364  3716  3766 I jxcore-log: 
08-10 12:14:20.365  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 12:14:20.365  3716  3766 I jxcore-log: 
08-10 12:14:20.366  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 12:14:20.366  3716  3766 I jxcore-log: 
,08-10 12:14:20.367  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 12:14:20.367  3716  3766 I jxcore-log: 
08-10 12:14:20.368  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 12:14:20.368  3716  3766 I jxcore-log: 
08-10 12:14:20.369  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.369  3716  3766 I jxcore-log: 
08-10 12:14:20.369  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.369  3716  3766 I jxcore-log: 
08-10 12:14:20.370  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 12:14:20.370  3716  3766 I jxcore-log: 
08-10 12:14:20.371  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 12:14:20.371  3716  3766 I jxcore-log: 
08-10 12:14:20.372  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 12:14:20.372  3716  3766 I jxcore-log: 
08-10 12:14:20.373  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 12:14:20.373  3716  3766 I jxcore-log: 
08-10 12:14:20.373  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 12:14:20.373  3716  3766 I jxcore-log: 
08-10 12:14:20.374  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 12:14:20.374  3716  3766 I jxcore-log: 
08-10 12:14:20.375  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 12:14:20.375  3716  3766 I jxcore-log: 
08-10 12:14:20.376  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 12:14:20.376  3716  3766 I jxcore-log: 
08-10 12:14:20.376  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-10 12:14:20.376  3716  3766 I jxcore-log: 
08-10 12:14:20.377  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.377  3716  3766 I jxcore-log: 
08-10 12:14:20.378  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.378  3716  3766 I jxcore-log: 
08-10 12:14:20.379  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.379  3716  3766 I jxcore-log: 
08-10 12:14:20.380  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.380  3716  3766 I jxcore-log: 
08-10 12:14:20.380  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.380  3716  3766 I jxcore-log: 
08-10 12:14:20.381  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.381  3716  3766 I jxcore-log: 
08-10 12:14:20.381  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 12:14:20.381  3716  3766 I jxcore-log: 
08-10 12:14:20.384  3716  3766 I jxcore-log: My device name is: motorola-Nexus 6
08-10 12:14:20.384  3716  3766 I jxcore-log: 
,08-10 12:14:20.626  3716  3716 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 12:14:20.721  3716  3716 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 12:14:20.791  3716  3716 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 12:14:21.811   875  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 16 -> obsolete
,08-10 12:14:22.630  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-10 12:14:22.630  3716  3766 I jxcore-log: 
,08-10 12:14:23.243  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-10 12:14:23.243  3716  3766 I jxcore-log: 
,08-10 12:14:23.268  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-10 12:14:23.268  3716  3766 I jxcore-log: 
,08-10 12:14:23.805  1810  2338 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-10 12:14:24.010   875  4142 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.18.174,2a00:1450:4001:80d::200e
,08-10 12:14:24.084   875  4142 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 10:14:24 GMT], X-Android-Received-Millis=[1470824064082], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470824064055]}
,08-10 12:14:24.089   875  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 12:14:24.092   875  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-10 12:14:24.093   875  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-10 12:14:24.099   875  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-10 12:14:24.260  2971  4161 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-10 12:14:24.647  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-10 12:14:24.647  3716  3766 I jxcore-log: 
,08-10 12:14:24.873  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-10 12:14:24.873  3716  3766 I jxcore-log: 
,08-10 12:14:24.879  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-10 12:14:24.879  3716  3766 I jxcore-log: 
,08-10 12:14:24.896  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-10 12:14:24.896  3716  3766 I jxcore-log: 
,08-10 12:14:24.901  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-10 12:14:24.901  3716  3766 I jxcore-log: 
,08-10 12:14:25.575  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-10 12:14:25.575  3716  3766 I jxcore-log: 
,08-10 12:14:25.587  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-10 12:14:25.587  3716  3766 I jxcore-log: 
,08-10 12:14:25.597  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-10 12:14:25.597  3716  3766 I jxcore-log: 
,08-10 12:14:25.605  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-10 12:14:25.605  3716  3766 I jxcore-log: 
,08-10 12:14:25.654  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-10 12:14:25.654  3716  3766 I jxcore-log: 
,08-10 12:14:25.710  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-10 12:14:25.710  3716  3766 I jxcore-log: 
,08-10 12:14:25.718  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-10 12:14:25.718  3716  3766 I jxcore-log: 
,08-10 12:14:25.885  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-10 12:14:25.885  3716  3766 I jxcore-log: 
,08-10 12:14:25.912  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-10 12:14:25.912  3716  3766 I jxcore-log: 
,08-10 12:14:25.918  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-10 12:14:25.918  3716  3766 I jxcore-log: 
,08-10 12:14:25.924  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-10 12:14:25.924  3716  3766 I jxcore-log: 
,08-10 12:14:25.943  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-10 12:14:25.943  3716  3766 I jxcore-log: 
,08-10 12:14:26.028  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-10 12:14:26.028  3716  3766 I jxcore-log: 
,08-10 12:14:26.040  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-10 12:14:26.040  3716  3766 I jxcore-log: 
,08-10 12:14:26.069  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-10 12:14:26.069  3716  3766 I jxcore-log: 
,08-10 12:14:26.081  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-10 12:14:26.081  3716  3766 I jxcore-log: 
,08-10 12:14:26.100  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-10 12:14:26.100  3716  3766 I jxcore-log: 
,08-10 12:14:26.137  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-10 12:14:26.137  3716  3766 I jxcore-log: 
,08-10 12:14:26.144  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-10 12:14:26.144  3716  3766 I jxcore-log: 
,08-10 12:14:26.376  3716  3766 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-10 12:14:26.376  3716  3766 I jxcore-log: 
,08-10 12:14:26.387  3716  3766 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-10 12:14:26.388  3716  3766 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-10 12:14:26.388  3716  3766 I jxcore-log: 
,08-10 12:14:26.436  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 12:14:26.436  3716  3766 I jxcore-log: 
,08-10 12:14:26.437  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 12:14:26.437  3716  3766 I jxcore-log: 
08-10 12:14:26.437  3716  3766 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 12:14:26.437  3716  3766 I jxcore-log: 
,08-10 12:14:26.437  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 12:14:26.438  3716  3766 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
08-10 12:14:26.438  3716  3766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 12:14:26.438  3716  3766 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-10 12:14:26.906   875  1307 D ConnectivityService: handlePromptUnvalidated 102
,08-10 12:14:31.533  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:31.668  1492  4177 I VacuumService: Vacuum at: now=1470824071668 tag=VacuumService
,08-10 12:14:31.804  1492  4178 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-10 12:14:31.810  1492  4178 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-10 12:14:31.839  1492  4178 W Uploader:  no longer exists, so no auth token.
,08-10 12:14:31.880  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:31.892  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:31.896  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:31.927  1492  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 12:14:31.928  1492  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-10 12:14:31.928  1492  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:14:31.928  1492  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:14:31.970  3454  3454 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 12:14:31.970  3454  3454 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 12:14:31.970  3454  3454 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-10 12:14:32.154  1492  4178 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-10 12:14:32.154  1492  4178 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-10 12:14:32.154  1492  4178 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:14:32.154  1492  4178 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:14:32.178  1492  4178 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 12:14:32.178  1492  4178 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 12:14:32.178  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 12:14:32.178  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 12:14:32.178  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-10 12:14:32.178  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-10 12:14:32.178  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-10 12:14:32.178  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-10 12:14:32.178  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-10 12:14:32.178  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-10 12:14:32.178  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-10 12:14:32.178  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-10 12:14:32.178  1492  4178 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-10 12:14:32.866  1492  4178 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-10 12:14:32.866  1492  4178 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-10 12:14:32.867  1492  4178 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:14:32.867  1492  4178 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:14:32.882  1492  4178 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 12:14:32.882  1492  4178 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 12:14:32.882  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 12:14:32.882  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 12:14:32.882  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-10 12:14:32.882  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-10 12:14:32.882  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-10 12:14:32.882  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-10 12:14:32.882  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-10 12:14:32.882  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-10 12:14:32.882  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-10 12:14:32.882  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-10 12:14:32.882  1492  4178 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-10 12:14:33.114  1492  4178 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-10 12:14:33.115  1492  4178 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-10 12:14:33.115  1492  4178 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:14:33.115  1492  4178 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:14:33.134  1492  4178 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 12:14:33.134  1492  4178 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 12:14:33.134  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 12:14:33.134  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 12:14:33.134  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-10 12:14:33.134  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-10 12:14:33.134  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-10 12:14:33.134  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-10 12:14:33.134  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-10 12:14:33.134  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-10 12:14:33.134  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-10 12:14:33.134  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-10 12:14:33.134  1492  4178 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-10 12:14:33.178   875  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 16 -> obsolete
,08-10 12:14:33.552  1492  4178 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-10 12:14:33.552  1492  4178 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-10 12:14:33.552  1492  4178 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:14:33.553  1492  4178 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:14:33.572  1492  4178 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 12:14:33.572  1492  4178 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 12:14:33.572  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 12:14:33.572  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 12:14:33.572  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-10 12:14:33.572  1492  4178 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-10 12:14:33.572  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-10 12:14:33.572  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-10 12:14:33.572  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-10 12:14:33.572  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-10 12:14:33.572  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-10 12:14:33.572  1492  4178 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-10 12:14:33.572  1492  4178 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-10 12:14:38.887   875  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 16 -> obsolete
,08-10 12:14:49.195   875   887 I ActivityManager: Start proc 4190:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-10 12:14:49.261  4190  4190 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-10 12:14:49.355  3957  4202 V KeepSync: Connecting to GoogleApiClient
,08-10 12:14:49.356   875  1742 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 12:14:49.371  4190  4190 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-10 12:14:49.391  4190  4190 I BooksApp: Created application version: 3.6.9 (30609)
,08-10 12:14:49.412  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:49.414  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:49.452  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 12:14:49.452  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 12:14:49.453  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:14:49.453  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:14:49.487  1778  4208 V BaseAuthAsyncOperation: access token request failed
,08-10 12:14:49.490  3957  4202 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 12:14:49.519  4190  4209 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 12:14:49.722  4190  4215 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 12:14:49.819  1492  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 12:14:49.819  1492  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 12:14:49.819  1492  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:14:49.819  1492  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-10 12:14:49.838  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 12:14:49.839  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 12:14:49.839  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:14:49.839  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:14:49.882  1492  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 12:14:49.882  1492  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 12:14:49.882  1492  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:14:49.882  1492  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:14:49.913  4190  4215 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 12:14:49.915  4190  4209 E BooksSync: Soft error
08-10 12:14:49.915  4190  4209 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:14:49.915  4190  4209 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 12:14:49.915  4190  4209 E BooksSync: Sync error
08-10 12:14:49.915  4190  4209 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:14:49.915  4190  4209 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 12:14:49.915  4190  4209 I BooksSync: Finished books sync
,08-10 12:14:49.920  3957  4202 E KeepSync: IOException
08-10 12:14:49.920  3957  4202 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 12:14:49.920  3957  4202 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 12:14:49.920  3957  4202 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 12:14:49.920  3957  4202 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 12:14:49.920  3957  4202 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 12:14:49.920  3957  4202 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 12:14:49.920  3957  4202 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 12:14:49.920  3957  4202 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 12:14:49.920  3957  4202 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 12:14:49.920  3957  4202 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 12:14:49.920  3957  4202 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 12:14:49.920  3957  4202 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 12:14:49.920  3957  4202 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 12:14:49.920  3957  4202 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 12:14:49.920  3957  4202 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 12:14:49.920  3957  4202 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 12:14:49.920  3957  4202 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 12:14:49.920  3957  4202 E KeepSync: 	... 10 more
,08-10 12:14:49.920  3957  4202 W KeepSync: Sync result 2
,08-10 12:14:49.927   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 159908, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:14:49.959   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 158418, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:14:50.038   875  1762 I ActivityManager: Killing 3362:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-10 12:14:52.252  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:52.314  1492  2930 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 12:14:52.314  1492  2930 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-10 12:14:52.314  1492  2930 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:14:52.315  1492  2930 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:14:52.359  3454  3454 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 12:14:52.360  3454  3454 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 12:14:52.363  3454  3454 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-10 12:14:54.384  4190  4206 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-10 12:14:59.449  3454  3464 D Finsky  : [288] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-10 12:14:59.466  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:59.482  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:59.488  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:14:59.554  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 12:14:59.554  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-10 12:14:59.554  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:14:59.555  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:14:59.615  3454  3464 D Finsky  : [288] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-10 12:15:12.450   875   888 I ActivityManager: Start proc 4221:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,08-10 12:15:12.546  4221  4221 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,08-10 12:15:12.565  4221  4221 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-10 12:15:12.565  4221  4221 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-10 12:15:12.565  4221  4221 I GAv4    :   adb logcat -s GAv4
,08-10 12:15:12.578  4221  4221 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-10 12:15:12.582  4221  4221 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-10 12:15:12.593  4221  4236 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-10 12:15:12.612  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:15:12.631  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:15:12.637  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:15:12.685  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 12:15:12.685  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 12:15:12.685  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:15:12.685  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:15:12.733  3454  3454 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-10 12:15:12.733  3454  3454 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 12:15:12.733  3454  3454 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-10 12:15:12.751   875   886 I ActivityManager: Killing 3540:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-10 12:15:18.367  1653  1807 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-10 12:15:18.367  1653  1807 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-10 12:15:18.427  1492  1492 I ConfigService: onCreate
,08-10 12:15:21.363  4190  4238 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 12:15:21.412  4190  4239 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 12:15:21.429  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:15:21.434  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:15:21.465  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 12:15:21.466  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 12:15:21.466  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:15:21.466  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:15:21.503  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:15:21.506  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:15:21.530  1492  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 12:15:21.530  1492  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 12:15:21.530  1492  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:15:21.530  1492  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:15:21.552  4190  4239 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 12:15:21.552  4190  4238 E BooksSync: Soft error
08-10 12:15:21.552  4190  4238 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:15:21.552  4190  4238 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 12:15:21.553  4190  4238 E BooksSync: Sync error
08-10 12:15:21.553  4190  4238 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:15:21.553  4190  4238 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 12:15:21.553  4190  4238 I BooksSync: Finished books sync
,08-10 12:15:21.566   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 213147, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:15:21.648  3957  4240 V KeepSync: Connecting to GoogleApiClient
,08-10 12:15:21.649   875  1762 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 12:15:21.710  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:15:21.715  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:15:21.743  1492  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 12:15:21.743  1492  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-10 12:15:21.743  1492  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:15:21.743  1492  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:15:21.765  1778  4241 V BaseAuthAsyncOperation: access token request failed
,08-10 12:15:21.767  3957  4240 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 12:15:21.822  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 12:15:21.823  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 12:15:21.823  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:15:21.823  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:15:21.842  3957  4240 E KeepSync: IOException
08-10 12:15:21.842  3957  4240 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 12:15:21.842  3957  4240 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 12:15:21.842  3957  4240 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 12:15:21.842  3957  4240 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 12:15:21.842  3957  4240 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 12:15:21.842  3957  4240 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 12:15:21.842  3957  4240 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 12:15:21.842  3957  4240 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 12:15:21.842  3957  4240 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 12:15:21.842  3957  4240 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 12:15:21.842  3957  4240 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 12:15:21.842  3957  4240 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 12:15:21.842  3957  4240 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 12:15:21.842  3957  4240 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 12:15:21.842  3957  4240 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 12:15:21.842  3957  4240 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 12:15:21.842  3957  4240 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 12:15:21.842  3957  4240 E KeepSync: 	... 10 more
,08-10 12:15:21.842  3957  4240 W KeepSync: Sync result 2
,08-10 12:15:21.851   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 213195, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:15:23.511  1492  1492 I ConfigService: onDestroy
,08-10 12:15:29.632   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=221490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:15:33.001  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:15:33.010  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:15:33.012  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:15:33.053  1492  2930 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 12:15:33.053  1492  2930 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 12:15:33.053  1492  2930 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:15:33.053  1492  2930 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:15:33.084  3454  3454 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 12:15:33.085  3454  3454 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 12:15:33.085  3454  3454 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-10 12:15:35.593   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=227451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:15:56.473  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:15:56.475  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:15:56.501  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 12:15:56.501  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 12:15:56.501  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:15:56.501  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:15:56.518  2956  4245 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 12:15:56.518  2956  4245 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at blb.a(PG:3937)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at czp.a(PG:18188)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:15:56.518  2956  4245 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	... 12 more
08-10 12:15:56.518  2956  4245 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at fal.a(PG:38)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:15:56.518  2956  4245 E HttpOperation: 	... 14 more
,08-10 12:15:56.562  1492  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:15:56.563  1492  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 12:15:56.563  1492  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:15:56.563  1492  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:15:56.588  2956  4245 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 12:15:56.588  2956  4245 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at hec.a(PG:42)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at hee.a(PG:102)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at czr.a(PG:65)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at kka.a(PG:108)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at czp.a(PG:19176)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:15:56.588  2956  4245 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	... 15 more
08-10 12:15:56.588  2956  4245 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at fal.a(PG:38)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:15:56.588  2956  4245 E HttpOperation: 	... 17 more
,08-10 12:15:56.589  2956  4245 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 12:15:56.589  2956  4245 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at hec.a(PG:42)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at hee.a(PG:102)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at czr.a(PG:65)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at kka.a(PG:108)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	... 15 more
08-10 12:15:56.589  2956  4245 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at fal.a(PG:38)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 12:15:56.589  2956  4245 E ExperimentLoader: 	... 17 more
,08-10 12:15:56.710   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 247995, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:16:05.259   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=257117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:16:11.566   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=263423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:16:27.007  4190  4248 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 12:16:27.042  4190  4250 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 12:16:27.058  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:16:27.063  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:16:27.103  3957  4249 V KeepSync: Connecting to GoogleApiClient
08-10 12:16:27.103   875  1763 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 12:16:27.108  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-10 12:16:27.108  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 12:16:27.109  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:16:27.109  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:16:27.151  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:16:27.154  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:16:27.266  1492  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 12:16:27.266  1492  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 12:16:27.266  1492  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:16:27.266  1492  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 12:16:27.267  1492  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-10 12:16:27.267  1492  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-10 12:16:27.267  1492  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:16:27.267  1492  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:16:27.295  4190  4250 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:16:27.296  4190  4248 E BooksSync: Soft error
08-10 12:16:27.296  4190  4248 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:16:27.296  4190  4248 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 12:16:27.296  4190  4248 E BooksSync: Sync error
08-10 12:16:27.296  4190  4248 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:16:27.296  4190  4248 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 12:16:27.296  4190  4248 I BooksSync: Finished books sync
08-10 12:16:27.298  1778  4251 V BaseAuthAsyncOperation: access token request failed
08-10 12:16:27.299  3957  4249 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 12:16:27.307   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 276146, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:16:27.351  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 12:16:27.351  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 12:16:27.351  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:16:27.351  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:16:27.363  3957  4249 E KeepSync: IOException
08-10 12:16:27.363  3957  4249 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 12:16:27.363  3957  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 12:16:27.363  3957  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 12:16:27.363  3957  4249 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 12:16:27.363  3957  4249 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 12:16:27.363  3957  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 12:16:27.363  3957  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 12:16:27.363  3957  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 12:16:27.363  3957  4249 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 12:16:27.363  3957  4249 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 12:16:27.363  3957  4249 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 12:16:27.363  3957  4249 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 12:16:27.363  3957  4249 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 12:16:27.363  3957  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 12:16:27.363  3957  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 12:16:27.363  3957  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 12:16:27.363  3957  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 12:16:27.363  3957  4249 E KeepSync: 	... 10 more
08-10 12:16:27.363  3957  4249 W KeepSync: Sync result 2
,08-10 12:16:27.368   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 276465, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:16:41.206   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=293064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:16:47.499   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=299357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:16:57.710  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:16:57.713  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:16:57.752  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:16:57.752  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 12:16:57.752  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:16:57.752  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:16:57.783  2956  4258 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 12:16:57.783  2956  4258 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at blb.a(PG:3937)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at czp.a(PG:18188)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:16:57.783  2956  4258 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	... 12 more
08-10 12:16:57.783  2956  4258 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at fal.a(PG:38)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:16:57.783  2956  4258 E HttpOperation: 	... 14 more
,08-10 12:16:57.902  1492  2930 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:16:57.902  1492  2930 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 12:16:57.902  1492  2930 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:16:57.902  1492  2930 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:16:57.945  2956  4258 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 12:16:57.945  2956  4258 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at hec.a(PG:42)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at hee.a(PG:102)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at czr.a(PG:65)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at kka.a(PG:108)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at czp.a(PG:19176)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:16:57.945  2956  4258 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	... 15 more
08-10 12:16:57.945  2956  4258 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at fal.a(PG:38)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:16:57.945  2956  4258 E HttpOperation: 	... 17 more
,08-10 12:16:57.946  2956  4258 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 12:16:57.946  2956  4258 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at hec.a(PG:42)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at hee.a(PG:102)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at czr.a(PG:65)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at kka.a(PG:108)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	... 15 more
08-10 12:16:57.946  2956  4258 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at fal.a(PG:38)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 12:16:57.946  2956  4258 E ExperimentLoader: 	... 17 more
,08-10 12:16:58.132   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 279522, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:17:17.153   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=329011, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:17:23.566   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=335423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:17:29.811  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:17:29.820  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 12:17:29.821  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:17:29.869  1492  2930 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-10 12:17:29.869  1492  2930 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 12:17:29.869  1492  2930 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:17:29.869  1492  2930 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:17:29.897  1492  2930 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 12:17:29.897  1492  2930 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 12:17:29.897  1492  2930 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 12:17:29.897  1492  2930 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 12:17:29.897  1492  2930 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 12:17:29.897  1492  2930 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 12:17:29.897  1492  2930 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 12:17:29.907  3454  3491 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 12:17:29.907  3454  3491 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 12:17:29.907  3454  3491 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 12:17:29.907  3454  3491 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 12:17:29.907  3454  3491 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 12:17:29.907  3454  3491 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 12:17:29.907  3454  3491 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 12:17:55.350   875  1408 I ActivityManager: Start proc 4265:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-10 12:17:55.431  4265  4265 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-10 12:17:55.501  4265  4277 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-10 12:17:55.611  4265  4277 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-10 12:17:55.682  4265  4277 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-10 12:17:55.714  4265  4265 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-10 12:17:55.939  4265  4265 W InstanceID/Rpc: Found 10011
,08-10 12:17:56.134  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:17:56.135  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:17:56.166  3934  4334 V GoogleAuthProtoRequest: [358] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 12:17:56.179  4303  4303 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads1304917892.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1304917892.dex
,08-10 12:17:56.207  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-10 12:17:56.207  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-10 12:17:56.208  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:17:56.208  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:17:56.243  3934  4334 W ExperimentUpdateService: [358] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 12:17:56.244  3934  4334 W ExperimentUpdateService: [358] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 12:17:56.244  3934  4334 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 12:17:56.244  3934  4334 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 12:17:56.244  3934  4334 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 12:17:56.244  3934  4334 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 12:17:56.244  3934  4334 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 12:17:56.244  3934  4334 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 12:17:56.244  3934  4334 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 12:17:56.244  3934  4334 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 12:17:56.244  3934  4334 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 12:17:56.244  3934  4334 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 12:17:56.252   875  1686 I ActivityManager: Killing 3641:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-10 12:17:56.281  4303  4303 I dex2oat : dex2oat took 106.915ms (threads: 4) arena alloc=388KB java alloc=29KB native alloc=1515KB free=1812KB
,08-10 12:18:00.274  1492  2930 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:18:00.274  1492  2930 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 12:18:00.274  1492  2930 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:18:00.274  1492  2930 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:18:00.295  2956  4349 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 12:18:00.295  2956  4349 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at blb.a(PG:3937)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at czp.a(PG:18188)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:18:00.295  2956  4349 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	... 12 more
08-10 12:18:00.295  2956  4349 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at fal.a(PG:38)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:18:00.295  2956  4349 E HttpOperation: 	... 14 more
,08-10 12:18:00.345  1492  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:18:00.345  1492  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 12:18:00.346  1492  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:18:00.346  1492  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:18:00.364  2956  4349 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 12:18:00.364  2956  4349 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at hec.a(PG:42)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at hee.a(PG:102)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at czr.a(PG:65)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at kka.a(PG:108)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at czp.a(PG:19176)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:18:00.364  2956  4349 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	... 15 more
08-10 12:18:00.364  2956  4349 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at fal.a(PG:38)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:18:00.364  2956  4349 E HttpOperation: 	... 17 more
,08-10 12:18:00.365  2956  4349 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 12:18:00.365  2956  4349 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at hec.a(PG:42)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at hee.a(PG:102)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at czr.a(PG:65)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at kka.a(PG:108)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	,at jdj.a(PG:4091)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	... 15 more
08-10 12:18:00.365  2956  4349 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at fal.a(PG:38)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 12:18:00.365  2956  4349 E ExperimentLoader: 	... 17 more
,08-10 12:18:00.510   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 371897, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:18:26.465  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:18:26.467  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:18:26.478  3934  4354 V GoogleAuthProtoRequest: [359] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 12:18:26.526  1492  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-10 12:18:26.526  1492  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-10 12:18:26.526  1492  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:18:26.527  1492  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:18:26.547  3934  4354 W ExperimentUpdateService: [359] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 12:18:26.547  3934  4354 W ExperimentUpdateService: [359] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 12:18:26.547  3934  4354 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 12:18:26.547  3934  4354 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 12:18:26.547  3934  4354 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 12:18:26.547  3934  4354 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 12:18:26.547  3934  4354 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 12:18:26.547  3934  4354 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 12:18:26.547  3934  4354 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 12:18:26.547  3934  4354 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 12:18:26.547  3934  4354 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 12:18:26.547  3934  4354 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 12:18:31.792   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=403650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:18:32.823  4190  4355 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 12:18:32.858  4190  4356 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 12:18:32.881  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:18:32.883  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:18:32.914  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-10 12:18:32.914  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 12:18:32.914  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:18:32.914  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:18:32.944  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:18:32.946  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:18:32.973  1492  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 12:18:32.973  1492  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 12:18:32.973  1492  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:18:32.973  1492  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:18:32.995  4190  4356 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 12:18:32.996  4190  4355 E BooksSync: Soft error
08-10 12:18:32.996  4190  4355 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:18:32.996  4190  4355 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 12:18:32.997  4190  4355 E BooksSync: Sync error
08-10 12:18:32.997  4190  4355 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:18:32.997  4190  4355 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 12:18:32.997  4190  4355 I BooksSync: Finished books sync
,08-10 12:18:33.008   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 404609, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:18:33.126  3957  4357 V KeepSync: Connecting to GoogleApiClient
,08-10 12:18:33.126   875  1681 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 12:18:33.183  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:18:33.185  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:18:33.223  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 12:18:33.223  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 12:18:33.223  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:18:33.223  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:18:33.250  1778  4358 V BaseAuthAsyncOperation: access token request failed
,08-10 12:18:33.253  3957  4357 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 12:18:33.324  1492  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-10 12:18:33.324  1492  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-10 12:18:33.324  1492  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:18:33.324  1492  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:18:33.347  3957  4357 E KeepSync: IOException
08-10 12:18:33.347  3957  4357 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 12:18:33.347  3957  4357 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 12:18:33.347  3957  4357 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 12:18:33.347  3957  4357 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 12:18:33.347  3957  4357 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 12:18:33.347  3957  4357 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 12:18:33.347  3957  4357 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 12:18:33.347  3957  4357 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 12:18:33.347  3957  4357 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 12:18:33.347  3957  4357 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 12:18:33.347  3957  4357 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 12:18:33.347  3957  4357 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 12:18:33.347  3957  4357 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 12:18:33.347  3957  4357 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 12:18:33.347  3957  4357 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 12:18:33.347  3957  4357 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 12:18:33.347  3957  4357 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 12:18:33.347  3957  4357 E KeepSync: 	... 10 more
08-10 12:18:33.347  3957  4357 W KeepSync: Sync result 2
,08-10 12:18:33.360   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 404742, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:18:39.126   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=410984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:19:08.726   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=440583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:19:16.366   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=448223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:19:26.700  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:19:26.702  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:19:26.709  3934  4363 V GoogleAuthProtoRequest: [360] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 12:19:26.724  1492  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-10 12:19:26.724  1492  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-10 12:19:26.724  1492  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:19:26.724  1492  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:19:26.736  3934  4363 W ExperimentUpdateService: [360] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 12:19:26.736  3934  4363 W ExperimentUpdateService: [360] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 12:19:26.736  3934  4363 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 12:19:26.736  3934  4363 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 12:19:26.736  3934  4363 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 12:19:26.736  3934  4363 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 12:19:26.736  3934  4363 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 12:19:26.736  3934  4363 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 12:19:26.736  3934  4363 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 12:19:26.736  3934  4363 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 12:19:26.736  3934  4363 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 12:19:26.736  3934  4363 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 12:19:46.059   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=477917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:19:51.713   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=483570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:20:04.629  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:20:04.630  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:20:04.655  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:20:04.655  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 12:20:04.655  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:20:04.655  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:20:04.670  2956  4366 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 12:20:04.670  2956  4366 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at blb.a(PG:3937)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at czp.a(PG:18188)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:20:04.670  2956  4366 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	... 12 more
08-10 12:20:04.670  2956  4366 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at fal.a(PG:38)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:20:04.670  2956  4366 E HttpOperation: 	... 14 more
,08-10 12:20:04.752  1492  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:20:04.752  1492  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 12:20:04.752  1492  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:20:04.752  1492  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:20:04.776  2956  4366 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 12:20:04.776  2956  4366 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at hec.a(PG:42)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at hee.a(PG:102)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at czr.a(PG:65)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at kka.a(PG:108)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at czp.a(PG:19176)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:20:04.776  2956  4366 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	... 15 more
08-10 12:20:04.776  2956  4366 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at fal.a(PG:38)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:20:04.776  2956  4366 E HttpOperation: 	... 17 more
08-10 12:20:04.777  2956  4366 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 12:20:04.777  2956  4366 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at hec.a(PG:42)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at hee.a(PG:102)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at czr.a(PG:65)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at kka.a(PG:108)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	... 15 more
08-10 12:20:04.777  2956  4366 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at fal.a(PG:38)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 12:20:04.777  2956  4366 E ExperimentLoader: 	... 17 more
,08-10 12:20:04.914   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 496181, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:20:21.366   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=513224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:20:27.553   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=519410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:20:57.206   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=549064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:21:03.579   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=555437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:21:26.880  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 12:21:26.881  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:21:26.894  3934  4373 V GoogleAuthProtoRequest: [361] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 12:21:26.937  1492  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-10 12:21:26.938  1492  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-10 12:21:26.938  1492  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:21:26.938  1492  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:21:26.959  3934  4373 W ExperimentUpdateService: [361] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-10 12:21:26.960  3934  4373 W ExperimentUpdateService: [361] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 12:21:26.960  3934  4373 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 12:21:26.960  3934  4373 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 12:21:26.960  3934  4373 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 12:21:26.960  3934  4373 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 12:21:26.960  3934  4373 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 12:21:26.960  3934  4373 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 12:21:26.960  3934  4373 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 12:21:26.960  3934  4373 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 12:21:26.960  3934  4373 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 12:21:26.960  3934  4373 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 12:21:33.259   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=585117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:21:39.512   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=591370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:22:09.206   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=621064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:22:17.873   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=629731, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:22:44.018  4190  4380 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 12:22:44.039  4190  4381 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 12:22:44.050  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:22:44.052  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:22:44.084  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 12:22:44.084  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 12:22:44.084  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:22:44.084  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:22:44.117  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:22:44.119  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:22:44.143  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 12:22:44.144  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 12:22:44.144  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:22:44.144  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:22:44.177  4190  4381 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 12:22:44.178  4190  4380 E BooksSync: Soft error
08-10 12:22:44.178  4190  4380 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:22:44.178  4190  4380 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 12:22:44.178  4190  4380 E BooksSync: Sync error
08-10 12:22:44.178  4190  4380 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:22:44.178  4190  4380 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 12:22:44.179  4190  4380 I BooksSync: Finished books sync
,08-10 12:22:44.199   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 655754, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:22:47.499   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=659357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:22:53.393   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=665250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:23:14.449  3957  4384 V KeepSync: Connecting to GoogleApiClient
,08-10 12:23:14.449   875  1686 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 12:23:14.508  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:23:14.510  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:23:14.551  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-10 12:23:14.552  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-10 12:23:14.552  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:23:14.552  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:23:14.577  1778  4385 V BaseAuthAsyncOperation: access token request failed
,08-10 12:23:14.578  3957  4384 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 12:23:14.657  1492  2930 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 12:23:14.658  1492  2930 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 12:23:14.658  1492  2930 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:23:14.658  1492  2930 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:23:14.679  3957  4384 E KeepSync: IOException
08-10 12:23:14.679  3957  4384 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 12:23:14.679  3957  4384 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 12:23:14.679  3957  4384 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 12:23:14.679  3957  4384 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 12:23:14.679  3957  4384 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 12:23:14.679  3957  4384 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 12:23:14.679  3957  4384 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 12:23:14.679  3957  4384 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 12:23:14.679  3957  4384 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 12:23:14.679  3957  4384 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 12:23:14.679  3957  4384 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 12:23:14.679  3957  4384 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 12:23:14.679  3957  4384 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 12:23:14.679  3957  4384 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 12:23:14.679  3957  4384 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 12:23:14.679  3957  4384 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 12:23:14.679  3957  4384 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 12:23:14.679  3957  4384 E KeepSync: 	... 10 more
08-10 12:23:14.679  3957  4384 W KeepSync: Sync result 2
,08-10 12:23:14.691   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 656245, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:23:23.019   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=694877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:23:28.780   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=700637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:23:58.433   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=730290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:24:04.139   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=735997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:24:12.866  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:24:12.867  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:24:12.918  1492  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:24:12.918  1492  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 12:24:12.918  1492  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:24:12.918  1492  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:24:12.941  2956  4390 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 12:24:12.941  2956  4390 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at blb.a(PG:3937)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at czp.a(PG:18188)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:24:12.941  2956  4390 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	... 12 more
08-10 12:24:12.941  2956  4390 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at fal.a(PG:38)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:24:12.941  2956  4390 E HttpOperation: 	... 14 more
,08-10 12:24:13.012  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:24:13.015  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 12:24:13.015  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:24:13.015  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:24:13.041  2956  4390 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 12:24:13.041  2956  4390 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at hec.a(PG:42)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at hee.a(PG:102)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at czr.a(PG:65)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at kka.a(PG:108)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at czp.a(PG:19176)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:24:13.041  2956  4390 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	... 15 more
08-10 12:24:13.041  2956  4390 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at fal.a(PG:38)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:24:13.041  2956  4390 E HttpOperation: 	... 17 more
,08-10 12:24:13.042  2956  4390 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 12:24:13.042  2956  4390 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at hec.a(PG:42)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at hee.a(PG:102)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at czr.a(PG:65)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at kka.a(PG:108)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	... 15 more
08-10 12:24:13.042  2956  4390 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at fal.a(PG:38)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 12:24:13.042  2956  4390 E ExperimentLoader: 	... 17 more
,08-10 12:24:13.156   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 744396, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:24:33.739   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=765597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:24:39.473   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=771330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:25:09.153   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=801010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:25:14.832   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=806690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:25:27.084  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:25:27.086  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:25:27.101  3934  4396 V GoogleAuthProtoRequest: [362] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 12:25:27.131  1492  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-10 12:25:27.131  1492  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-10 12:25:27.131  1492  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:25:27.131  1492  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:25:27.153  3934  4396 W ExperimentUpdateService: [362] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 12:25:27.154  3934  4396 W ExperimentUpdateService: [362] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 12:25:27.154  3934  4396 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 12:25:27.154  3934  4396 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 12:25:27.154  3934  4396 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 12:25:27.154  3934  4396 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 12:25:27.154  3934  4396 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 12:25:27.154  3934  4396 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 12:25:27.154  3934  4396 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 12:25:27.154  3934  4396 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 12:25:27.154  3934  4396 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 12:25:27.154  3934  4396 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 12:25:44.459   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=836317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:25:50.299   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=842157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:26:19.979   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=871837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:26:26.379   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=878237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:26:43.872   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=895730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:26:51.619   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=903477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:27:09.099   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=920957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:27:17.446   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=929303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:27:34.913   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=946771, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:27:40.633   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=952491, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:27:58.113   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=969970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:28:05.873   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=977730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:28:23.339   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=995197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:28:31.473   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1003330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:28:48.939   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1020797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:28:56.726   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1028584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:29:14.219   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1046077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:29:22.539   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1054397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:29:39.979   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1071836, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:29:48.486   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1080344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:30:05.953   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1097810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:30:13.713   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1105570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:30:31.180   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1123037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:30:39.472   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1131330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:30:56.939   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1148797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:31:04.726   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1156584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:31:06.274  4190  4412 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 12:31:06.298  4190  4413 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 12:31:06.314  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:31:06.319  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:31:06.357  1492  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 12:31:06.357  1492  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 12:31:06.357  1492  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:31:06.357  1492  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:31:06.397  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:31:06.400  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:31:06.445  1492  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 12:31:06.445  1492  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 12:31:06.445  1492  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:31:06.446  1492  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:31:06.477  4190  4413 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 12:31:06.479  4190  4412 E BooksSync: Soft error
08-10 12:31:06.479  4190  4412 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:31:06.479  4190  4412 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 12:31:06.479  4190  4412 E BooksSync: Sync error
08-10 12:31:06.479  4190  4412 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:31:06.479  4190  4412 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 12:31:06.480  4190  4412 I BooksSync: Finished books sync
,08-10 12:31:06.493   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1157833, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:31:22.753   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1174610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:31:30.486   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1182343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:31:36.861  3957  4416 V KeepSync: Connecting to GoogleApiClient
,08-10 12:31:36.862   875  1762 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 12:31:36.921  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:31:36.924  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:31:36.958  1492  2930 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 12:31:36.958  1492  2930 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 12:31:36.958  1492  2930 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:31:36.958  1492  2930 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:31:36.980  1778  4417 V BaseAuthAsyncOperation: access token request failed
,08-10 12:31:36.981  3957  4416 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 12:31:37.033  1492  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 12:31:37.033  1492  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 12:31:37.033  1492  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:31:37.033  1492  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:31:37.048  3957  4416 E KeepSync: IOException
08-10 12:31:37.048  3957  4416 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 12:31:37.048  3957  4416 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 12:31:37.048  3957  4416 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 12:31:37.048  3957  4416 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 12:31:37.048  3957  4416 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 12:31:37.048  3957  4416 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 12:31:37.048  3957  4416 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 12:31:37.048  3957  4416 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 12:31:37.048  3957  4416 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 12:31:37.048  3957  4416 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 12:31:37.048  3957  4416 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 12:31:37.048  3957  4416 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 12:31:37.048  3957  4416 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 12:31:37.048  3957  4416 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 12:31:37.048  3957  4416 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 12:31:37.048  3957  4416 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 12:31:37.048  3957  4416 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 12:31:37.048  3957  4416 E KeepSync: 	... 10 more
08-10 12:31:37.048  3957  4416 W KeepSync: Sync result 2
,08-10 12:31:37.063   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1188597, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:31:42.592   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1194450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:31:51.366   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1203224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:32:03.446   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1215304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:32:06.129   875   887 I UsageStatsService: User[0] Flushing usage stats to disk
,08-10 12:32:11.579   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1223437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:32:23.660   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1235517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:32:28.744  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
08-10 12:32:28.745  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:32:28.781  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:32:28.781  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 12:32:28.781  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:32:28.781  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:32:28.798  2956  4421 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 12:32:28.798  2956  4421 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at blb.a(PG:3937)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at czp.a(PG:18188)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:32:28.798  2956  4421 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	... 12 more
08-10 12:32:28.798  2956  4421 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at fal.a(PG:38)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:32:28.798  2956  4421 E HttpOperation: 	... 14 more
,08-10 12:32:28.842  1492  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:32:28.842  1492  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 12:32:28.842  1492  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:32:28.842  1492  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:32:28.859  2956  4421 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 12:32:28.859  2956  4421 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at hec.a(PG:42)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at hee.a(PG:102)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at czr.a(PG:65)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at kka.a(PG:108)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at czp.a(PG:19176)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,08-10 12:32:28.859  2956  4421 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:32:28.859  2956  4421 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	... 15 more
08-10 12:32:28.859  2956  4421 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at fal.a(PG:38)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:32:28.859  2956  4421 E HttpOperation: 	... 17 more
,08-10 12:32:28.859  2956  4421 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 12:32:28.859  2956  4421 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at hec.a(PG:42)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at hee.a(PG:102)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at czr.a(PG:65)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at kka.a(PG:108)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	... 15 more
08-10 12:32:28.859  2956  4421 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at fal.a(PG:38)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 12:32:28.859  2956  4421 E ExperimentLoader: 	... 17 more
,08-10 12:32:29.002   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1240262, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:32:32.340   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1244197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:32:44.460   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1256317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:32:52.526   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1264384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:33:04.620   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1276477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:33:12.699   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1284557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:33:24.779   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1296637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:33:27.287  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:33:27.289  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:33:27.299  3934  4428 V GoogleAuthProtoRequest: [363] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 12:33:27.329  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-10 12:33:27.329  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-10 12:33:27.329  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:33:27.329  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:33:27.346  3934  4428 W ExperimentUpdateService: [363] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 12:33:27.347  3934  4428 W ExperimentUpdateService: [363] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 12:33:27.347  3934  4428 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 12:33:27.347  3934  4428 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 12:33:27.347  3934  4428 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 12:33:27.347  3934  4428 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 12:33:27.347  3934  4428 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 12:33:27.347  3934  4428 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 12:33:27.347  3934  4428 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 12:33:27.347  3934  4428 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 12:33:27.347  3934  4428 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 12:33:27.347  3934  4428 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 12:33:32.006   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1303863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 12:33:39.153   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1311010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:33:48.579   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1320437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:34:01.419   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1333277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:34:09.459   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1341317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:34:21.579   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1353436, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:34:29.646   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1361503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:34:41.739   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1373597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:34:50.566   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1382423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:35:02.646   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1394504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:35:10.780   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1402637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:35:23.446   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1415304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:35:31.499   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1423357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:35:43.606   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1435464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:35:51.766   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1443623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:36:04.193   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1456050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:36:12.246   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1464103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:36:24.459   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1476317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:36:34.406   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1486263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:36:54.486   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1506344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:36:59.646   875  4143 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1511503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,TIME-OUT KILL (timeout was 1400000ms)
```
