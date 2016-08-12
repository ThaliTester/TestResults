#### Test 80912877c1aacde_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-12 11:11:11.605  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:11:11.620  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 11:11:11.626  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 11:11:11.687  1495  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 11:11:11.688  1495  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 11:11:11.688  1495  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:11:11.689  1495  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-12 11:11:11.730  3500  3500 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-12 11:11:11.733  3500  3500 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 11:11:11.733  3500  3500 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
08-12 11:11:12.320  3749  3749 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 11:11:12.326  3749  3749 D AndroidRuntime: CheckJNI is OFF
08-12 11:11:12.369  3749  3749 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 11:11:12.441  3749  3749 I Radio-JNI: register_android_hardware_Radio DONE
08-12 11:11:12.468  3749  3749 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 11:11:12.473   873   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 11:11:12.492  3749  3749 D AndroidRuntime: Shutting down VM
08-12 11:11:12.496  2015  3711 W SearchService: Abort, client detached.
08-12 11:11:12.507  2015  2322 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@189536b
08-12 11:11:12.507  2015  2330 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 11:11:12.507  2015  2015 I HotwordDetector: Closing mic
08-12 11:11:12.519   873  1981 I ActivityManager: Start proc 3759:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-12 11:11:12.555   375  2332 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 11:11:12.557   375  2332 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 11:11:12.562   375  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 11:11:12.564  2015  2326 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-12 11:11:12.565  2015  2329 I MicroRecognitionRnrImpl: Detection finished
08-12 11:11:12.587  3759  3759 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-12 11:11:12.616  3759  3759 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-12 11:11:12.624  3759  3759 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9818-9821)
08-12 11:11:12.624  3759  3759 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 11:11:12.637  3759  3759 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8b5b1ac}
08-12 11:11:12.637  3759  3759 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 11:11:12.638  3759  3759 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 11:11:12.644  3759  3759 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 11:11:12.645  3759  3759 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 11:11:12.673  3759  3759 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-12 11:11:12.684  3759  3759 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 11:11:12.684  3759  3759 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 11:11:12.684  3759  3759 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 11:11:12.684  3759  3759 I Adreno  : Build Date                       : 10/20/15
08-12 11:11:12.684  3759  3759 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 11:11:12.684  3759  3759 I Adreno  : Local Branch                     : M14
08-12 11:11:12.684  3759  3759 I Adreno  : Remote Branch                    : 
08-12 11:11:12.684  3759  3759 I Adreno  : Remote Branch                    : 
08-12 11:11:12.684  3759  3759 I Adreno  : Reconstruct Branch               : 
,08-12 11:11:12.747   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e78acb9:true
,08-12 11:11:12.747   873  2092 D NetlinkSocketObserver: NeighborEvent{elapsedMs=119943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 11:11:12.777  3759  3759 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 11:11:12.787  3759  3759 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-12 11:11:12.852  3759  3797 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 11:11:12.873  3759  3784 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-12 11:11:12.906  3759  3797 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 11:11:12.989   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +489ms
,08-12 11:11:13.003  1868  1868 I Keyboard.Facilitator: onFinishInput()
,08-12 11:11:13.015  3759  3759 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3759
,08-12 11:11:13.136  3759  3759 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 11:11:13.306  3759  3800 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1682175696
,08-12 11:11:13.314  3759  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 11:11:13.314  3759  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 11:11:13.314  3759  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 11:11:13.314  3759  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 11:11:13.314  3759  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 11:11:13.314  3759  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9031b3 added. We now have 1 listener(s)
,08-12 11:11:13.318  3759  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-12 11:11:13.319  3759  3800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 11:11:13.319  3759  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 11:11:13.320  3759  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 11:11:13.328  3759  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cddbf6e added. We now have 1 listener(s)
08-12 11:11:13.329  3759  3800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 11:11:13.332   873  1307 D WifiService: New client listening to asynchronous messages
,08-12 11:11:13.334  3759  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 11:11:13.334  3759  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 11:11:13.334  3759  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 11:11:13.334  3759  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 11:11:13.334  3759  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 11:11:13.338   873  1975 I ActivityManager: Killing 2974:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-12 11:11:13.386   873  1975 I ActivityManager: Killing 3072:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-12 11:11:13.423  3759  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 11:11:13.424  3759  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-12 11:11:13.433  3759  3800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage,
,08-12 11:11:13.433  3759  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 11:11:13.433  3759  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 11:11:13.433  3759  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 11:11:13.433  3759  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 11:11:13.433  3759  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 11:11:13.433  3759  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 11:11:13.433  3759  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 11:11:13.433  3759  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 11:11:13.433  3759  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 11:11:13.433  3759  3800 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 11:11:13.434  3759  3800 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 11:11:13.551  3759  3759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 11:11:13.554  3759  3759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 11:11:13.557  3759  3759 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 11:11:14.339  3759  3809 W jxcore-log: Initializing JXcore engine
,08-12 11:11:14.339  3759  3809 W jxcore-log: JXcore engine is ready
,08-12 11:11:14.382  3809  3809 W Thread-317: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-12 11:11:14.382  3809  3809 W Thread-317: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11720]" dev="sockfs" ino=11720 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 11:11:14.382  3809  3809 W Thread-317: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-12 11:11:14.382  3809  3809 W Thread-317: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24404]" dev="sockfs" ino=24404 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-12 11:11:14.397  3759  3809 W jxcore-log: Starting JXcore engine
,08-12 11:11:14.525  3759  3809 W jxcore-log: Platform android
08-12 11:11:14.525  3759  3809 W jxcore-log: 
,08-12 11:11:14.526  3759  3809 W jxcore-log: Process ARCH arm
08-12 11:11:14.526  3759  3809 W jxcore-log: 
,08-12 11:11:14.771  3759  3809 I jxcore-log: JXcore Cordova bridge is ready!
08-12 11:11:14.771  3759  3809 I jxcore-log: 
,08-12 11:11:14.772  3759  3809 W jxcore-log: JXcore engine is started
,08-12 11:11:14.782  3759  3800 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 11:11:14.788  3759  3759 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 11:11:16.367   873  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-12 11:11:18.426   873  2092 D NetlinkSocketObserver: NeighborEvent{elapsedMs=125623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 11:11:20.376  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:11:20.381  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:11:20.413  1495  2987 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-12 11:11:20.414  1495  2987 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-12 11:11:20.414  1495  2987 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:11:20.414  1495  2987 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:11:20.453  2991  3817 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 11:11:20.453  2991  3817 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at jdm.a(PG:82)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at jcs.o(PG:406)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at jcn.a(PG:1379)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at jcs.i(PG:143)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at blb.a(PG:3937)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at czp.a(PG:18188)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at czp.a(PG:9081)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at czq.run(PG:1686)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:11:20.453  2991  3817 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at jdj.a(PG:4091)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at jdj.a(PG:1125)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at jdm.a(PG:77)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	... 12 more
08-12 11:11:20.453  2991  3817 E HttpOperation: Caused by: faj: BadAuthentication
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at fal.a(PG:38)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	at jdj.a(PG:4089)
08-12 11:11:20.453  2991  3817 E HttpOperation: 	... 14 more
,08-12 11:11:20.486  1495  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 11:11:20.487  1495  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 11:11:20.487  1495  2036 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-12 11:11:20.487  1495  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:11:20.499  2991  3817 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 11:11:20.499  2991  3817 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at jdm.a(PG:82)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at jcs.o(PG:406)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at jcn.a(PG:1379)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at jcs.i(PG:143)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at hec.a(PG:42)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at hee.a(PG:102)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at czr.a(PG:65)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at kka.a(PG:108)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at czp.a(PG:19176)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at czp.a(PG:9081)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at czq.run(PG:1686)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:11:20.499  2991  3817 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at jdj.a(PG:4091)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at jdj.a(PG:1125)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at jdm.a(PG:77)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	... 15 more
08-12 11:11:20.499  2991  3817 E HttpOperation: Caused by: faj: BadAuthentication
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at fal.a(PG:38)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	at jdj.a(PG:4089)
08-12 11:11:20.499  2991  3817 E HttpOperation: 	... 17 more
,08-12 11:11:20.500  2991  3817 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 11:11:20.500  2991  3817 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at hec.a(PG:42)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at hee.a(PG:102)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at czr.a(PG:65)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at kka.a(PG:108)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	... 15 more
08-12 11:11:20.500  2991  3817 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at fal.a(PG:38)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 11:11:20.500  2991  3817 E ExperimentLoader: 	... 17 more
,08-12 11:11:20.587   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 127378, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 11:11:20.652  3034  3819 V KeepSync: Connecting to GoogleApiClient
08-12 11:11:20.652   873  1977 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 11:11:20.717  1495  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-12 11:11:20.717  1495  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-12 11:11:20.717  1495  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:11:20.717  1495  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:11:20.753  1706  3820 V BaseAuthAsyncOperation: access token request failed
,08-12 11:11:20.754  3034  3819 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 11:11:20.814  1495  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 11:11:20.815  1495  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-12 11:11:20.815  1495  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:11:20.815  1495  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:11:20.848  3034  3819 E KeepSync: IOException
08-12 11:11:20.848  3034  3819 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 11:11:20.848  3034  3819 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 11:11:20.848  3034  3819 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 11:11:20.848  3034  3819 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 11:11:20.848  3034  3819 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 11:11:20.848  3034  3819 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 11:11:20.848  3034  3819 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 11:11:20.848  3034  3819 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 11:11:20.848  3034  3819 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 11:11:20.848  3034  3819 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 11:11:20.848  3034  3819 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 11:11:20.848  3034  3819 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 11:11:20.848  3034  3819 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 11:11:20.848  3034  3819 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 11:11:20.848  3034  3819 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 11:11:20.848  3034  3819 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 11:11:20.848  3034  3819 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 11:11:20.848  3034  3819 E KeepSync: 	... 10 more
,08-12 11:11:20.848  3034  3819 W KeepSync: Sync result 2
,08-12 11:11:20.853   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127667, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 11:11:24.973  3759  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 11:11:24.973  3759  3809 I jxcore-log: 
,08-12 11:11:24.975  3759  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 11:11:24.975  3759  3809 I jxcore-log: 
,08-12 11:11:24.988  3759  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 11:11:24.988  3759  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 11:11:24.988  3759  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 11:11:24.988  3759  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 11:11:24.988  3759  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 11:11:24.988  3759  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 11:11:24.988  3759  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 11:11:24.988  3759  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 11:11:24.994  3759  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-12 11:11:24.997  3759  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 11:11:24.997  3759  3809 I jxcore-log: 
,08-12 11:11:24.999  3759  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 11:11:24.999  3759  3809 I jxcore-log: 
,08-12 11:11:25.329  3759  3809 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-12 11:11:25.330  3759  3809 I jxcore-log: Failed to execute UT.
08-12 11:11:25.330  3759  3809 I jxcore-log: 
,08-12 11:11:25.330  3759  3809 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 11:11:25.330  3759  3809 I jxcore-log: 
,08-12 11:11:25.333  3759  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 11:11:25.333  3759  3809 I jxcore-log: 
,08-12 11:11:25.357  3759  3759 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 11:11:25.982  3825  3825 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-12 11:11:25.987  3825  3825 D AndroidRuntime: CheckJNI is OFF
,08-12 11:11:26.023  3825  3825 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 11:11:26.063  3825  3825 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 11:11:26.083  3825  3825 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 11:11:26.099   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-12 11:11:26.099   873   886 I ActivityManager: Killing 3759:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-12 11:11:26.215   873   896 W PackageSettings: Skipping PackageSetting{c5b470b com.example.hello/10273} due to missing metadata
,08-12 11:11:26.221   873  1975 I WindowState: WIN DEATH: Window{4413629 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 11:11:26.223   873  1391 D GraphicsStats: Buffer count: 2
,08-12 11:11:26.226   873  1307 D WifiService: Client connection lost with reason: 4
,08-12 11:11:26.253   873   886 W ActivityManager: Force removing ActivityRecord{b4f5876 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,08-12 11:11:26.272   873   896 I art     : Starting a blocking GC Explicit
,08-12 11:11:26.282   873  1983 W ActivityManager: Spurious death for ProcessRecord{fa37188 0:com.test.thalitest/u0a0}, curProc for 3759: null
,08-12 11:11:26.315   873  1977 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3759 uid 10000
,08-12 11:11:26.322  1868  1868 I Keyboard.Facilitator: onFinishInput()
,08-12 11:11:26.337   873   896 I art     : Explicit concurrent mark sweep GC freed 43927(2MB) AllocSpace objects, 11(224KB) LOS objects, 33% free, 29MB/43MB, paused 946us total 60.990ms
,08-12 11:11:26.375   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 11:11:26.383  3825  3825 I art     : System.exit called, status: 0
,08-12 11:11:26.383  3825  3825 I AndroidRuntime: VM exiting with result code 0.
08-12 11:11:26.385  2015  3838 I MicroRecognitionRnrImpl: Starting detection.
08-12 11:11:26.388  2015  3839 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@4f5b0b2
08-12 11:11:26.391   375  3841 I AudioFlinger: AudioFlinger's thread 0xb3140000 ready to run
,08-12 11:11:26.391   375  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 11:11:26.392  2015  3839 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@4f5b0b2
,08-12 11:11:26.396   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-12 11:11:26.402   375  3841 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
08-12 11:11:26.402   375  3841 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-12 11:11:26.402   375  3841 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-12 11:11:26.409   375  3841 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-12 11:11:26.419  2629  2629 D BluetoothMapAppObserver: onReceive
,08-12 11:11:26.419  2629  2629 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-12 11:11:26.423  1880  2245 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 11:11:26.425   873  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 11:11:26.427  1868  1868 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-12 11:11:26.445  1868  3844 I Keyboard.Facilitator.DecoderInitializer: run()
,08-12 11:11:26.449  3601  3601 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-12 11:11:26.457  1868  3844 I Decoder : createOrResetDecoder
,08-12 11:11:26.471  1937  1937 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 11:11:26.487  1495  1495 I ConfigService: onCreate
,08-12 11:11:26.494  2015  2015 I HotwordWorkerImpl: onReady
,08-12 11:11:26.510  1495  1495 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-12 11:11:26.510  1495  1495 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-12 11:11:26.517  1868  3844 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-12 11:11:26.530  1706  3855 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-12 11:11:26.530  1706  3855 D AccountUtils: Clearing selected account for com.test.thalitest
,08-12 11:11:26.535  1687  3851 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-12 11:11:26.540  1706  3855 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-12 11:11:26.546  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-12 11:11:26.547  1706  1706 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-12 11:11:26.552   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 11:11:26.554  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-12 11:11:26.554  1706  1706 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-12 11:11:26.564  1706  3860 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-12 11:11:26.564  1706  3860 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
08-12 11:11:26.564  1706  3860 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
,08-12 11:11:26.564  1706  3860 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
,08-12 11:11:26.570  2015  3864 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-12 11:11:26.570  1706  3860 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db, release reference: 1
08-12 11:11:26.570  1706  3860 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 2
08-12 11:11:26.571  1706  3860 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 1
,08-12 11:11:26.576  1706  3860 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,08-12 11:11:26.576  1706  3860 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db: 2
08-12 11:11:26.579  1868  3844 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-12 11:11:26.580  1868  3844 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-12 11:11:26.580  1868  3844 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-12 11:11:26.586  1706  3860 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,08-12 11:11:26.587  1706  3860 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 0
08-12 11:11:26.587  1706  3860 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db, release reference: 0
,08-12 11:11:26.587  1706  3860 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,08-12 11:11:26.597  1868  3844 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict,
,08-12 11:11:26.597  1868  3844 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-12 11:11:26.597  1868  3844 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-12 11:11:26.598  1868  3844 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-12 11:11:26.598  1868  3844 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-12 11:11:26.598  1868  3844 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-12 11:11:26.598  1868  3844 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-12 11:11:26.604  1687  3851 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-12 11:11:26.606  1868  3844 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-12 11:11:26.606  1868  3844 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-12 11:11:26.606  1868  3844 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-12 11:11:26.608  2015  3864 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
--------- beginning of crash
08-12 11:11:26.608  1687  3851 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-12 11:11:26.608  1687  3851 E AndroidRuntime: Process: android.process.acore, PID: 1687
08-12 11:11:26.608  1687  3851 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-12 11:11:26.608  1,687  3851 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:11:26.608  1687  3851 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 11:11:26.615   873   884 I ActivityManager: Start proc 3868:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-12 11:11:26.627   873  1601 I ActivityManager: Start proc 3880:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-12 11:11:26.629  2015  3864 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-12 11:11:26.629  2015  3864 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-12 11:11:26.629  2015  3864 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2015
08-12 11:11:26.629  2015  3864 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at com.google.android.search.core.icings,ync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:11:26.629  2015  3864 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 11:11:26.634  1957  2643 E ObservedEventLogger: Failed to write the stream file
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2431: open failed: EROFS (Read-only file system)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:11:26.634  1957  2643 E ObservedEventLogger: 	... 16 more
,08-12 11:11:26.635   873  3885 E DropBoxManagerService: Can't write: system_app_crash
08-12 11:11:26.635   873  3885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
08-12 11:11:26.635   873  3885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:11:26.635   873  3885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:11:26.635   873  3885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:11:26.635   873  3885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:11:26.635   873  3885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:11:26.635   873  3885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:11:26.635   873  3885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:11:26.635   873  3885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:11:26.635   873  3885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:11:26.635   873  3885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:11:26.635   873  3885 E DropBoxManagerService: 	... 5 more
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: Failed to write the stream file
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2432: open failed: EROFS (Read-only file system)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:11:26.636  1957  2643 E ObservedEventLogger: 	... 16 more
08-12 11:11:26.644   873  3893 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-12 11:11:26.650  1706  3861 W BaseAppContext: Using Auth Proxy for data requests.
08-12 11:11:26.652  1706  3894 I GMPM-SVC: App measurement is starting up
08-12 11:11:26.653   873  3896 E DropBoxManagerService: Can't write: system_app_crash
08-12 11:11:26.653   873  3896 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-12 11:11:26.653   873  3896 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:11:26.653   873  3896 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:11:26.653   873  3896 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:11:26.653   873  3896 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:11:26.653   873  3896 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:11:26.653   873  3896 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:11:26.653   873  3896 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:11:26.653   873  3896 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:11:26.653   873  3896 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:11:26.653   873  3896 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:11:26.653   873  3896 E DropBoxManagerService: 	... 5 more
08-12 11:11:26.654  1706  3894 E GMPM-SVC: AppMeasurementService not registered/enabled
08-12 11:11:26.654  1706  3894 E GMPM-SVC: Uploading is not possible. App measurement disabled
08-12 11:11:26.664  1706  1706 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-12 11:11:26.665  1706  3861 W BaseAppContext: Using Auth Proxy for data requests.
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement.db'.
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:11:26.668  1706  3894 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
08-12 11:11:26.668  1706  3894 E GMPM-SVC: Opening the database failed, dropping and recreating it
08-12 11:11:26.670  1706  2509 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml.bak
08-12 11:11:26.671  1706  1706 I ConfigFetchService: service connected
,08-12 11:11:26.673  1706  3894 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement.db'.
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:11:26.673  1706  3894 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
08-12 11:11:26.673  1706  3894 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/app_state.db'.
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:11:26.674  1706  3861 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: Runtime exception while performing operation
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: Killing (on development devices) due to RuntimeException
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:11:26.675  1706  3861 E ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:11:26.676  1706  3894 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
08-12 11:11:26.676  1706  3894 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
08-12 11:11:26.679  1706  2509 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
08-12 11:11:26.680  1706  2509 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
08-12 11:11:26.680  1706  2509 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
08-12 11:11:26.680  1706  2509 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
08-12 11:11:26.680  1706  2509 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
08-12 11:11:26.680  1706  2509 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
08-12 11:11:26.683  1706  3898 I PeopleContactsSync: CP2 sync disabled
08-12 11:11:26.684   873  3899 E DropBoxManagerService: Can't write: system_app_wtf
08-12 11:11:26.684   873  3899 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-12 11:11:26.684   873  3899 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:11:26.684   873  3899 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:11:26.684   873  3899 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:11:26.684   873  3899 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:11:26.684   873  3899 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:11:26.684   873  3899 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:11:26.684   873  3899 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:11:26.684   873  3899 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:11:26.684   873  3899 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:11:26.684   873  3899 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:11:26.684   873  3899 E DropBoxManagerService: 	... 5 more
08-12 11:11:26.684  1706  2336 I Icing   : doRemovePackageData com.test.thalitest
08-12 11:11:26.685  3868  3868 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
08-12 11:11:26.688   873  3893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 11:11:26.688   873  3893 I Adreno  : Build Date                       : 10/20/15
08-12 11:11:26.688   873  3893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 11:11:26.688   873  3893 I Adreno  : Local Branch                     : M14
08-12 11:11:26.688   873  3893 I Adreno  : Remote Branch                    : 
08-12 11:11:26.688   873  3893 I Adreno  : Remote Branch                    : 
08-12 11:11:26.688   873  3893 I Adreno  : Reconstruct Branch               : 
08-12 11:11:26.692  3868  3868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
08-12 11:11:26.696   873  3893 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 11:11:26.709  1957  2053 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-12 11:11:26.713  1957  2053 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-12 11:11:26.713  1957  2053 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1957
08-12 11:11:26.713  1957  2053 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 11:11:26.713  1957  2053 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 11:11:26.713  1957  2053 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 11:11:26.713  1957  2053 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 11:11:26.713  1957  2053 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 11:11:26.713  1957  2053 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 11:11:26.713  1957  2053 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-12 11:11:26.713  1957  2053 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-12 11:11:26.713  1957  2053 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 11:11:26.713  1957  2053 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 11:11:26.713  1957  2053 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:11:26.713  1957  2053 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 11:11:26.716   873  3903 E DropBoxManagerService: Can't write: system_app_crash
08-12 11:11:26.716   873  3903 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-12 11:11:26.716   873  3903 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:11:26.716   873  3903 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:11:26.716   873  3903 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:11:26.716   873  3903 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:11:26.716   873  3903 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:11:26.716   873  3903 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:11:26.716   873  3903 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:11:26.716   873  3903 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:11:26.716   873  3903 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:11:26.716   873  3903 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:11:26.716   873  3903 E DropBoxManagerService: 	... 5 more
08-12 11:11:26.717   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-12 11:11:26.717   873   885 E PackageManager: Failed to write settings, restoring backup
08-12 11:11:26.717   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-12 11:11:26.717   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-12 11:11:26.717   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-12 11:11:26.717   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-12 11:11:26.717   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-12 11:11:26.717   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:11:26.717   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:11:26.717   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 11:11:26.719   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-12 11:11:26.719   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 11:11:26.719   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:11:26.719   873   886 E DropBoxManagerService: 	... 13 more
08-12 11:11:26.721   873  1681 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-12 11:11:26.722   873  1681 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-12 11:11:26.726   873  1681 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-12 11:11:26.728   873  1681 I ActivityManager: Killing 1957:com.google.android.googlequicksearchbox/u0a28 (adj 0): crash
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:11:26.736  3868  3906 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-12 11:11:26.737  3868  3906 E AndroidRuntime: Process: com.android.keychain, PID: 3868
08-12 11:11:26.737  3868  3906 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:11:26.737  3868  3906 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 11:11:26.769   873  1394 D GraphicsStats: Buffer count: 2
,08-12 11:11:26.771  2015  2015 E AttachedClient: AttachedClient[8405251021938, ClientConfig[mFlags=[210d800202] mSuggestFlags=[3b] mClientStats=SearchBoxStats[gel/android-search-app]]]: failed callback onGenericEvent()
08-12 11:11:26.771  2015  2015 E AttachedClient: android.os.DeadObjectException
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at android.os.BinderProxy.transactNative(Native Method)
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at android.os.BinderProxy.transact(Binder.java:503)
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at com.google.android.apps.gsa.search.shared.service.l.c(ISearchServiceUiCallback.java:578)
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at com.google.android.search.core.service.a.c(AttachedClient.java:4725)
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at com.google.android.search.core.service.a.b(AttachedClient.java:185)
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at com.google.android.search.core.ad.c(SearchController.java:51069)
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at com.google.android.search.core.service.SearchService.bca(SearchService.java:373)
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at com.google.android.search.core.service.SearchService$1.run(SearchService.java:83)
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 11:11:26.771  2015  2015 E AttachedClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-12 11:11:26.771  2015  2015 I SearchService: Ignoring already detached client
08-12 11:11:26.772  2015  2015 I HotwordDetector: Closing mic
,08-12 11:11:26.772  2015  2322 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@4f5b0b2
08-12 11:11:26.773  2015  3839 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-12 11:11:26.796   873  1681 I ActivityManager: Start proc 3908:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-12 11:11:26.807   873  1982 W ActivityManager: Spurious death for ProcessRecord{32cf6c5 0:com.google.android.googlequicksearchbox/u0a28}, curProc for 1957: null
,08-12 11:11:26.811   873  3913 E DropBoxManagerService: Can't write: system_app_crash
08-12 11:11:26.811   873  3913 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-12 11:11:26.811   873  3913 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:11:26.811   873  3913 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:11:26.811   873  3913 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:11:26.811   873  3913 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:11:26.811   873  3913 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:11:26.811   873  3913 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:11:26.811   873  3913 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:11:26.811   873  3913 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:11:26.811   873  3913 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:11:26.811   873  3913 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:11:26.811   873  3913 E DropBoxManagerService: 	... 5 more
,08-12 11:11:26.816   375  3841 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-12 11:11:26.817   375  3841 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 11:11:26.820   375  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 11:11:26.822  2015  3838 I MicroRecognitionRnrImpl: Detection finished
,08-12 11:11:26.822  2015  2326 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-12 11:11:26.825   873   873 I ActivityManager: Start proc 3923:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,08-12 11:11:26.868  3908  3908 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688),
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 11:11:26.868  3908  3908 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 11:11:26.869  3908  3908 D AndroidRuntime: Shutting down VM
,08-12 11:11:26.879  3908  3908 E AndroidRuntime: FATAL EXCEPTION: main
08-12 11:11:26.879  3908  3908 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3908
08-12 11:11:26.879  3908  3908 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 11:11:26.879  3908  3908 E AndroidRuntime: 	... 10 more
,08-12 11:11:26.883   873  3936 E DropBoxManagerService: Can't write: system_app_crash
08-12 11:11:26.883   873  3936 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-12 11:11:26.883   873  3936 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:11:26.883   873  3936 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:11:26.883   873  3936 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:11:26.883   873  3936 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:11:26.883   873  3936 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:11:26.883   873  3936 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:11:26.883   873  3936 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:11:26.883   873  3936 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:11:26.883   873  3936 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:11:26.883   873  3936 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:11:26.883   873  3936 E DropBoxManagerService: 	... 5 more
,08-12 11:11:26.889  2015  3922 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-12 11:11:26.890   873  1983 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-12 11:11:26.919  1706  3935 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-12 11:11:26.920  1706  3935 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-12 11:11:26.925  1706  3935 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-12 11:11:26.926  1706  3935 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-12 11:11:26.937  1706  3935 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-12 11:11:26.939  1706  3935 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-12 11:11:26.941  3923  3923 W System  : ClassLoader referenced unknown path: /system/app/DocumentsUI/lib/arm
,08-12 11:11:26.960  3923  3923 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.documentsui/databases/recents.db'.
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:398)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1398)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 11:11:26.960  3923  3923 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-12 11:11:26.964  3923  3923 D AndroidRuntime: Shutting down VM
,08-12 11:11:26.965  3923  3923 E AndroidRuntime: FATAL EXCEPTION: main
08-12 11:11:26.965  3923  3923 E AndroidRuntime: Process: com.android.documentsui, PID: 3923
08-12 11:11:26.965  3923  3923 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:398)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1398)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
08-12 11:11:26.965  3923  3923 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-12 11:11:2,6.965  3923  3923 E AndroidRuntime: 	... 8 more
,08-12 11:11:26.968   873  3938 E DropBoxManagerService: Can't write: system_app_crash
08-12 11:11:26.968   873  3938 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
08-12 11:11:26.968   873  3938 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:11:26.968   873  3938 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:11:26.968   873  3938 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:11:26.968   873  3938 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:11:26.968   873  3938 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:11:26.968   873  3938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:11:26.968   873  3938 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:11:26.968   873  3938 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:11:26.968   873  3938 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:11:26.968   873  3938 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:11:26.968   873  3938 E DropBoxManagerService: 	... 5 more
,08-12 11:11:26.968  1341  2426 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10000)] disk I/O error
,08-12 11:11:26.969  1341  2426 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-12 11:11:26.969  1341  2426 E AndroidRuntime: Process: android.process.media, PID: 1341
08-12 11:11:26.969  1341  2426 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	,at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1215)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:117)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.-wrap1(DownloadReceiver.java)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:85)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:11:26.969  1341  2426 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 11:11:26.980   873  3939 E DropBoxManagerService: Can't write: system_app_crash
08-12 11:11:26.980   873  3939 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
08-12 11:11:26.980   873  3939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:11:26.980   873  3939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:11:26.980   873  3939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:11:26.980   873  3939 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:11:26.980   873  3939 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:11:26.980   873  3939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:11:26.980   873  3939 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:11:26.980   873  3939 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:11:26.980   873  3939 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:11:26.980   873  3939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:11:26.980   873  3939 E DropBoxManagerService: 	... 5 more
,08-12 11:11:27.021   280   280 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-12 11:11:27.022   280   280 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-12 11:11:27.022   280   280 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-12 11:11:27.022   280   280 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-12 11:11:27.022   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-12 11:11:27.022   280   280 E qdoverlay: MdpCtrl close error in unset
,08-12 11:11:27.024   873  1982 I ActivityManager: Start proc 3940:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,08-12 11:11:27.269   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 11:11:27.269   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted

```
