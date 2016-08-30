#### Test 7976383051d2164_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-30 11:36:42.594  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 11:36:42.608  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 11:36:42.613  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 11:36:42.680  1505  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 11:36:42.680  1505  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 11:36:42.681  1505  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 11:36:42.681  1505  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 11:36:42.730  3553  3553 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 11:36:42.731  3553  3553 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 11:36:42.732  3553  3553 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-30 11:36:43.244   874  2110 D NetlinkSocketObserver: NeighborEvent{elapsedMs=119730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
08-30 11:36:43.258  3797  3797 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 11:36:43.263  3797  3797 D AndroidRuntime: CheckJNI is OFF
08-30 11:36:43.305  3797  3797 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 11:36:43.353  3797  3797 I Radio-JNI: register_android_hardware_Radio DONE
08-30 11:36:43.375  3797  3797 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 11:36:43.380   874  1984 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 11:36:43.444  2090  3785 W SearchService: Abort, client detached.
08-30 11:36:43.446  2090  2090 I HotwordDetector: Closing mic
08-30 11:36:43.447  2090  2360 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@265f404
08-30 11:36:43.447  2090  2366 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 11:36:43.455  3797  3797 D AndroidRuntime: Shutting down VM
08-30 11:36:43.488   874  1387 I ActivityManager: Start proc 3807:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 11:36:43.508   377  2370 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 11:36:43.512   377  2370 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 11:36:43.520   377  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 11:36:43.522  2090  2363 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 11:36:43.522  2090  2364 I MicroRecognitionRnrImpl: Detection finished
08-30 11:36:43.593  3807  3807 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 11:36:43.624  3807  3807 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 11:36:43.633  3807  3807 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 116-119)
08-30 11:36:43.633  3807  3807 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 11:36:43.650  3807  3807 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ac2f24b}
08-30 11:36:43.650  3807  3807 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 11:36:43.651  3807  3807 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 11:36:43.658  3807  3807 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 11:36:43.660  3807  3807 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 11:36:43.680  3807  3807 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 11:36:43.692  3807  3807 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 11:36:43.692  3807  3807 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 11:36:43.692  3807  3807 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 11:36:43.692  3807  3807 I Adreno  : Build Date                       : 10/20/15
08-30 11:36:43.692  3807  3807 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 11:36:43.692  3807  3807 I Adreno  : Local Branch                     : M14
08-30 11:36:43.692  3807  3807 I Adreno  : Remote Branch                    : 
08-30 11:36:43.692  3807  3807 I Adreno  : Remote Branch                    : 
08-30 11:36:43.692  3807  3807 I Adreno  : Reconstruct Branch               : 
,08-30 11:36:43.748   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fe33e6:true
,08-30 11:36:43.781  3807  3807 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 11:36:43.797  3807  3807 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 11:36:43.860  3807  3847 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 11:36:43.873  3807  3833 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 11:36:43.936  3807  3847 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 11:36:44.057  1900  1900 I Keyboard.Facilitator: onFinishInput()
,08-30 11:36:44.060   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +596ms
,08-30 11:36:44.126  3807  3807 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3807
,08-30 11:36:44.267  3807  3807 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 11:36:44.310   874  1971 I ActivityManager: Killing 3220:com.google.android.gm/u0a78 (adj 15): empty #17
,08-30 11:36:44.357   874  1971 I ActivityManager: Killing 3272:com.google.android.youtube/u0a86 (adj 15): empty #18
,08-30 11:36:44.442  3807  3850 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1682245328
,08-30 11:36:44.449  3807  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 11:36:44.449  3807  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 11:36:44.449  3807  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 11:36:44.449  3807  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 11:36:44.449  3807  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 11:36:44.450  3807  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@916ab7e added. We now have 1 listener(s)
,08-30 11:36:44.454  3807  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-30 11:36:44.455  3807  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 11:36:44.456  3807  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:36:44.456  3807  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 11:36:44.460  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@681eff5 added. We now have 1 listener(s)
,08-30 11:36:44.460  3807  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:36:44.470   874  1318 D WifiService: New client listening to asynchronous messages
,08-30 11:36:44.471  3807  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 11:36:44.471  3807  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 11:36:44.471  3807  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 11:36:44.471  3807  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-30 11:36:44.471  3807  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 11:36:44.474  3807  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:36:44.474  3807  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 11:36:44.481  3807  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 11:36:44.483  3807  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:44.483  3807  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:44.483  3807  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:44.483  3807  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:44.483  3807  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:44.483  3807  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:44.483  3807  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:44.483  3807  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:36:44.484  3807  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 11:36:44.484  3807  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 11:36:44.485  3807  3850 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 11:36:44.485  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:44.487  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:44.661  3807  3807 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 11:36:45.311  3807  3857 W jxcore-log: Initializing JXcore engine
,08-30 11:36:45.311  3807  3857 W jxcore-log: JXcore engine is ready
,08-30 11:36:45.352  3857  3857 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-30 11:36:45.352  3857  3857 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10803]" dev="sockfs" ino=10803 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 11:36:45.352  3857  3857 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 11:36:45.356  3857  3857 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26780]" dev="sockfs" ino=26780 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 11:36:45.369  3807  3857 W jxcore-log: Starting JXcore engine
,08-30 11:36:45.453  3807  3857 W jxcore-log: Platform android
08-30 11:36:45.453  3807  3857 W jxcore-log: 
,08-30 11:36:45.453  3807  3857 W jxcore-log: Process ARCH arm
08-30 11:36:45.453  3807  3857 W jxcore-log: 
,08-30 11:36:45.733  3807  3857 I jxcore-log: JXcore Cordova bridge is ready!
08-30 11:36:45.733  3807  3857 I jxcore-log: 
,08-30 11:36:45.733  3807  3857 W jxcore-log: JXcore engine is started
,08-30 11:36:45.744  3807  3850 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 11:36:45.748  3807  3807 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 11:36:47.110   874  1317 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 11:36:49.403   874  2110 D NetlinkSocketObserver: NeighborEvent{elapsedMs=125890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 11:36:50.042  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 11:36:50.047  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 11:36:50.084  1505  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 11:36:50.084  1505  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 11:36:50.084  1505  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 11:36:50.085  1505  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 11:36:50.124  3019  3866 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 11:36:50.124  3019  3866 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at jdm.a(PG:82)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at jcs.o(PG:406)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at jcn.a(PG:1379)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at jcs.i(PG:143)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at blb.a(PG:3937)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at czp.a(PG:18188)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at czp.a(PG:9081)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at czq.run(PG:1686)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 11:36:50.124  3019  3866 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at jdj.a(PG:4091)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at jdj.a(PG:1125)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at jdm.a(PG:77)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	... 12 more
08-30 11:36:50.124  3019  3866 E HttpOperation: Caused by: faj: BadAuthentication
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at fal.a(PG:38)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	at jdj.a(PG:4089)
08-30 11:36:50.124  3019  3866 E HttpOperation: 	... 14 more
,08-30 11:36:50.179  1505  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 11:36:50.179  1505  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 11:36:50.179  1505  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 11:36:50.179  1505  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 11:36:50.205  3019  3866 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 11:36:50.205  3019  3866 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at jdm.a(PG:82)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at jcs.o(PG:406)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at jcn.a(PG:1379)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at jcs.i(PG:143)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at hec.a(PG:42)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at hee.a(PG:102)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at czr.a(PG:65)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at kka.a(PG:108)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at czp.a(PG:19176)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at czp.a(PG:9081)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at czq.run(PG:1686)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 11:36:50.205  3019  3866 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at jdj.a(PG:4091)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at jdj.a(PG:1125)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at jdm.a(PG:77)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	... 15 more
08-30 11:36:50.205  3019  3866 E HttpOperation: Caused by: faj: BadAuthentication
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at fal.a(PG:38)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	at jdj.a(PG:4089)
08-30 11:36:50.205  3019  3866 E HttpOperation: 	... 17 more
08-30 11:36:50.205  3019  3866 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 11:36:50.205  3019  3866 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at hec.a(PG:42)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at hee.a(PG:102)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at czr.a(PG:65)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at kka.a(PG:108)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	... 15 more
08-30 11:36:50.205  3019  3866 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at fal.a(PG:38)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 11:36:50.205  3019  3866 E ExperimentLoader: 	... 17 more
,08-30 11:36:50.294   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 126329, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-30 11:36:52.785   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 11:36:55.606  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 11:36:55.606  3807  3857 I jxcore-log: 
,08-30 11:36:55.608  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 11:36:55.608  3807  3857 I jxcore-log: 
,08-30 11:36:55.620  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:55.620  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:55.620  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:55.620  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:55.620  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:55.620  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:55.620  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:55.620  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:36:55.627  3807  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:36:55.629  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 11:36:55.629  3807  3857 I jxcore-log: 
,08-30 11:36:55.631  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 11:36:55.631  3807  3857 I jxcore-log: 
,08-30 11:36:55.823   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 11:36:56.138  3807  3857 D executeNativeTests: Running unit tests
,08-30 11:36:56.195  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:36:56.196  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef added. We now have 2 listener(s)
,08-30 11:36:56.197  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 11:36:56.197  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 11:36:56.197  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:36:56.197  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:36:56.197  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc added. We now have 2 listener(s)
08-30 11:36:56.197  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:36:56.198  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 11:36:56.204  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:36:56.215  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:56.215  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:56.215  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:56.215  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:56.215  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:56.215  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:56.215  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:56.215  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:36:56.220  3807  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:36:56.220  3807  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 11:36:56.222  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 11:36:56.224  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 11:36:56.224  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 11:36:56.226  3807  3857 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 11:36:56.226  3807  3857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 11:36:56.226  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 11:36:56.226  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 11:36:56.226  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 11:36:56.227  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 11:36:56.227  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:56.230  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:36:56.230  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:56.230  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 11:36:56.230  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.230  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:36:56.230  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:36:56.230  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef removed from the list
08-30 11:36:56.230  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:56.230  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc removed from the list,
08-30 11:36:56.236  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:56.237  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.237  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.237  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.237  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.242  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.243  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:36:56.243  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:56.244  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
,08-30 11:36:56.249  3807  3857 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-30 11:36:56.251  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 11:36:56.251  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:56.251  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:56.252  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 11:36:56.252  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.253  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.253  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.254  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.254  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.254  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.254  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.255  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.255  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:36:56.255  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.256  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.257  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.257  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.257  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
,08-30 11:36:56.261  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 11:36:56.261  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 11:36:56.261  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-30 11:36:56.261  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 11:36:56.261  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 11:36:56.261  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 11:36:56.261  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 11:36:56.261  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-30 11:36:56.261  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-30 11:36:56.261  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-30 11:36:56.261  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-30 11:36:56.261  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 11:36:56.261  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 11:36:56.261  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 11:36:56.262  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 11:36:56.262  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.263  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:56.263  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:56.263  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.263  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.263  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.263  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.263  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.263  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.263  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.263  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.263  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.263  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.263  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.265  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.265  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.265  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.265  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.266  3807  3857 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 11:36:56.267  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:56.271  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:56.271  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:56.271  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:56.271  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:56.271  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:56.271  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:56.271  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:56.271  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:36:56.274  3807  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:56.274  3807  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:36:56.274  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:36:56.274  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:36:56.274  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 11:36:56.274  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:56.274  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 11:36:56.276  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:56.279  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:56.281  3807  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 11:36:56.281  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 11:36:56.287  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 11:36:56.289  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 11:36:56.290  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 11:36:56.293  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 11:36:56.295  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-30 11:36:56.295  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 11:36:56.295  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 11:36:56.296  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 11:36:56.297  3807  3857 D BluetoothAdapter: STATE_ON
,08-30 11:36:56.302  2662  2787 D BtGatt.GattService: registerClient() - UUID=61a2262c-5166-4be4-b544-b81df10a7b46
,08-30 11:36:56.303  2662  2695 D BtGatt.GattService: onClientRegistered() - UUID=61a2262c-5166-4be4-b544-b81df10a7b46, clientIf=5
08-30 11:36:56.303  3807  3819 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 11:36:56.304  2662  2673 D BtGatt.GattService: start scan with filters
,08-30 11:36:56.310  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 11:36:56.310  2662  2698 D BtGatt.ScanManager: handling starting scan
08-30 11:36:56.310  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 11:36:56.310  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 11:36:56.310  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 11:36:56.311  2662  2698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
,08-30 11:36:56.312  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:36:56.313  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 11:36:56.313  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:36:56.314  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 11:36:56.318  2662  2695 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 11:36:56.318  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:36:56.319  2662  2698 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 11:36:56.319  3807  3857 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 11:36:56.323  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 11:36:56.324  2662  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 11:36:56.324  3807  3857 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 11:36:56.324  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:36:56.324  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:36:56.324  2662  2698 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 11:36:56.324  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 11:36:56.324  2662  2698 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 11:36:56.324  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.325  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 11:36:56.325  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 11:36:56.325  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 11:36:56.325  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 11:36:56.325  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 11:36:56.326  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 11:36:56.327  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 11:36:56.328  3807  3857 D BluetoothAdapter: STATE_ON
08-30 11:36:56.329  2662  2787 D BtGatt.GattService: stopScan() - queue size =1
08-30 11:36:56.330  2662  2674 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 11:36:56.331  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:56.331  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 11:36:56.331  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 11:36:56.331  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 11:36:56.331  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 11:36:56.333  2662  2695 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 11:36:56.333  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:36:56.333  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:36:56.333  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 11:36:56.334  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 11:36:56.334  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 11:36:56.335  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:36:56.336  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 11:36:56.336  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.336  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:36:56.336  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:36:56.336  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.336  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.336  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.336  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.336  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.336  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:36:56.336  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:36:56.337  3807  3857 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 11:36:56.339  2662  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 11:36:56.339  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:36:56.339  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:56.344  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:56.344  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:56.344  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:56.344  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:56.344  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:56.344  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:56.344  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:56.344  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:36:56.346  3807  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:36:56.346  3807  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:36:56.346  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:36:56.346  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:36:56.346  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 11:36:56.346  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:36:56.346  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 11:36:56.349  3807  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 11:36:56.349  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 11:36:56.349  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:56.351  2662  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 11:36:56.351  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:36:56.351  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:56.351  2662  2698 D BtGatt.ScanManager: stopping BLe Batch
08-30 11:36:56.352  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 11:36:56.352  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 11:36:56.352  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 11:36:56.356  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 11:36:56.357  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 11:36:56.357  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 11:36:56.357  3807  3857 D BluetoothAdapter: STATE_ON
,08-30 11:36:56.358  2662  2673 D BtGatt.GattService: registerClient() - UUID=33dc1d94-afe6-4c11-959e-2265b8dba170
08-30 11:36:56.359  2662  2695 D BtGatt.GattService: onClientRegistered() - UUID=33dc1d94-afe6-4c11-959e-2265b8dba170, clientIf=5
08-30 11:36:56.359  3807  3820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 11:36:56.359  2662  2787 D BtGatt.GattService: start scan with filters
,08-30 11:36:56.361  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 11:36:56.361  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 11:36:56.361  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 11:36:56.361  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 11:36:56.363  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 11:36:56.363  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 11:36:56.363  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 11:36:56.363  2662  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 11:36:56.363  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:36:56.364  2662  2698 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 11:36:56.364  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 11:36:56.366  3807  3857 I io.jxcore.node.ConnectionHelper: start: OK
08-30 11:36:56.368  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.368  3807  3857 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 11:36:56.368  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:36:56.368  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 11:36:56.368  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.368  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 11:36:56.368  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 11:36:56.369  2662  2695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 11:36:56.369  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:36:56.368  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 11:36:56.369  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 11:36:56.369  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 11:36:56.369  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 11:36:56.369  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 11:36:56.369  3807  3857 D BluetoothAdapter: STATE_ON
08-30 11:36:56.370  2662  2673 D BtGatt.GattService: stopScan() - queue size =0
,08-30 11:36:56.370  2662  2787 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 11:36:56.370  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:56.371  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 11:36:56.371  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 11:36:56.371  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 11:36:56.371  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 11:36:56.371  2662  2698 D BtGatt.ScanManager: handling starting scan
,08-30 11:36:56.371  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:36:56.371  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 11:36:56.371  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 11:36:56.371  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 11:36:56.372  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 11:36:56.373  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:36:56.373  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:36:56.374  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:36:56.374  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.374  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.374  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 11:36:56.374  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.374  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.374  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
,08-30 11:36:56.374  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.374  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.375  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.375  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.375  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.376  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.376  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:56.376  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.376  3807  3857 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 11:36:56.377  2662  2695 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 11:36:56.378  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:36:56.378  2662  2698 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 11:36:56.378  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:36:56.383  2662  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 11:36:56.383  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:36:56.383  2662  2698 D BtGatt.ScanManager: Starting BLE batch scan
08-30 11:36:56.383  2662  2698 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 11:36:56.385  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:56.385  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:56.385  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:56.385  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:56.385  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:56.385  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:56.385  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:56.385  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:36:56.388  3807  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:36:56.388  3807  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:36:56.388  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 11:36:56.388  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:36:56.389  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 11:36:56.389  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:56.389  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 11:36:56.391  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:56.393  3807  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 11:36:56.393  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 11:36:56.393  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:56.394  2662  2695 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 11:36:56.394  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:36:56.399  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 11:36:56.399  2662  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 11:36:56.399  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:36:56.400  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 11:36:56.400  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 11:36:56.405  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 11:36:56.405  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 11:36:56.405  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 11:36:56.406  2662  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 11:36:56.406  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:36:56.406  2662  2698 D BtGatt.ScanManager: stopping BLe Batch
,08-30 11:36:56.406  3807  3857 D BluetoothAdapter: STATE_ON
,08-30 11:36:56.409  2662  2787 D BtGatt.GattService: registerClient() - UUID=946f6444-f069-4dc5-be75-2d4b65efda5f
,08-30 11:36:56.410  2662  2695 D BtGatt.GattService: onClientRegistered() - UUID=946f6444-f069-4dc5-be75-2d4b65efda5f, clientIf=5
,08-30 11:36:56.410  3807  3820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 11:36:56.410  2662  2777 D BtGatt.GattService: start scan with filters
,08-30 11:36:56.412  2662  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 11:36:56.412  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:36:56.412  2662  2698 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 11:36:56.416  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 11:36:56.416  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 11:36:56.416  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 11:36:56.416  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 11:36:56.419  2662  2695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 11:36:56.419  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:36:56.420  2662  2698 D BtGatt.ScanManager: handling starting scan
,08-30 11:36:56.421  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:36:56.421  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 11:36:56.422  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:36:56.425  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 11:36:56.426  2662  2695 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 11:36:56.426  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:36:56.427  2662  2698 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 11:36:56.431  3807  3857 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 11:36:56.431  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.432  3807  3857 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 11:36:56.432  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:36:56.432  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 11:36:56.432  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.432  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 11:36:56.432  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
08-30 11:36:56.432  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 11:36:56.432  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 11:36:56.433  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 11:36:56.433  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 11:36:56.433  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 11:36:56.434  2662  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 11:36:56.434  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:36:56.434  2662  2698 D BtGatt.ScanManager: Starting BLE batch scan
08-30 11:36:56.434  2662  2698 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 11:36:56.435  3807  3857 D BluetoothAdapter: STATE_ON
,08-30 11:36:56.435  2662  2674 D BtGatt.GattService: stopScan() - queue size =1
08-30 11:36:56.436  2662  2673 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 11:36:56.436  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:56.436  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 11:36:56.436  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 11:36:56.437  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 11:36:56.437  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 11:36:56.438  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 11:36:56.438  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 11:36:56.438  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 11:36:56.438  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 11:36:56.439  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 11:36:56.440  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:36:56.440  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 11:36:56.440  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:36:56.441  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.441  3807  3857 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 11:36:56.441  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:56.441  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 11:36:56.441  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.441  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.442  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:36:56.442  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.442  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.442  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
,08-30 11:36:56.442  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.442  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.443  2662  2695 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 11:36:56.443  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:36:56.443  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.443  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.445  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.445  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.445  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:56.445  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.446  3807  3857 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 11:36:56.446  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.446  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:56.446  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:56.447  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.447  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:36:56.447  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.447  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.447  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.447  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.447  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.447  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.447  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.447  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:36:56.447  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.447  2662  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 11:36:56.448  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:36:56.448  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.448  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.448  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.448  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
,08-30 11:36:56.449  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 11:36:56.449  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.449  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:56.449  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:56.450  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.450  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.450  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.450  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.450  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.450  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.450  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.450  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.450  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.450  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.451  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.451  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.451  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.451  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.452  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
,08-30 11:36:56.452  3807  3857 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 11:36:56.452  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.452  2662  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 11:36:56.452  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:36:56.452  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:36:56.453  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:56.453  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.453  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:36:56.453  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.453  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.453  2662  2698 D BtGatt.ScanManager: stopping BLe Batch
08-30 11:36:56.453  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.453  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.453  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.453  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:36:56.453  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.453  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.453  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.454  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.454  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.454  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:56.454  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.455  3807  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 11:36:56.455  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.455  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:56.455  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:56.455  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 11:36:56.455  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.455  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.456  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.456  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.456  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.456  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 11:36:56.456  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.456  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.456  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.456  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.457  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.457  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.457  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.457  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
,08-30 11:36:56.458  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 11:36:56.458  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 11:36:56.458  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 11:36:56.458  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 11:36:56.458  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 11:36:56.458  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 11:36:56.458  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.458  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:56.458  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 11:36:56.459  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.459  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.459  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.459  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.459  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.459  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.459  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 11:36:56.459  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.459  2662  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 11:36:56.459  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:36:56.459  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.459  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.459  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.460  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.460  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.460  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.460  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.461  3807  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 11:36:56.461  3807  3857 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-30 11:36:56.461  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 11:36:56.461  2662  2698 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 11:36:56.464  3807  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 11:36:56.464  3807  3857 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-30 11:36:56.465  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-30 11:36:56.465  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110],
,08-30 11:36:56.465  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 11:36:56.465  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 11:36:56.465  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 11:36:56.465  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-30 11:36:56.465  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 11:36:56.465  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 11:36:56.465  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-30 11:36:56.465  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910],
08-30 11:36:56.465  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-30 11:36:56.465  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-30 11:36:56.465  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 11:36:56.466  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-30 11:36:56.466  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 11:36:56.466  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510],
08-30 11:36:56.466  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 11:36:56.466  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-30 11:36:56.466  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 11:36:56.466  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-30 11:36:56.466  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 11:36:56.466  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 11:36:56.466  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-30 11:36:56.466  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 11:36:56.466  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 11:36:56.466  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-30 11:36:56.466  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 11:36:56.467  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-30 11:36:56.467  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-30 11:36:56.467  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 11:36:56.467  3807  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 11:36:56.467  3807  3857 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-30 11:36:56.467  3807  3857 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 11:36:56.467  3807  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 11:36:56.467  3807  3857 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 11:36:56.468  3807  3857 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-30 11:36:56.468  3807  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 11:36:56.468  3807  3857 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 11:36:56.468  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-30 11:36:56.469  2662  2695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 11:36:56.469  2662  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:36:56.471  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 11:36:56.472  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-30 11:36:56.472  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 11:36:56.472  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 11:36:56.472  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 11:36:56.472  3807  3857 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 11:36:56.472  3807  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 11:36:56.473  3807  3857 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 11:36:56.473  3807  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 385)
08-30 11:36:56.474  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.474  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:56.474  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 11:36:56.474  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.474  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.474  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.474  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 11:36:56.474  3807  3871 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 11:36:56.475  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
,08-30 11:36:56.475  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.475  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.475  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.475  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.475  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.475  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.475  3807  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 385
08-30 11:36:56.475  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.475  3807  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 385)
08-30 11:36:56.475  3807  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 385)
08-30 11:36:56.476  3807  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 385)
08-30 11:36:56.478  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 11:36:56.478  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.478  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.478  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.478  3807  3857 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 11:36:56.479  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.479  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:36:56.480  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:56.480  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.480  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.480  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.480  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.480  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:56.480  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.480  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.480  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.480  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.480  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.480  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.481  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.481  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.481  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.481  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.482  3807  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 11:36:56.482  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.482  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:56.482  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 11:36:56.482  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.482  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.482  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.482  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
,08-30 11:36:56.482  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.482  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.483  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.483  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.483  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.483  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.483  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.483  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.483  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.483  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.483  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.484  3807  3857 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-30 11:36:56.484  3807  3857 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 11:36:56.484  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 11:36:56.484  3807  3857 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 11:36:56.484  3807  3857 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 11:36:56.484  3807  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,08-30 11:36:56.484  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 11:36:56.484  3807  3857 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 11:36:56.484  3807  3857 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 11:36:56.484  3807  3857 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 11:36:56.484  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 11:36:56.485  3807  3857 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-30 11:36:56.485  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.485  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:56.485  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:56.485  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.485  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.485  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.485  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
,08-30 11:36:56.485  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.485  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.485  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.485  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.485  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.485  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.485  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.486  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.486  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.486  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.486  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.487  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.487  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:36:56.487  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.487  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.487  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.487  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.487  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.487  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:36:56.487  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.487  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.487  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
,08-30 11:36:56.487  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.487  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.487  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.487  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.487  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.487  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:36:56.488  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:56.488  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.488  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.488  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.488  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.488  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.488  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.488  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 11:36:56.488  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.488  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.488  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.488  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.489  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.489  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:36:56.489  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.489  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.490  3807  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 11:36:56.491  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:56.491  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 11:36:56.492  3807  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 11:36:56.492  3807  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 11:36:56.492  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 11:36:56.492  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 11:36:56.492  3807  3807 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-30 11:36:56.492  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.492  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 11:36:56.492  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 11:36:56.492  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 11:36:56.493  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.493  3807  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 11:36:56.493  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.493  3807  3807 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 11:36:56.493  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.493  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 11:36:56.493  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 11:36:56.493  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 11:36:56.493  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.493  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.493  3807  3873 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 11:36:56.494  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:36:56.494  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.495  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.495  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:36:56.495  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:36:56.495  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:36:56.495  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:56.495  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.495  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:36:56.495  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.495  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.495  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.495  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:56.495  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.495  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.495  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.495  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.495  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:36:56.495  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.496  3807  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 11:36:56.496  3807  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 11:36:56.496  3807  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 11:36:56.496  3807  3807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 11:36:56.497  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.497  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:36:56.497  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.497  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.498  3807  3857 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 11:36:56.498  3807  3857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 11:36:56.498  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 11:36:56.498  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 11:36:56.498  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.498  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:56.499  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:56.499  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.499  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.499  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.499  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
,08-30 11:36:56.499  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.499  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.499  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.499  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.499  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.499  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.499  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.500  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.500  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.500  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.500  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.504  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.504  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:36:56.504  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:56.504  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.504  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.505  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.505  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.505  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:56.505  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.505  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:56.505  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.505  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.505  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.505  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.506  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.506  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:36:56.506  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.506  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.506  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:56.506  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:56.506  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 11:36:56.506  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:56.506  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.507  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:56.507  3807  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cff9ef not in the list
08-30 11:36:56.507  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:56.507  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.507  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 11:36:56.507  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.507  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:56.507  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:56.507  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 11:36:56.508  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:56.508  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:56.508  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:56.508  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88e6cfc not in the list
08-30 11:36:56.509  3807  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 11:36:56.509  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 11:36:56.509  3807  3857 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 11:36:56.509  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 11:36:56.509  3807  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 11:36:56.509  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 11:36:56.511  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-30 11:36:56.511  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 11:36:56.511  3807  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 11:36:56.511  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 11:36:56.511  3807  3857 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 11:36:56.512  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-30 11:36:56.512  3807  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 11:36:56.512  3807  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 11:36:56.512  3807  3857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 11:36:56.512  3807  3857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 11:36:56.513  3807  3857 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 11:36:56.513  3807  3857 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-30 11:36:56.513  3807  3857 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 11:36:56.513  3807  3857 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 11:36:56.514  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:36:56.514  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c745f7e added. We now have 2 listener(s)
08-30 11:36:56.514  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:36:56.515  3807  3857 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 11:36:56.516   874  2019 D WifiService: setWifiEnabled: true pid=3807, uid=10000
08-30 11:36:56.516   874  2019 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 11:36:56.517  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 11:36:56.517  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c193cdf added. We now have 3 listener(s)
08-30 11:36:56.517  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:36:56.525  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:36:56.525  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ac50d2c added. We now have 4 listener(s)
08-30 11:36:56.525  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:36:56.527  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:36:56.527  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bf233f5 added. We now have 5 listener(s)
,08-30 11:36:56.527  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:36:56.530   874   885 D WifiService: setWifiEnabled: false pid=3807, uid=10000
08-30 11:36:56.530   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 11:36:56.536  2662  2691 D BluetoothAdapterState: Current state: ON, message: 23
08-30 11:36:56.536  2662  2691 D BluetoothAdapterProperties: Setting state to 13
08-30 11:36:56.536  2662  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 11:36:56.537  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:56.537  2662  2691 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 11:36:56.538  2662  2691 I BluetoothAdapterState: Entering PendingCommandState
08-30 11:36:56.539  2662  2662 D BluetoothMapService: onReceive
08-30 11:36:56.539  2662  2662 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:36:56.539  2662  2662 D BluetoothMapService: STATE_TURNING_OFF
08-30 11:36:56.539  2662  2662 D BluetoothMapService: MAP Service closeService in
08-30 11:36:56.539  2662  2662 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 11:36:56.539  2662  2662 D ObexServerSockets0: shutdown(block = true)
08-30 11:36:56.540  2662  2662 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 11:36:56.540  2662  2662 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 11:36:56.540  2662  2800 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 11:36:56.540  2662  2773 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 11:36:56.541  2662  2801 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 11:36:56.542  2662  2662 I BtOppRfcommListener: stopping Accept Thread
08-30 11:36:56.542  2662  3449 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 11:36:56.542  2662  3449 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 11:36:56.544  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:56.544  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:56.544  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:56.544  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:56.544  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:56.544  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:56.544  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:56.544  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:56.544  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:36:56.545  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:36:56.545  3807  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:36:56.545  3807  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 11:36:56.547  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 11:36:56.549   874  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 11:36:56.549   874  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 11:36:56.549  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:56.549   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 11:36:56.549   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 11:36:56.553  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:56.554   874   887 I ActivityManager: Start proc 3876:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-30 11:36:56.555  2662  2695 D BluetoothAdapterProperties: Scan Mode:20
,08-30 11:36:56.555  2662  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 11:36:56.559  2662  2662 D HeadsetService: Received stop request...Stopping profile...
,08-30 11:36:56.560   373   872 D CommandListener: Clearing all IP addresses on wlan0
,08-30 11:36:56.560   874  2114 D DhcpClient: Clearing IP address
,08-30 11:36:56.562  2003  2105 D BluetoothHeadset: Proxy object disconnected
08-30 11:36:56.562  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:36:56.562  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:56.562  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:56.562  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:56.562  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:56.562  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:56.562  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:56.562  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:56.562  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:36:56.563  1375  1388 D BluetoothHeadset: Proxy object disconnected
,08-30 11:36:56.563   874   874 D BluetoothHeadset: Proxy object disconnected
,08-30 11:36:56.563   874   874 D BluetoothHeadset: Proxy object disconnected
,08-30 11:36:56.563   874   874 D BluetoothHeadset: Proxy object disconnected
,08-30 11:36:56.564   373   872 D CommandListener: Setting iface cfg
,08-30 11:36:56.564  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:56.564  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:36:56.566  2662  2662 V BluetoothAdapterState: isTurningOff()=true
08-30 11:36:56.566  2662  2662 V BluetoothAdapterState: isTurningOn()=false
08-30 11:36:56.566  2662  2662 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 11:36:56.566  2662  2662 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:36:56.566  2662  2662 D A2dpService: Received stop request...Stopping profile...
08-30 11:36:56.566  1505  2531 V NativeCrypto: Read error: ssl=0x9b303a00: I/O error during system call, Connection timed out
08-30 11:36:56.567  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:56.568  1505  2531 V NativeCrypto: SSL shutdown failed: ssl=0x9b303a00: I/O error during system call, Broken pipe
08-30 11:36:56.568   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 11:36:56.568   874  1317 D WifiStateMachine: Start Disconnecting Watchdog 1
08-30 11:36:56.569   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-30 11:36:56.569   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 11:36:56.569  2662  2779 D A2dpStateMachine: Exit Disconnected: -1
08-30 11:36:56.571  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:36:56.571  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:56.571  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:56.571  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:56.571  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:56.571  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:56.571  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:56.571  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:56.571  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:36:56.572  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:56.572  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:36:56.575   409   409 E Parcel  : Reading a NULL string not supported here.
08-30 11:36:56.576   874   874 D BluetoothA2dp: Proxy object disconnected
08-30 11:36:56.577   373   872 D CommandListener: Clearing all IP addresses on wlan0
08-30 11:36:56.578  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:56.578  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:56.578  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:56.578  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:56.578  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:56.578  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:56.578  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:56.578  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:56.578  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:36:56.579  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:56.580  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:36:56.581  2662  2662 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 11:36:56.581  2662  2662 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 11:36:56.581  2662  2695 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 11:36:56.581  2662  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 11:36:56.581  2662  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 11:36:56.581  2662  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 11:36:56.581  2662  2695 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-30 11:36:56.583  2662  2662 D HidService: Received stop request...Stopping profile...
08-30 11:36:56.583  2662  2662 D HidService: Stopping Bluetooth HidService
08-30 11:36:56.584   874  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 11:36:56.587   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 11:36:56.587  2662  2662 D HealthService: Received stop request...Stopping profile...
08-30 11:36:56.589  2662  2662 D PanService: Received stop request...Stopping profile...
08-30 11:36:56.589  1853  2259 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:56.590  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:56.590  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:56.590  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:56.590  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:56.590  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:36:56.590  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:56.590  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:56.590  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:56.590  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:36:56.591  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:36:56.591  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:36:56.591  2662  2662 V BluetoothAdapterState: isTurningOff()=true
08-30 11:36:56.591  2662  2662 V BluetoothAdapterState: isTurningOn()=false
08-30 11:36:56.591  2662  2662 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:36:56.591  2662  2662 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:36:56.592   874  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 11:36:56.592  2662  2695 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 11:36:56.592  2662  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 11:36:56.593  2662  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 11:36:56.593  2662  2753 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 11:36:56.593  2662  2753 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:36:56.593  2662  2753 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:36:56.593  2662  2753 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:36:56.593  2662  2662 D BluetoothMapService: Received stop request...Stopping profile...
08-30 11:36:56.593  2662  2662 D BluetoothMapService: stop()
08-30 11:36:56.594  2662  2662 D BluetoothMapAppObserver: deinitObservers()
08-30 11:36:56.594  2662  2662 D BluetoothMapAppObserver: removeReceiver()
08-30 11:36:56.594  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:56.594  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:56.594  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:56.594  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:56.594  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:36:56.594  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:56.594  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:56.594  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:56.594  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:36:56.595  2662  2662 V BluetoothAdapterState: isTurningOff()=true
08-30 11:36:56.595  2662  2662 V BluetoothAdapterState: isTurningOn()=false
08-30 11:36:56.595  2662  2662 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 11:36:56.595  2662  2662 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 11:36:56.595  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:56.595  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:36:56.595  2662  2662 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 11:36:56.595  2662  2662 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 11:36:56.596  2662  2695 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 11:36:56.596  2662  2662 V BluetoothAdapterState: isTurningOff()=true
08-30 11:36:56.596  2662  2662 V BluetoothAdapterState: isTurningOn()=false
08-30 11:36:56.596  2662  2662 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:36:56.596  2662  2662 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 11:36:56.596  2662  2662 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 11:36:56.596  2662  2695 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 11:36:56.597  2662  2662 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 11:36:56.597  2662  2662 V BluetoothAdapterState: isTurningOff()=true
08-30 11:36:56.597  2662  2662 V BluetoothAdapterState: isTurningOn()=false
08-30 11:36:56.597  2662  2662 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:36:56.597  2662  2662 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:36:56.600  2662  2662 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 11:36:56.600  2662  2662 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 11:36:56.601  2662  2662 D BluetoothMapService: MAP Service closeService in
08-30 11:36:56.602  2662  2662 V BluetoothAdapterState: isTurningOff()=true
08-30 11:36:56.602  2662  2662 V BluetoothAdapterState: isTurningOn()=false
08-30 11:36:56.602  2662  2662 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:36:56.602  2662  2662 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:36:56.602  2662  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 11:36:56.602  2662  2691 D BluetoothAdapterProperties: Setting state to 15
08-30 11:36:56.602  2662  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 11:36:56.603   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 11:36:56.603  1375  1375 D HeadsetProfile: Bluetooth service disconnected
08-30 11:36:56.603  1375  2123 D BluetoothPan: onBluetoothStateChange on: false
08-30 11:36:56.603  1375  1375 D BluetoothA2dp: Proxy object disconnected
08-30 11:36:56.603  1375  1375 D BluetoothInputDevice: Proxy object disconnected
08-30 11:36:56.603  1375  1375 D HidProfile: Bluetooth service disconnected
08-30 11:36:56.603  2662  2691 I BluetoothAdapterState: Entering BleOnState
08-30 11:36:56.604  1375  1386 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 11:36:56.605  2003  2242 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 11:36:56.605  2662  2662 D BluetoothMapService: cleanup()
,08-30 11:36:56.605  1375  2123 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 11:36:56.605  2662  2662 D BluetoothMapService: MAP Service closeService in
08-30 11:36:56.606   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 11:36:56.606  1375  1388 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 11:36:56.607   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 11:36:56.607  1375  2123 D BluetoothMap: onBluetoothStateChange: up=false
08-30 11:36:56.609   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 11:36:56.609  1375  1388 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 11:36:56.610   874  2121 D DhcpClient: Receive thread stopped
08-30 11:36:56.610  2662  2691 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 11:36:56.611  2662  2691 D BluetoothAdapterProperties: Setting state to 16
08-30 11:36:56.611  2662  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 11:36:56.611  2662  2691 D BluetoothAdapterProperties: onBleDisable
08-30 11:36:56.612  2662  2691 I BluetoothAdapterState: Entering PendingCommandState
,08-30 11:36:56.612  2662  2692 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 11:36:56.612  2662  2695 D BluetoothAdapterProperties: Scan Mode:20
08-30 11:36:56.612  2662  2753 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 11:36:56.613  2662  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 11:36:56.614  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:56.614  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:56.614  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:56.614  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:56.614  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:36:56.614  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:56.614  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:56.614  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:56.614  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:36:56.617  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:56.618  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:56.619  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:56.631   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 11:36:56.644  3876  3876 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-30 11:36:56.648   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 11:36:56.649   874  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 11:36:56.649   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 11:36:56.652   874   891 D Tethering: MasterInitialState.processMessage what=3
08-30 11:36:56.653  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:56.655  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:56.655  3436  3436 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@85b98df and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-30 11:36:56.658  2090  2090 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-30 11:36:56.668  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 11:36:56.672   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f7e9730:true
,08-30 11:36:56.672  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 11:36:56.685   874  1979 I ActivityManager: Start proc 3895:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-30 11:36:56.694  3876  3876 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 11:36:56.697  3876  3876 D BluetoothMap: Create BluetoothMap proxy object
,08-30 11:36:56.700   373   872 E Netd    : netlink response contains error (No such file or directory)
,08-30 11:36:56.705  3876  3876 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 11:36:56.715  3895  3895 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-30 11:36:56.718  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,08-30 11:36:56.725   874   884 I ActivityManager: Killing 2985:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-30 11:36:56.815  2662  2695 I bt_hci  : shut_down
,08-30 11:36:56.824  2662  2699 I bt_vendor: low_power_mode_cb
,08-30 11:36:56.828  2662  2699 D bt_hwcfg: hw_epilog_process
,08-30 11:36:56.851  2662  2699 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 11:36:56.851  2662  2699 I bt_vendor: epilog_cb
,08-30 11:36:56.851  2662  2699 I bt_hci  : epilog_finished_callback
,08-30 11:36:56.855  2662  2695 I bt_hci_h4: hal_close
,08-30 11:36:56.855  2662  2695 I bt_userial_vendor: device fd = 51 close
,08-30 11:36:56.880  3895  3895 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 11:36:56.880  3895  3895 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 11:36:56.880  3895  3895 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 11:36:56.880  3895  3895 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 11:36:56.880  3895  3895 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 11:36:56.880  3895  3895 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 11:36:56.880  3895  3895 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 11:36:56.880  3895  3895 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 11:36:56.880  3895  3895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 11:36:56.921   874  2052 I ActivityManager: Start proc 3925:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-30 11:36:56.922   874  2052 I ActivityManager: Killing 3436:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-30 11:36:56.995  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 11:36:57.039  3895  3916 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 11:36:57.068  2662  2692 D bt_stack_manager: event_shut_down_stack finished.
,08-30 11:36:57.069  2662  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-30 11:36:57.070  2662  2691 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 11:36:57.070  2662  2662 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 11:36:57.072  2662  2662 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 11:36:57.072  2662  2662 D BtGatt.GattService: stop()
08-30 11:36:57.073  2662  2662 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 11:36:57.075  2662  2662 V BluetoothAdapterState: isTurningOff()=false
,08-30 11:36:57.075  2662  2662 V BluetoothAdapterState: isTurningOn()=false
08-30 11:36:57.075  2662  2662 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:36:57.075  2662  2662 V BluetoothAdapterState: isBleTurningOff()=true
08-30 11:36:57.075  2662  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 11:36:57.075  2662  2691 D BluetoothAdapterProperties: Setting state to 10
08-30 11:36:57.075  2662  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-30 11:36:57.076  2662  2691 I BluetoothAdapterState: Entering OffState
08-30 11:36:57.079   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 11:36:57.084  3925  3925 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-30 11:36:57.100  2662  2662 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-30 11:36:57.100  2662  2662 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 11:36:57.100  2662  2662 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 11:36:57.101  2662  2692 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 11:36:57.103  2662  2692 D bt_stack_manager: event_clean_up_stack finished.
,08-30 11:36:57.112  2662  2662 I art     : System.exit called, status: 0
,08-30 11:36:57.112  2662  2662 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 11:36:57.158   874  2013 I ActivityManager: Process com.android.bluetooth (pid 2662) has died
,08-30 11:36:57.162   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cb04842:true
,08-30 11:36:57.169  3925  3925 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 11:36:57.190  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 11:36:57.212   874  2019 I ActivityManager: Start proc 3954:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-30 11:36:57.214  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,08-30 11:36:57.293  3954  3954 D AdapterServiceConfig: Adding HeadsetService
,08-30 11:36:57.294  3954  3954 D AdapterServiceConfig: Adding A2dpService
,08-30 11:36:57.294  3954  3954 D AdapterServiceConfig: Adding HidService
,08-30 11:36:57.295  3954  3954 D AdapterServiceConfig: Adding HealthService
,08-30 11:36:57.296  3954  3954 D AdapterServiceConfig: Adding PanService
,08-30 11:36:57.296  3954  3954 D AdapterServiceConfig: Adding GattService
,08-30 11:36:57.297  3954  3954 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 11:36:57.300   874  2049 I ActivityManager: Killing 3616:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-30 11:36:57.352  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 11:36:57.380  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 11:36:57.386  1713  1713 D SystemUpdateService: onCreate
,08-30 11:36:57.393  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 11:36:57.401  1713  3966 I SystemUpdateService: active receiver: enabled
,08-30 11:36:57.405  1713  3966 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 11:36:57.407  1713  3966 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 11:36:57.407  1713  3966 I SystemUpdateService: now status is 0 (complete)
08-30 11:36:57.407  1713  3966 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 11:36:57.407  1713  3966 I SystemUpdateService: file has been verified
08-30 11:36:57.408  1713  3966 I SystemUpdateService: OTA package size = 12249756
,08-30 11:36:57.410  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 11:36:57.413  1713  3966 I SystemUpdateService: showing system update notification
,08-30 11:36:57.416  1713  2509 I iu.UploadsManager: num queued entries: 0
,08-30 11:36:57.417  1713  2509 I iu.UploadsManager: num updated entries: 0
08-30 11:36:57.417  1713  2509 I iu.SyncManager: NEXT; no task
,08-30 11:36:57.443  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 11:36:57.444  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 11:36:57.462   874  2052 I ActivityManager: Start proc 3968:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 11:36:57.465  1713  1713 D SystemUpdateService: onDestroy
,08-30 11:36:57.505  3968  3968 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 11:36:57.508  3968  3968 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:36:57.513  3968  3968 D SprintDMHelper: simOperator: 
08-30 11:36:57.514  3968  3968 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 11:36:57.530   874  1688 I ActivityManager: Start proc 3980:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 11:36:57.534   874  1688 I ActivityManager: Killing 3503:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 11:36:57.659  2167  3994 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 11:36:57.678   874  1688 I ActivityManager: Start proc 3995:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 11:36:57.681   874  1387 I ActivityManager: Killing 1692:android.process.acore/u0a5 (adj 15): empty #17
,08-30 11:36:57.757  3995  3995 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 11:36:57.829  3995  3995 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 11:36:57.829  3995  3995 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 11:36:57.829  3995  3995 I GAv4    :   adb logcat -s GAv4
,08-30 11:36:57.854  3995  3995 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 11:36:57.860  3995  3995 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 11:36:57.886  3995  4012 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 11:36:57.986  3995  3995 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 11:36:58.025  3995  3995 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 11:36:58.044  3995  3995 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4527-4530)
08-30 11:36:58.044  3995  3995 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 11:36:58.054  3995  3995 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e0277cf}
,08-30 11:36:58.055  3995  3995 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 11:36:58.056  3995  3995 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 11:36:58.064  3995  3995 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 11:36:58.066  3995  3995 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 11:36:58.092  3995  3995 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 11:36:58.105  3995  3995 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 11:36:58.105  3995  3995 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 11:36:58.105  3995  3995 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 11:36:58.105  3995  3995 I Adreno  : Build Date                       : 10/20/15
08-30 11:36:58.105  3995  3995 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 11:36:58.105  3995  3995 I Adreno  : Local Branch                     : M14
08-30 11:36:58.105  3995  3995 I Adreno  : Remote Branch                    : 
08-30 11:36:58.105  3995  3995 I Adreno  : Remote Branch                    : 
08-30 11:36:58.105  3995  3995 I Adreno  : Reconstruct Branch               : 
,08-30 11:36:58.172  3995  3995 I NSApplication: Starting up...
,08-30 11:36:58.171  3995  4042 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 11:36:58.218   874  1387 I ActivityManager: Start proc 4047:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-30 11:36:58.219   874  1387 I ActivityManager: Killing 3690:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 11:36:58.288  4047  4047 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 11:36:58.491   874  1997 I ActivityManager: Killing 3706:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 11:36:59.548   874  1997 D WifiService: setWifiEnabled: true pid=3807, uid=10000
,08-30 11:36:59.548   874  1997 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 11:36:59.565   874  1317 D WifiConfigStore: Loading config and enabling all networks 
,08-30 11:36:59.573  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:36:59.573  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:59.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:59.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:59.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:59.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:59.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:59.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:59.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:36:59.574  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:36:59.574  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:36:59.578  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:59.579  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:59.579  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:59.579  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:59.579  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:59.579  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:59.579  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:59.579  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:59.579  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:36:59.579  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:59.579  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-30 11:36:59.587   874  1317 D WifiConfigStore: loaded 0 passpoint configs
08-30 11:36:59.588   874  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-30 11:36:59.589   874  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 11:36:59.589   874  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 11:36:59.590   874  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 11:36:59.590   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-30 11:36:59.590   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 11:36:59.607   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 11:36:59.608   373   872 D CommandListener: Setting iface cfg
,08-30 11:36:59.609   874  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '131 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 131 Failed to set address (No such device)'
,08-30 11:36:59.609   874  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 11:36:59.610   874  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=13.25 rxSuccessRate=11.75 delta 1000 -> 994
,08-30 11:36:59.611   874  1316 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 11:36:59.612   874  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 11:36:59.619   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 11:36:59.619   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 11:36:59.643   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 11:36:59.721   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 11:36:59.723  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 11:37:00.480  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 11:37:00.534  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 11:37:00.535  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 11:37:00.542   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 11:37:00.557   874  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 11:37:00.558   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
08-30 11:37:00.558   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 11:37:00.581   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 11:37:00.594   373   872 D CommandListener: Setting iface cfg
,08-30 11:37:00.594   874  1317 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 11:37:00.611   874  1319 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-30 11:37:00.615   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 11:37:00.629   874  4070 D DhcpClient: Receive thread started
,08-30 11:37:00.711   874  1317 E native  : do suspend false
,08-30 11:37:00.730   874  2114 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 11:37:00.752   874  4070 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172686, domain null
,08-30 11:37:00.754   874  2114 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172686 seconds
,08-30 11:37:00.757   874  2114 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 11:37:00.770   874  4070 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 11:37:00.771   874  2114 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 11:37:00.777   373   872 D CommandListener: Setting iface cfg
,08-30 11:37:00.789   874  2114 D DhcpClient: Scheduling renewal in 86399s
,08-30 11:37:00.794   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 11:37:00.807   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 11:37:00.811   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 11:37:00.812   874  1317 D WifiConfigStore: No blacklist allowed without epno enabled
08-30 11:37:00.813   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 11:37:00.816   874  1319 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 11:37:00.838   874  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 11:37:00.880   874  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 11:37:00.880   874  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 11:37:00.882   874  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 11:37:00.883   874  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 11:37:00.884   874  1319 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 11:37:00.893   874  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 11:37:00.899   874  1319 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 11:37:00.899   874  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-30 11:37:00.900   874  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 11:37:00.900   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 11:37:00.900   874  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-30 11:37:00.901   874  1319 D ConnectivityService:    accepting network in place of null
,08-30 11:37:00.902   874  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 11:37:00.939   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 11:37:00.954   874  4069 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137441, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 11:37:00.972   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 11:37:00.976   874  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 11:37:00.976   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:37:00.985   874  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-30 11:37:00.988   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-30 11:37:00.994  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:37:00.995  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:00.995  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:00.995  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:00.995  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:00.995  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:37:00.995  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:00.995  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:37:00.995  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:37:00.995  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:00.995  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:01.001  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:37:01.001  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:01.001  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:01.001  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:01.001  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:01.001  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:37:01.001  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:01.001  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:37:01.001  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:37:01.003  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:01.004  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:37:01.022  2090  2090 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-30 11:37:01.024  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 11:37:01.027  1713  1713 D SystemUpdateService: onCreate
,08-30 11:37:01.033   874  4068 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 11:37:01.033  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 11:37:01.038  1713  4082 I SystemUpdateService: active receiver: enabled
,08-30 11:37:01.045  1713  4082 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 11:37:01.047  1713  4082 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 11:37:01.047  1713  4082 I SystemUpdateService: now status is 0 (complete)
,08-30 11:37:01.047  1713  4082 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 11:37:01.047  1713  4082 I SystemUpdateService: file has been verified
08-30 11:37:01.047  1713  4082 I SystemUpdateService: OTA package size = 12249756
,08-30 11:37:01.051  1713  4082 I SystemUpdateService: showing system update notification
,08-30 11:37:01.061   874   886 I ActivityManager: Start proc 4085:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-30 11:37:01.067  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 11:37:01.074  1713  2509 I iu.UploadsManager: num queued entries: 0
,08-30 11:37:01.075  1713  2509 I iu.UploadsManager: num updated entries: 0
,08-30 11:37:01.080  1713  2509 I iu.SyncManager: NEXT; no task
,08-30 11:37:01.081  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 11:37:01.082  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 11:37:01.085  1713  4093 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 11:37:01.085  1713  4093 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 11:37:01.087  1713  4093 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 11:37:01.088  3968  3968 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:37:01.091  1713  1713 D SystemUpdateService: onDestroy
08-30 11:37:01.094  3968  3968 D SprintDMHelper: simOperator: 
08-30 11:37:01.094  3968  3968 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-30 11:37:01.097  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 11:37:01.098  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 11:37:01.104  4085  4085 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-30 11:37:01.128  1505  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 11:37:01.128  1505  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 11:37:01.130  1505  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 11:37:01.130   874  4068 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 09:37:01 GMT], X-Android-Received-Millis=[1472549821129], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472549821076]}
,08-30 11:37:01.130  1505  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 11:37:01.131   874  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 11:37:01.131   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-30 11:37:01.131   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 11:37:01.132   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 11:37:01.150  1713  4093 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-30 11:37:01.177  3059  4102 V KeepSync: Connecting to GoogleApiClient
,08-30 11:37:01.178   874  1979 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 11:37:01.180  4085  4085 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-30 11:37:01.191  4085  4085 I BooksApp: Created application version: 3.6.9 (30609)
,08-30 11:37:01.210  1505  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 11:37:01.210  1505  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 11:37:01.210  1505  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 11:37:01.210  1505  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 11:37:01.225  1713  4110 V BaseAuthAsyncOperation: access token request failed
,08-30 11:37:01.226  3059  4102 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 11:37:01.239  4085  4111 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 11:37:01.313  1505  4115 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-30 11:37:01.314  1505  2250 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 11:37:01.314  1505  2250 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 11:37:01.314  1505  2250 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 11:37:01.315  1505  2250 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 11:37:01.315  1505  4115 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 11:37:01.320  2167  4099 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 11:37:01.332  3059  4102 E KeepSync: IOException
08-30 11:37:01.332  3059  4102 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 11:37:01.332  3059  4102 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 11:37:01.332  3059  4102 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 11:37:01.332  3059  4102 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 11:37:01.332  3059  4102 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 11:37:01.332  3059  4102 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 11:37:01.332  3059  4102 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 11:37:01.332  3059  4102 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 11:37:01.332  3059  4102 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 11:37:01.332  3059  4102 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 11:37:01.332  3059  4102 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 11:37:01.332  3059  4102 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 11:37:01.332  3059  4102 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 11:37:01.332  3059  4102 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 11:37:01.332  3059  4102 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 11:37:01.332  3059  4102 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 11:37:01.332  3059  4102 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 11:37:01.332  3059  4102 E KeepSync: 	... 10 more
,08-30 11:37:01.332  3059  4102 W KeepSync: Sync result 2
,08-30 11:37:01.337   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 130384, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 11:37:01.341  1505  4115 W Uploader:  no longer exists, so no auth token.
,08-30 11:37:01.365  4085  4125 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 11:37:01.403  1505  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 11:37:01.403  1505  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 11:37:01.404  1505  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 11:37:01.404  1505  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 11:37:01.441  1505  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-30 11:37:01.441  1505  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 11:37:01.441  1505  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 11:37:01.442  1505  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 11:37:01.462  4085  4125 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 11:37:01.464  4085  4111 E BooksSync: Soft error
08-30 11:37:01.464  4085  4111 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 11:37:01.464  4085  4111 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 11:37:01.464  4085  4111 E BooksSync: Sync error
08-30 11:37:01.464  4085  4111 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 11:37:01.464  4085  4111 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 11:37:01.464  4085  4111 I BooksSync: Finished books sync
,08-30 11:37:01.471   874  1984 I ActivityManager: Killing 3464:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 11:37:01.471   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 129424, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 11:37:01.976   874  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 11:37:02.193   874  2013 I ActivityManager: Killing 3728:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-30 11:37:02.562   874  1689 D WifiService: setWifiEnabled: false pid=3807, uid=10000
,08-30 11:37:02.563   874  1689 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 11:37:02.588  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 11:37:02.590   874  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 11:37:02.591   874  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 11:37:02.591   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 11:37:02.591   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 11:37:02.613   874  2114 D DhcpClient: Clearing IP address
,08-30 11:37:02.613   373   872 D CommandListener: Clearing all IP addresses on wlan0
,08-30 11:37:02.616   373   872 D CommandListener: Setting iface cfg
,08-30 11:37:02.620  1505  4112 V NativeCrypto: Read error: ssl=0x9b303000: I/O error during system call, Connection timed out
,08-30 11:37:02.623  1505  4112 V NativeCrypto: SSL shutdown failed: ssl=0x9b303000: I/O error during system call, Broken pipe
,08-30 11:37:02.637   874  4070 D DhcpClient: Receive thread stopped
,08-30 11:37:02.638  1505  4115 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/216.58.208.42 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
08-30 11:37:02.643   874  2051 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-30 11:37:02.643   874  4068 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-30 11:37:02.645   874  4068 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 11:37:02.650   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-30 11:37:02.651   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-30 11:37:02.652   409   409 E Parcel  : Reading a NULL string not supported here.
,08-30 11:37:02.656   874  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-30 11:37:02.663   874  1317 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-30 11:37:02.664   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 11:37:02.666   874  4068 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:802::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-30 11:37:02.691   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 11:37:02.716   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 11:37:02.716   373   872 D CommandListener: Clearing all IP addresses on wlan0
08-30 11:37:02.716   874  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 11:37:02.716   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:37:02.718   874   891 D Tethering: MasterInitialState.processMessage what=3
08-30 11:37:02.720  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:37:02.720  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:02.720  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:02.720  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:02.720  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:02.720  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:37:02.720  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:02.720  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:02.720  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:02.720  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:02.720  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:02.721  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:02.721  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:02.721  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:02.721  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:02.721  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:02.721  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:37:02.721  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:02.721  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:02.721  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:02.721  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:37:02.721  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:02.726   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 11:37:02.729  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:02.729  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:37:02.729  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:02.729  1853  2259 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:02.729  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:02.729  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:02.730  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:02.730  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:02.730   874  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 11:37:02.732  2090  2090 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-30 11:37:02.737  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 11:37:02.740  1713  1713 D SystemUpdateService: onCreate
,08-30 11:37:02.744  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 11:37:02.750  1713  4139 I SystemUpdateService: active receiver: enabled
,08-30 11:37:02.753  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 11:37:02.760  1713  2509 I iu.UploadsManager: num queued entries: 0
08-30 11:37:02.760  1713  2509 I iu.UploadsManager: num updated entries: 0
,08-30 11:37:02.762  1713  4139 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 11:37:02.764  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 11:37:02.766   373   872 E Netd    : netlink response contains error (No such file or directory)
08-30 11:37:02.766  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-30 11:37:02.767   874  1319 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 11:37:02.767   874  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 11:37:02.768  3968  3968 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:02.772  3968  3968 D SprintDMHelper: simOperator: 
,08-30 11:37:02.772  3968  3968 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 11:37:02.790  1713  2509 I iu.SyncManager: NEXT; no task
,08-30 11:37:02.790  1713  4139 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 11:37:02.790  1713  4139 I SystemUpdateService: now status is 0 (complete)
,08-30 11:37:02.790  1713  4139 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 11:37:02.794  1713  4139 I SystemUpdateService: file has been verified
,08-30 11:37:02.795  2167  4142 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 11:37:02.802  1713  4139 I SystemUpdateService: OTA package size = 12249756
,08-30 11:37:02.816  1713  4139 I SystemUpdateService: showing system update notification
,08-30 11:37:02.823  3995  3995 I art     : Waiting for a blocking GC DisableMovingGc
,08-30 11:37:02.826  3995  3995 I art     : Starting a blocking GC DisableMovingGc
,08-30 11:37:02.871  1713  1713 D SystemUpdateService: onDestroy
,08-30 11:37:05.600   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9c61e7a:true
,08-30 11:37:05.601  3954  3954 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 11:37:05.606  3954  3954 I bt_bluedroid: init
08-30 11:37:05.607  3954  4146 I BluetoothAdapterState: Entering OffState
,08-30 11:37:05.613  3954  4147 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 11:37:05.613  3954  4147 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 11:37:05.613  3954  4147 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 11:37:05.614  3954  4147 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 11:37:05.615  3954  3954 I bt_bluedroid: get_profile_interface socket
,08-30 11:37:05.617  3954  3954 I bt_bluedroid: get_profile_interface sdp
,08-30 11:37:05.620  3954  3964 I bt_bluedroid: config_hci_snoop_log
,08-30 11:37:05.621  3954  4150 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-30 11:37:05.622   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-30 11:37:05.624  3954  4150 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 11:37:05.632  3954  4146 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 11:37:05.633  3954  4146 D BluetoothAdapterProperties: Setting state to 14
08-30 11:37:05.633  3954  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 11:37:05.639  3954  4146 D BluetoothBondStateMachine: make
,08-30 11:37:05.644  3954  4151 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 11:37:05.651  3954  4146 I BluetoothAdapterState: Entering PendingCommandState
,08-30 11:37:05.652  3954  3954 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 11:37:05.656  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
,08-30 11:37:05.657  3954  3954 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 11:37:05.657  3954  3954 D BtGatt.GattService: Received start request. Starting profile...
,08-30 11:37:05.658  3954  3954 D BtGatt.GattService: start()
,08-30 11:37:05.658  3954  3954 I bt_bluedroid: get_profile_interface gatt
,08-30 11:37:05.660  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
08-30 11:37:05.660  3954  3954 D BtGatt.AdvertiseManager: advertise manager created
,08-30 11:37:05.667  3954  3954 V BluetoothAdapterState: isTurningOff()=false
,08-30 11:37:05.667  3954  3954 V BluetoothAdapterState: isTurningOn()=false
08-30 11:37:05.667  3954  3954 V BluetoothAdapterState: isBleTurningOn()=true
08-30 11:37:05.667  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:05.667  3954  4146 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 11:37:05.668  3954  4146 I bt_bluedroid: enable
,08-30 11:37:05.668  3954  4147 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 11:37:05.669  3954  4147 I bt_hci  : start_up
,08-30 11:37:05.678  3954  4147 I bt_vendor: alloc value 0xb3979189
08-30 11:37:05.679  3954  4147 I bt_vendor: init
08-30 11:37:05.679  3954  4147 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 11:37:05.679  3954  4147 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 11:37:05.789  3954  4147 D bt_hci  : start_up starting async portion
,08-30 11:37:05.790  3954  4154 I bt_hci  : event_finish_startup
08-30 11:37:05.790  3954  4154 I bt_hci_h4: hal_open
08-30 11:37:05.790  3954  4154 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 11:37:05.799  3954  4154 I bt_userial_vendor: device fd = 51 open
,08-30 11:37:05.830  3954  4154 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 11:37:05.862  3954  4154 D bt_hwcfg: Chipset BCM4354A2
08-30 11:37:05.862  3954  4154 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 11:37:05.863  3954  4154 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 11:37:06.171  4085  4108 I art     : Waiting for a blocking GC DisableMovingGc
,08-30 11:37:06.175  4085  4108 I art     : Starting a blocking GC DisableMovingGc
,08-30 11:37:06.186  4085  4108 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-30 11:37:06.461  3954  4154 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 11:37:06.463  3954  4154 D bt_hwcfg: Settlement delay -- 100 ms
08-30 11:37:06.463  3954  4154 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 11:37:06.580  3954  4154 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 11:37:06.581  3954  4154 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 11:37:06.610  3954  4154 I bt_hwcfg: vendor lib fwcfg completed
,08-30 11:37:06.611  3954  4154 I bt_vendor: firmware callback
08-30 11:37:06.611  3954  4154 I bt_hci  : firmware_config_callback
,08-30 11:37:06.622  3954  4158 I bt_btu  : btu_task pending for preload complete event,
08-30 11:37:06.622  3954  4158 I bt_btu_task: Bluetooth chip preload is complete
08-30 11:37:06.623  3954  4158 I bt_btu  : btu_task received preload complete event
,08-30 11:37:06.633  3954  4158 I         : BTE_InitTraceLevels -- TRC_HCI,
08-30 11:37:06.634  3954  4158 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 11:37:06.634  3954  4158 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
08-30 11:37:06.634  3954  4158 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 11:37:06.634  3954  4158 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 11:37:06.635  3954  4158 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 11:37:06.635  3954  4158 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 11:37:06.635  3954  4158 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 11:37:06.635  3954  4158 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 11:37:06.636  3954  4158 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 11:37:06.636  3954  4158 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 11:37:06.636  3954  4158 I         : BTE_InitTraceLevels -- TRC_GATT
,08-30 11:37:06.636  3954  4158 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 11:37:06.637  3954  4158 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 11:37:06.637  3954  4158 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 11:37:06.774  3954  4158 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f6d9d
08-30 11:37:06.775  3954  4158 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f6d9d 
,08-30 11:37:06.786  3954  4150 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 11:37:06.788  3954  4150 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 11:37:06.789  3954  4150 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 11:37:06.795  3954  4150 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 11:37:06.801  3954  4150 D BluetoothAdapterProperties: Scan Mode:20
,08-30 11:37:06.802  3954  4150 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 11:37:06.803  3954  4150 D bt_hci  : do_postload posting postload work item
08-30 11:37:06.803  3954  4154 I bt_hci  : event_postload
08-30 11:37:06.803  3954  4154 I bt_vendor: sco_config_cb
,08-30 11:37:06.803  3954  4154 I bt_hci  : sco_config_callback postload finished.
,08-30 11:37:06.807  3954  4150 D bt_bte_conf: Device ID record 1 : primary
08-30 11:37:06.807  3954  4150 D bt_bte_conf:   vendorId            = 000f
08-30 11:37:06.807  3954  4150 D bt_bte_conf:   vendorIdSource      = 0001
08-30 11:37:06.807  3954  4150 D bt_bte_conf:   product             = 1200
,08-30 11:37:06.807  3954  4150 D bt_bte_conf:   version             = 1436
08-30 11:37:06.807  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:06.808  3954  4150 D bt_bte_conf:   clientExecutableURL = 
08-30 11:37:06.808  3954  4150 D bt_bte_conf:   serviceDescription  = 
08-30 11:37:06.808  3954  4150 D bt_bte_conf:   documentationURL    = 
,08-30 11:37:06.808  3954  4150 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 11:37:06.809  3954  4147 D bt_stack_manager: event_start_up_stack finished
08-30 11:37:06.810  3954  4146 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 11:37:06.810  3954  4146 D BluetoothAdapterProperties: Setting state to 15
08-30 11:37:06.811  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:06.812  3954  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 11:37:06.814  3954  4154 I bt_vendor: low_power_mode_cb
08-30 11:37:06.815  3954  4146 I BluetoothAdapterState: Entering BleOnState
,08-30 11:37:06.819  3954  4146 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 11:37:06.820  3954  4146 D BluetoothAdapterProperties: Setting state to 11
,08-30 11:37:06.820  3954  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 11:37:06.828  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:06.830  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
08-30 11:37:06.831  3954  3954 D HeadsetService: Received start request. Starting profile...
08-30 11:37:06.831  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:06.834  3954  3954 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 11:37:06.835  3954  3954 D HeadsetStateMachine: make
08-30 11:37:06.845  3954  4146 I BluetoothAdapterState: Entering PendingCommandState
,08-30 11:37:06.847  3954  3954 D HeadsetStateMachine: max_hf_connections = 1
08-30 11:37:06.847  3954  3954 I bt_bluedroid: get_profile_interface handsfree
,08-30 11:37:06.849  3954  4150 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 11:37:06.849  3954  4150 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 11:37:06.854  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
,08-30 11:37:06.855  3954  3954 D A2dpService: Received start request. Starting profile...
08-30 11:37:06.856  3954  3954 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 11:37:06.857  3954  3954 I bt_bluedroid: get_profile_interface avrcp
,08-30 11:37:06.863  3954  3954 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 11:37:06.863  3954  3954 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 11:37:06.864  3954  3954 D A2dpStateMachine: make
,08-30 11:37:06.865  3954  3954 I bt_bluedroid: get_profile_interface a2dp
,08-30 11:37:06.866  3954  4150 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-30 11:37:06.867  3954  4167 D A2dpStateMachine: Enter Disconnected: -2
,08-30 11:37:06.868  3954  3954 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 11:37:06.869  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
08-30 11:37:06.870  3954  3954 D HidService: Received start request. Starting profile...
08-30 11:37:06.870  3954  3954 I bt_bluedroid: get_profile_interface hidhost
08-30 11:37:06.870  3954  3954 D HidService: setHidService(): set to: null
,08-30 11:37:06.870  3954  4150 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d83e5
08-30 11:37:06.871  3954  4150 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 11:37:06.871  3954  3954 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 11:37:06.872  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
08-30 11:37:06.872  3876  3876 D BluetoothInputDevice: Proxy object connected
08-30 11:37:06.872  3954  3954 D HealthService: Received start request. Starting profile...
08-30 11:37:06.873  3876  3876 D HidProfile: Bluetooth service connected
,08-30 11:37:06.877  3954  3954 I bt_bluedroid: get_profile_interface health
08-30 11:37:06.877  3954  3954 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 11:37:06.878  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
,08-30 11:37:06.879  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 11:37:06.880  3876  3876 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 11:37:06.880  3954  3954 D PanService: Received start request. Starting profile...
,08-30 11:37:06.880  3954  3954 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 11:37:06.880  3954  3954 I bt_bluedroid: get_profile_interface pan
,08-30 11:37:06.881  3954  4150 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 11:37:06.881  3876  3876 D PanProfile: Bluetooth service connected
,08-30 11:37:06.884  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
,08-30 11:37:06.885  3954  3954 D BluetoothMapService: Received start request. Starting profile...
08-30 11:37:06.885  3954  3954 D BluetoothMapService: start()
,08-30 11:37:06.885  3876  3876 D BluetoothMap: Proxy object connected
08-30 11:37:06.886  3876  3876 D MapProfile: Bluetooth service connected
08-30 11:37:06.886  3876  3876 D BluetoothMap: getConnectedDevices()
,08-30 11:37:06.886  3876  3876 D BluetoothMap: Bluetooth is Not enabled
,08-30 11:37:06.887  3954  3954 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 11:37:06.888  3954  3954 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 11:37:06.888  3954  3954 D BluetoothMapAppObserver: createReceiver()
,08-30 11:37:06.889  3954  3954 D BluetoothMapAppObserver: initObservers()
08-30 11:37:06.889  3954  3954 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 11:37:06.895  3954  3954 V BluetoothAdapterState: isTurningOff()=false
,08-30 11:37:06.895  3954  3954 V BluetoothAdapterState: isTurningOn()=true
,08-30 11:37:06.895  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 11:37:06.895  3954  4165 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 11:37:06.895  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:06.896  3954  3954 V BluetoothAdapterState: isTurningOff()=false
,08-30 11:37:06.896  3954  3954 V BluetoothAdapterState: isTurningOn()=true
08-30 11:37:06.896  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false,
,08-30 11:37:06.896  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 11:37:06.897  3954  3954 V BluetoothAdapterState: isTurningOff()=false
08-30 11:37:06.897  3954  3954 V BluetoothAdapterState: isTurningOn()=true
,08-30 11:37:06.897  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:37:06.897  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:06.897  3954  3954 V BluetoothAdapterState: isTurningOff()=false
08-30 11:37:06.897  3954  3954 V BluetoothAdapterState: isTurningOn()=true
08-30 11:37:06.897  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:37:06.897  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:06.897  3954  3954 V BluetoothAdapterState: isTurningOff()=false
08-30 11:37:06.897  3954  3954 V BluetoothAdapterState: isTurningOn()=true
08-30 11:37:06.897  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:37:06.897  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:06.899  3954  3954 V BluetoothAdapterState: isTurningOff()=false
08-30 11:37:06.900  3954  3954 V BluetoothAdapterState: isTurningOn()=true
08-30 11:37:06.900  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:37:06.900  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 11:37:06.901  3954  4146 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 11:37:06.901  3954  4146 D BluetoothAdapterProperties: ScanMode =  20
,08-30 11:37:06.901  3954  4146 D BluetoothAdapterProperties: State =  11
08-30 11:37:06.902  3954  4146 D BluetoothAdapterProperties: Setting state to 12
08-30 11:37:06.902  3954  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 11:37:06.903   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 11:37:06.903  1375  2123 D BluetoothPan: onBluetoothStateChange on: true
,08-30 11:37:06.904  3954  4150 D BluetoothAdapterProperties: Scan Mode:21
08-30 11:37:06.904  3954  4150 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 11:37:06.904  3954  4146 I BluetoothAdapterState: Entering OnState
08-30 11:37:06.905  1375  1375 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 11:37:06.905  1375  1375 D PanProfile: Bluetooth service connected
08-30 11:37:06.905  3876  3887 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 11:37:06.907  1375  1386 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 11:37:06.908  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:06.908  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:06.908  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:06.908  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:06.908  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:06.908  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:06.908  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:06.908  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:06.909  2003  2014 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 11:37:06.910  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:06.910  1375  1388 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 11:37:06.912  3876  3888 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 11:37:06.912   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 11:37:06.912  3876  3887 D BluetoothPan: onBluetoothStateChange on: true
08-30 11:37:06.912  1375  1386 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 11:37:06.912  1375  1375 D BluetoothA2dp: Proxy object connected
08-30 11:37:06.913  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:06.913  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:06.913  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:06.913  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:06.913  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:06.913  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:06.913  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:06.913  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:06.915  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:06.915  3876  3888 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 11:37:06.915   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 11:37:06.915  3954  3954 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 11:37:06.916  1375  1375 D BluetoothInputDevice: Proxy object connected
08-30 11:37:06.916  1375  1375 D HidProfile: Bluetooth service connected
08-30 11:37:06.916   874   874 D BluetoothA2dp: Proxy object connected
08-30 11:37:06.916  3954  3954 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 11:37:06.916  1375  2123 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 11:37:06.917  3954  3954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 11:37:06.920  3954  3954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 11:37:06.920  1375  1375 D BluetoothMap: Proxy object connected
08-30 11:37:06.920   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 11:37:06.920  1375  1375 D MapProfile: Bluetooth service connected
08-30 11:37:06.920  1375  1375 D BluetoothMap: getConnectedDevices()
08-30 11:37:06.920  1375  1386 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 11:37:06.921  3954  3954 D ObexServerSockets: Succeed to create listening sockets 
,08-30 11:37:06.921  3954  3954 D ObexServerSockets0: startAccept()
08-30 11:37:06.921  3954  3954 D ObexServerSockets0: prepareForNewConnect()
08-30 11:37:06.922   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 11:37:06.923  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:06.925  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:06.925  3954  3954 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 11:37:06.925  3954  3954 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 11:37:06.925  3876  3876 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 11:37:06.925  3954  3954 D BluetoothMapService: onReceive
08-30 11:37:06.925  3954  3954 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:06.925  3954  3954 D BluetoothMapService: STATE_ON
08-30 11:37:06.926  3954  4174 D ObexServerSockets0: Accepting socket connection...
08-30 11:37:06.926  3954  4176 D ObexServerSockets0: Accepting socket connection...
08-30 11:37:06.929  3876  3876 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 11:37:06.936  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 11:37:06.938  3876  3876 D BluetoothA2dp: Proxy object connected
,08-30 11:37:06.943  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 11:37:06.945  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,08-30 11:37:06.949  1375  1375 D BluetoothPbap: Proxy object connected
,08-30 11:37:06.949  1375  1375 D PbapServerProfile: Bluetooth service connected
08-30 11:37:06.950  3876  3876 D BluetoothPbap: Proxy object connected
,08-30 11:37:06.950  3954  3954 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 11:37:06.950  3954  3954 D ObexServerSockets0: prepareForNewConnect()
,08-30 11:37:06.950  3876  3876 D PbapServerProfile: Bluetooth service connected
,08-30 11:37:06.958  3954  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 11:37:06.972  3954  4184 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 11:37:06.973  3954  4184 I BtOppRfcommListener: Accept thread started.
,08-30 11:37:07.005  2003  2242 D BluetoothHeadset: Proxy object connected
,08-30 11:37:07.005  1375  1388 D BluetoothHeadset: Proxy object connected
,08-30 11:37:07.006   874   874 D BluetoothHeadset: Proxy object connected
,08-30 11:37:07.006  1375  1375 D HeadsetProfile: Bluetooth service connected
08-30 11:37:07.006   874   874 D BluetoothHeadset: Proxy object connected
08-30 11:37:07.006   874   874 D BluetoothHeadset: Proxy object connected
,08-30 11:37:07.009  2003  2015 D BluetoothHeadset: Proxy object connected
,08-30 11:37:07.012   874   891 D BluetoothHeadset: Proxy object connected
,08-30 11:37:07.020   874   891 D BluetoothHeadset: Proxy object connected
,08-30 11:37:07.021  1375  1386 D BluetoothHeadset: Proxy object connected
,08-30 11:37:07.021  1375  1375 D HeadsetProfile: Bluetooth service connected
,08-30 11:37:07.032  3876  3887 D BluetoothHeadset: Proxy object connected
,08-30 11:37:07.032  3876  3876 D HeadsetProfile: Bluetooth service connected
,08-30 11:37:07.978  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 11:37:07.995  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 11:37:08.001  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 11:37:08.078  1505  2142 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 11:37:08.078  1505  2142 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 11:37:08.079  1505  2142 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 11:37:08.079  1505  2142 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 11:37:08.134  3553  3553 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 11:37:08.135  3553  3553 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 11:37:08.136  3553  3553 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-30 11:37:08.584  3954  4146 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 11:37:08.584  3954  4146 D BluetoothAdapterProperties: Setting state to 13
08-30 11:37:08.585  3954  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 11:37:08.586  3954  4146 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 11:37:08.590  3954  4146 I BluetoothAdapterState: Entering PendingCommandState
,08-30 11:37:08.599  3954  3954 D BluetoothMapService: onReceive
08-30 11:37:08.599  3954  3954 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:08.599  3954  3954 D BluetoothMapService: STATE_TURNING_OFF
08-30 11:37:08.600  3954  3954 D BluetoothMapService: MAP Service closeService in
08-30 11:37:08.600  3954  3954 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 11:37:08.600  3954  3954 D ObexServerSockets0: shutdown(block = true)
08-30 11:37:08.601  3954  4174 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-30 11:37:08.604  3954  3954 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 11:37:08.604  3954  4176 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 11:37:08.604  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:08.604  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:08.604  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:08.604  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:08.604  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:08.604  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:37:08.604  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:08.604  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:08.604  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:08.605  3954  4160 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-30 11:37:08.605  3954  3954 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 11:37:08.605  3954  3954 I BtOppRfcommListener: stopping Accept Thread
08-30 11:37:08.605  3954  4184 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 11:37:08.606  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:08.606  3954  4184 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 11:37:08.606  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:08.608  3954  4150 D BluetoothAdapterProperties: Scan Mode:20
,08-30 11:37:08.609  3954  4146 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 11:37:08.609  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:37:08.610  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:08.610  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:08.610  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:08.610  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:08.610  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:37:08.610  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:08.610  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:08.610  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:08.611  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:37:08.611  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:08.612  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 11:37:08.616  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:08.617  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:08.621  3954  3954 D HeadsetService: Received stop request...Stopping profile...
08-30 11:37:08.624  2003  2105 D BluetoothHeadset: Proxy object disconnected
08-30 11:37:08.625  1375  2123 D BluetoothHeadset: Proxy object disconnected
08-30 11:37:08.625   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 11:37:08.625   874   874 D BluetoothHeadset: Proxy object disconnected
,08-30 11:37:08.625   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 11:37:08.625  1375  1375 D HeadsetProfile: Bluetooth service disconnected
,08-30 11:37:08.625  3954  3954 D A2dpService: Received stop request...Stopping profile...
08-30 11:37:08.626  3876  3887 D BluetoothHeadset: Proxy object disconnected
08-30 11:37:08.626  3954  4167 D A2dpStateMachine: Exit Disconnected: -1
08-30 11:37:08.627   874   874 D BluetoothA2dp: Proxy object disconnected
08-30 11:37:08.628  1375  1375 D BluetoothA2dp: Proxy object disconnected
08-30 11:37:08.629  3876  3876 D DockEventReceiver: finishStartingService: stopping service
08-30 11:37:08.629  3876  3876 D HeadsetProfile: Bluetooth service disconnected
08-30 11:37:08.630  3876  3876 D BluetoothA2dp: Proxy object disconnected
08-30 11:37:08.630  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 11:37:08.636  3954  3954 V BluetoothAdapterState: isTurningOff()=true
08-30 11:37:08.636  3954  3954 V BluetoothAdapterState: isTurningOn()=false
08-30 11:37:08.636  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:37:08.636  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 11:37:08.638  3954  3954 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 11:37:08.638  3954  4150 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 11:37:08.638  3954  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 11:37:08.638  3954  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 11:37:08.638  3954  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 11:37:08.639  3954  4150 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
08-30 11:37:08.638  3954  3954 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 11:37:08.640  3954  3954 D HidService: Received stop request...Stopping profile...
,08-30 11:37:08.640  3954  3954 D HidService: Stopping Bluetooth HidService
08-30 11:37:08.641  3954  3954 D HealthService: Received stop request...Stopping profile...
,08-30 11:37:08.641  3876  3876 D BluetoothInputDevice: Proxy object disconnected
,08-30 11:37:08.641  3876  3876 D HidProfile: Bluetooth service disconnected
08-30 11:37:08.643  1375  1375 D BluetoothInputDevice: Proxy object disconnected
08-30 11:37:08.643  1375  1375 D HidProfile: Bluetooth service disconnected
08-30 11:37:08.643  3954  3954 V BluetoothAdapterState: isTurningOff()=true
,08-30 11:37:08.643  3954  3954 V BluetoothAdapterState: isTurningOn()=false
08-30 11:37:08.643  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:37:08.643  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:08.644  3954  3954 D PanService: Received stop request...Stopping profile...
08-30 11:37:08.645  1375  1375 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 11:37:08.645  1375  1375 D PanProfile: Bluetooth service disconnected
,08-30 11:37:08.646  3954  3954 D BluetoothMapService: Received stop request...Stopping profile...
08-30 11:37:08.646  3954  3954 D BluetoothMapService: stop()
08-30 11:37:08.647  3876  3876 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 11:37:08.647  3876  3876 D PanProfile: Bluetooth service disconnected
08-30 11:37:08.647  3954  3954 D BluetoothMapAppObserver: deinitObservers()
,08-30 11:37:08.647  3954  3954 D BluetoothMapAppObserver: removeReceiver()
,08-30 11:37:08.648  1375  1375 D BluetoothMap: Proxy object disconnected
08-30 11:37:08.648  1375  1375 D MapProfile: Bluetooth service disconnected
,08-30 11:37:08.649  3876  3876 D BluetoothMap: Proxy object disconnected
08-30 11:37:08.649  3876  3876 D MapProfile: Bluetooth service disconnected
,08-30 11:37:08.650  3954  4150 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-30 11:37:08.650  3954  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 11:37:08.650  3954  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 11:37:08.651  3954  4158 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 11:37:08.651  3954  4158 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 11:37:08.651  3954  4158 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 11:37:08.651  3954  4158 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 11:37:08.651  3876  3876 D BluetoothPbap: Proxy object disconnected
08-30 11:37:08.651  3876  3876 D PbapServerProfile: Bluetooth service disconnected
08-30 11:37:08.651  1375  1375 D BluetoothPbap: Proxy object disconnected
08-30 11:37:08.652  1375  1375 D PbapServerProfile: Bluetooth service disconnected
08-30 11:37:08.652  3954  3954 V BluetoothAdapterState: isTurningOff()=true
08-30 11:37:08.654  3954  3954 V BluetoothAdapterState: isTurningOn()=false
08-30 11:37:08.654  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 11:37:08.654  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:08.654  3954  3954 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 11:37:08.654  3954  4150 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 11:37:08.655  3954  3954 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 11:37:08.655  3954  3954 V BluetoothAdapterState: isTurningOff()=true
08-30 11:37:08.655  3954  3954 V BluetoothAdapterState: isTurningOn()=false
08-30 11:37:08.655  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:37:08.655  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:08.655  3954  3954 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 11:37:08.655  3954  4150 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 11:37:08.656  3954  3954 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 11:37:08.657  3954  3954 V BluetoothAdapterState: isTurningOff()=true
08-30 11:37:08.657  3954  3954 V BluetoothAdapterState: isTurningOn()=false
,08-30 11:37:08.657  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:37:08.657  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:08.657  3954  3954 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 11:37:08.658  3954  3954 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 11:37:08.660  3954  3954 D BluetoothMapService: MAP Service closeService in
08-30 11:37:08.660  3954  3954 V BluetoothAdapterState: isTurningOff()=true
08-30 11:37:08.660  3954  3954 V BluetoothAdapterState: isTurningOn()=false
08-30 11:37:08.660  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 11:37:08.660  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:08.661  3954  4146 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-30 11:37:08.661  3954  4146 D BluetoothAdapterProperties: Setting state to 15
08-30 11:37:08.661  3954  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 11:37:08.661  3954  4146 I BluetoothAdapterState: Entering BleOnState
08-30 11:37:08.662   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 11:37:08.662  1375  1388 D BluetoothPan: onBluetoothStateChange on: false
,08-30 11:37:08.663  3954  3954 D BluetoothMapService: cleanup()
08-30 11:37:08.663  3954  3954 D BluetoothMapService: MAP Service closeService in
08-30 11:37:08.663  3876  3888 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 11:37:08.664  1375  1386 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 11:37:08.664  2003  2014 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 11:37:08.664  1375  2123 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 11:37:08.665  3876  3887 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 11:37:08.665   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 11:37:08.666  3876  3888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 11:37:08.666  3876  3887 D BluetoothPan: onBluetoothStateChange on: false
,08-30 11:37:08.667  1375  1388 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 11:37:08.668  3876  3888 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 11:37:08.668   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 11:37:08.668  1375  1386 D BluetoothMap: onBluetoothStateChange: up=false
08-30 11:37:08.669  3876  3887 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 11:37:08.669   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 11:37:08.669  1375  2123 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 11:37:08.670  3954  4146 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 11:37:08.670  3954  4146 D BluetoothAdapterProperties: Setting state to 16
,08-30 11:37:08.670  3954  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-30 11:37:08.672  3954  4146 D BluetoothAdapterProperties: onBleDisable
08-30 11:37:08.672  3954  4146 I BluetoothAdapterState: Entering PendingCommandState
,08-30 11:37:08.672  3954  4147 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 11:37:08.673  3954  4158 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 11:37:08.673  3954  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 11:37:08.673  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 11:37:08.674  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:08.675  3954  4150 D BluetoothAdapterProperties: Scan Mode:20
08-30 11:37:08.677  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:08.678  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:08.679  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:08.679  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 11:37:08.688  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,08-30 11:37:08.878  3954  4150 I bt_hci  : shut_down
,08-30 11:37:08.889  3954  4154 I bt_vendor: low_power_mode_cb
08-30 11:37:08.889  3954  4154 D bt_hwcfg: hw_epilog_process
,08-30 11:37:08.906   874  1319 D ConnectivityService: handlePromptUnvalidated 101
,08-30 11:37:08.916  3954  4154 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-30 11:37:08.916  3954  4154 I bt_vendor: epilog_cb
08-30 11:37:08.917  3954  4154 I bt_hci  : epilog_finished_callback
,08-30 11:37:08.925  3954  4150 I bt_hci_h4: hal_close
,08-30 11:37:08.927  3954  4150 I bt_userial_vendor: device fd = 51 close
,08-30 11:37:09.043  3954  4147 D bt_stack_manager: event_shut_down_stack finished.
,08-30 11:37:09.044  3954  4146 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 11:37:09.050  3954  4146 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 11:37:09.050  3954  3954 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 11:37:09.052  3954  3954 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 11:37:09.052  3954  3954 D BtGatt.GattService: stop()
,08-30 11:37:09.052  3954  3954 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 11:37:09.057  3954  3954 V BluetoothAdapterState: isTurningOff()=false
,08-30 11:37:09.057  3954  3954 V BluetoothAdapterState: isTurningOn()=false
08-30 11:37:09.059  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:37:09.060  3954  3954 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 11:37:09.060  3954  4146 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 11:37:09.061  3954  4146 D BluetoothAdapterProperties: Setting state to 10
08-30 11:37:09.061  3954  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-30 11:37:09.063  3954  4146 I BluetoothAdapterState: Entering OffState
,08-30 11:37:09.065   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 11:37:09.081  3954  3954 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 11:37:09.081  3954  3954 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 11:37:09.081  3954  3954 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 11:37:09.082  3954  4147 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-30 11:37:09.086  3954  4147 D bt_stack_manager: event_clean_up_stack finished.
,08-30 11:37:09.088  3954  3954 I art     : System.exit called, status: 0
,08-30 11:37:09.088  3954  3954 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 11:37:09.154   874  1688 I ActivityManager: Process com.android.bluetooth (pid 3954) has died
,08-30 11:37:11.273  3553  3565 D Finsky  : [269] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-30 11:37:11.289  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 11:37:11.337  1505  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-30 11:37:11.337  1505  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-30 11:37:11.337  1505  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 11:37:11.337  1505  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 11:37:11.361  3553  3565 D Finsky  : [269] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-30 11:37:11.580  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:11.581  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:13.670   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 11:37:13.680  1900  1900 I Keyboard.Facilitator: onFinishInput()
,08-30 11:37:13.684   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 11:37:13.684   874   894 I Adreno  : Build Date                       : 10/20/15
08-30 11:37:13.684   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 11:37:13.684   874   894 I Adreno  : Local Branch                     : M14
08-30 11:37:13.684   874   894 I Adreno  : Remote Branch                    : 
08-30 11:37:13.684   874   894 I Adreno  : Remote Branch                    : 
08-30 11:37:13.684   874   894 I Adreno  : Reconstruct Branch               : 
,08-30 11:37:13.718   281  1307 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (199 us)
,08-30 11:37:14.375  3807  3807 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 11:37:14.375  3807  3807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 11:37:14.414   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
08-30 11:37:14.415  3807  3807 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d59ab79 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@87ec7fb, 16908290=android.view.AbsSavedState$1@87ec7fb}, android:focusedViewId=100}]}]
08-30 11:37:14.415  3807  3807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 11:37:14.416  3807  3807 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 11:37:14.416  3807  3807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 11:37:14.425   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-30 11:37:14.428   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-30 11:37:14.431   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,08-30 11:37:14.431   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-30 11:37:14.587  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 11:37:14.588  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60bd018 added. We now have 6 listener(s)
08-30 11:37:14.588  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:37:14.593  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 11:37:14.593  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6ff1a71 added. We now have 7 listener(s)
08-30 11:37:14.594  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:14.595  3807  3857 I System.out: IsBluetoothEnabled
,08-30 11:37:14.608  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:14.643   874   891 I ActivityManager: Start proc 4198:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 11:37:14.652   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 11:37:14.654   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-30 11:37:14.655   874  1343 D SurfaceControl: Excessive delay in setPowerMode(): 226ms
08-30 11:37:14.656   874   894 I DreamManagerService: Entering dreamland.
08-30 11:37:14.657   874   894 I PowerManagerService: Dozing...
08-30 11:37:14.659   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-30 11:37:14.708   377  1325 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-30 11:37:14.708   377  1325 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-30 11:37:14.717   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 11:37:14.722   874  1317 E native  : do suspend false
,08-30 11:37:14.724  1987  4211 D NfcService: Discovery configuration equal, not updating.
,08-30 11:37:14.743  4198  4198 D AdapterServiceConfig: Adding HeadsetService
,08-30 11:37:14.744  4198  4198 D AdapterServiceConfig: Adding A2dpService
,08-30 11:37:14.744  4198  4198 D AdapterServiceConfig: Adding HidService
,08-30 11:37:14.744  4198  4198 D AdapterServiceConfig: Adding HealthService
,08-30 11:37:14.744  4198  4198 D AdapterServiceConfig: Adding PanService
08-30 11:37:14.744  4198  4198 D AdapterServiceConfig: Adding GattService
08-30 11:37:14.744  4198  4198 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 11:37:14.750   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 11:37:14.753   874  1317 E native  : do suspend true
,08-30 11:37:14.756   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b43d343:true
08-30 11:37:14.756  4198  4198 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 11:37:14.759  4198  4198 I bt_bluedroid: init
08-30 11:37:14.759  4198  4213 I BluetoothAdapterState: Entering OffState
,08-30 11:37:14.762  4198  4214 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 11:37:14.762  4198  4214 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 11:37:14.762  4198  4214 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 11:37:14.763  4198  4214 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 11:37:14.764  4198  4198 I bt_bluedroid: get_profile_interface socket
,08-30 11:37:14.765  4198  4198 I bt_bluedroid: get_profile_interface sdp
,08-30 11:37:14.770  4198  4217 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 11:37:14.773  4198  4217 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 11:37:14.850   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-30 11:37:14.851   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 11:37:14.857  4198  4209 I bt_bluedroid: config_hci_snoop_log
,08-30 11:37:14.861   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 11:37:14.878  4198  4213 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 11:37:14.879  4198  4213 D BluetoothAdapterProperties: Setting state to 14
,08-30 11:37:14.881  4198  4213 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 11:37:14.886  4198  4213 D BluetoothBondStateMachine: make
,08-30 11:37:14.895  4198  4218 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 11:37:14.908  4198  4213 I BluetoothAdapterState: Entering PendingCommandState
,08-30 11:37:14.909  4198  4198 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 11:37:14.918  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
,08-30 11:37:14.920  4198  4198 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 11:37:14.923  4198  4198 D BtGatt.GattService: Received start request. Starting profile...
,08-30 11:37:14.923  4198  4198 D BtGatt.GattService: start()
08-30 11:37:14.923  4198  4198 I bt_bluedroid: get_profile_interface gatt
08-30 11:37:14.925  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
,08-30 11:37:14.926  4198  4198 D BtGatt.AdvertiseManager: advertise manager created
,08-30 11:37:14.940  4198  4198 V BluetoothAdapterState: isTurningOff()=false
,08-30 11:37:14.940  4198  4198 V BluetoothAdapterState: isTurningOn()=false
08-30 11:37:14.940  4198  4198 V BluetoothAdapterState: isBleTurningOn()=true
08-30 11:37:14.940  4198  4198 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 11:37:14.941  4198  4213 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 11:37:14.942  4198  4213 I bt_bluedroid: enable
08-30 11:37:14.943  4198  4214 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 11:37:14.944  4198  4214 I bt_hci  : start_up
,08-30 11:37:14.954  4198  4214 I bt_vendor: alloc value 0xb39cd189
08-30 11:37:14.954  4198  4214 I bt_vendor: init
08-30 11:37:14.954  4198  4214 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 11:37:14.954  4198  4214 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 11:37:15.060  4198  4214 D bt_hci  : start_up starting async portion
08-30 11:37:15.061  4198  4223 I bt_hci  : event_finish_startup
,08-30 11:37:15.061  4198  4223 I bt_hci_h4: hal_open
08-30 11:37:15.061  4198  4223 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 11:37:15.070  4198  4223 I bt_userial_vendor: device fd = 51 open
,08-30 11:37:15.103  4198  4223 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 11:37:15.135  4198  4223 D bt_hwcfg: Chipset BCM4354A2
,08-30 11:37:15.135  4198  4223 D bt_hwcfg: Target name = [BCM4354A2]
08-30 11:37:15.136  4198  4223 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 11:37:15.804  4198  4223 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 11:37:15.806  4198  4223 D bt_hwcfg: Settlement delay -- 100 ms
08-30 11:37:15.806  4198  4223 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 11:37:15.923  4198  4223 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 11:37:15.924  4198  4223 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 11:37:15.954  4198  4223 I bt_hwcfg: vendor lib fwcfg completed
08-30 11:37:15.954  4198  4223 I bt_vendor: firmware callback
08-30 11:37:15.954  4198  4223 I bt_hci  : firmware_config_callback
,08-30 11:37:15.966  4198  4225 I bt_btu  : btu_task pending for preload complete event
08-30 11:37:15.966  4198  4225 I bt_btu_task: Bluetooth chip preload is complete
,08-30 11:37:15.966  4198  4225 I bt_btu  : btu_task received preload complete event
,08-30 11:37:15.976  4198  4225 I         : BTE_InitTraceLevels -- TRC_HCI,
,08-30 11:37:15.976  4198  4225 I         : BTE_InitTraceLevels -- TRC_L2CAP,
08-30 11:37:15.976  4198  4225 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 11:37:15.977  4198  4225 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 11:37:15.977  4198  4225 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 11:37:15.977  4198  4225 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 11:37:15.977  4198  4225 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 11:37:15.978  4198  4225 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 11:37:15.978  4198  4225 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 11:37:15.978  4198  4225 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 11:37:15.978  4198  4225 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 11:37:15.979  4198  4225 I         : BTE_InitTraceLevels -- TRC_GATT
,08-30 11:37:15.979  4198  4225 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 11:37:15.979  4198  4225 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 11:37:15.980  4198  4225 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 11:37:16.117  4198  4225 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb394ad9d
08-30 11:37:16.118  4198  4225 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb394ad9d 
,08-30 11:37:16.131  4198  4217 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 11:37:16.133  4198  4217 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 11:37:16.133  4198  4217 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 11:37:16.136  4198  4217 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 11:37:16.141  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:16.143  4198  4217 D BluetoothAdapterProperties: Scan Mode:20
08-30 11:37:16.144  4198  4217 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 11:37:16.144  4198  4217 D bt_hci  : do_postload posting postload work item
,08-30 11:37:16.144  4198  4223 I bt_hci  : event_postload
08-30 11:37:16.144  4198  4223 I bt_vendor: sco_config_cb
08-30 11:37:16.144  4198  4223 I bt_hci  : sco_config_callback postload finished.
08-30 11:37:16.147  4198  4217 D bt_bte_conf: Device ID record 1 : primary
08-30 11:37:16.147  4198  4217 D bt_bte_conf:   vendorId            = 000f
08-30 11:37:16.147  4198  4217 D bt_bte_conf:   vendorIdSource      = 0001
08-30 11:37:16.147  4198  4217 D bt_bte_conf:   product             = 1200
08-30 11:37:16.148  4198  4217 D bt_bte_conf:   version             = 1436
08-30 11:37:16.148  4198  4217 D bt_bte_conf:   clientExecutableURL = 
08-30 11:37:16.148  4198  4217 D bt_bte_conf:   serviceDescription  = 
08-30 11:37:16.148  4198  4217 D bt_bte_conf:   documentationURL    = 
08-30 11:37:16.148  4198  4217 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 11:37:16.149  4198  4214 D bt_stack_manager: event_start_up_stack finished
08-30 11:37:16.150  4198  4223 I bt_vendor: low_power_mode_cb
08-30 11:37:16.150  4198  4213 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 11:37:16.151  4198  4213 D BluetoothAdapterProperties: Setting state to 15
08-30 11:37:16.152  4198  4213 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 11:37:16.153  4198  4213 I BluetoothAdapterState: Entering BleOnState
,08-30 11:37:16.157  4198  4213 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 11:37:16.158  4198  4213 D BluetoothAdapterProperties: Setting state to 11
08-30 11:37:16.158  4198  4213 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 11:37:16.164  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
,08-30 11:37:16.164  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:16.164  4198  4198 D HeadsetService: Received start request. Starting profile...
08-30 11:37:16.168  4198  4198 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 11:37:16.168  4198  4198 D HeadsetStateMachine: make
,08-30 11:37:16.177  4198  4213 I BluetoothAdapterState: Entering PendingCommandState
,08-30 11:37:16.179  4198  4198 D HeadsetStateMachine: max_hf_connections = 1
,08-30 11:37:16.179  4198  4198 I bt_bluedroid: get_profile_interface handsfree
,08-30 11:37:16.179  4198  4217 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 11:37:16.180  4198  4217 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 11:37:16.183  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
,08-30 11:37:16.184  4198  4198 D A2dpService: Received start request. Starting profile...
,08-30 11:37:16.185  4198  4198 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 11:37:16.185  4198  4198 I bt_bluedroid: get_profile_interface avrcp
,08-30 11:37:16.191  4198  4198 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 11:37:16.192  4198  4198 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 11:37:16.192  4198  4198 D A2dpStateMachine: make
,08-30 11:37:16.193  4198  4198 I bt_bluedroid: get_profile_interface a2dp
,08-30 11:37:16.194  4198  4217 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 11:37:16.196  4198  4234 D A2dpStateMachine: Enter Disconnected: -2
,08-30 11:37:16.197  4198  4198 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 11:37:16.198  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 11:37:16.199  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
,08-30 11:37:16.200  4198  4198 D HidService: Received start request. Starting profile...
,08-30 11:37:16.200  4198  4198 I bt_bluedroid: get_profile_interface hidhost
08-30 11:37:16.201  4198  4198 D HidService: setHidService(): set to: null
,08-30 11:37:16.201  4198  4217 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb392c3e5
08-30 11:37:16.201  4198  4217 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 11:37:16.201  4198  4198 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 11:37:16.203  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
,08-30 11:37:16.204  4198  4198 D HealthService: Received start request. Starting profile...
,08-30 11:37:16.205  4198  4198 I bt_bluedroid: get_profile_interface health
,08-30 11:37:16.206  4198  4198 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 11:37:16.207  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
,08-30 11:37:16.208  4198  4198 D PanService: Received start request. Starting profile...
08-30 11:37:16.208  4198  4198 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-30 11:37:16.208  4198  4198 I bt_bluedroid: get_profile_interface pan
,08-30 11:37:16.209  4198  4217 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 11:37:16.212  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
,08-30 11:37:16.213  4198  4198 D BluetoothMapService: Received start request. Starting profile...
08-30 11:37:16.213  4198  4198 D BluetoothMapService: start()
,08-30 11:37:16.216  4198  4198 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 11:37:16.217  4198  4198 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 11:37:16.217  4198  4198 D BluetoothMapAppObserver: createReceiver()
,08-30 11:37:16.219  4198  4198 D BluetoothMapAppObserver: initObservers()
,08-30 11:37:16.219  4198  4198 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 11:37:16.227  4198  4198 V BluetoothAdapterState: isTurningOff()=false
,08-30 11:37:16.227  4198  4198 V BluetoothAdapterState: isTurningOn()=true
08-30 11:37:16.227  4198  4198 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:37:16.228  4198  4198 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:16.228  4198  4232 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 11:37:16.230  4198  4198 V BluetoothAdapterState: isTurningOff()=false
,08-30 11:37:16.230  4198  4198 V BluetoothAdapterState: isTurningOn()=true
,08-30 11:37:16.230  4198  4198 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 11:37:16.230  4198  4198 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:16.230  4198  4198 V BluetoothAdapterState: isTurningOff()=false
08-30 11:37:16.231  4198  4198 V BluetoothAdapterState: isTurningOn()=true
08-30 11:37:16.231  4198  4198 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:37:16.231  4198  4198 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:16.231  4198  4198 V BluetoothAdapterState: isTurningOff()=false
08-30 11:37:16.231  4198  4198 V BluetoothAdapterState: isTurningOn()=true
08-30 11:37:16.231  4198  4198 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:37:16.231  4198  4198 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:16.231  4198  4198 V BluetoothAdapterState: isTurningOff()=false
08-30 11:37:16.231  4198  4198 V BluetoothAdapterState: isTurningOn()=true
08-30 11:37:16.231  4198  4198 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:37:16.232  4198  4198 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:16.232  4198  4198 V BluetoothAdapterState: isTurningOff()=false
08-30 11:37:16.232  4198  4198 V BluetoothAdapterState: isTurningOn()=true
08-30 11:37:16.232  4198  4198 V BluetoothAdapterState: isBleTurningOn()=false
08-30 11:37:16.232  4198  4198 V BluetoothAdapterState: isBleTurningOff()=false
08-30 11:37:16.236  4198  4213 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 11:37:16.236  4198  4213 D BluetoothAdapterProperties: ScanMode =  20
08-30 11:37:16.236  4198  4213 D BluetoothAdapterProperties: State =  11
08-30 11:37:16.237  4198  4213 D BluetoothAdapterProperties: Setting state to 12
08-30 11:37:16.237  4198  4213 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 11:37:16.238  4198  4213 I BluetoothAdapterState: Entering OnState
08-30 11:37:16.238   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 11:37:16.239  1375  1386 D BluetoothPan: onBluetoothStateChange on: true
08-30 11:37:16.240  4198  4217 D BluetoothAdapterProperties: Scan Mode:21
,08-30 11:37:16.240  4198  4217 D BluetoothAdapterProperties: Discoverable Timeout:120,
08-30 11:37:16.242  3876  3887 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 11:37:16.244  1375  1375 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 11:37:16.244  1375  1375 D PanProfile: Bluetooth service connected
08-30 11:37:16.244  1375  1388 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 11:37:16.245  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:16.245  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:16.245  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:16.245  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:16.245  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:16.245  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:16.245  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:16.245  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:16.245  4198  4198 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 11:37:16.246  4198  4198 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 11:37:16.247  2003  2105 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 11:37:16.247  1375  1386 D BluetoothA2dp: onBluetoothStateChange: up=true,
08-30 11:37:16.248  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:16.249  4198  4198 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 11:37:16.251  3876  3888 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 11:37:16.251  4198  4198 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
08-30 11:37:16.253  4198  4198 D ObexServerSockets: Succeed to create listening sockets 
08-30 11:37:16.253  4198  4198 D ObexServerSockets0: startAccept()
08-30 11:37:16.253  4198  4198 D ObexServerSockets0: prepareForNewConnect()
08-30 11:37:16.256   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 11:37:16.257  3876  3887 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 11:37:16.257  4198  4198 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 11:37:16.257  4198  4198 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 11:37:16.258  3876  3888 D BluetoothPan: onBluetoothStateChange on: true
08-30 11:37:16.259  4198  4239 D ObexServerSockets0: Accepting socket connection...,
08-30 11:37:16.259  1375  1375 D BluetoothA2dp: Proxy object connected
08-30 11:37:16.260  4198  4240 D ObexServerSockets0: Accepting socket connection...
08-30 11:37:16.261  1375  1388 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 11:37:16.263  3876  3887 D BluetoothMap: onBluetoothStateChange: up=true,
,08-30 11:37:16.263  1375  1375 D BluetoothInputDevice: Proxy object connected
,08-30 11:37:16.263  3876  3876 D BluetoothInputDevice: Proxy object connected
08-30 11:37:16.264  3876  3876 D HidProfile: Bluetooth service connected
08-30 11:37:16.263  1375  1375 D HidProfile: Bluetooth service connected
08-30 11:37:16.266   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 11:37:16.266  3876  3876 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 11:37:16.266  3876  3876 D PanProfile: Bluetooth service connected
08-30 11:37:16.266  3876  3876 D BluetoothMap: Proxy object connected
08-30 11:37:16.266  3876  3876 D MapProfile: Bluetooth service connected
08-30 11:37:16.266  3876  3876 D BluetoothMap: getConnectedDevices()
,08-30 11:37:16.267   874   874 D BluetoothA2dp: Proxy object connected
08-30 11:37:16.267  1375  2123 D BluetoothMap: onBluetoothStateChange: up=true
08-30 11:37:16.270  3876  4241 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 11:37:16.269  1375  1375 D BluetoothMap: Proxy object connected
,08-30 11:37:16.270  1375  1375 D MapProfile: Bluetooth service connected
08-30 11:37:16.270  1375  1375 D BluetoothMap: getConnectedDevices()
,08-30 11:37:16.272   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 11:37:16.272  3876  3876 D BluetoothA2dp: Proxy object connected
,08-30 11:37:16.272  1375  1386 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 11:37:16.276  4198  4198 D BluetoothMapService: onReceive
08-30 11:37:16.276  4198  4198 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:16.276   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 11:37:16.276  4198  4198 D BluetoothMapService: STATE_ON
,08-30 11:37:16.279  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:16.284  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 11:37:16.292  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 11:37:16.300  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,08-30 11:37:16.300  4198  4198 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 11:37:16.300  4198  4198 D ObexServerSockets0: prepareForNewConnect()
08-30 11:37:16.301  3876  3876 D BluetoothPbap: Proxy object connected
,08-30 11:37:16.301  3876  3876 D PbapServerProfile: Bluetooth service connected
,08-30 11:37:16.304  1375  1375 D BluetoothPbap: Proxy object connected
,08-30 11:37:16.304  1375  1375 D PbapServerProfile: Bluetooth service connected
,08-30 11:37:16.313  4198  4247 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 11:37:16.331  4198  4251 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 11:37:16.332  4198  4251 I BtOppRfcommListener: Accept thread started.
,08-30 11:37:16.341  2003  2014 D BluetoothHeadset: Proxy object connected
,08-30 11:37:16.342  1375  2123 D BluetoothHeadset: Proxy object connected
,08-30 11:37:16.342  1375  1375 D HeadsetProfile: Bluetooth service connected
08-30 11:37:16.342   874   874 D BluetoothHeadset: Proxy object connected
,08-30 11:37:16.342   874   874 D BluetoothHeadset: Proxy object connected
,08-30 11:37:16.342   874   874 D BluetoothHeadset: Proxy object connected
08-30 11:37:16.343  3876  3888 D BluetoothHeadset: Proxy object connected
08-30 11:37:16.343  3876  3876 D HeadsetProfile: Bluetooth service connected
,08-30 11:37:16.348  2003  2242 D BluetoothHeadset: Proxy object connected
,08-30 11:37:16.356   874   891 D BluetoothHeadset: Proxy object connected
,08-30 11:37:16.358  3876  3887 D BluetoothHeadset: Proxy object connected
,08-30 11:37:16.358  3876  3876 D HeadsetProfile: Bluetooth service connected
,08-30 11:37:16.373   874   891 D BluetoothHeadset: Proxy object connected
,08-30 11:37:16.373  1375  1388 D BluetoothHeadset: Proxy object connected
08-30 11:37:16.373  1375  1375 D HeadsetProfile: Bluetooth service connected
,08-30 11:37:16.630  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:16.630  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:16.630  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:16.630  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:16.630  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:16.630  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:16.630  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:16.630  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:16.637  3807  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:16.642  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:16.642  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@912e056 added. We now have 8 listener(s)
,08-30 11:37:16.642  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:37:16.648   874  2019 D WifiService: setWifiEnabled: false pid=3807, uid=10000
,08-30 11:37:16.648   874  2019 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 11:37:16.661  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:16.662   874  1401 D WifiService: setWifiEnabled: true pid=3807, uid=10000
,08-30 11:37:16.662   874  1401 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 11:37:16.675   874  1317 D WifiConfigStore: Loading config and enabling all networks 
,08-30 11:37:16.693  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:16.693  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:16.693  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:16.693  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:16.693  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:16.693  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:16.693  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:16.693  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:16.700  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:16.705   874  1317 D WifiConfigStore: loaded 0 passpoint configs
,08-30 11:37:16.707   874  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 11:37:16.708   874  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 11:37:16.709   874  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 11:37:16.709   874  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 11:37:16.710   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 11:37:16.710   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 11:37:16.726   874  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.07 rxSuccessRate=0.06 delta 1000 -> 1000
,08-30 11:37:16.726   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-30 11:37:16.726   874  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 11:37:16.728   373   872 D CommandListener: Setting iface cfg
,08-30 11:37:16.729   874  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
,08-30 11:37:16.729   874  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 11:37:16.736   874  1317 E native  : do suspend true
,08-30 11:37:16.747   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-30 11:37:16.747   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 11:37:16.748   874  1316 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 11:37:16.756   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 11:37:16.757   874  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 11:37:16.835   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 11:37:16.838  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 11:37:17.294  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 11:37:17.348  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 11:37:17.348  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 11:37:17.360   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 11:37:17.370   874  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 11:37:17.371   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 11:37:17.371   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 11:37:17.392   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 11:37:17.404   373   872 D CommandListener: Setting iface cfg
,08-30 11:37:17.406   874  1317 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 11:37:17.413   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 11:37:17.426   874  4259 D DhcpClient: Receive thread started
,08-30 11:37:17.513   874  1317 E native  : do suspend false
,08-30 11:37:17.532   874  2114 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 11:37:17.548   874  4259 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-30 11:37:17.551   874  2114 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-30 11:37:17.555   874  2114 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 11:37:17.585   874  4259 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 11:37:17.587   874  2114 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 11:37:17.592   373   872 D CommandListener: Setting iface cfg
,08-30 11:37:17.596   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 11:37:17.598   874  1317 E native  : do suspend true
,08-30 11:37:17.600   874  2114 D DhcpClient: Scheduling renewal in 86399s
,08-30 11:37:17.618   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-30 11:37:17.619   874  1317 D WifiConfigStore: No blacklist allowed without epno enabled
08-30 11:37:17.620   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 11:37:17.622   874  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 11:37:17.622   874  1319 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 11:37:17.667   874  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 11:37:17.668   874  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 11:37:17.669   874  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 11:37:17.670   874  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 11:37:17.670   874  1319 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1],
,08-30 11:37:17.679   874  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 11:37:17.681  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:17.681  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:17.681  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:17.681  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:17.681  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:17.681  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:17.681  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:17.681  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:17.683  3807  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:17.686   874  1319 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 11:37:17.686   874  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-30 11:37:17.686   874  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-30 11:37:17.686   874  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 11:37:17.686   874  1319 D ConnectivityService:    accepting network in place of null
,08-30 11:37:17.687   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 11:37:17.688  3807  3857 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-30 11:37:17.688   874  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 11:37:17.688  3807  3857 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 11:37:17.690  3807  3857 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d59ab79 Bundle[{}]
08-30 11:37:17.691  3807  3857 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 11:37:17.691  3807  3857 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 11:37:17.692  3807  3857 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 11:37:17.692  3807  3857 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 11:37:17.693  3807  3857 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 11:37:17.694  3807  3857 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 11:37:17.698  3807  3857 I System.out: Running OutgoingSocketThread
08-30 11:37:17.700  3807  4264 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 416)
,08-30 11:37:17.702  3807  4264 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37657
,08-30 11:37:17.702  3807  4264 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 11:37:17.717   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 11:37:17.743   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 11:37:17.746   874  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-30 11:37:17.747   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:17.748   874  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-30 11:37:17.750   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-30 11:37:17.760  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:17.760  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:17.760  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:17.760  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:17.760  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:17.760  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:17.760  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:37:17.760  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:37:17.764  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:37:17.769  2090  2090 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-30 11:37:17.774  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 11:37:17.783  1713  1713 D SystemUpdateService: onCreate
,08-30 11:37:17.788  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 11:37:17.794  1713  4271 I SystemUpdateService: active receiver: enabled
,08-30 11:37:17.806  1713  4271 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 11:37:17.810  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 11:37:17.815  1713  2509 I iu.UploadsManager: num queued entries: 0
,08-30 11:37:17.816  1713  2509 I iu.UploadsManager: num updated entries: 0
08-30 11:37:17.817  1713  2509 I iu.SyncManager: NEXT; no task
,08-30 11:37:17.818  1713  4271 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 11:37:17.819  1713  4271 I SystemUpdateService: now status is 0 (complete)
08-30 11:37:17.819  1713  4271 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 11:37:17.819  1713  4271 I SystemUpdateService: file has been verified
,08-30 11:37:17.824  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 11:37:17.824  1713  4271 I SystemUpdateService: OTA package size = 12249756
,08-30 11:37:17.828  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 11:37:17.833  1713  4274 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 11:37:17.834  1713  4274 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 11:37:17.837  1713  4274 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 11:37:17.839  1713  4271 I SystemUpdateService: showing system update notification
,08-30 11:37:17.842  3968  3968 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:37:17.849  3968  3968 D SprintDMHelper: simOperator: 
,08-30 11:37:17.849  3968  3968 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 11:37:17.855  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 11:37:17.859  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 11:37:17.872  1713  1713 D SystemUpdateService: onDestroy
,08-30 11:37:17.927  1505  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-30 11:37:17.927  1505  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 11:37:17.928  1505  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 11:37:17.928  1505  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 11:37:17.948  1713  4274 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-30 11:37:18.701  3807  3857 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 417)
,08-30 11:37:18.702  3807  3857 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 417)
,08-30 11:37:18.715  3807  3857 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
,08-30 11:37:18.719  3807  3857 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 11:37:18.719  3807  3857 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 423)
,08-30 11:37:18.724   874  4258 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155211, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 11:37:18.727  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 11:37:18.727  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e7e8d7 added. We now have 2 listener(s)
08-30 11:37:18.729  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 11:37:18.729  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:18.730  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.730  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.730  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f9d5c4 added. We now have 9 listener(s)
08-30 11:37:18.730  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.730  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 11:37:18.736  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-30 11:37:18.745  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-30 11:37:18.745  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:18.745  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:18.745  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:18.745  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:18.745  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:18.745  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:37:18.745  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:37:18.747   874  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-30 11:37:18.750  3807  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:18.750  3807  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:37:18.750  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:18.750  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4abe2 added. We now have 3 listener(s)
08-30 11:37:18.752  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 11:37:18.752  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:18.752  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.752  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.753  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e583b73 added. We now have 10 listener(s)
08-30 11:37:18.753  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.753  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:37:18.753  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:18.753  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:37:18.753  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:18.753  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.753  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:18.753  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:18.753  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e7e8d7 removed from the list
08-30 11:37:18.754  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.754  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f9d5c4 removed from the list
08-30 11:37:18.755  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:18.760  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:18.761  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:18.761  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:18.762  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.762  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:18.765  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 11:37:18.765  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:37:18.765  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.765  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f9d5c4 not in the list
08-30 11:37:18.766  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:37:18.766  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.768  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:18.768  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.768  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.768  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e583b73 removed from the list
08-30 11:37:18.768  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 11:37:18.768  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.768  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:18.768  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 11:37:18.768  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4abe2 removed from the list
,08-30 11:37:18.769  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:18.769  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba08a30 added. We now have 2 listener(s)
08-30 11:37:18.771  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 11:37:18.771  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:18.771  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.772  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 11:37:18.772  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e95a6a9 added. We now have 9 listener(s)
08-30 11:37:18.772  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.772  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 11:37:18.776  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:18.783  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:37:18.783  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:18.783  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:18.783  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:18.783  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:18.783  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:18.783  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:37:18.783  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:37:18.787  3807  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:37:18.787  3807  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:37:18.788  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 11:37:18.789  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e711bcf added. We now have 3 listener(s)
,08-30 11:37:18.792  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:18.794  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 11:37:18.794  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:18.795  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 11:37:18.795  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.795  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbc195c added. We now have 10 listener(s)
08-30 11:37:18.796  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:37:18.796  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:37:18.797  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:37:18.797  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-30 11:37:18.797  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:18.797  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 11:37:18.798  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:18.804  3807  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 11:37:18.804  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 11:37:18.809  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 11:37:18.810  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 11:37:18.810  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-30 11:37:18.816  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 11:37:18.816  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 11:37:18.817  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 11:37:18.818  3807  3857 D BluetoothAdapter: STATE_ON
,08-30 11:37:18.822  4198  4208 D BtGatt.GattService: registerClient() - UUID=b530aaeb-76d3-4d4e-8bed-daf97fdd3d1b
,08-30 11:37:18.823  4198  4217 D BtGatt.GattService: onClientRegistered() - UUID=b530aaeb-76d3-4d4e-8bed-daf97fdd3d1b, clientIf=5,
,08-30 11:37:18.823  3807  3819 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 11:37:18.826  4198  4243 D BtGatt.GattService: start scan with filters
,08-30 11:37:18.834  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 11:37:18.834  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 11:37:18.834  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 11:37:18.834  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 11:37:18.835  4198  4222 D BtGatt.ScanManager: handling starting scan
,08-30 11:37:18.838  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:37:18.838  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 11:37:18.839  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 11:37:18.840  4198  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@388447d
08-30 11:37:18.840  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 11:37:18.845  3807  3857 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 11:37:18.845  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:37:18.845  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 11:37:18.845  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.846  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 11:37:18.847  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 11:37:18.847  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 11:37:18.847  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 11:37:18.847  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 11:37:18.847  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 11:37:18.847  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 11:37:18.848  4198  4217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 11:37:18.848  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:37:18.849  3807  3857 D BluetoothAdapter: STATE_ON
,08-30 11:37:18.850  4198  4222 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 11:37:18.851  4198  4208 D BtGatt.GattService: stopScan() - queue size =1
,08-30 11:37:18.854  4198  4243 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 11:37:18.855  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 11:37:18.855  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 11:37:18.856  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 11:37:18.856  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 11:37:18.856  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 11:37:18.858  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 11:37:18.859  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 11:37:18.859  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 11:37:18.859  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 11:37:18.860  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:18.863  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:37:18.864  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:37:18.864  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 11:37:18.866  4198  4217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 11:37:18.866  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:37:18.867  4198  4222 D BtGatt.ScanManager: Starting BLE batch scan
08-30 11:37:18.867  4198  4222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 11:37:18.868  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:37:18.868  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:18.869  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 11:37:18.870  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:18.871  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.871  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:18.871  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 11:37:18.871  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba08a30 removed from the list
08-30 11:37:18.872  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:37:18.872  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e95a6a9 removed from the list
08-30 11:37:18.872  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:18.872  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:18.874  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:37:18.874  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:18.875  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.875  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:37:18.876  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.876  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e95a6a9 not in the list
08-30 11:37:18.876  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.876  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:18.877  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:37:18.877  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.877  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.877  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbc195c removed from the list
08-30 11:37:18.878  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:18.878  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:37:18.878  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.878  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:18.878  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e711bcf removed from the list
08-30 11:37:18.879  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:18.879  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f6f48 added. We now have 2 listener(s)
,08-30 11:37:18.882  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 11:37:18.882  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 11:37:18.882  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.882  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.882  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17a81e1 added. We now have 9 listener(s)
,08-30 11:37:18.882  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.883  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 11:37:18.887  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:37:18.893  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:37:18.893  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:18.893  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:18.893  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:18.893  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:18.893  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:18.893  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:37:18.893  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:37:18.894  4198  4217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 11:37:18.894  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:37:18.896  3807  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:37:18.896  3807  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:37:18.896  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 11:37:18.896  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39eb5c7 added. We now have 3 listener(s)
,08-30 11:37:18.899  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:18.900  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 11:37:18.900  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 11:37:18.901  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.901  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.902  4198  4217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 11:37:18.902  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:37:18.903  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:18.903  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e037f4 added. We now have 10 listener(s)
08-30 11:37:18.903  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.903  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 11:37:18.904  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 11:37:18.905  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:37:18.905  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 11:37:18.905  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:18.905  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 11:37:18.911  3807  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 11:37:18.911  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 11:37:18.913  4198  4217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 11:37:18.913  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:37:18.914  4198  4222 D BtGatt.ScanManager: stopping BLe Batch
,08-30 11:37:18.916  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 11:37:18.917  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 11:37:18.917  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 11:37:18.920  4198  4217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 11:37:18.920  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:37:18.921  4198  4222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 11:37:18.922  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 11:37:18.923  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 11:37:18.923  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 11:37:18.924  3807  3857 D BluetoothAdapter: STATE_ON
,08-30 11:37:18.927  4198  4217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 11:37:18.927  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:37:18.927  4198  4231 D BtGatt.GattService: registerClient() - UUID=22a4ce4f-6271-4799-8f43-01287d94cf99
08-30 11:37:18.927  4198  4217 D BtGatt.GattService: onClientRegistered() - UUID=22a4ce4f-6271-4799-8f43-01287d94cf99, clientIf=5
08-30 11:37:18.927  3807  3819 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 11:37:18.928  4198  4209 D BtGatt.GattService: start scan with filters
,08-30 11:37:18.933  4198  4222 D BtGatt.ScanManager: handling starting scan
08-30 11:37:18.933  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 11:37:18.933  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 11:37:18.933  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 11:37:18.933  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 11:37:18.937  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:37:18.937  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 11:37:18.937  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:37:18.939  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 11:37:18.941  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 11:37:18.941  3807  3857 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 11:37:18.941  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:37:18.941  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:18.941  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 11:37:18.941  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:18.942  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.942  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 11:37:18.942  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 11:37:18.942  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f6f48 removed from the list
08-30 11:37:18.942  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.942  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17a81e1 removed from the list
08-30 11:37:18.942  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:18.942  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 11:37:18.943  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.943  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 11:37:18.943  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:37:18.943  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:18.944  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.944  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:37:18.944  4198  4217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 11:37:18.944  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.944  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:37:18.944  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17a81e1 not in the list
08-30 11:37:18.944  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 11:37:18.944  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 11:37:18.945  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 11:37:18.945  4198  4222 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 11:37:18.945  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 11:37:18.945  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 11:37:18.946  3807  3857 D BluetoothAdapter: STATE_ON
,08-30 11:37:18.947  4198  4209 D BtGatt.GattService: stopScan() - queue size =1
08-30 11:37:18.947  4198  4242 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 11:37:18.947  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:37:18.947  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
08-30 11:37:18.948  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 11:37:18.948  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 11:37:18.948  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 11:37:18.949  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:37:18.949  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 11:37:18.949  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-30 11:37:18.949  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 11:37:18.949  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:18.951  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:18.951  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.951  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:37:18.951  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:37:18.951  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e037f4 removed from the list
08-30 11:37:18.951  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 11:37:18.951  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.951  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:37:18.951  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 11:37:18.951  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:18.951  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39eb5c7 removed from the list
,08-30 11:37:18.951  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:37:18.952  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:18.952  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc2df60 added. We now have 2 listener(s),
08-30 11:37:18.954  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 11:37:18.954  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 11:37:18.954  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 11:37:18.954  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.954  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3488c19 added. We now have 9 listener(s)
08-30 11:37:18.954  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:37:18.954  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 11:37:18.957  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:37:18.959  4198  4217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 11:37:18.959  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:37:18.959  4198  4222 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 11:37:18.960  4198  4222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 11:37:18.962  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:37:18.962  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:18.962  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:18.962  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:18.962  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:18.962  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:18.962  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:37:18.962  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:37:18.967  3807  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:37:18.967  3807  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:37:18.970  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 11:37:18.971  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 11:37:18.971  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab696bf added. We now have 3 listener(s)
08-30 11:37:18.972  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:18.972  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 11:37:18.973  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 11:37:18.973  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.973  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 11:37:18.973  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@866918c added. We now have 10 listener(s)
,08-30 11:37:18.973  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.973  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 11:37:18.973  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:37:18.973  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 11:37:18.973  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:37:18.973  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 11:37:18.977  3807  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 11:37:18.977  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 11:37:18.980  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 11:37:18.982  4198  4217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 11:37:18.982  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:37:18.983  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 11:37:18.983  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 11:37:18.987  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 11:37:18.987  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 11:37:18.988  3807  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 11:37:18.988  3807  3857 D BluetoothAdapter: STATE_ON
,08-30 11:37:18.990  4198  4217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 11:37:18.991  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:37:18.995  4198  4243 D BtGatt.GattService: registerClient() - UUID=74177623-4241-4b7d-9e83-9c1cca745f13
,08-30 11:37:18.996  4198  4217 D BtGatt.GattService: onClientRegistered() - UUID=74177623-4241-4b7d-9e83-9c1cca745f13, clientIf=5
,08-30 11:37:18.996  3807  3820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 11:37:18.996  4198  4231 D BtGatt.GattService: start scan with filters
,08-30 11:37:19.000  4198  4217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 11:37:19.000  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:37:19.001  4198  4222 D BtGatt.ScanManager: stopping BLe Batch
,08-30 11:37:19.003  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 11:37:19.003  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 11:37:19.003  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 11:37:19.003  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
08-30 11:37:19.005  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:37:19.006  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 11:37:19.006  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 11:37:19.007  4198  4217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
08-30 11:37:19.007  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:37:19.007  4198  4222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 11:37:19.008  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 11:37:19.013  4198  4217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 11:37:19.013  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:37:19.013  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 11:37:19.014  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:37:19.014  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 11:37:19.014  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 11:37:19.014  4198  4222 D BtGatt.ScanManager: handling starting scan
08-30 11:37:19.014  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:37:19.015  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 11:37:19.015  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:19.015  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc2df60 removed from the list
,08-30 11:37:19.015  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:19.015  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3488c19 removed from the list
,08-30 11:37:19.015  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:19.015  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:19.016  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:37:19.016  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 11:37:19.016  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:19.016  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 11:37:19.017  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:19.017  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:19.017  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 11:37:19.017  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3488c19 not in the list
08-30 11:37:19.017  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 11:37:19.017  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 11:37:19.017  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 11:37:19.018  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 11:37:19.018  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 11:37:19.018  3807  3857 D BluetoothAdapter: STATE_ON
,08-30 11:37:19.019  4198  4242 D BtGatt.GattService: stopScan() - queue size =1
08-30 11:37:19.019  4198  4243 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 11:37:19.020  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:37:19.020  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 11:37:19.020  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 11:37:19.020  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 11:37:19.020  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 11:37:19.021  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:37:19.021  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 11:37:19.021  3807  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-30 11:37:19.021  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 11:37:19.021  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:19.026  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:37:19.026  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 11:37:19.027  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:37:19.027  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:37:19.027  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:19.027  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:19.027  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@866918c removed from the list
,08-30 11:37:19.027  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:19.027  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:37:19.027  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:19.027  4198  4217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 11:37:19.027  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:19.027  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:37:19.028  4198  4222 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 11:37:19.027  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab696bf removed from the list
08-30 11:37:19.028  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:19.028  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b13a78 added. We now have 2 listener(s)
08-30 11:37:19.030  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 11:37:19.030  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:19.030  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:19.030  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:19.030  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@416a551 added. We now have 9 listener(s)
08-30 11:37:19.031  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:19.031  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 11:37:19.034  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:19.039  4198  4217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 11:37:19.039  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:37:19.039  4198  4222 D BtGatt.ScanManager: Starting BLE batch scan
08-30 11:37:19.039  4198  4222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 11:37:19.041  3807  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:37:19.041  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:19.041  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:19.041  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:19.041  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:19.041  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:19.041  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:37:19.041  3807  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:37:19.043  3807  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:19.043  3807  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:37:19.043  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:19.044  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fda9eb7 added. We now have 3 listener(s)
08-30 11:37:19.045  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 11:37:19.046  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:19.047  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:19.047  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:19.047  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4fb8624 added. We now have 10 listener(s)
08-30 11:37:19.047  3807  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:19.047  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:19.047  3807  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:37:19.047  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:19.047  3807  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:37:19.048  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:19.048  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:19.048  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:19.048  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:19.048  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b13a78 removed from the list
08-30 11:37:19.048  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:19.048  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@416a551 removed from the list
08-30 11:37:19.051  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:19.051  3807  3857 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:19.051  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:19.051  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:37:19.051  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:19.053  4198  4217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 11:37:19.053  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:37:19.057  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:19.057  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-30 11:37:19.057  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:19.057  3807  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@416a551 not in the list
08-30 11:37:19.057  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:19.057  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:19.058  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:19.058  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 11:37:19.058  3807  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:19.058  3807  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4fb8624 removed from the list
08-30 11:37:19.058  3807  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:19.058  3807  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:19.058  3807  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:19.058  3807  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:19.058  3807  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fda9eb7 removed from the list
,08-30 11:37:19.059  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 11:37:19.060  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 11:37:19.060  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 11:37:19.060  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 11:37:19.060  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 11:37:19.060  3807  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:37:19.065  3807  4280 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: My test thread name)
,08-30 11:37:19.066  3807  4280 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: My test thread name)
,08-30 11:37:19.066  3807  4280 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 11:37:19.069  4198  4217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 11:37:19.069  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:37:19.070  3807  4281 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: My test thread name)
,08-30 11:37:19.071  3807  4281 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: My test thread name)
,08-30 11:37:19.071  3807  4281 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 11:37:19.074  3807  3857 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-30 11:37:19.074  3807  3857 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 11:37:19.074  3807  3857 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 11:37:19.074  3807  3857 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 11:37:19.074  3807  3857 D com.test.thalitest.ThaliTestRunner: Total duration: 22880 ms
,08-30 11:37:19.076  3807  3857 I jxcore-log: *Native tests were executed*
08-30 11:37:19.076  3807  3857 I jxcore-log: 
08-30 11:37:19.077  3807  3857 I jxcore-log: Total number of executed tests:  80
08-30 11:37:19.077  3807  3857 I jxcore-log: 
08-30 11:37:19.077  3807  3857 I jxcore-log: Number of passed tests:  80
08-30 11:37:19.077  3807  3857 I jxcore-log: 
08-30 11:37:19.077  3807  3857 I jxcore-log: Number of failed tests:  0
08-30 11:37:19.077  3807  3857 I jxcore-log: 
,08-30 11:37:19.077  3807  3857 I jxcore-log: Number of ignored tests:  0
08-30 11:37:19.077  3807  3857 I jxcore-log: 
,08-30 11:37:19.078  3807  3857 I jxcore-log: Total duration:  22880
08-30 11:37:19.078  3807  3857 I jxcore-log: 
08-30 11:37:19.079  4198  4217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 11:37:19.079  3807  3857 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 11:37:19.079  3807  3857 I jxcore-log: 
08-30 11:37:19.079  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:37:19.079  4198  4222 D BtGatt.ScanManager: stopping BLe Batch
08-30 11:37:19.086  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.086  3807  3857 I jxcore-log: 
08-30 11:37:19.087  3807  3807 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 11:37:19.090  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.090  3807  3857 I jxcore-log: 
08-30 11:37:19.091  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.091  3807  3857 I jxcore-log: 
08-30 11:37:19.092  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.092  3807  3857 I jxcore-log: 
08-30 11:37:19.093  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.093  3807  3857 I jxcore-log: 
08-30 11:37:19.095  4198  4217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 11:37:19.095  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 11:37:19.095  4198  4222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 11:37:19.095  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.095  3807  3857 I jxcore-log: 
08-30 11:37:19.098  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.098  3807  3857 I jxcore-log: 
,08-30 11:37:19.100  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 11:37:19.100  3807  3857 I jxcore-log: 
,08-30 11:37:19.102  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 11:37:19.102  3807  3857 I jxcore-log: 
08-30 11:37:19.103  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 11:37:19.103  3807  3857 I jxcore-log: 
08-30 11:37:19.104  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 11:37:19.104  3807  3857 I jxcore-log: 
08-30 11:37:19.105  4198  4217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 11:37:19.105  4198  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 11:37:19.107  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 11:37:19.107  3807  3857 I jxcore-log: 
,08-30 11:37:19.110  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 11:37:19.110  3807  3857 I jxcore-log: 
,08-30 11:37:19.113  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 11:37:19.113  3807  3857 I jxcore-log: 
,08-30 11:37:19.116  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.116  3807  3857 I jxcore-log: 
,08-30 11:37:19.118  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.118  3807  3857 I jxcore-log: 
,08-30 11:37:19.124  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 11:37:19.124  3807  3857 I jxcore-log: 
,08-30 11:37:19.126  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 11:37:19.126  3807  3857 I jxcore-log: 
,08-30 11:37:19.127  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 11:37:19.127  3807  3857 I jxcore-log: 
,08-30 11:37:19.129  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 11:37:19.129  3807  3857 I jxcore-log: 
,08-30 11:37:19.130  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 11:37:19.130  3807  3857 I jxcore-log: 
,08-30 11:37:19.132  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 11:37:19.132  3807  3857 I jxcore-log: 
,08-30 11:37:19.133  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 11:37:19.133  3807  3857 I jxcore-log: 
,08-30 11:37:19.135  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 11:37:19.135  3807  3857 I jxcore-log: 
,08-30 11:37:19.137  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 11:37:19.137  3807  3857 I jxcore-log: 
,08-30 11:37:19.138  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 11:37:19.138  3807  3857 I jxcore-log: 
,08-30 11:37:19.140  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 11:37:19.140  3807  3857 I jxcore-log: 
,08-30 11:37:19.141  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 11:37:19.141  3807  3857 I jxcore-log: 
,08-30 11:37:19.143  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.143  3807  3857 I jxcore-log: 
,08-30 11:37:19.144  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.144  3807  3857 I jxcore-log: 
,08-30 11:37:19.144  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.144  3807  3857 I jxcore-log: 
,08-30 11:37:19.145  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.145  3807  3857 I jxcore-log: 
,08-30 11:37:19.146  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.146  3807  3857 I jxcore-log: 
,08-30 11:37:19.146  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:19.146  3807  3857 I jxcore-log: 
,08-30 11:37:19.365  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 11:37:19.369  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 11:37:19.369  3807  3857 I jxcore-log: 
,08-30 11:37:19.430   874  4257 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 11:37:19.451  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 11:37:19.454  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 11:37:19.454  3807  3857 I jxcore-log: 
,08-30 11:37:19.527  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 11:37:19.528  3807  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-30 11:37:19.528  3807  3857 I jxcore-log: 
,08-30 11:37:19.769  4283  4283 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 11:37:19.774  4283  4283 D AndroidRuntime: CheckJNI is OFF
,08-30 11:37:19.797  1853  2676 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 11:37:19.817  4283  4283 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 11:37:19.865  4283  4283 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 11:37:19.888  4283  4283 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 11:37:19.901   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-30 11:37:19.902   874   887 I ActivityManager: Killing 3807:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 11:37:19.926  2167  4276 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 11:37:19.988   874  1387 D GraphicsStats: Buffer count: 2
,08-30 11:37:19.988   874  1387 I WindowState: WIN DEATH: Window{a316296 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 11:37:19.990   874  1318 D WifiService: Client connection lost with reason: 4
,08-30 11:37:20.029   874   897 W PackageSettings: Skipping PackageSetting{bf65cb6 com.example.hello/10273} due to missing metadata
,08-30 11:37:20.065   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-30 11:37:20.065   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-30 11:37:20.067   874   897 I art     : Starting a blocking GC Explicit
,08-30 11:37:20.068   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-30 11:37:20.068   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 11:37:20.068   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:20.068   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:37:20.068   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 11:37:20.068   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 11:37:20.069   874   887 I ActivityManager:   Force finishing activity ActivityRecord{c7403f u0 com.test.thalitest/.MainActivity t2}
,08-30 11:37:20.084   874  1979 W ActivityManager: Spurious death for ProcessRecord{be7552f 0:com.test.thalitest/u0a0}, curProc for 3807: null
,08-30 11:37:20.122   874   897 I art     : Explicit concurrent mark sweep GC freed 13900(958KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 949us total 55.431ms
,08-30 11:37:20.155   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 11:37:20.161  4283  4283 I art     : System.exit called, status: 0
,08-30 11:37:20.162  4283  4283 I AndroidRuntime: VM exiting with result code 0.
,08-30 11:37:20.172   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 11:37:20.190   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 11:37:20.198  1853  2204 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 11:37:20.198   874  1309 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 11:37:20.201  4198  4198 D BluetoothMapAppObserver: onReceive
08-30 11:37:20.201  4198  4198 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-30 11:37:20.203  3676  3676 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-30 11:37:20.207  1900  1900 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 11:37:20.255  2003  2003 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 11:37:20.256  1900  4297 I Keyboard.Facilitator.DecoderInitializer: run()
08-30 11:37:20.257  1900  4297 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-30 11:37:20.257  1900  4297 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-30 11:37:20.257  1900  4297 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-30 11:37:20.257  1900  4297 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-30 11:37:20.257  1900  4297 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-30 11:37:20.257  1900  4297 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-30 11:37:20.259  1900  4297 I Decoder : createOrResetDecoder
,08-30 11:37:20.260   874  1315 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-30 11:37:20.264   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 11:37:20.274   874  1979 I ActivityManager: Start proc 4298:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-30 11:37:20.297  1505  1505 I ConfigService: onCreate,
,08-30 11:37:20.301  1505  4310 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 11:37:20.301  1505  4310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 11:37:20.301  1505  4310 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-30 11:37:20.303  1505  4310 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-30 11:37:20.311  4298  4298 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 11:37:20.315  1900  4297 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 11:37:20.320   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-30 11:37:20.320   874   886 E PackageManager: Failed to write settings, restoring backup,
08-30 11:37:20.320   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 11:37:20.320   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 11:37:20.320   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 11:37:20.320   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 11:37:20.320   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 11:37:20.320   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:20.320   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:37:20.320   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 11:37:20.333   874  2051 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3807 uid 10000
,08-30 11:37:20.334  2016  2116 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-30 11:37:20.335   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-30 11:37:20.335   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328),
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 11:37:20.335   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 11:37:20.335   874   887 E DropBoxManagerService: 	... 13 more
08-30 11:37:20.335  1900  1900 I Keyboard.Facilitator: onFinishInput()
,08-30 11:37:20.347   874  1971 I ActivityManager: Start proc 4311:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-30 11:37:20.348  2016  2116 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 11:37:20.348  2016  2116 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2016
08-30 11:37:20.348  2016  2116 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 11:37:20.348  2016  2116 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 11:37:20.348  2016  2116 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 11:37:20.348  2016  2116 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 11:37:20.348  2016  2116 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 11:37:20.348  2016  2116 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 11:37:20.348  2016  2116 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 11:37:20.348  2016  2116 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 11:37:20.348  2016  2116 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 11:37:20.348  2016  2116 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 11:37:20.348  2016  2116 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:37:20.348  2016  2116 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 11:37:20.350   874  1689 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 11:37:20.352   874  4317 E DropBoxManagerService: Can't write: system_app_crash
08-30 11:37:20.352   874  4317 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-30 11:37:20.352   874  4317 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 11:37:20.352   874  4317 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 11:37:20.352   874  4317 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 11:37:20.352   874  4317 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 11:37:20.352   874  4317 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 11:37:20.352   874  4317 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 11:37:20.352   874  4317 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 11:37:20.352   874  4317 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 11:37:20.352   874  4317 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 11:37:20.352   874  4317 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 11:37:20.352   874  4317 E DropBoxManagerService: 	... 5 more
08-30 11:37:20.359  2016  2116 I Process : Sending signal. PID: 2016 SIG: 9
08-30 11:37:20.375  1900  4297 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-30 11:37:20.377  1900  4297 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-30 11:37:20.377  1900  4297 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-30 11:37:20.379  1900  4297 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-30 11:37:20.379  1900  4297 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-30 11:37:20.380  1900  4297 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-30 11:37:20.380  1900  4297 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 11:37:20.380  1900  4297 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 11:37:20.380  1900  4297 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-30 11:37:20.380  1900  4297 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-30 11:37:20.381  1900  4297 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 11:37:20.381  1900  4297 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 11:37:20.381  1900  4297 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 11:37:20.402  4298  4298 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 11:37:20.417  4298  4325 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:37:20.417  4298  4325 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:37:20.417  4298  4325 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 11:37:20.421   874  2019 I ActivityManager: Start proc 4330:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-30 11:37:20.425   874  1689 D GraphicsStats: Buffer count: 1
,08-30 11:37:20.425   874  1971 I WindowState: WIN DEATH: Window{22b2273 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-30 11:37:20.436   874  2013 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2016) has died
,08-30 11:37:20.436   874  2013 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-30 11:37:20.438   874  2013 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 11:37:20.447  4298  4328 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 11:37:20.455   874   887 I ActivityManager: Start proc 4342:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 11:37:20.477  4330  4330 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-30 11:37:20.507  1505  1505 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-30 11:37:20.507  1505  1505 D AndroidRuntime: Shutting down VM
08-30 11:37:20.508  1505  1505 E AndroidRuntime: FATAL EXCEPTION: main
08-30 11:37:20.508  1505  1505 E AndroidRuntime: Process: com.google.process.gapps, PID: 1505
,08-30 11:37:20.508  1505  1505 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 11:37:20.508  1505  1505 E AndroidRuntime: 	... 8 more
,08-30 11:37:20.511  1505  1505 I Process : Sending signal. PID: 1505 SIG: 9
,08-30 11:37:20.513   874  4358 E DropBoxManagerService: Can't write: system_app_crash
08-30 11:37:20.513   874  4358 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-30 11:37:20.513   874  4358 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 11:37:20.513   874  4358 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 11:37:20.513   874  4358 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 11:37:20.513   874  4358 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 11:37:20.513   874  4358 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 11:37:20.513   874  4358 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 11:37:20.513   874  4358 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 11:37:20.513   874  4358 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 11:37:20.513   874  4358 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 11:37:20.513   874  4358 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 11:37:20.513   874  4358 E DropBoxManagerService: 	... 5 more
,08-30 11:37:20.518  4342  4342 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 11:37:20.518  4342  4342 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 11:37:20.519  4342  4342 D AndroidRuntime: Shutting down VM
,08-30 11:37:20.526  4342  4342 E AndroidRuntime: FATAL EXCEPTION: main
08-30 11:37:20.526  4342  4342 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4342
08-30 11:37:20.526  4342  4342 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 11:37:20.526  4342  4342 E AndroidRuntime: 	... 10 more
08-30 11:37:20.528   874  2019 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 11:37:20.528  4342  4342 I Process : Sending signal. PID: 4342 SIG: 9
08-30 11:37:20.529   874  4360 E DropBoxManagerService: Can't write: system_app_crash
08-30 11:37:20.529   874  4360 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-30 11:37:20.529   874  4360 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 11:37:20.529   874  4360 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 11:37:20.529   874  4360 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 11:37:20.529   874  4360 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 11:37:20.529   874  4360 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 11:37:20.529   874  4360 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 11:37:20.529   874  4360 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 11:37:20.529   874  4360 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 11:37:20.529   874  4360 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 11:37:20.529   874  4360 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 11:37:20.529   874  4360 E DropBoxManagerService: 	... 5 more
08-30 11:37:20.553  4298  4325 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-30 11:37:20.557  4298  4328 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:37:20.557  4298  4328 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 11:37:20.558  4298  4328 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 11:37:20.558  4298  4328 E AndroidRuntime: Process: android.process.acore, PID: 4298
08-30 11:37:20.558  4298  4328 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 11:37:20.558  4298  4328 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 11:37:20.559  4298  4325 I Process : Sending signal. PID: 4298 SIG: 9
,08-30 11:37:20.569   874  1318 D WifiService: Client connection lost with reason: 4
,08-30 11:37:20.569   874  1689 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4342) has died
,08-30 11:37:20.570  1713  4356 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@a9810bf
,08-30 11:37:20.571   874  1689 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 11:37:20.575   279   279 E lowmemorykiller: Error writing /proc/4298/oom_score_adj; errno=22
,08-30 11:37:20.576   874   884 I ActivityManager: Process com.google.process.gapps (pid 1505) has died
,08-30 11:37:20.576   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-30 11:37:20.576   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 11000ms
08-30 11:37:20.576   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms,
,08-30 11:37:20.576   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 31000ms
,08-30 11:37:20.577   279   279 E lowmemorykiller: Error writing /proc/4298/oom_score_adj; errno=22
08-30 11:37:20.580   874  4362 E DropBoxManagerService: Can't write: system_app_crash
08-30 11:37:20.580   874  4362 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-30 11:37:20.580   874  4362 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 11:37:20.580   874  4362 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 11:37:20.580   874  4362 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 11:37:20.580   874  4362 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 11:37:20.580   874  4362 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 11:37:20.580   874  4362 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 11:37:20.580   874  4362 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 11:37:20.580   874  4362 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 11:37:20.580   874  4362 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 11:37:20.580   874  4362 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 11:37:20.580   874  4362 E DropBoxManagerService: 	... 5 more
,08-30 11:37:20.585  1713  1713 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-30 11:37:20.589   874   887 I ActivityManager: Start proc 4363:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 11:37:20.608   874  1401 I ActivityManager: Start proc 4374:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-30 11:37:20.609   874   885 I ActivityManager: Process android.process.acore (pid 4298) has died
,08-30 11:37:20.610   874   885 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40966ms
,08-30 11:37:20.645  4374  4374 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 11:37:20.646   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
