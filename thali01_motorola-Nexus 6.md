#### Test 81418577b3d8250_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-26 11:20:15.341  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 11:20:15.351  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 11:20:15.355  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 11:20:15.395  1510  3717 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-26 11:20:15.395  1510  3717 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 11:20:15.396  1510  3717 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 11:20:15.396  1510  3717 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 11:20:15.423  3606  3606 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-26 11:20:15.423  3606  3606 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 11:20:15.424  3606  3606 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-26 11:20:15.951  3874  3874 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 11:20:15.956  3874  3874 D AndroidRuntime: CheckJNI is OFF
08-26 11:20:15.998  3874  3874 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 11:20:16.048  3874  3874 I Radio-JNI: register_android_hardware_Radio DONE
08-26 11:20:16.070  3874  3874 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 11:20:16.076   872  2003 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 11:20:16.120  2036  3835 W SearchService: Abort, client detached.
08-26 11:20:16.134  2036  2036 I HotwordDetector: Closing mic
08-26 11:20:16.134  2036  2328 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@6fcd0ab
08-26 11:20:16.134  2036  2344 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-26 11:20:16.136  3874  3874 D AndroidRuntime: Shutting down VM
08-26 11:20:16.161   872  1965 I ActivityManager: Start proc 3883:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-26 11:20:16.188   375  2347 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 11:20:16.190   375  2347 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-26 11:20:16.193   375  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-26 11:20:16.194  2036  2334 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-26 11:20:16.194  2036  2342 I MicroRecognitionRnrImpl: Detection finished
08-26 11:20:16.241  3883  3883 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 11:20:16.243  1510  3103 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: mobilepersonalfeeds
08-26 11:20:16.243  1510  3103 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mobilepersonalfeeds without consulting the cloud.
08-26 11:20:16.243  1510  3103 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 11:20:16.243  1510  3103 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: User recoverable exception for scope: mobilepersonalfeeds
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-26 11:20:16.260  2036  2228 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-26 11:20:16.262  2036  2220 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 11:20:16.263  3883  3883 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 11:20:16.271  3883  3883 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 131-134)
08-26 11:20:16.271  3883  3883 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 11:20:16.283  3883  3883 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {acffc9f}
08-26 11:20:16.284  3883  3883 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 11:20:16.284  3883  3883 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 11:20:16.290  3883  3883 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 11:20:16.291  3883  3883 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 11:20:16.304  2036  2220 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 11:20:16.311  2036  2220 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 172-175)
08-26 11:20:16.311  2036  2220 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 11:20:16.312  3883  3883 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-26 11:20:16.322  3883  3883 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 11:20:16.322  3883  3883 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 11:20:16.322  3883  3883 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 11:20:16.322  3883  3883 I Adreno  : Build Date                       : 10/20/15
08-26 11:20:16.322  3883  3883 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 11:20:16.322  3883  3883 I Adreno  : Local Branch                     : M14
08-26 11:20:16.322  3883  3883 I Adreno  : Remote Branch                    : 
08-26 11:20:16.322  3883  3883 I Adreno  : Remote Branch                    : 
08-26 11:20:16.322  3883  3883 I Adreno  : Reconstruct Branch               : 
,08-26 11:20:16.385   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b3f9287:true
,08-26 11:20:16.409  3883  3883 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 11:20:16.421  3883  3883 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-26 11:20:16.489  3883  3934 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 11:20:16.497  3883  3915 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-26 11:20:16.535  3883  3934 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 11:20:16.595   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +449ms
,08-26 11:20:16.605  1876  1876 I Keyboard.Facilitator: onFinishInput()
,08-26 11:20:16.642  3883  3883 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3883
,08-26 11:20:16.732  3883  3883 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 11:20:16.969  3883  3939 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1680668368
,08-26 11:20:16.976  3883  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 11:20:16.976  3883  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 11:20:16.976  3883  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 11:20:16.976  3883  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 11:20:16.976  3883  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 11:20:16.976  3883  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@260f562 added. We now have 1 listener(s)
,08-26 11:20:16.980  3883  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-26 11:20:16.981  3883  3939 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 11:20:16.981  3883  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 11:20:16.981  3883  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 11:20:16.985  3883  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9f9e29 added. We now have 1 listener(s)
08-26 11:20:16.985  3883  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:16.988   872  1316 D WifiService: New client listening to asynchronous messages
,08-26 11:20:16.990  3883  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 11:20:16.990  3883  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-26 11:20:16.990  3883  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 11:20:16.990  3883  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 11:20:16.990  3883  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 11:20:16.995  3883  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 11:20:16.995  3883  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-26 11:20:17.005  3883  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 11:20:17.005  3883  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:17.005  3883  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:17.005  3883  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:17.005  3883  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:17.005  3883  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:17.005  3883  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:17.005  3883  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:17.005  3883  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 11:20:17.006  3883  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-26 11:20:17.006  3883  3939 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 11:20:17.009  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:17.010  3883  3939 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 11:20:17.012  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:17.185  3883  3883 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 11:20:17.274   872  1965 I ActivityManager: Killing 3131:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-26 11:20:17.342   872  1965 I ActivityManager: Killing 3193:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-26 11:20:17.763  3883  3947 W jxcore-log: Initializing JXcore engine
,08-26 11:20:17.763  3883  3947 W jxcore-log: JXcore engine is ready
,08-26 11:20:17.798  3947  3947 W Thread-345: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8986 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-26 11:20:17.798  3947  3947 W Thread-345: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12707]" dev="sockfs" ino=12707 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-26 11:20:17.798  3947  3947 W Thread-345: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-26 11:20:17.798  3947  3947 W Thread-345: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26032]" dev="sockfs" ino=26032 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-26 11:20:17.814  3883  3947 W jxcore-log: Starting JXcore engine
,08-26 11:20:17.897  3883  3947 W jxcore-log: Platform android
08-26 11:20:17.897  3883  3947 W jxcore-log: 
08-26 11:20:17.897  3883  3947 W jxcore-log: Process ARCH arm
08-26 11:20:17.897  3883  3947 W jxcore-log: 
,08-26 11:20:18.092  3883  3947 I jxcore-log: JXcore Cordova bridge is ready!
08-26 11:20:18.092  3883  3947 I jxcore-log: 
,08-26 11:20:18.093  3883  3947 W jxcore-log: JXcore engine is started
,08-26 11:20:18.099  3883  3939 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 11:20:18.104  3883  3883 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 11:20:19.854   872  1315 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-26 11:20:21.493   872  2141 D NetlinkSocketObserver: NeighborEvent{elapsedMs=125356, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 11:20:26.050  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 11:20:26.055  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 11:20:26.087  1510  2308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 11:20:26.087  1510  2308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-26 11:20:26.087  1510  2308 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 11:20:26.087  1510  2308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 11:20:26.108  3107  3958 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-26 11:20:26.108  3107  3958 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at jdm.a(PG:82)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at jcs.o(PG:406)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at jcn.a(PG:1379)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at jcs.i(PG:143)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at blb.a(PG:3937)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at czp.a(PG:18188)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at czp.a(PG:9081)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at czq.run(PG:1686)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 11:20:26.108  3107  3958 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at jdj.a(PG:4091)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at jdj.a(PG:1125)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at jdm.a(PG:77)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	... 12 more
08-26 11:20:26.108  3107  3958 E HttpOperation: Caused by: faj: BadAuthentication
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at fal.a(PG:38)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	at jdj.a(PG:4089)
08-26 11:20:26.108  3107  3958 E HttpOperation: 	... 14 more
,08-26 11:20:26.168  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 11:20:26.168  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-26 11:20:26.168  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 11:20:26.168  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 11:20:26.189  3107  3958 E HttpOperation: [getmobileexperiments] Unexpected exception
08-26 11:20:26.189  3107  3958 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at jdm.a(PG:82)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at jcs.o(PG:406)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at jcn.a(PG:1379)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at jcs.i(PG:143)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at hec.a(PG:42)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at hee.a(PG:102)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at czr.a(PG:65)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at kka.a(PG:108)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at czp.a(PG:19176)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at czp.a(PG:9081)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at czq.run(PG:1686)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 11:20:26.189  3107  3958 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at jdj.a(PG:4091)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at jdj.a(PG:1125)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at jdm.a(PG:77)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	... 15 more
08-26 11:20:26.189  3107  3958 E HttpOperation: Caused by: faj: BadAuthentication
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at fal.a(PG:38)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	at jdj.a(PG:4089)
08-26 11:20:26.189  3107  3958 E HttpOperation: 	... 17 more
,08-26 11:20:26.189  3107  3958 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-26 11:20:26.189  3107  3958 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at jdm.a(PG:82)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at jcs.o(PG:406)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at jcn.a(PG:1379)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at jcs.i(PG:143)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at hec.a(PG:42)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at hee.a(PG:102)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at czr.a(PG:65)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at kka.a(PG:108)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at czp.a(PG:19176)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at czp.a(PG:9081)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at czq.run(PG:1686)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at jdj.a(PG:4091)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at jdj.a(PG:1125)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at jdm.a(PG:77)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	... 15 more
08-26 11:20:26.189  3107  3958 E ExperimentLoader: Caused by: faj: BadAuthentication
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at fal.a(PG:38)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	at jdj.a(PG:4089)
08-26 11:20:26.189  3107  3958 E ExperimentLoader: 	... 17 more
,08-26 11:20:26.289   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129668, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-26 11:20:28.087  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 11:20:28.087  3883  3947 I jxcore-log: 
,08-26 11:20:28.089  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 11:20:28.089  3883  3947 I jxcore-log: 
,08-26 11:20:28.101  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:28.101  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:28.101  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:28.101  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:28.101  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:28.101  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:28.101  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:28.101  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 11:20:28.108  3883  3947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 11:20:28.110  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 11:20:28.110  3883  3947 I jxcore-log: 
,08-26 11:20:28.112  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 11:20:28.112  3883  3947 I jxcore-log: 
,08-26 11:20:28.617  3883  3947 D executeNativeTests: Running unit tests
,08-26 11:20:28.674  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:28.674  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 added. We now have 2 listener(s)
,08-26 11:20:28.676  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 11:20:28.676  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:28.676  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:28.676  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 11:20:28.676  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 added. We now have 2 listener(s)
08-26 11:20:28.676  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:28.676  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 11:20:28.679  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 11:20:28.686  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:28.686  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:28.686  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:28.686  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:28.686  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:28.686  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:28.686  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:28.686  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 11:20:28.690  3883  3947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:28.690  3883  3947 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 11:20:28.693  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 11:20:28.694  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 11:20:28.694  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
,08-26 11:20:28.695  3883  3947 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-26 11:20:28.696  3883  3947 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-26 11:20:28.696  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 11:20:28.696  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 11:20:28.696  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 11:20:28.697  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 11:20:28.697  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 11:20:28.697  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 11:20:28.697  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:28.697  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:28.697  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 11:20:28.697  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 11:20:28.698  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 removed from the list
08-26 11:20:28.698  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:28.698  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 removed from the list
08-26 11:20:28.698  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:28.700  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:28.700  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.701  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.702  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.702  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.706  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 11:20:28.707  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.707  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.708  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
,08-26 11:20:28.715  3883  3947 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 11:20:28.716  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 11:20:28.716  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.716  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 11:20:28.716  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.716  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:28.717  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.717  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.717  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:28.717  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.717  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.717  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:28.717  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.717  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:28.717  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.718  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:28.718  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.718  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:28.718  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.723  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 11:20:28.723  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 11:20:28.723  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 11:20:28.724  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 11:20:28.725  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 11:20:28.725  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 11:20:28.725  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 11:20:28.725  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 11:20:28.725  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 11:20:28.725  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 11:20:28.725  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 11:20:28.725  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 11:20:28.725  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 11:20:28.725  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 11:20:28.725  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.725  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.725  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:28.725  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.725  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.725  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.725  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.726  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.726  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.726  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.726  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.726  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.726  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.726  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.727  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:28.727  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.727  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.727  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.728  3883  3947 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 11:20:28.730  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:28.738  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:28.738  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:28.738  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:28.738  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:28.738  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:28.738  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:28.738  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:28.738  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:28.741  3883  3947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:28.742  3883  3947 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 11:20:28.742  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 11:20:28.743  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 11:20:28.743  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 11:20:28.743  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:28.743  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 11:20:28.744  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:28.745  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:28.752  3883  3947 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 11:20:28.752  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 11:20:28.764  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 11:20:28.767  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 11:20:28.768  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 11:20:28.770  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 11:20:28.772  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 11:20:28.772  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 11:20:28.772  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 11:20:28.773  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 11:20:28.774  3883  3947 D BluetoothAdapter: STATE_ON
,08-26 11:20:28.778  2696  2708 D BtGatt.GattService: registerClient() - UUID=acc1552d-bbbb-4dbb-8e0f-59a27a919832
08-26 11:20:28.780  2696  2733 D BtGatt.GattService: onClientRegistered() - UUID=acc1552d-bbbb-4dbb-8e0f-59a27a919832, clientIf=5
08-26 11:20:28.783  3883  3894 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 11:20:28.784  2696  2719 D BtGatt.GattService: start scan with filters
08-26 11:20:28.788  2696  2739 D BtGatt.ScanManager: handling starting scan
08-26 11:20:28.788  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 11:20:28.788  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 11:20:28.788  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 11:20:28.788  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 11:20:28.789  2696  2739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
08-26 11:20:28.792  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 11:20:28.793  3883  3883 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 11:20:28.794  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 11:20:28.796  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 11:20:28.796  2696  2733 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 11:20:28.796  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:28.797  2696  2739 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 11:20:28.800  3883  3947 I io.jxcore.node.ConnectionHelper: start: OK
08-26 11:20:28.804  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.804  2696  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 11:20:28.804  3883  3947 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 11:20:28.804  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:28.804  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.804  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 11:20:28.804  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.804  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 11:20:28.804  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 11:20:28.804  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 11:20:28.804  2696  2739 D BtGatt.ScanManager: Starting BLE batch scan
08-26 11:20:28.804  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 11:20:28.804  2696  2739 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 11:20:28.804  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 11:20:28.805  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 11:20:28.805  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 11:20:28.805  3883  3947 D BluetoothAdapter: STATE_ON
08-26 11:20:28.806  2696  2708 D BtGatt.GattService: stopScan() - queue size =1
08-26 11:20:28.808  2696  2719 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 11:20:28.809  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:28.809  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 11:20:28.809  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 11:20:28.809  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 11:20:28.809  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 11:20:28.812  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 11:20:28.813  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 11:20:28.813  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 11:20:28.813  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 11:20:28.813  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 11:20:28.815  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:28.816  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.816  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:28.816  3883  3883 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 11:20:28.816  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
,08-26 11:20:28.816  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.816  3883  3883 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 11:20:28.816  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.816  3883  3883 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 11:20:28.816  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.816  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.817  3883  3947 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 11:20:28.817  2696  2733 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 11:20:28.818  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:28.818  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:28.822  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:28.822  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:28.822  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:28.822  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:28.822  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:28.822  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:28.822  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:28.822  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:28.823  2696  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 11:20:28.823  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:28.826  3883  3947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:28.826  3883  3947 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 11:20:28.827  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 11:20:28.827  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 11:20:28.827  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 11:20:28.827  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:28.827  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 11:20:28.829  2696  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 11:20:28.829  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:28.829  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:28.830  2696  2739 D BtGatt.ScanManager: stopping BLe Batch
08-26 11:20:28.833  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:28.836  3883  3947 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 11:20:28.836  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 11:20:28.837  2696  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 11:20:28.837  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:28.837  2696  2739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 11:20:28.841  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 11:20:28.842  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 11:20:28.842  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 11:20:28.844  2696  2733 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 11:20:28.844  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:28.848  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 11:20:28.848  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 11:20:28.848  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 11:20:28.850  3883  3947 D BluetoothAdapter: STATE_ON
,08-26 11:20:28.853  2696  2719 D BtGatt.GattService: registerClient() - UUID=2d3b76eb-7c47-45c7-9748-e4ede503af9a
,08-26 11:20:28.853  2696  2733 D BtGatt.GattService: onClientRegistered() - UUID=2d3b76eb-7c47-45c7-9748-e4ede503af9a, clientIf=5
08-26 11:20:28.854  3883  3896 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 11:20:28.854  2696  2708 D BtGatt.GattService: start scan with filters
,08-26 11:20:28.859  2696  2739 D BtGatt.ScanManager: handling starting scan
,08-26 11:20:28.859  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 11:20:28.859  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 11:20:28.860  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 11:20:28.860  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 11:20:28.862  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 11:20:28.862  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 11:20:28.862  3883  3883 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 11:20:28.863  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 11:20:28.865  2696  2733 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 11:20:28.866  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:28.866  3883  3947 I io.jxcore.node.ConnectionHelper: start: OK
08-26 11:20:28.866  2696  2739 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 11:20:28.871  2696  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 11:20:28.872  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:28.872  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.872  2696  2739 D BtGatt.ScanManager: Starting BLE batch scan
08-26 11:20:28.872  2696  2739 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 11:20:28.872  3883  3947 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 11:20:28.872  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.872  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 11:20:28.872  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.872  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 11:20:28.872  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 11:20:28.872  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 11:20:28.872  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 11:20:28.872  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 11:20:28.872  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 11:20:28.872  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 11:20:28.873  3883  3947 D BluetoothAdapter: STATE_ON
,08-26 11:20:28.874  2696  2722 D BtGatt.GattService: stopScan() - queue size =1
,08-26 11:20:28.877  2696  2708 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 11:20:28.877  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 11:20:28.878  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 11:20:28.878  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 11:20:28.878  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 11:20:28.878  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 11:20:28.880  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 11:20:28.881  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 11:20:28.881  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 11:20:28.881  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 11:20:28.882  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 11:20:28.883  2696  2733 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 11:20:28.883  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:28.884  3883  3883 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 11:20:28.884  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.884  3883  3883 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 11:20:28.884  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.884  3883  3883 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 11:20:28.884  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:28.884  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
,08-26 11:20:28.884  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.886  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.886  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.886  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.887  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.887  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.889  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:28.889  2696  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 11:20:28.889  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.889  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:28.889  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:28.892  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.892  3883  3947 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 11:20:28.894  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 11:20:28.899  2696  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 11:20:28.899  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:28.899  2696  2739 D BtGatt.ScanManager: stopping BLe Batch
08-26 11:20:28.899  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:28.899  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:28.899  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:28.899  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:28.899  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:28.899  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:28.899  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:28.899  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 11:20:28.901  3883  3947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 11:20:28.901  3883  3947 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 11:20:28.901  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 11:20:28.902  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 11:20:28.902  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 11:20:28.902  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:28.902  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 11:20:28.904  3883  3947 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 11:20:28.904  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 11:20:28.905  2696  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 11:20:28.905  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:28.905  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:28.905  2696  2739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 11:20:28.907  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 11:20:28.907  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:28.909  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 11:20:28.909  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 11:20:28.910  2696  2733 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 11:20:28.910  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:28.913  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 11:20:28.913  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 11:20:28.913  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 11:20:28.914  3883  3947 D BluetoothAdapter: STATE_ON
,08-26 11:20:28.916  2696  2722 D BtGatt.GattService: registerClient() - UUID=d04eda17-7f7c-403f-b7c3-97e9205fc43c
08-26 11:20:28.917  2696  2733 D BtGatt.GattService: onClientRegistered() - UUID=d04eda17-7f7c-403f-b7c3-97e9205fc43c, clientIf=5
08-26 11:20:28.917  3883  3894 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 11:20:28.917  2696  2719 D BtGatt.GattService: start scan with filters
,08-26 11:20:28.921  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 11:20:28.921  2696  2739 D BtGatt.ScanManager: handling starting scan
08-26 11:20:28.921  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 11:20:28.921  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 11:20:28.921  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 11:20:28.924  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 11:20:28.924  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 11:20:28.924  3883  3883 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 11:20:28.926  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 11:20:28.926  2696  2733 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 11:20:28.926  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:28.927  2696  2739 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 11:20:28.928  3883  3947 I io.jxcore.node.ConnectionHelper: start: OK
08-26 11:20:28.929  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.929  3883  3947 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 11:20:28.929  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.929  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 11:20:28.929  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:28.929  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 11:20:28.929  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 11:20:28.929  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 11:20:28.929  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 11:20:28.929  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 11:20:28.929  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 11:20:28.929  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 11:20:28.930  3883  3947 D BluetoothAdapter: STATE_ON
08-26 11:20:28.930  2696  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 11:20:28.930  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:28.930  2696  2739 D BtGatt.ScanManager: Starting BLE batch scan
08-26 11:20:28.931  2696  2739 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 11:20:28.931  2696  2719 D BtGatt.GattService: stopScan() - queue size =1
08-26 11:20:28.931  2696  2818 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 11:20:28.932  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 11:20:28.932  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 11:20:28.932  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 11:20:28.932  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 11:20:28.932  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 11:20:28.934  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 11:20:28.934  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 11:20:28.934  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 11:20:28.934  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 11:20:28.935  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:28.936  3883  3883 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 11:20:28.936  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.936  3883  3883 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 11:20:28.936  3883  3947 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 11:20:28.936  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 11:20:28.936  3883  3883 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 11:20:28.936  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:28.936  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.936  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.936  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:28.936  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.936  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.936  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
,08-26 11:20:28.936  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.936  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.937  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.937  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.938  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 11:20:28.938  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.938  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.938  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.938  3883  3947 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 11:20:28.938  2696  2733 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 11:20:28.938  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:28.939  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.939  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 11:20:28.939  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:28.939  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.939  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.939  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.939  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.939  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.939  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.939  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.939  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.939  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.940  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.940  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.940  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:28.940  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 11:20:28.940  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.940  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.941  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 11:20:28.941  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.942  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.942  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:28.942  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:28.942  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.942  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.942  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.942  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.942  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.942  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.942  2696  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 11:20:28.943  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:28.942  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.943  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.943  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.943  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.944  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:28.944  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.944  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:28.944  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
,08-26 11:20:28.945  3883  3947 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 11:20:28.945  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.945  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.945  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 11:20:28.945  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.946  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:28.946  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.946  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.946  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.946  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
,08-26 11:20:28.946  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.946  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.946  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.946  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.946  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.948  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 11:20:28.948  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.948  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.948  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.948  2696  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 11:20:28.948  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:28.948  2696  2739 D BtGatt.ScanManager: stopping BLe Batch
08-26 11:20:28.949  3883  3947 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-26 11:20:28.949  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.949  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.949  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:28.949  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.949  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.949  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.949  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.949  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.949  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.949  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.949  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.950  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.950  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.950  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.950  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:28.950  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.950  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.951  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.951  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 11:20:28.951  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 11:20:28.951  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 11:20:28.951  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 11:20:28.952  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 11:20:28.952  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 11:20:28.952  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 11:20:28.952  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.952  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:28.952  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.952  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.952  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.952  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.952  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.952  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.952  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.952  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.953  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.953  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.953  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.953  2696  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 11:20:28.953  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:28.953  2696  2739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 11:20:28.954  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:28.954  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.954  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.954  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.955  3883  3947 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 11:20:28.955  3883  3947 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 11:20:28.955  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 11:20:28.959  2696  2733 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 11:20:28.959  2696  2733 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:28.959  3883  3947 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 11:20:28.959  3883  3947 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 11:20:28.959  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 11:20:28.959  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 11:20:28.959  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-26 11:20:28.959  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 11:20:28.960  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-26 11:20:28.961  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 11:20:28.961  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 11:20:28.961  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 11:20:28.961  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 11:20:28.961  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 11:20:28.961  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-26 11:20:28.961  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 11:20:28.961  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 11:20:28.961  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 11:20:28.961  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 11:20:28.961  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 11:20:28.961  3883  3947 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 11:20:28.962  3883  3947 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 11:20:28.962  3883  3947 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-26 11:20:28.962  3883  3947 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 11:20:28.962  3883  3947 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 11:20:28.962  3883  3947 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 11:20:28.962  3883  3947 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 11:20:28.962  3883  3947 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 11:20:28.962  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-26 11:20:28.966  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 11:20:28.967  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 11:20:28.967  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 11:20:28.967  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 11:20:28.968  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 11:20:28.968  3883  3947 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 11:20:28.968  3883  3947 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 11:20:28.968  3883  3947 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 11:20:28.969  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.969  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.969  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:28.969  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:28.969  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.969  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.970  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 11:20:28.971  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.971  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.971  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.971  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.971  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:28.971  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.971  3883  3962 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 409)
,08-26 11:20:28.971  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.971  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.971  3883  3963 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 409
,08-26 11:20:28.972  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:28.972  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.972  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.972  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.973  3883  3947 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 11:20:28.973  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.973  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.973  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 11:20:28.973  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.973  3883  3962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 11:20:28.973  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.973  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.973  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.974  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.974  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.974  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 11:20:28.974  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.974  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.974  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.974  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.974  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:28.975  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.975  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.975  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
,08-26 11:20:28.977  3883  3947 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 11:20:28.977  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.978  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.978  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:28.978  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.978  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.978  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.978  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.978  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:28.978  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.979  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.979  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.979  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.979  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.979  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.980  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 11:20:28.980  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.980  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.980  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.980  3883  3947 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 11:20:28.980  3883  3947 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 11:20:28.980  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 11:20:28.981  3883  3947 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 11:20:28.981  3883  3947 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 11:20:28.981  3883  3947 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 11:20:28.981  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 11:20:28.981  3883  3947 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 11:20:28.981  3883  3947 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 11:20:28.981  3883  3947 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-26 11:20:28.981  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 11:20:28.981  3883  3947 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 11:20:28.981  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.981  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.981  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:28.981  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.981  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.982  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.982  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.982  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.982  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.982  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.982  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.982  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.982  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.982  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.983  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:28.983  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.983  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.983  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.983  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.984  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.984  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.984  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.984  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.984  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.984  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.984  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.984  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.984  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.984  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.984  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.984  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.984  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.984  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.984  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.985  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.985  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:28.985  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.985  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.985  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.985  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.985  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.985  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
,08-26 11:20:28.985  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 11:20:28.985  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.985  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.985  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.985  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.986  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:28.986  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.986  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.986  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.987  3883  3947 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 11:20:28.988  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:28.988  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 11:20:28.989  3883  3947 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 11:20:28.989  3883  3947 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 11:20:28.989  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 11:20:28.989  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 11:20:28.989  3883  3883 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 11:20:28.990  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.990  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 11:20:28.990  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 11:20:28.990  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 11:20:28.990  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.990  3883  3947 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-26 11:20:28.990  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.990  3883  3883 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 11:20:28.990  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.990  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 11:20:28.990  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 11:20:28.990  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 11:20:28.990  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.990  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.990  3883  3964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 11:20:28.991  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 11:20:28.991  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.991  3883  3883 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 11:20:28.991  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.991  3883  3883 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 11:20:28.991  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.991  3883  3883 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 11:20:28.991  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:28.991  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.991  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.991  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.991  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.991  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.991  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.992  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.992  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.992  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:28.992  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.992  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.992  3883  3964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 11:20:28.992  3883  3964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 11:20:28.992  3883  3964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 11:20:28.993  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:28.993  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:28.993  3883  3883 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 11:20:28.993  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.993  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.994  3883  3947 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-26 11:20:28.994  3883  3947 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 11:20:28.994  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 11:20:28.995  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 11:20:28.995  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:28.995  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:28.995  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:28.995  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:28.995  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.996  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.996  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:28.996  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:28.996  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:28.996  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:28.997  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.997  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.997  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:28.997  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:28.998  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:28.998  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 11:20:28.998  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:28.998  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:29.001  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:29.001  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:29.001  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:29.001  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:29.001  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:29.001  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:29.001  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:29.001  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:29.001  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
,08-26 11:20:29.001  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:29.001  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:29.001  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:29.002  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:29.002  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:29.002  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:29.002  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 11:20:29.002  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:29.002  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:29.003  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:29.003  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:29.003  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:29.003  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:29.003  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:29.003  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:29.003  3883  3947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb73b03 not in the list
08-26 11:20:29.003  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:29.003  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
,08-26 11:20:29.003  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:29.003  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:29.003  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:29.003  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:29.004  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:29.004  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 11:20:29.004  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:29.004  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:29.004  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5513a80 not in the list
08-26 11:20:29.005  3883  3947 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 11:20:29.005  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 11:20:29.005  3883  3947 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 11:20:29.005  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 11:20:29.005  3883  3947 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 11:20:29.005  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 11:20:29.006  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 11:20:29.007  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-26 11:20:29.007  3883  3947 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 11:20:29.007  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 11:20:29.007  3883  3947 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 11:20:29.007  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 11:20:29.007  3883  3947 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 11:20:29.007  3883  3947 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 11:20:29.008  3883  3947 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 11:20:29.008  3883  3947 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 11:20:29.008  3883  3947 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 11:20:29.008  3883  3947 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-26 11:20:29.008  3883  3947 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 11:20:29.008  3883  3947 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 11:20:29.009  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:29.009  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2386962 added. We now have 2 listener(s)
,08-26 11:20:29.009  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 11:20:29.012  3883  3947 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 11:20:29.012   872  1998 D WifiService: setWifiEnabled: true pid=3883, uid=10000
08-26 11:20:29.012   872  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 11:20:29.013  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:29.013  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5eceaf3 added. We now have 3 listener(s)
08-26 11:20:29.013  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 11:20:29.020  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:29.020  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6843b0 added. We now have 4 listener(s)
08-26 11:20:29.020  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 11:20:29.022  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:29.022  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b24a229 added. We now have 5 listener(s)
08-26 11:20:29.022  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 11:20:29.025   872  1999 D WifiService: setWifiEnabled: false pid=3883, uid=10000
08-26 11:20:29.025   872  1999 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 11:20:29.031  2696  2728 D BluetoothAdapterState: Current state: ON, message: 23
08-26 11:20:29.031  2696  2728 D BluetoothAdapterProperties: Setting state to 13
,08-26 11:20:29.031  2696  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 11:20:29.033  2696  2728 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 11:20:29.033  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 11:20:29.034  2696  2728 I BluetoothAdapterState: Entering PendingCommandState
08-26 11:20:29.036  2696  2733 D BluetoothAdapterProperties: Scan Mode:20
,08-26 11:20:29.036  2696  2728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-26 11:20:29.037  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:29.037  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:29.037  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:29.037  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:29.037  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:29.037  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:29.037  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:29.037  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:29.037  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:29.038  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:29.038  3883  3947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:29.039  3883  3947 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 11:20:29.039  2696  2696 D HeadsetService: Received stop request...Stopping profile...,
08-26 11:20:29.041  1952  2176 D BluetoothHeadset: Proxy object disconnected
,08-26 11:20:29.042  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 11:20:29.043  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:29.044   872  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 11:20:29.044   872  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-26 11:20:29.044   872  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 11:20:29.044   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 11:20:29.045  1360  1371 D BluetoothHeadset: Proxy object disconnected,
08-26 11:20:29.045  1360  1360 D HeadsetProfile: Bluetooth service disconnected
08-26 11:20:29.045   872   872 D BluetoothHeadset: Proxy object disconnected
,08-26 11:20:29.045   872   872 D BluetoothHeadset: Proxy object disconnected
,08-26 11:20:29.045   872   872 D BluetoothHeadset: Proxy object disconnected
,08-26 11:20:29.048  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:29.048  2696  2696 D A2dpService: Received stop request...Stopping profile...
,08-26 11:20:29.049  2696  2811 D A2dpStateMachine: Exit Disconnected: -1
08-26 11:20:29.050  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:29.050  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:29.050  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:29.050  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:29.050  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:29.050  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:29.050  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:29.050  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:29.050  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:29.052  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:29.052  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:29.053   872   872 D BluetoothA2dp: Proxy object disconnected
,08-26 11:20:29.053  1360  1360 D BluetoothA2dp: Proxy object disconnected
,08-26 11:20:29.055  2696  2696 V BluetoothAdapterState: isTurningOff()=true
,08-26 11:20:29.055  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:29.055  2696  2696 V BluetoothAdapterState: isTurningOn()=false
,08-26 11:20:29.055  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 11:20:29.055  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:29.056   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-26 11:20:29.056   872  2144 D DhcpClient: Clearing IP address
,08-26 11:20:29.057  2696  2696 D HidService: Received stop request...Stopping profile...
,08-26 11:20:29.057  2696  2696 D HidService: Stopping Bluetooth HidService
,08-26 11:20:29.058  1360  1360 D BluetoothInputDevice: Proxy object disconnected
,08-26 11:20:29.058  1360  1360 D HidProfile: Bluetooth service disconnected
08-26 11:20:29.058   371   870 D CommandListener: Setting iface cfg
08-26 11:20:29.059  2696  2696 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 11:20:29.059  2696  2696 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 11:20:29.059  2696  2733 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 11:20:29.059  2696  2803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 11:20:29.059  2696  2803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 11:20:29.059  2696  2803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 11:20:29.059  2696  2733 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-26 11:20:29.060  2696  2696 D HealthService: Received stop request...Stopping profile...
08-26 11:20:29.061  1510  2546 V NativeCrypto: Read error: ssl=0x9b28c400: I/O error during system call, Connection timed out
,08-26 11:20:29.061  2696  2696 D PanService: Received stop request...Stopping profile...
08-26 11:20:29.062  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 11:20:29.062  1360  1360 D PanProfile: Bluetooth service disconnected
08-26 11:20:29.063  1510  2546 V NativeCrypto: SSL shutdown failed: ssl=0x9b28c400: I/O error during system call, Broken pipe
,08-26 11:20:29.064  2696  2696 D BluetoothMapService: Received stop request...Stopping profile...
08-26 11:20:29.064  2696  2696 D BluetoothMapService: stop()
08-26 11:20:29.064   872  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-26 11:20:29.064  2696  2696 D BluetoothMapAppObserver: deinitObservers()
,08-26 11:20:29.064  2696  2696 D BluetoothMapAppObserver: removeReceiver()
08-26 11:20:29.065   872  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 11:20:29.067   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 11:20:29.067   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-26 11:20:29.072   395   395 E Parcel  : Reading a NULL string not supported here.
,08-26 11:20:29.073  1360  1360 D BluetoothMap: Proxy object disconnected
08-26 11:20:29.073  1360  1360 D MapProfile: Bluetooth service disconnected
08-26 11:20:29.074   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-26 11:20:29.075  2696  2696 V BluetoothAdapterState: isTurningOff()=true
08-26 11:20:29.075  2696  2696 V BluetoothAdapterState: isTurningOn()=false
,08-26 11:20:29.075  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:29.075  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 11:20:29.075   872  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 11:20:29.076   872  2175 D DhcpClient: Receive thread stopped
08-26 11:20:29.079  2696  2733 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-26 11:20:29.079  2696  2803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 11:20:29.079  2696  2696 V BluetoothAdapterState: isTurningOff()=true
08-26 11:20:29.079  2696  2803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 11:20:29.079  2696  2696 V BluetoothAdapterState: isTurningOn()=false
,08-26 11:20:29.079  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:29.079  2696  2803 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 11:20:29.079  2696  2803 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 11:20:29.079  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 11:20:29.079  2696  2803 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 11:20:29.079  2696  2803 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 11:20:29.082   872  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 11:20:29.085  2696  2696 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-26 11:20:29.085  2696  2733 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 11:20:29.085  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:29.085  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:29.085  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:29.085  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:29.085  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:29.085  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:29.085  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:29.085  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:29.085  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 11:20:29.085  2696  2696 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 11:20:29.085   872  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 11:20:29.086  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:29.086  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 11:20:29.086  2696  2696 V BluetoothAdapterState: isTurningOff()=true
,08-26 11:20:29.086  2696  2696 V BluetoothAdapterState: isTurningOn()=false
,08-26 11:20:29.086  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 11:20:29.086  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 11:20:29.086  2696  2696 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 11:20:29.087  2696  2733 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-26 11:20:29.087  2696  2696 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 11:20:29.088  2696  2696 V BluetoothAdapterState: isTurningOff()=true
08-26 11:20:29.088  2696  2696 V BluetoothAdapterState: isTurningOn()=false
08-26 11:20:29.088  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:29.088  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:29.088  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:29.088  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:29.088  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:29.088  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:29.088  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:29.088  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:29.088  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:29.088  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:29.088  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 11:20:29.088  2696  2696 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 11:20:29.088  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:29.088  2696  2696 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 11:20:29.088  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:29.090  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:29.091  2696  2696 D BluetoothMapService: MAP Service closeService in
,08-26 11:20:29.091  2696  2696 D BluetoothMapMasInstance0: MAP Service shutdown
,08-26 11:20:29.091  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:29.091  2696  2696 D ObexServerSockets0: shutdown(block = true)
08-26 11:20:29.091  2696  2819 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 11:20:29.091  2696  2696 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 11:20:29.092  2696  2820 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 11:20:29.092  2696  2806 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 11:20:29.092  2696  2696 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 11:20:29.093  2696  2696 V BluetoothAdapterState: isTurningOff()=true
08-26 11:20:29.093  2696  2696 V BluetoothAdapterState: isTurningOn()=false
,08-26 11:20:29.093  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:29.093  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:29.093  2696  2728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 11:20:29.093  2696  2728 D BluetoothAdapterProperties: Setting state to 15
08-26 11:20:29.093  2696  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 11:20:29.094  2696  2728 I BluetoothAdapterState: Entering BleOnState
08-26 11:20:29.094  2696  2696 D BluetoothMapService: cleanup()
08-26 11:20:29.094  2696  2696 D BluetoothMapService: MAP Service closeService in
,08-26 11:20:29.094  2696  2696 I BtOppRfcommListener: stopping Accept Thread
08-26 11:20:29.094  2696  3514 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 11:20:29.095  2696  3514 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 11:20:29.099  1889  2283 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:29.108   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 11:20:29.110   872  3220 I ActivityManager: Start proc 3970:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-26 11:20:29.114  1360  1378 D BluetoothPan: onBluetoothStateChange on: false
,08-26 11:20:29.114   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 11:20:29.114  1360  1371 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 11:20:29.115  1952  2306 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 11:20:29.115   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 11:20:29.116  1360  2090 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 11:20:29.116  1360  1378 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 11:20:29.116   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 11:20:29.117  1360  1371 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 11:20:29.120  1360  2090 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 11:20:29.120   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 11:20:29.121  2696  2728 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 11:20:29.121  2696  2728 D BluetoothAdapterProperties: Setting state to 16
,08-26 11:20:29.121  2696  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-26 11:20:29.122  2696  2728 D BluetoothAdapterProperties: onBleDisable
08-26 11:20:29.123  2696  2728 I BluetoothAdapterState: Entering PendingCommandState
08-26 11:20:29.123  2696  2729 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 11:20:29.123  2696  2733 D BluetoothAdapterProperties: Scan Mode:20
08-26 11:20:29.126  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:29.127  2696  2803 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-26 11:20:29.127  2696  2803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 11:20:29.128  3883  3962 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 409)
,08-26 11:20:29.129  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:29.132  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:29.134  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:29.150   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 11:20:29.150  3970  3970 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-26 11:20:29.151   872  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 11:20:29.151   872  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:29.153   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 11:20:29.156  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:29.157  3517  3517 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9d886f3 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-26 11:20:29.158  2036  2036 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-26 11:20:29.159  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:29.203   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-26 11:20:29.205  3970  3970 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-26 11:20:29.227   872  2100 I ActivityManager: Start proc 4001:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-26 11:20:29.230   872  1965 I ActivityManager: Killing 3313:com.google.android.gm/u0a78 (adj 15): empty #17
,08-26 11:20:29.286  4001  4001 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-26 11:20:29.297  4001  4001 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 11:20:29.302   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e1164b:true
,08-26 11:20:29.312  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 11:20:29.321  4001  4001 D LocalBluetoothProfileManager: Adding local MAP profile
,08-26 11:20:29.324  4001  4001 D BluetoothMap: Create BluetoothMap proxy object
,08-26 11:20:29.330  2696  2733 I bt_hci  : shut_down
08-26 11:20:29.330  2696  2740 D bt_hwcfg: hw_epilog_process
,08-26 11:20:29.341   872   882 I ActivityManager: Start proc 4013:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-26 11:20:29.347  4001  4001 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-26 11:20:29.349  2696  2740 I bt_vendor: low_power_mode_cb
,08-26 11:20:29.359  4001  4001 D DockEventReceiver: finishStartingService: stopping service
,08-26 11:20:29.361   872  1998 I ActivityManager: Killing 3517:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-26 11:20:29.368  2696  2740 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-26 11:20:29.368  2696  2740 I bt_vendor: epilog_cb
08-26 11:20:29.368  2696  2740 I bt_hci  : epilog_finished_callback
,08-26 11:20:29.412  2696  2733 I bt_hci_h4: hal_close
,08-26 11:20:29.413  2696  2733 I bt_userial_vendor: device fd = 51 close
,08-26 11:20:29.433  4013  4013 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-26 11:20:29.494  3883  3883 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 11:20:29.545  2696  2729 D bt_stack_manager: event_shut_down_stack finished.
,08-26 11:20:29.547  2696  2728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 11:20:29.554  2696  2696 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 11:20:29.554  2696  2728 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-26 11:20:29.556  2696  2696 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 11:20:29.556  2696  2696 D BtGatt.GattService: stop()
08-26 11:20:29.556  2696  2696 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 11:20:29.559  2696  2696 V BluetoothAdapterState: isTurningOff()=false
08-26 11:20:29.559  2696  2696 V BluetoothAdapterState: isTurningOn()=false
08-26 11:20:29.559  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:29.560  2696  2696 V BluetoothAdapterState: isBleTurningOff()=true
08-26 11:20:29.560  2696  2728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 11:20:29.561  2696  2728 D BluetoothAdapterProperties: Setting state to 10
08-26 11:20:29.561  2696  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-26 11:20:29.581  4013  4013 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 11:20:29.581  4013  4013 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 11:20:29.581  4013  4013 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 11:20:29.581  4013  4013 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 11:20:29.581  4013  4013 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.r.k.d(PG:583)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 11:20:29.581  4013  4013 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 11:20:29.581  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 11:20:29.582  4013  4013 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 11:20:29.582  4013  4013 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 11:20:29.582  4013  4013 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 11:20:29.599   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-26 11:20:29.597  2696  2728 I BluetoothAdapterState: Entering OffState
08-26 11:20:29.603  4001  4001 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 11:20:29.649  4001  4001 D DockEventReceiver: finishStartingService: stopping service
08-26 11:20:29.650  2696  2696 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-26 11:20:29.650  2696  2696 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 11:20:29.652  2696  2696 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 11:20:29.653  2696  2729 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 11:20:29.654   872  2100 I ActivityManager: Killing 2660:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-26 11:20:29.657  2696  2729 D bt_stack_manager: event_clean_up_stack finished.
,08-26 11:20:29.679  2696  2696 I art     : System.exit called, status: 0
,08-26 11:20:29.679  2696  2696 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 11:20:29.731   872  1687 I ActivityManager: Process com.android.bluetooth (pid 2696) has died
,08-26 11:20:29.737  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 11:20:29.768   872  1408 I ActivityManager: Start proc 4046:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,08-26 11:20:29.866  4046  4046 D AdapterServiceConfig: Adding HeadsetService
,08-26 11:20:29.866  4046  4046 D AdapterServiceConfig: Adding A2dpService
08-26 11:20:29.866  4046  4046 D AdapterServiceConfig: Adding HidService
08-26 11:20:29.866  4046  4046 D AdapterServiceConfig: Adding HealthService
08-26 11:20:29.866  4046  4046 D AdapterServiceConfig: Adding PanService
08-26 11:20:29.866  4046  4046 D AdapterServiceConfig: Adding GattService
08-26 11:20:29.867  4046  4046 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 11:20:29.881  1711  1711 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 11:20:29.884  1711  1711 D SystemUpdateService: onCreate
,08-26 11:20:29.886  1711  1711 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 11:20:29.892  1711  4060 I SystemUpdateService: active receiver: enabled
,08-26 11:20:29.896  1711  1711 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 11:20:29.898  1711  4060 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 11:20:29.898  1711  2522 I iu.UploadsManager: num queued entries: 0
08-26 11:20:29.899  1711  2522 I iu.UploadsManager: num updated entries: 0
08-26 11:20:29.900  1711  4060 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-26 11:20:29.900  1711  4060 I SystemUpdateService: now status is 0 (complete)
08-26 11:20:29.900  1711  4060 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 11:20:29.900  1711  4060 I SystemUpdateService: file has been verified
08-26 11:20:29.900  1711  4060 I SystemUpdateService: OTA package size = 12249756
08-26 11:20:29.901  1711  2522 I iu.SyncManager: NEXT; no task
,08-26 11:20:29.914  1711  4060 I SystemUpdateService: showing system update notification
,08-26 11:20:29.916  1711  1711 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 11:20:29.917  1711  1711 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 11:20:29.931   872  3220 I ActivityManager: Start proc 4062:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-26 11:20:29.934  1711  1711 D SystemUpdateService: onDestroy
,08-26 11:20:29.940  4013  4031 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 11:20:29.954   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@304c95d:true
,08-26 11:20:29.964  4062  4062 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-26 11:20:29.967  4062  4062 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 11:20:29.973  4062  4062 D SprintDMHelper: simOperator: 
,08-26 11:20:29.973  4062  4062 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 11:20:29.987   872  1972 I ActivityManager: Start proc 4074:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-26 11:20:29.989   872  1972 I ActivityManager: Killing 1691:android.process.acore/u0a5 (adj 15): empty #17
,08-26 11:20:30.131   872   883 I ActivityManager: Start proc 4089:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-26 11:20:30.133  2825  4088 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-26 11:20:30.137   872  2100 I ActivityManager: Killing 3738:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-26 11:20:30.205  4089  4089 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-26 11:20:30.263  4089  4089 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 11:20:30.263  4089  4089 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 11:20:30.263  4089  4089 I GAv4    :   adb logcat -s GAv4
,08-26 11:20:30.284  4089  4089 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 11:20:30.293  4089  4089 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 11:20:30.320  4089  4107 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 11:20:30.434  4089  4089 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-26 11:20:30.469  4089  4089 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-26 11:20:30.484  4089  4089 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 4341-4348)
,08-26 11:20:30.484  4089  4089 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 11:20:30.501  4089  4089 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cb112e3}
,08-26 11:20:30.501  4089  4089 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 11:20:30.502  4089  4089 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 11:20:30.511  4089  4089 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 11:20:30.512  4089  4089 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 11:20:30.531  4089  4089 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 11:20:30.543  4089  4089 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 11:20:30.544  4089  4089 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 11:20:30.544  4089  4089 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 11:20:30.544  4089  4089 I Adreno  : Build Date                       : 10/20/15
08-26 11:20:30.544  4089  4089 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 11:20:30.544  4089  4089 I Adreno  : Local Branch                     : M14
08-26 11:20:30.544  4089  4089 I Adreno  : Remote Branch                    : 
08-26 11:20:30.544  4089  4089 I Adreno  : Remote Branch                    : 
08-26 11:20:30.544  4089  4089 I Adreno  : Reconstruct Branch               : 
,08-26 11:20:30.607  4089  4089 I NSApplication: Starting up...
,08-26 11:20:30.621  4089  4135 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 11:20:30.644   872  1408 I ActivityManager: Start proc 4140:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-26 11:20:30.645   872  1408 I ActivityManager: Killing 3753:com.android.musicfx/u0a18 (adj 15): empty #17
,08-26 11:20:30.734  4140  4140 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-26 11:20:30.920   872  1688 I ActivityManager: Killing 3542:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-26 11:20:32.043   872  1972 D WifiService: setWifiEnabled: true pid=3883, uid=10000
,08-26 11:20:32.043   872  1972 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 11:20:32.057   872  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-26 11:20:32.065  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:32.065  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:32.065  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:32.065  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:32.065  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:32.065  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:32.065  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:32.065  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:32.065  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 11:20:32.065  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:32.066  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 11:20:32.069  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:32.069  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:32.069  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:32.069  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:32.069  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:32.069  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:32.069  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:32.069  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:32.069  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 11:20:32.069  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:32.070  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 11:20:32.104   872  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-26 11:20:32.105   872  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 11:20:32.106   872  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 11:20:32.107   872  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 11:20:32.107   872  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 11:20:32.107   872  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-26 11:20:32.107   872  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 11:20:32.120   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 11:20:32.120   872  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.50 rxSuccessRate=13.62 delta 1000 -> 994
,08-26 11:20:32.121   371   870 D CommandListener: Setting iface cfg
,08-26 11:20:32.122   872  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-26 11:20:32.122   872  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 11:20:32.131   872  1314 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 11:20:32.131   872  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 11:20:32.133   872  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-26 11:20:32.133   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 11:20:32.141   872  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 11:20:32.201   872  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 11:20:32.207  1472  1472 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 11:20:32.639  1472  1472 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 11:20:32.682  1472  1472 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 11:20:32.685  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 11:20:32.690   872  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 11:20:32.708   872  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 11:20:32.708   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 11:20:32.708   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 11:20:32.737   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 11:20:32.753   371   870 D CommandListener: Setting iface cfg
08-26 11:20:32.754   872  1315 D WifiStateMachine: Start Dhcp Watchdog 2
,08-26 11:20:32.772   872  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 11:20:32.772   872  1317 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-26 11:20:32.777   872  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 11:20:32.790   872  4165 D DhcpClient: Receive thread started
,08-26 11:20:32.874   872  1315 E native  : do suspend false
,08-26 11:20:32.893   872  2144 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 11:20:32.909   872  4165 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172687, domain null
,08-26 11:20:32.910   872  2144 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172687 seconds
,08-26 11:20:32.914   872  2144 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 11:20:32.927   872  4165 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 11:20:32.929   872  2144 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 11:20:32.937   371   870 D CommandListener: Setting iface cfg
,08-26 11:20:32.947   872  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 11:20:32.948   872  2144 D DhcpClient: Scheduling renewal in 86399s
,08-26 11:20:32.967   872  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 11:20:32.970   872  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 11:20:32.971   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 11:20:32.980   872  1317 D ConnectivityService: Adding iface wlan0 to network 101
,08-26 11:20:32.984   872  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 11:20:33.037   872  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 11:20:33.038   872  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-26 11:20:33.042   872  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-26 11:20:33.045   872  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-26 11:20:33.047   872  1317 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 11:20:33.054   872  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 11:20:33.059   872  1317 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-26 11:20:33.060   872  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-26 11:20:33.060   872  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-26 11:20:33.060   872  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-26 11:20:33.060   872  1317 D ConnectivityService:    accepting network in place of null
08-26 11:20:33.061   872  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 11:20:33.061   872  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 11:20:33.080   872  4164 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 11:20:33.107   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 11:20:33.140   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 11:20:33.144   872  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 11:20:33.144   872  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 11:20:33.145   872  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-26 11:20:33.147   872   889 D Tethering: MasterInitialState.processMessage what=3
08-26 11:20:33.163   872  4163 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:811::200e
08-26 11:20:33.173  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:33.173  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:33.173  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:33.173  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:33.173  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:33.173  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:33.173  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:33.173  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:33.173  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 11:20:33.173  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:33.173  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:33.174  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:33.175  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:33.175  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:33.175  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:33.175  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:33.175  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:33.175  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:33.175  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:33.175  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 11:20:33.175  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:33.175  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 11:20:33.181  1711  1711 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 11:20:33.183  2036  2036 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-26 11:20:33.184  1711  1711 D SystemUpdateService: onCreate
08-26 11:20:33.185  1711  1711 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 11:20:33.188  1711  4175 I SystemUpdateService: active receiver: enabled
,08-26 11:20:33.192  1711  4175 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 11:20:33.195  1711  4175 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 11:20:33.195  1711  4175 I SystemUpdateService: now status is 0 (complete)
,08-26 11:20:33.196  1711  4175 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 11:20:33.196  1711  4175 I SystemUpdateService: file has been verified
08-26 11:20:33.196  1711  4175 I SystemUpdateService: OTA package size = 12249756
,08-26 11:20:33.200  1711  4175 I SystemUpdateService: showing system update notification
,08-26 11:20:33.206  1711  1711 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 11:20:33.208  1711  2522 I iu.UploadsManager: num queued entries: 0
08-26 11:20:33.208  1711  2522 I iu.UploadsManager: num updated entries: 0
,08-26 11:20:33.209  1711  2522 I iu.SyncManager: NEXT; no task
,08-26 11:20:33.211  1711  1711 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 11:20:33.212  1711  1711 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 11:20:33.213  1711  4179 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-26 11:20:33.213  1711  4179 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 11:20:33.214  1711  4179 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 11:20:33.215  4062  4062 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 11:20:33.218  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 11:20:33.220  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 11:20:33.220  4062  4062 D SprintDMHelper: simOperator: 
08-26 11:20:33.221  4062  4062 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 11:20:33.227  1711  1711 D SystemUpdateService: onDestroy
,08-26 11:20:33.254   872  4163 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 09:20:33 GMT], X-Android-Received-Millis=[1472203233253], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472203233219]}
,08-26 11:20:33.258   872  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-26 11:20:33.258   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-26 11:20:33.258   872  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 11:20:33.258  3667  4176 V KeepSync: Connecting to GoogleApiClient
08-26 11:20:33.259   872  1379 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
08-26 11:20:33.259   872  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 11:20:33.263  1510  2034 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 11:20:33.263  1510  2034 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 11:20:33.263  1510  2034 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 11:20:33.263  1510  2034 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 11:20:33.277  1711  4179 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-26 11:20:33.309  1510  3645 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-26 11:20:33.309  1510  3645 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-26 11:20:33.309  1510  3645 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 11:20:33.309  1510  3645 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 11:20:33.322  1711  4187 V BaseAuthAsyncOperation: access token request failed
,08-26 11:20:33.323  3667  4176 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-26 11:20:33.359  2825  4182 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 11:20:33.375  1510  2308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-26 11:20:33.375  1510  2308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-26 11:20:33.375  1510  2308 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 11:20:33.375  1510  2308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 11:20:33.393  3667  4176 E KeepSync: IOException
08-26 11:20:33.393  3667  4176 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-26 11:20:33.393  3667  4176 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-26 11:20:33.393  3667  4176 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-26 11:20:33.393  3667  4176 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-26 11:20:33.393  3667  4176 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-26 11:20:33.393  3667  4176 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-26 11:20:33.393  3667  4176 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-26 11:20:33.393  3667  4176 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-26 11:20:33.393  3667  4176 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-26 11:20:33.393  3667  4176 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-26 11:20:33.393  3667  4176 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-26 11:20:33.393  3667  4176 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-26 11:20:33.393  3667  4176 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-26 11:20:33.393  3667  4176 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-26 11:20:33.393  3667  4176 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 11:20:33.393  3667  4176 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 11:20:33.393  3667  4176 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-26 11:20:33.393  3667  4176 E KeepSync: 	... 10 more
08-26 11:20:33.393  3667  4176 W KeepSync: Sync result 2
,08-26 11:20:33.399   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 131637, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-26 11:20:34.146   872  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-26 11:20:34.943   872  1965 I ActivityManager: Killing 3778:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-26 11:20:35.050   872  1408 D WifiService: setWifiEnabled: false pid=3883, uid=10000
,08-26 11:20:35.051   872  1408 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 11:20:35.084  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 11:20:35.098   872  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 11:20:35.098   872  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-26 11:20:35.098   872  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 11:20:35.099   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 11:20:35.126   872  2144 D DhcpClient: Clearing IP address
,08-26 11:20:35.127   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-26 11:20:35.137  1510  4189 V NativeCrypto: Read error: ssl=0x9b28b800: I/O error during system call, Connection timed out
,08-26 11:20:35.142  1510  4189 V NativeCrypto: SSL shutdown failed: ssl=0x9b28b800: I/O error during system call, Broken pipe
,08-26 11:20:35.145   371   870 D CommandListener: Setting iface cfg
,08-26 11:20:35.149   872  4165 D DhcpClient: Receive thread stopped
,08-26 11:20:35.150   872  1972 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-26 11:20:35.151   872  4163 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-26 11:20:35.153   872  4163 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:811::200e
,08-26 11:20:35.154   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 11:20:35.154   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-26 11:20:35.157   395   395 E Parcel  : Reading a NULL string not supported here.
08-26 11:20:35.162   872  1315 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-26 11:20:35.163   872  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 11:20:35.164   872  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 11:20:35.166   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-26 11:20:35.169   872  4163 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:811::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-26 11:20:35.193   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 11:20:35.220   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 11:20:35.222   872  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 11:20:35.222   872  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 11:20:35.228   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 11:20:35.236  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:35.237  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:35.237  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:35.237  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:35.237  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:35.237  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:35.237  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:35.237  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:35.237  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:35.237  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:35.238   872  1315 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 11:20:35.238  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:35.241   872  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 11:20:35.243  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:35.243  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:35.243  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:35.243  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:35.243  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:35.243  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:35.243  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:35.243  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:35.243  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:35.243  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:35.243  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 11:20:35.246  1889  2283 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 11:20:35.247  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:35.247  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:35.247  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:35.247  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:35.247  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:35.247  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:35.247  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:35.247  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:35.247  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:35.247  2036  2036 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-26 11:20:35.247  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:35.247  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:35.251  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:35.251  1711  1711 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-26 11:20:35.256  1711  1711 D SystemUpdateService: onCreate
,08-26 11:20:35.259  1711  1711 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-26 11:20:35.269  1711  1711 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 11:20:35.271  1711  2522 I iu.UploadsManager: num queued entries: 0
,08-26 11:20:35.279  1711  1711 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 11:20:35.280  1711  1711 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 11:20:35.282  4062  4062 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 11:20:35.286  4062  4062 D SprintDMHelper: simOperator: 
,08-26 11:20:35.286  4062  4062 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 11:20:35.303  1711  2522 I iu.UploadsManager: num updated entries: 0
,08-26 11:20:35.303  2825  4205 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 11:20:35.309   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-26 11:20:35.310  1711  4200 I SystemUpdateService: active receiver: enabled
,08-26 11:20:35.310   872  1317 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-26 11:20:35.310   872  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 11:20:35.311  1711  2522 I iu.SyncManager: NEXT; no task
,08-26 11:20:35.321  1711  4200 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 11:20:35.328  4089  4089 I art     : Waiting for a blocking GC DisableMovingGc
,08-26 11:20:35.328  1711  4200 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-26 11:20:35.329  1711  4200 I SystemUpdateService: now status is 0 (complete),
08-26 11:20:35.329  1711  4200 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-26 11:20:35.329  1711  4200 I SystemUpdateService: file has been verified
,08-26 11:20:35.329  1711  4200 I SystemUpdateService: OTA package size = 12249756
,08-26 11:20:35.331  4089  4089 I art     : Starting a blocking GC DisableMovingGc
,08-26 11:20:35.374  1711  4200 I SystemUpdateService: showing system update notification
,08-26 11:20:35.387  1711  1711 D SystemUpdateService: onDestroy
,08-26 11:20:37.258  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 11:20:37.296  1510  3717 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 11:20:37.296  1510  3717 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-26 11:20:37.296  1510  3717 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 11:20:37.296  1510  3717 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 11:20:37.325  3606  3606 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 11:20:37.325  3606  3606 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-26 11:20:37.326  3606  3606 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-26 11:20:38.099   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4ddb9d9:true
,08-26 11:20:38.100  4046  4046 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 11:20:38.112  4046  4210 I BluetoothAdapterState: Entering OffState
,08-26 11:20:38.113  4046  4046 I bt_bluedroid: init
,08-26 11:20:38.116  4046  4211 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 11:20:38.117  4046  4211 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-26 11:20:38.117  4046  4211 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 11:20:38.117  4046  4211 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 11:20:38.118  4046  4046 I bt_bluedroid: get_profile_interface socket
,08-26 11:20:38.121  4046  4214 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 11:20:38.123  4046  4046 I bt_bluedroid: get_profile_interface sdp
,08-26 11:20:38.125  4046  4214 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 11:20:38.128  4046  4058 I bt_bluedroid: config_hci_snoop_log
08-26 11:20:38.131   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 11:20:38.140  4046  4210 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 11:20:38.140  4046  4210 D BluetoothAdapterProperties: Setting state to 14
08-26 11:20:38.140  4046  4210 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 11:20:38.143  4046  4210 D BluetoothBondStateMachine: make
,08-26 11:20:38.146  4046  4215 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 11:20:38.153  4046  4210 I BluetoothAdapterState: Entering PendingCommandState
08-26 11:20:38.153  4046  4046 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 11:20:38.157  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
,08-26 11:20:38.158  4046  4046 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 11:20:38.159  4046  4046 D BtGatt.GattService: Received start request. Starting profile...
08-26 11:20:38.160  4046  4046 D BtGatt.GattService: start()
,08-26 11:20:38.160  4046  4046 I bt_bluedroid: get_profile_interface gatt
,08-26 11:20:38.162  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
,08-26 11:20:38.163  4046  4046 D BtGatt.AdvertiseManager: advertise manager created
,08-26 11:20:38.175  4046  4046 V BluetoothAdapterState: isTurningOff()=false
,08-26 11:20:38.175  4046  4046 V BluetoothAdapterState: isTurningOn()=false
08-26 11:20:38.175  4046  4046 V BluetoothAdapterState: isBleTurningOn()=true
08-26 11:20:38.176  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 11:20:38.177  4046  4210 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-26 11:20:38.178  4046  4210 I bt_bluedroid: enable
,08-26 11:20:38.178  4046  4211 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 11:20:38.179  4046  4211 I bt_hci  : start_up
,08-26 11:20:38.193  4046  4211 I bt_vendor: alloc value 0xb39f9189
,08-26 11:20:38.194  4046  4211 I bt_vendor: init
08-26 11:20:38.194  4046  4211 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 11:20:38.194  4046  4211 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 11:20:38.302  4046  4211 D bt_hci  : start_up starting async portion
,08-26 11:20:38.302  4046  4218 I bt_hci  : event_finish_startup
,08-26 11:20:38.303  4046  4218 I bt_hci_h4: hal_open
,08-26 11:20:38.303  4046  4218 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0,
,08-26 11:20:38.315  4046  4218 I bt_userial_vendor: device fd = 51 open
,08-26 11:20:38.343  4046  4218 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 11:20:38.378  4046  4218 D bt_hwcfg: Chipset BCM4354A2
08-26 11:20:38.378  4046  4218 D bt_hwcfg: Target name = [BCM4354A2]
,08-26 11:20:38.379  4046  4218 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 11:20:39.054  4046  4218 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 11:20:39.055  4046  4218 D bt_hwcfg: Settlement delay -- 100 ms
08-26 11:20:39.055  4046  4218 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 11:20:39.172  4046  4218 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 11:20:39.173  4046  4218 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 11:20:39.203  4046  4218 I bt_hwcfg: vendor lib fwcfg completed
08-26 11:20:39.204  4046  4218 I bt_vendor: firmware callback
08-26 11:20:39.204  4046  4218 I bt_hci  : firmware_config_callback
,08-26 11:20:39.215  4046  4220 I bt_btu  : btu_task pending for preload complete event
08-26 11:20:39.215  4046  4220 I bt_btu_task: Bluetooth chip preload is complete
08-26 11:20:39.216  4046  4220 I bt_btu  : btu_task received preload complete event
,08-26 11:20:39.225  4046  4220 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 11:20:39.226  4046  4220 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 11:20:39.226  4046  4220 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 11:20:39.226  4046  4220 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 11:20:39.227  4046  4220 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 11:20:39.227  4046  4220 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 11:20:39.227  4046  4220 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-26 11:20:39.227  4046  4220 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 11:20:39.228  4046  4220 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 11:20:39.228  4046  4220 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 11:20:39.228  4046  4220 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 11:20:39.228  4046  4220 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 11:20:39.229  4046  4220 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 11:20:39.229  4046  4220 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 11:20:39.229  4046  4220 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 11:20:39.360  4046  4220 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
08-26 11:20:39.361  4046  4220 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,08-26 11:20:39.373  4046  4214 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 11:20:39.374  4046  4214 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 11:20:39.375  4046  4214 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 11:20:39.385  4046  4214 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 11:20:39.392  4046  4214 D BluetoothAdapterProperties: Scan Mode:20
,08-26 11:20:39.392  4046  4214 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 11:20:39.393  4046  4214 D bt_hci  : do_postload posting postload work item
08-26 11:20:39.393  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:39.393  4046  4218 I bt_hci  : event_postload
,08-26 11:20:39.393  4046  4218 I bt_vendor: sco_config_cb
,08-26 11:20:39.394  4046  4218 I bt_hci  : sco_config_callback postload finished.
08-26 11:20:39.395  4046  4218 I bt_vendor: low_power_mode_cb
08-26 11:20:39.397  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:39.400  4046  4214 D bt_bte_conf: Device ID record 1 : primary
08-26 11:20:39.400  4046  4214 D bt_bte_conf:   vendorId            = 000f
08-26 11:20:39.400  4046  4214 D bt_bte_conf:   vendorIdSource      = 0001
,08-26 11:20:39.400  4046  4214 D bt_bte_conf:   product             = 1200
08-26 11:20:39.400  4046  4214 D bt_bte_conf:   version             = 1436
08-26 11:20:39.400  4046  4214 D bt_bte_conf:   clientExecutableURL = 
08-26 11:20:39.400  4046  4214 D bt_bte_conf:   serviceDescription  = 
08-26 11:20:39.400  4046  4214 D bt_bte_conf:   documentationURL    = 
08-26 11:20:39.401  4046  4214 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 11:20:39.401  4046  4211 D bt_stack_manager: event_start_up_stack finished
08-26 11:20:39.401  4046  4210 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 11:20:39.401  4046  4210 D BluetoothAdapterProperties: Setting state to 15
08-26 11:20:39.402  4046  4210 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 11:20:39.403  4046  4210 I BluetoothAdapterState: Entering BleOnState
08-26 11:20:39.406  4046  4210 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-26 11:20:39.406  4046  4210 D BluetoothAdapterProperties: Setting state to 11
08-26 11:20:39.406  4046  4210 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 11:20:39.410  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
08-26 11:20:39.411  4046  4046 D HeadsetService: Received start request. Starting profile...,
,08-26 11:20:39.414  4046  4046 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 11:20:39.414  4046  4046 D HeadsetStateMachine: make
,08-26 11:20:39.421  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:39.425  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:39.429  4046  4046 D HeadsetStateMachine: max_hf_connections = 1
,08-26 11:20:39.429  4046  4046 I bt_bluedroid: get_profile_interface handsfree
,08-26 11:20:39.430  4046  4214 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 11:20:39.433  4046  4214 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-26 11:20:39.436  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
,08-26 11:20:39.437  4046  4046 D A2dpService: Received start request. Starting profile...
08-26 11:20:39.438  4046  4210 I BluetoothAdapterState: Entering PendingCommandState
08-26 11:20:39.439  4046  4046 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 11:20:39.439  4046  4046 I bt_bluedroid: get_profile_interface avrcp
,08-26 11:20:39.450  4046  4046 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 11:20:39.450  4046  4046 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 11:20:39.451  4046  4046 D A2dpStateMachine: make
08-26 11:20:39.452  4046  4046 I bt_bluedroid: get_profile_interface a2dp
,08-26 11:20:39.452  4046  4214 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 11:20:39.454  4046  4229 D A2dpStateMachine: Enter Disconnected: -2
,08-26 11:20:39.457  4046  4046 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 11:20:39.458  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 11:20:39.459  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
,08-26 11:20:39.461  4001  4001 D BluetoothInputDevice: Proxy object connected
,08-26 11:20:39.461  4046  4046 D HidService: Received start request. Starting profile...
08-26 11:20:39.461  4046  4046 I bt_bluedroid: get_profile_interface hidhost
08-26 11:20:39.462  4046  4214 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
,08-26 11:20:39.462  4046  4214 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 11:20:39.462  4046  4046 D HidService: setHidService(): set to: null
,08-26 11:20:39.463  4001  4001 D HidProfile: Bluetooth service connected
,08-26 11:20:39.464  4046  4046 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 11:20:39.465  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
,08-26 11:20:39.466  4046  4046 D HealthService: Received start request. Starting profile...
,08-26 11:20:39.467  4046  4046 I bt_bluedroid: get_profile_interface health
,08-26 11:20:39.468  4046  4046 V BluetoothAdapterState: isTurningOff()=false
08-26 11:20:39.468  4046  4046 V BluetoothAdapterState: isTurningOn()=true
08-26 11:20:39.468  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 11:20:39.468  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 11:20:39.471  4046  4046 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 11:20:39.472  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
,08-26 11:20:39.473  4001  4001 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 11:20:39.473  4046  4046 D PanService: Received start request. Starting profile...
08-26 11:20:39.474  4001  4001 D PanProfile: Bluetooth service connected
08-26 11:20:39.474  4046  4046 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 11:20:39.474  4046  4046 I bt_bluedroid: get_profile_interface pan
,08-26 11:20:39.474  4046  4214 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 11:20:39.477  4046  4226 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 11:20:39.478  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
,08-26 11:20:39.480  4001  4001 D BluetoothMap: Proxy object connected
08-26 11:20:39.480  4046  4046 D BluetoothMapService: Received start request. Starting profile...
08-26 11:20:39.480  4046  4046 D BluetoothMapService: start()
,08-26 11:20:39.480  4001  4001 D MapProfile: Bluetooth service connected
,08-26 11:20:39.480  4001  4001 D BluetoothMap: getConnectedDevices()
,08-26 11:20:39.481  4001  4001 D BluetoothMap: Bluetooth is Not enabled
08-26 11:20:39.482  4046  4046 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 11:20:39.482  4046  4046 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-26 11:20:39.482  4046  4046 D BluetoothMapAppObserver: createReceiver()
,08-26 11:20:39.483  4046  4046 D BluetoothMapAppObserver: initObservers()
,08-26 11:20:39.484  4046  4046 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 11:20:39.489  4046  4046 V BluetoothAdapterState: isTurningOff()=false
08-26 11:20:39.489  4046  4046 V BluetoothAdapterState: isTurningOn()=true
08-26 11:20:39.489  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:39.489  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 11:20:39.490  4046  4046 V BluetoothAdapterState: isTurningOff()=false
08-26 11:20:39.490  4046  4046 V BluetoothAdapterState: isTurningOn()=true
,08-26 11:20:39.490  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:39.490  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:39.490  4046  4046 V BluetoothAdapterState: isTurningOff()=false
08-26 11:20:39.490  4046  4046 V BluetoothAdapterState: isTurningOn()=true
08-26 11:20:39.490  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:39.490  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:39.490  4046  4046 V BluetoothAdapterState: isTurningOff()=false
08-26 11:20:39.490  4046  4046 V BluetoothAdapterState: isTurningOn()=true
08-26 11:20:39.491  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:39.491  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 11:20:39.491  4046  4046 V BluetoothAdapterState: isTurningOff()=false
,08-26 11:20:39.491  4046  4046 V BluetoothAdapterState: isTurningOn()=true
,08-26 11:20:39.491  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:39.491  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:39.491  4046  4210 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 11:20:39.491  4046  4210 D BluetoothAdapterProperties: ScanMode =  20
08-26 11:20:39.491  4046  4210 D BluetoothAdapterProperties: State =  11
,08-26 11:20:39.493  4046  4214 D BluetoothAdapterProperties: Scan Mode:21
08-26 11:20:39.494  4046  4210 D BluetoothAdapterProperties: Setting state to 12
08-26 11:20:39.494  4046  4210 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 11:20:39.494  4046  4214 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 11:20:39.494  4046  4210 I BluetoothAdapterState: Entering OnState
,08-26 11:20:39.494  1360  2090 D BluetoothPan: onBluetoothStateChange on: true
,08-26 11:20:39.496  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:39.496  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:39.496  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:39.496  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:39.496  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:39.496  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:39.496  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:39.496  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:39.497  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 11:20:39.497  4001  4011 D BluetoothPan: onBluetoothStateChange on: true
08-26 11:20:39.497  1360  1360 D PanProfile: Bluetooth service connected
,08-26 11:20:39.498   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 11:20:39.498  1360  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 11:20:39.498  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:39.499  1360  1360 D BluetoothInputDevice: Proxy object connected
08-26 11:20:39.499  1360  1360 D HidProfile: Bluetooth service connected
08-26 11:20:39.500  1952  1964 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 11:20:39.501  4001  4012 D BluetoothMap: onBluetoothStateChange: up=true
08-26 11:20:39.501  4001  4011 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 11:20:39.501  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:39.501  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:39.501  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:39.501  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:39.501  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:39.501  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:39.501  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:39.501  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:39.502   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 11:20:39.502  1360  1371 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 11:20:39.503  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:39.503  1360  1378 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 11:20:39.504   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 11:20:39.504  1360  2090 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 11:20:39.506  1360  1360 D BluetoothA2dp: Proxy object connected
08-26 11:20:39.506  1360  1371 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 11:20:39.507  1360  1360 D BluetoothMap: Proxy object connected
08-26 11:20:39.507  1360  1360 D MapProfile: Bluetooth service connected
08-26 11:20:39.507  1360  1360 D BluetoothMap: getConnectedDevices()
08-26 11:20:39.508   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 11:20:39.508   872   872 D BluetoothA2dp: Proxy object connected
08-26 11:20:39.508  4001  4012 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 11:20:39.509  4046  4046 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 11:20:39.509  4046  4046 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-26 11:20:39.511  4046  4046 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 11:20:39.513  4046  4046 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 11:20:39.514   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 11:20:39.514  4046  4046 D ObexServerSockets: Succeed to create listening sockets 
,08-26 11:20:39.515  4046  4046 D ObexServerSockets0: startAccept()
08-26 11:20:39.515  4046  4046 D ObexServerSockets0: prepareForNewConnect()
08-26 11:20:39.515  4001  4001 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-26 11:20:39.515  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:39.516  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:39.518  4046  4046 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 11:20:39.518  4046  4046 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 11:20:39.518  4046  4236 D ObexServerSockets0: Accepting socket connection...
,08-26 11:20:39.518  4046  4046 D BluetoothMapService: onReceive
08-26 11:20:39.519  4046  4046 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 11:20:39.519  4046  4046 D BluetoothMapService: STATE_ON
08-26 11:20:39.519  4046  4237 D ObexServerSockets0: Accepting socket connection...
08-26 11:20:39.519  4001  4001 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-26 11:20:39.524  4001  4001 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 11:20:39.528  4001  4001 D BluetoothA2dp: Proxy object connected
,08-26 11:20:39.531  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 11:20:39.536  4001  4001 D DockEventReceiver: finishStartingService: stopping service
,08-26 11:20:39.549  1360  1360 D BluetoothPbap: Proxy object connected
,08-26 11:20:39.549  1360  1360 D PbapServerProfile: Bluetooth service connected
,08-26 11:20:39.550  4001  4001 D BluetoothPbap: Proxy object connected
08-26 11:20:39.550  4001  4001 D PbapServerProfile: Bluetooth service connected
,08-26 11:20:39.555  4046  4046 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 11:20:39.555  4046  4046 D ObexServerSockets0: prepareForNewConnect()
,08-26 11:20:39.564  4046  4241 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 11:20:39.578  4046  4245 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 11:20:39.580  4046  4245 I BtOppRfcommListener: Accept thread started.
,08-26 11:20:39.599  1952  2305 D BluetoothHeadset: Proxy object connected
,08-26 11:20:39.599  1360  2090 D BluetoothHeadset: Proxy object connected
,08-26 11:20:39.599  1360  1360 D HeadsetProfile: Bluetooth service connected
08-26 11:20:39.600   872   872 D BluetoothHeadset: Proxy object connected
08-26 11:20:39.600   872   872 D BluetoothHeadset: Proxy object connected
08-26 11:20:39.600   872   872 D BluetoothHeadset: Proxy object connected
,08-26 11:20:39.601  1952  2306 D BluetoothHeadset: Proxy object connected
,08-26 11:20:39.602   872   889 D BluetoothHeadset: Proxy object connected
,08-26 11:20:39.604  1360  1371 D BluetoothHeadset: Proxy object connected
,08-26 11:20:39.604  1360  1360 D HeadsetProfile: Bluetooth service connected
08-26 11:20:39.604   872   889 D BluetoothHeadset: Proxy object connected
,08-26 11:20:39.622  4001  4011 D BluetoothHeadset: Proxy object connected
,08-26 11:20:39.624  4001  4001 D HeadsetProfile: Bluetooth service connected
,08-26 11:20:41.066   872  1317 D ConnectivityService: handlePromptUnvalidated 101
,08-26 11:20:41.071  4046  4210 D BluetoothAdapterState: Current state: ON, message: 23
08-26 11:20:41.071  4046  4210 D BluetoothAdapterProperties: Setting state to 13
,08-26 11:20:41.071  4046  4210 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 11:20:41.073  4046  4210 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 11:20:41.079  4046  4210 I BluetoothAdapterState: Entering PendingCommandState
,08-26 11:20:41.090  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:41.090  4046  4046 D BluetoothMapService: onReceive
08-26 11:20:41.091  4046  4046 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 11:20:41.091  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:41.091  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:41.091  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:41.091  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:41.091  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:41.091  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:41.091  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:41.091  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 11:20:41.091  4046  4046 D BluetoothMapService: STATE_TURNING_OFF
08-26 11:20:41.092  4046  4046 D BluetoothMapService: MAP Service closeService in
08-26 11:20:41.093  4046  4046 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 11:20:41.094  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 11:20:41.094  4046  4046 D ObexServerSockets0: shutdown(block = true)
08-26 11:20:41.094  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:41.095  4046  4236 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-26 11:20:41.099  4046  4046 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 11:20:41.100  4046  4237 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 11:20:41.100  4046  4214 D BluetoothAdapterProperties: Scan Mode:20
08-26 11:20:41.101  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:41.101  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:41.101  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:41.101  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:41.101  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:41.101  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 11:20:41.101  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:41.101  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:41.101  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 11:20:41.101  4046  4210 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 11:20:41.101  4046  4223 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 11:20:41.102  3883  3883 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 11:20:41.102  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:41.102  4001  4001 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 11:20:41.102  4046  4046 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 11:20:41.103  4046  4046 I BtOppRfcommListener: stopping Accept Thread
08-26 11:20:41.103  4046  4245 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 11:20:41.103  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:41.105  4046  4245 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 11:20:41.105  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:41.117  4046  4046 D HeadsetService: Received stop request...Stopping profile...
08-26 11:20:41.119  4001  4011 D BluetoothHeadset: Proxy object disconnected
08-26 11:20:41.120  4046  4046 D A2dpService: Received stop request...Stopping profile...
08-26 11:20:41.120  1952  1973 D BluetoothHeadset: Proxy object disconnected
08-26 11:20:41.120  4046  4229 D A2dpStateMachine: Exit Disconnected: -1
08-26 11:20:41.120  1360  1378 D BluetoothHeadset: Proxy object disconnected
08-26 11:20:41.121   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 11:20:41.121  1360  1360 D HeadsetProfile: Bluetooth service disconnected
08-26 11:20:41.121   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 11:20:41.121   872   872 D BluetoothHeadset: Proxy object disconnected
,08-26 11:20:41.122   872   872 D BluetoothA2dp: Proxy object disconnected
,08-26 11:20:41.123  1360  1360 D BluetoothA2dp: Proxy object disconnected
,08-26 11:20:41.124  4001  4001 D DockEventReceiver: finishStartingService: stopping service
08-26 11:20:41.124  4001  4001 D HeadsetProfile: Bluetooth service disconnected
08-26 11:20:41.125  4046  4046 D HidService: Received stop request...Stopping profile...
08-26 11:20:41.125  4046  4046 D HidService: Stopping Bluetooth HidService
08-26 11:20:41.125  4001  4001 D BluetoothA2dp: Proxy object disconnected
08-26 11:20:41.126  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 11:20:41.128  1360  1360 D BluetoothInputDevice: Proxy object disconnected
08-26 11:20:41.128  1360  1360 D HidProfile: Bluetooth service disconnected
08-26 11:20:41.128  4001  4001 D BluetoothInputDevice: Proxy object disconnected
,08-26 11:20:41.128  4001  4001 D HidProfile: Bluetooth service disconnected
,08-26 11:20:41.130  4046  4046 D HealthService: Received stop request...Stopping profile...
,08-26 11:20:41.132  4046  4046 D PanService: Received stop request...Stopping profile...
,08-26 11:20:41.133  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 11:20:41.133  1360  1360 D PanProfile: Bluetooth service disconnected
08-26 11:20:41.133  4001  4001 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 11:20:41.134  4001  4001 D PanProfile: Bluetooth service disconnected
08-26 11:20:41.134  4046  4046 V BluetoothAdapterState: isTurningOff()=true
08-26 11:20:41.134  4046  4046 V BluetoothAdapterState: isTurningOn()=false
08-26 11:20:41.134  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 11:20:41.134  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 11:20:41.135  4046  4046 D BluetoothMapService: Received stop request...Stopping profile...
08-26 11:20:41.135  4046  4046 D BluetoothMapService: stop()
08-26 11:20:41.136  4046  4046 D BluetoothMapAppObserver: deinitObservers()
,08-26 11:20:41.136  4046  4046 D BluetoothMapAppObserver: removeReceiver()
08-26 11:20:41.137  1360  1360 D BluetoothMap: Proxy object disconnected
,08-26 11:20:41.137  1360  1360 D MapProfile: Bluetooth service disconnected
08-26 11:20:41.138  4001  4001 D BluetoothMap: Proxy object disconnected
08-26 11:20:41.138  4001  4001 D MapProfile: Bluetooth service disconnected
,08-26 11:20:41.139  4046  4046 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 11:20:41.139  4046  4046 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 11:20:41.139  4046  4214 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 11:20:41.139  4046  4046 V BluetoothAdapterState: isTurningOff()=true
,08-26 11:20:41.139  4046  4046 V BluetoothAdapterState: isTurningOn()=false
08-26 11:20:41.139  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:41.139  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:41.139  4046  4220 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 11:20:41.139  4046  4220 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 11:20:41.139  4046  4220 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 11:20:41.141  4046  4214 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
,08-26 11:20:41.141  4046  4214 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-26 11:20:41.141  4046  4220 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 11:20:41.142  4046  4220 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 11:20:41.142  4046  4220 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 11:20:41.142  4046  4220 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 11:20:41.142  4046  4220 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 11:20:41.142  4046  4220 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 11:20:41.144  4046  4046 V BluetoothAdapterState: isTurningOff()=true
,08-26 11:20:41.144  4046  4046 V BluetoothAdapterState: isTurningOn()=false
08-26 11:20:41.144  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:41.144  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:41.144  4046  4046 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 11:20:41.145  4046  4214 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 11:20:41.145  4046  4046 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-26 11:20:41.145  1360  1360 D BluetoothPbap: Proxy object disconnected
08-26 11:20:41.145  1360  1360 D PbapServerProfile: Bluetooth service disconnected
08-26 11:20:41.145  4046  4046 V BluetoothAdapterState: isTurningOff()=true
08-26 11:20:41.145  4046  4046 V BluetoothAdapterState: isTurningOn()=false
08-26 11:20:41.145  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:41.145  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:41.146  4001  4001 D BluetoothPbap: Proxy object disconnected
,08-26 11:20:41.146  4001  4001 D PbapServerProfile: Bluetooth service disconnected
08-26 11:20:41.147  4046  4046 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 11:20:41.147  4046  4214 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 11:20:41.148  4046  4046 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 11:20:41.148  4046  4046 V BluetoothAdapterState: isTurningOff()=true
08-26 11:20:41.148  4046  4046 V BluetoothAdapterState: isTurningOn()=false
,08-26 11:20:41.148  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 11:20:41.148  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:41.149  4046  4046 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 11:20:41.149  4046  4046 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 11:20:41.156  4046  4046 D BluetoothMapService: MAP Service closeService in
08-26 11:20:41.156  4046  4046 V BluetoothAdapterState: isTurningOff()=true
08-26 11:20:41.156  4046  4046 V BluetoothAdapterState: isTurningOn()=false
,08-26 11:20:41.156  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:41.156  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:41.157  4046  4210 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 11:20:41.157  4046  4210 D BluetoothAdapterProperties: Setting state to 15
08-26 11:20:41.157  4046  4210 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 11:20:41.157  4046  4210 I BluetoothAdapterState: Entering BleOnState
08-26 11:20:41.158  4046  4046 D BluetoothMapService: cleanup()
08-26 11:20:41.158  1360  1378 D BluetoothPan: onBluetoothStateChange on: false
,08-26 11:20:41.158  4046  4046 D BluetoothMapService: MAP Service closeService in
08-26 11:20:41.158  4001  4012 D BluetoothPan: onBluetoothStateChange on: false
08-26 11:20:41.159   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 11:20:41.159  4001  4011 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 11:20:41.159  1360  2090 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 11:20:41.160  1952  2176 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 11:20:41.160  4001  4012 D BluetoothMap: onBluetoothStateChange: up=false
08-26 11:20:41.161  4001  4011 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 11:20:41.161   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 11:20:41.161  1360  1371 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 11:20:41.162  1360  1378 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 11:20:41.162   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 11:20:41.162  1360  2090 D BluetoothMap: onBluetoothStateChange: up=false
08-26 11:20:41.163  1360  1371 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 11:20:41.163  4001  4012 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 11:20:41.164   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 11:20:41.164  4001  4011 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 11:20:41.164  4046  4210 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 11:20:41.165  4046  4210 D BluetoothAdapterProperties: Setting state to 16
08-26 11:20:41.165  4046  4210 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 11:20:41.165  4046  4210 D BluetoothAdapterProperties: onBleDisable
08-26 11:20:41.166  4046  4211 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 11:20:41.168  4046  4220 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 11:20:41.168  4046  4220 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 11:20:41.169  4046  4210 I BluetoothAdapterState: Entering PendingCommandState
,08-26 11:20:41.169  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:41.171  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:41.171  4046  4214 D BluetoothAdapterProperties: Scan Mode:20
,08-26 11:20:41.173  4001  4001 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 11:20:41.173  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:41.174  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:41.177  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 11:20:41.181  4001  4001 D DockEventReceiver: finishStartingService: stopping service
,08-26 11:20:41.369  4046  4214 I bt_hci  : shut_down
,08-26 11:20:41.390  4046  4218 D bt_hwcfg: hw_epilog_process
,08-26 11:20:41.391  4046  4218 I bt_vendor: low_power_mode_cb
,08-26 11:20:41.409  4046  4218 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 11:20:41.410  4046  4218 I bt_vendor: epilog_cb
08-26 11:20:41.410  4046  4218 I bt_hci  : epilog_finished_callback
,08-26 11:20:41.419  4046  4214 I bt_hci_h4: hal_close
,08-26 11:20:41.420  4046  4214 I bt_userial_vendor: device fd = 51 close
,08-26 11:20:41.535  4046  4211 D bt_stack_manager: event_shut_down_stack finished.
,08-26 11:20:41.536  4046  4210 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 11:20:41.543  4046  4046 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 11:20:41.543  4046  4210 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-26 11:20:41.545  4046  4046 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 11:20:41.545  4046  4046 D BtGatt.GattService: stop()
,08-26 11:20:41.545  4046  4046 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 11:20:41.551  4046  4046 V BluetoothAdapterState: isTurningOff()=false
,08-26 11:20:41.552  4046  4046 V BluetoothAdapterState: isTurningOn()=false
08-26 11:20:41.552  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:41.552  4046  4046 V BluetoothAdapterState: isBleTurningOff()=true
,08-26 11:20:41.553  4046  4210 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-26 11:20:41.554  4046  4210 D BluetoothAdapterProperties: Setting state to 10
08-26 11:20:41.555  4046  4210 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 11:20:41.557  4046  4210 I BluetoothAdapterState: Entering OffState
,08-26 11:20:41.559   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 11:20:41.581  4046  4046 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 11:20:41.581  4046  4046 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 11:20:41.581  4046  4211 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 11:20:41.584  4046  4211 D bt_stack_manager: event_clean_up_stack finished.
08-26 11:20:41.584  4046  4046 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 11:20:41.586  4046  4046 I art     : System.exit called, status: 0
,08-26 11:20:41.586  4046  4046 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 11:20:41.627   872  2003 I ActivityManager: Process com.android.bluetooth (pid 4046) has died
,08-26 11:20:44.065  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 11:20:44.065  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:46.346   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-26 11:20:46.365  1876  1876 I Keyboard.Facilitator: onFinishInput()
,08-26 11:20:46.376   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 11:20:46.376   872   892 I Adreno  : Build Date                       : 10/20/15
08-26 11:20:46.376   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 11:20:46.376   872   892 I Adreno  : Local Branch                     : M14
08-26 11:20:46.376   872   892 I Adreno  : Remote Branch                    : 
08-26 11:20:46.376   872   892 I Adreno  : Remote Branch                    : 
08-26 11:20:46.376   872   892 I Adreno  : Reconstruct Branch               : 
,08-26 11:20:46.415   280   347 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (183 us)
,08-26 11:20:47.044  3883  3883 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 11:20:47.045  3883  3883 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 11:20:47.069  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 11:20:47.069  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f61434f added. We now have 6 listener(s)
,08-26 11:20:47.069  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:47.071  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:47.071  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d05eadc added. We now have 7 listener(s)
08-26 11:20:47.071  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:47.071  3883  3947 I System.out: IsBluetoothEnabled
,08-26 11:20:47.095   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-26 11:20:47.098  3883  3883 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@53ee097 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@b3c37e5, 16908290=android.view.AbsSavedState$1@b3c37e5}, android:focusedViewId=100}]}]
,08-26 11:20:47.098  3883  3883 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 11:20:47.098  3883  3883 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 11:20:47.098  3883  3883 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 11:20:47.105   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
08-26 11:20:47.106  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:47.111   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-26 11:20:47.111   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-26 11:20:47.111   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-26 11:20:47.131   872   889 I ActivityManager: Start proc 4258:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 11:20:47.135   872   881 I art     : Background partial concurrent mark sweep GC freed 34640(2MB) AllocSpace objects, 13(448KB) LOS objects, 33% free, 29MB/43MB, paused 1.160ms total 114.006ms
,08-26 11:20:47.187  4258  4258 D AdapterServiceConfig: Adding HeadsetService
,08-26 11:20:47.187  4258  4258 D AdapterServiceConfig: Adding A2dpService
08-26 11:20:47.188  4258  4258 D AdapterServiceConfig: Adding HidService
08-26 11:20:47.188  4258  4258 D AdapterServiceConfig: Adding HealthService
,08-26 11:20:47.188  4258  4258 D AdapterServiceConfig: Adding PanService
08-26 11:20:47.188  4258  4258 D AdapterServiceConfig: Adding GattService
08-26 11:20:47.188  4258  4258 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 11:20:47.200   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@54d6799:true
,08-26 11:20:47.200  4258  4258 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 11:20:47.203  4258  4258 I bt_bluedroid: init
,08-26 11:20:47.203  4258  4271 I BluetoothAdapterState: Entering OffState
,08-26 11:20:47.204  4258  4272 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 11:20:47.204  4258  4272 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 11:20:47.204  4258  4272 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 11:20:47.204  4258  4272 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 11:20:47.205  4258  4258 I bt_bluedroid: get_profile_interface socket
,08-26 11:20:47.206  4258  4258 I bt_bluedroid: get_profile_interface sdp
,08-26 11:20:47.209  4258  4270 I bt_bluedroid: config_hci_snoop_log
,08-26 11:20:47.209   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 11:20:47.209  4258  4275 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 11:20:47.212  4258  4275 D BluetoothAdapterProperties: Name is: Nexus 6
08-26 11:20:47.212  4258  4271 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 11:20:47.212  4258  4271 D BluetoothAdapterProperties: Setting state to 14
08-26 11:20:47.212  4258  4271 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 11:20:47.223  4258  4271 D BluetoothBondStateMachine: make
,08-26 11:20:47.226  4258  4276 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 11:20:47.230  4258  4258 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 11:20:47.230  4258  4271 I BluetoothAdapterState: Entering PendingCommandState
,08-26 11:20:47.232  4258  4258 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
,08-26 11:20:47.232  4258  4258 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 11:20:47.233  4258  4258 D BtGatt.GattService: Received start request. Starting profile...
08-26 11:20:47.233  4258  4258 D BtGatt.GattService: start()
08-26 11:20:47.233  4258  4258 I bt_bluedroid: get_profile_interface gatt
,08-26 11:20:47.233  4258  4258 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
08-26 11:20:47.233  4258  4258 D BtGatt.AdvertiseManager: advertise manager created
,08-26 11:20:47.238  4258  4258 V BluetoothAdapterState: isTurningOff()=false
,08-26 11:20:47.238  4258  4258 V BluetoothAdapterState: isTurningOn()=false
08-26 11:20:47.238  4258  4258 V BluetoothAdapterState: isBleTurningOn()=true
08-26 11:20:47.238  4258  4258 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 11:20:47.238  4258  4271 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 11:20:47.239  4258  4271 I bt_bluedroid: enable
08-26 11:20:47.239  4258  4272 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 11:20:47.239  4258  4272 I bt_hci  : start_up
,08-26 11:20:47.244  4258  4272 I bt_vendor: alloc value 0xb3a67189
,08-26 11:20:47.244  4258  4272 I bt_vendor: init
08-26 11:20:47.244  4258  4272 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 11:20:47.244  4258  4272 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 11:20:47.347   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-26 11:20:47.351   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-26 11:20:47.352  4258  4272 D bt_hci  : start_up starting async portion
08-26 11:20:47.353   872  1340 D SurfaceControl: Excessive delay in setPowerMode(): 242ms,
08-26 11:20:47.353  4258  4279 I bt_hci  : event_finish_startup
,08-26 11:20:47.353  4258  4279 I bt_hci_h4: hal_open
08-26 11:20:47.354  4258  4279 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 11:20:47.358   872   892 I DreamManagerService: Entering dreamland.
,08-26 11:20:47.360   872   892 I PowerManagerService: Dozing...
08-26 11:20:47.362   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
08-26 11:20:47.363  4258  4279 I bt_userial_vendor: device fd = 51 open
,08-26 11:20:47.393  4258  4279 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 11:20:47.425  4258  4279 D bt_hwcfg: Chipset BCM4354A2
,08-26 11:20:47.425  4258  4279 D bt_hwcfg: Target name = [BCM4354A2]
08-26 11:20:47.426  4258  4279 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 11:20:47.446   375  1470 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-26 11:20:47.447   375  1470 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-26 11:20:47.457   872  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 11:20:47.471   872  1315 E native  : do suspend false
,08-26 11:20:47.494  1937  4282 D NfcService: Discovery configuration equal, not updating.
,08-26 11:20:47.531   872  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 11:20:47.535   872  1315 E native  : do suspend true
,08-26 11:20:47.571   375  1286 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-26 11:20:47.571   375  1286 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-26 11:20:48.079  4258  4279 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-26 11:20:48.080  4258  4279 D bt_hwcfg: Settlement delay -- 100 ms
08-26 11:20:48.080  4258  4279 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 11:20:48.197  4258  4279 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 11:20:48.198  4258  4279 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 11:20:48.228  4258  4279 I bt_hwcfg: vendor lib fwcfg completed
,08-26 11:20:48.228  4258  4279 I bt_vendor: firmware callback
08-26 11:20:48.229  4258  4279 I bt_hci  : firmware_config_callback
,08-26 11:20:48.242  4258  4286 I bt_btu  : btu_task pending for preload complete event
,08-26 11:20:48.242  4258  4286 I bt_btu_task: Bluetooth chip preload is complete
,08-26 11:20:48.243  4258  4286 I bt_btu  : btu_task received preload complete event
,08-26 11:20:48.254  4258  4286 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 11:20:48.255  4258  4286 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 11:20:48.255  4258  4286 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 11:20:48.255  4258  4286 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 11:20:48.256  4258  4286 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 11:20:48.256  4258  4286 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 11:20:48.256  4258  4286 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 11:20:48.257  4258  4286 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 11:20:48.257  4258  4286 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 11:20:48.257  4258  4286 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 11:20:48.258  4258  4286 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 11:20:48.258  4258  4286 I         : BTE_InitTraceLevels -- TRC_GATT
,08-26 11:20:48.258  4258  4286 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 11:20:48.259  4258  4286 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 11:20:48.259  4258  4286 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 11:20:48.393  4258  4286 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39e4d9d
,08-26 11:20:48.394  4258  4286 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39e4d9d 
,08-26 11:20:48.403  4258  4275 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 11:20:48.407  4258  4275 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 11:20:48.408  4258  4275 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 11:20:48.413  4258  4275 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 11:20:48.416  4258  4275 D BluetoothAdapterProperties: Scan Mode:20
,08-26 11:20:48.417  4258  4275 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 11:20:48.417  4258  4275 D bt_hci  : do_postload posting postload work item
08-26 11:20:48.418  4258  4279 I bt_hci  : event_postload
,08-26 11:20:48.418  4258  4279 I bt_vendor: sco_config_cb
08-26 11:20:48.418  4258  4279 I bt_hci  : sco_config_callback postload finished.
,08-26 11:20:48.419  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:48.425  4258  4275 D bt_bte_conf: Device ID record 1 : primary
,08-26 11:20:48.425  4258  4275 D bt_bte_conf:   vendorId            = 000f
,08-26 11:20:48.425  4258  4275 D bt_bte_conf:   vendorIdSource      = 0001
08-26 11:20:48.426  4258  4275 D bt_bte_conf:   product             = 1200
,08-26 11:20:48.426  4258  4275 D bt_bte_conf:   version             = 1436
,08-26 11:20:48.427  4258  4275 D bt_bte_conf:   clientExecutableURL = 
08-26 11:20:48.427  4258  4275 D bt_bte_conf:   serviceDescription  = 
08-26 11:20:48.427  4258  4279 I bt_vendor: low_power_mode_cb
08-26 11:20:48.427  4258  4275 D bt_bte_conf:   documentationURL    = 
08-26 11:20:48.428  4258  4275 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 11:20:48.429  4258  4272 D bt_stack_manager: event_start_up_stack finished
08-26 11:20:48.430  4258  4271 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 11:20:48.431  4258  4271 D BluetoothAdapterProperties: Setting state to 15
08-26 11:20:48.431  4258  4271 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 11:20:48.433  4258  4271 I BluetoothAdapterState: Entering BleOnState
,08-26 11:20:48.437  4258  4271 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-26 11:20:48.437  4258  4271 D BluetoothAdapterProperties: Setting state to 11
08-26 11:20:48.437  4258  4271 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 11:20:48.441  4258  4258 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
,08-26 11:20:48.443  4258  4258 D HeadsetService: Received start request. Starting profile...
,08-26 11:20:48.447  4258  4258 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 11:20:48.448  4258  4258 D HeadsetStateMachine: make
08-26 11:20:48.448  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:48.460  4258  4258 D HeadsetStateMachine: max_hf_connections = 1
08-26 11:20:48.460  4258  4258 I bt_bluedroid: get_profile_interface handsfree
08-26 11:20:48.460  4258  4275 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 11:20:48.461  4258  4275 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-26 11:20:48.461  4258  4271 I BluetoothAdapterState: Entering PendingCommandState
08-26 11:20:48.465  4258  4258 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
08-26 11:20:48.466  4258  4258 D A2dpService: Received start request. Starting profile...
08-26 11:20:48.467  4258  4258 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 11:20:48.467  4258  4258 I bt_bluedroid: get_profile_interface avrcp
,08-26 11:20:48.474  4258  4258 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 11:20:48.474  4258  4258 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 11:20:48.474  4258  4258 D A2dpStateMachine: make
,08-26 11:20:48.475  4258  4258 I bt_bluedroid: get_profile_interface a2dp
,08-26 11:20:48.476  4258  4275 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 11:20:48.477  4258  4295 D A2dpStateMachine: Enter Disconnected: -2
08-26 11:20:48.480  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 11:20:48.480  4258  4258 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 11:20:48.481  4258  4258 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
,08-26 11:20:48.482  4258  4258 D HidService: Received start request. Starting profile...
,08-26 11:20:48.483  4258  4258 I bt_bluedroid: get_profile_interface hidhost
08-26 11:20:48.483  4258  4258 D HidService: setHidService(): set to: null
08-26 11:20:48.483  4258  4275 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c63e5
08-26 11:20:48.483  4258  4275 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-26 11:20:48.485  4258  4258 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 11:20:48.486  4258  4258 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
,08-26 11:20:48.487  4258  4258 D HealthService: Received start request. Starting profile...
,08-26 11:20:48.488  4258  4258 I bt_bluedroid: get_profile_interface health
,08-26 11:20:48.489  4258  4258 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 11:20:48.490  4258  4258 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
,08-26 11:20:48.491  4258  4258 D PanService: Received start request. Starting profile...
08-26 11:20:48.491  4258  4258 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 11:20:48.491  4258  4258 I bt_bluedroid: get_profile_interface pan
,08-26 11:20:48.492  4258  4275 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 11:20:48.495  4258  4258 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
,08-26 11:20:48.495  4258  4258 D BluetoothMapService: Received start request. Starting profile...
08-26 11:20:48.496  4258  4258 D BluetoothMapService: start()
,08-26 11:20:48.498  4258  4258 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 11:20:48.499  4258  4258 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 11:20:48.499  4258  4258 D BluetoothMapAppObserver: createReceiver()
,08-26 11:20:48.500  4258  4258 D BluetoothMapAppObserver: initObservers()
08-26 11:20:48.500  4258  4258 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 11:20:48.506  4258  4258 V BluetoothAdapterState: isTurningOff()=false
,08-26 11:20:48.507  4258  4258 V BluetoothAdapterState: isTurningOn()=true
08-26 11:20:48.507  4258  4258 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 11:20:48.507  4258  4258 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 11:20:48.509  4258  4258 V BluetoothAdapterState: isTurningOff()=false
08-26 11:20:48.509  4258  4258 V BluetoothAdapterState: isTurningOn()=true
,08-26 11:20:48.509  4258  4258 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:48.509  4258  4258 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:48.509  4258  4293 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 11:20:48.513  4258  4258 V BluetoothAdapterState: isTurningOff()=false
,08-26 11:20:48.513  4258  4258 V BluetoothAdapterState: isTurningOn()=true
,08-26 11:20:48.513  4258  4258 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:48.513  4258  4258 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:48.513  4258  4258 V BluetoothAdapterState: isTurningOff()=false
08-26 11:20:48.514  4258  4258 V BluetoothAdapterState: isTurningOn()=true
08-26 11:20:48.514  4258  4258 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:48.514  4258  4258 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:48.514  4258  4258 V BluetoothAdapterState: isTurningOff()=false
08-26 11:20:48.514  4258  4258 V BluetoothAdapterState: isTurningOn()=true
08-26 11:20:48.514  4258  4258 V BluetoothAdapterState: isBleTurningOn()=false
08-26 11:20:48.514  4258  4258 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:48.514  4258  4258 V BluetoothAdapterState: isTurningOff()=false
08-26 11:20:48.514  4258  4258 V BluetoothAdapterState: isTurningOn()=true
08-26 11:20:48.514  4258  4258 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 11:20:48.515  4258  4258 V BluetoothAdapterState: isBleTurningOff()=false
08-26 11:20:48.515  4258  4271 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 11:20:48.515  4258  4271 D BluetoothAdapterProperties: ScanMode =  20
08-26 11:20:48.515  4258  4271 D BluetoothAdapterProperties: State =  11
08-26 11:20:48.515  4258  4271 D BluetoothAdapterProperties: Setting state to 12
08-26 11:20:48.515  4258  4271 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 11:20:48.516  4258  4271 I BluetoothAdapterState: Entering OnState
08-26 11:20:48.516  1360  2090 D BluetoothPan: onBluetoothStateChange on: true
,08-26 11:20:48.518  4258  4275 D BluetoothAdapterProperties: Scan Mode:21
08-26 11:20:48.518  4258  4275 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 11:20:48.520  4001  4012 D BluetoothPan: onBluetoothStateChange on: true
,08-26 11:20:48.521  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 11:20:48.521  1360  1360 D PanProfile: Bluetooth service connected
08-26 11:20:48.522   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 11:20:48.523  4001  4011 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 11:20:48.523  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:48.523  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:48.523  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:48.523  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:48.523  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:48.523  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:48.523  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:48.523  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 11:20:48.523  4001  4001 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 11:20:48.523  1360  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 11:20:48.523  4001  4001 D PanProfile: Bluetooth service connected
08-26 11:20:48.525  1952  2305 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 11:20:48.525  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:48.526  1360  1360 D BluetoothInputDevice: Proxy object connected
08-26 11:20:48.526  1360  1360 D HidProfile: Bluetooth service connected
08-26 11:20:48.527  4001  4012 D BluetoothMap: onBluetoothStateChange: up=true
08-26 11:20:48.527  4258  4258 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 11:20:48.528  4258  4258 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 11:20:48.529  4001  4011 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 11:20:48.530  4258  4258 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 11:20:48.530   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 11:20:48.531  1360  2090 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 11:20:48.532  4258  4258 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 11:20:48.534  4258  4258 D ObexServerSockets: Succeed to create listening sockets 
,08-26 11:20:48.534  1360  4269 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 11:20:48.534  4258  4258 D ObexServerSockets0: startAccept()
08-26 11:20:48.534  4258  4258 D ObexServerSockets0: prepareForNewConnect()
,08-26 11:20:48.534   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 11:20:48.534  1360  1378 D BluetoothMap: onBluetoothStateChange: up=true
08-26 11:20:48.536  4258  4258 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 11:20:48.536  4258  4258 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 11:20:48.536  1360  1371 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 11:20:48.537  4258  4301 D ObexServerSockets0: Accepting socket connection...
08-26 11:20:48.538  4258  4302 D ObexServerSockets0: Accepting socket connection...
08-26 11:20:48.538  1360  1360 D BluetoothMap: Proxy object connected
08-26 11:20:48.538  4001  4012 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 11:20:48.538  1360  1360 D MapProfile: Bluetooth service connected
08-26 11:20:48.538  1360  1360 D BluetoothMap: getConnectedDevices()
,08-26 11:20:48.540   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 11:20:48.541  1360  1360 D BluetoothA2dp: Proxy object connected
08-26 11:20:48.541   872   872 D BluetoothA2dp: Proxy object connected
,08-26 11:20:48.541  4001  4300 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 11:20:48.544  4001  4001 D BluetoothMap: Proxy object connected
08-26 11:20:48.544  4001  4001 D MapProfile: Bluetooth service connected
,08-26 11:20:48.544  4001  4001 D BluetoothMap: getConnectedDevices()
08-26 11:20:48.544   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 11:20:48.547  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:48.547  4258  4258 D BluetoothMapService: onReceive
08-26 11:20:48.547  4258  4258 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 11:20:48.547  4258  4258 D BluetoothMapService: STATE_ON
,08-26 11:20:48.549  4001  4001 D BluetoothA2dp: Proxy object connected
,08-26 11:20:48.551  4001  4001 D BluetoothInputDevice: Proxy object connected
,08-26 11:20:48.551  4001  4001 D HidProfile: Bluetooth service connected
,08-26 11:20:48.557  4001  4001 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 11:20:48.563  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 11:20:48.564  4001  4001 D DockEventReceiver: finishStartingService: stopping service
,08-26 11:20:48.571  4001  4001 D BluetoothPbap: Proxy object connected
08-26 11:20:48.571  4001  4001 D PbapServerProfile: Bluetooth service connected
,08-26 11:20:48.573  1360  1360 D BluetoothPbap: Proxy object connected
08-26 11:20:48.573  1360  1360 D PbapServerProfile: Bluetooth service connected
,08-26 11:20:48.578  4258  4258 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 11:20:48.578  4258  4258 D ObexServerSockets0: prepareForNewConnect()
,08-26 11:20:48.580  4258  4307 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 11:20:48.597  4258  4311 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 11:20:48.599  4258  4311 I BtOppRfcommListener: Accept thread started.
,08-26 11:20:48.625  4001  4011 D BluetoothHeadset: Proxy object connected
08-26 11:20:48.626  1952  1973 D BluetoothHeadset: Proxy object connected
,08-26 11:20:48.626  1952  2306 D BluetoothHeadset: Proxy object connected
08-26 11:20:48.626  4001  4001 D HeadsetProfile: Bluetooth service connected
,08-26 11:20:48.626  1360  1371 D BluetoothHeadset: Proxy object connected
,08-26 11:20:48.627  1360  1360 D HeadsetProfile: Bluetooth service connected
08-26 11:20:48.627   872   872 D BluetoothHeadset: Proxy object connected
08-26 11:20:48.627   872   872 D BluetoothHeadset: Proxy object connected
08-26 11:20:48.627   872   872 D BluetoothHeadset: Proxy object connected
,08-26 11:20:48.630   872   889 D BluetoothHeadset: Proxy object connected
,08-26 11:20:48.634  1360  4269 D BluetoothHeadset: Proxy object connected
,08-26 11:20:48.635   872   889 D BluetoothHeadset: Proxy object connected
08-26 11:20:48.635  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-26 11:20:49.129  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:49.129  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:49.129  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:49.129  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 11:20:49.129  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:49.129  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:49.129  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:49.129  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 11:20:49.136  3883  3947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 11:20:49.140  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 11:20:49.141  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c9c2ba added. We now have 8 listener(s)
08-26 11:20:49.141  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 11:20:49.147   872  1998 D WifiService: setWifiEnabled: false pid=3883, uid=10000
,08-26 11:20:49.147   872  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 11:20:49.162  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:49.163   872  2003 D WifiService: setWifiEnabled: true pid=3883, uid=10000
08-26 11:20:49.163   872  2003 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 11:20:49.179   872  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-26 11:20:49.197  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:49.197  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:49.197  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:49.197  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:49.197  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:49.197  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:49.197  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:49.197  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 11:20:49.202  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 11:20:49.214   872  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-26 11:20:49.215   872  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 11:20:49.216   872  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-26 11:20:49.217   872  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 11:20:49.218   872  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-26 11:20:49.218   872  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-26 11:20:49.218   872  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 11:20:49.235   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 11:20:49.236   872  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.05 rxSuccessRate=0.06 delta 1000 -> 1000
,08-26 11:20:49.236   872  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-26 11:20:49.237   371   870 D CommandListener: Setting iface cfg
,08-26 11:20:49.238   872  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-26 11:20:49.238   872  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 11:20:49.249   872  1315 E native  : do suspend true
,08-26 11:20:49.249   872  1314 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 11:20:49.255   872  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 11:20:49.271   872  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 11:20:49.272   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 11:20:49.286   872  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 11:20:49.367   872  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 11:20:49.369  1472  1472 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 11:20:49.799  1472  1472 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 11:20:49.843  1472  1472 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 11:20:49.843  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 11:20:49.852   872  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 11:20:49.863   872  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 11:20:49.863   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 11:20:49.864   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 11:20:49.886   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 11:20:49.896   371   870 D CommandListener: Setting iface cfg
,08-26 11:20:49.898   872  1315 D WifiStateMachine: Start Dhcp Watchdog 3
,08-26 11:20:49.911   872  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 11:20:49.964   872  4321 D DhcpClient: Receive thread started
,08-26 11:20:50.053   872  1315 E native  : do suspend false
,08-26 11:20:50.073   872  2144 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 11:20:50.087   872  4321 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-26 11:20:50.089   872  2144 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,08-26 11:20:50.094   872  2144 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 11:20:50.111   872  4321 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 11:20:50.112   872  2144 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 11:20:50.117   371   870 D CommandListener: Setting iface cfg
,08-26 11:20:50.127   872  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 11:20:50.128   872  2144 D DhcpClient: Scheduling renewal in 86399s
,08-26 11:20:50.130   872  1315 E native  : do suspend true
,08-26 11:20:50.153   872  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE],
08-26 11:20:50.154   872  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 11:20:50.155   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 11:20:50.156   872  1317 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 11:20:50.163   872  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 11:20:50.186  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:50.186  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:50.186  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:50.186  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:50.186  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:50.186  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 11:20:50.186  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 11:20:50.186  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 11:20:50.187   872  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 11:20:50.187   872  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-26 11:20:50.187  3883  3947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 11:20:50.189   872  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-26 11:20:50.189  3883  3947 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 11:20:50.189  3883  3947 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 11:20:50.190   872  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-26 11:20:50.191  3883  3947 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@53ee097 Bundle[{}]
,08-26 11:20:50.191  3883  3947 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 11:20:50.191   872  1317 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-26 11:20:50.191  3883  3947 I io.jxcore.node.LifeCycleMonitor: stop: OK,
08-26 11:20:50.191  3883  3947 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 11:20:50.192  3883  3947 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 11:20:50.192  3883  3947 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 11:20:50.192  3883  3947 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 11:20:50.195  3883  3947 I System.out: Running OutgoingSocketThread
08-26 11:20:50.198  3883  4324 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 440)
,08-26 11:20:50.199  3883  4324 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43396
08-26 11:20:50.199  3883  4324 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-26 11:20:50.199   872  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 11:20:50.205   872  1317 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-26 11:20:50.205   872  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-26 11:20:50.205   872  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-26 11:20:50.205   872  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-26 11:20:50.205   872  1317 D ConnectivityService:    accepting network in place of null
08-26 11:20:50.206   872  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 11:20:50.206   872  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 11:20:50.218   872  4320 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154082, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 11:20:50.233   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 11:20:50.254   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 11:20:50.263   872  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-26 11:20:50.265   872  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 11:20:50.271   872  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-26 11:20:50.273   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 11:20:50.288  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 11:20:50.288  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:50.288  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:50.288  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:50.288  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:50.288  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:50.288  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:50.288  3883  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 11:20:50.290  3883  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 11:20:50.292  2036  2036 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-26 11:20:50.298   872  4319 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:815::200e
,08-26 11:20:50.304  1711  1711 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 11:20:50.307  1711  1711 D SystemUpdateService: onCreate
,08-26 11:20:50.312  1711  1711 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 11:20:50.320  1711  4331 I SystemUpdateService: active receiver: enabled
,08-26 11:20:50.329  1711  4331 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 11:20:50.334  1711  4331 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 11:20:50.335  1711  4331 I SystemUpdateService: now status is 0 (complete)
08-26 11:20:50.335  1711  4331 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 11:20:50.335  1711  4331 I SystemUpdateService: file has been verified
,08-26 11:20:50.335  1711  4331 I SystemUpdateService: OTA package size = 12249756
,08-26 11:20:50.340  1711  1711 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 11:20:50.344  1711  2522 I iu.UploadsManager: num queued entries: 0
,08-26 11:20:50.344  1711  2522 I iu.UploadsManager: num updated entries: 0
08-26 11:20:50.345  1711  2522 I iu.SyncManager: NEXT; no task
,08-26 11:20:50.359  1711  4334 I MDM     : [186] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-26 11:20:50.360  1711  4334 W BaseAppContext: Using Auth Proxy for data requests.
08-26 11:20:50.361  1711  4334 V GoogleAuthProtoRequest: [186] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 11:20:50.366  1711  4331 I SystemUpdateService: showing system update notification
,08-26 11:20:50.368  1711  1711 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 11:20:50.369  1711  1711 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-26 11:20:50.369  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 11:20:50.370  4062  4062 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 11:20:50.380  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 11:20:50.381  4062  4062 D SprintDMHelper: simOperator: 
,08-26 11:20:50.381  4062  4062 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 11:20:50.398   872  4319 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 09:20:50 GMT], X-Android-Received-Millis=[1472203250397], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472203250351]}
,08-26 11:20:50.401   872  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-26 11:20:50.401   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-26 11:20:50.402   872  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 11:20:50.403   872  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 11:20:50.422  1711  1711 D SystemUpdateService: onDestroy
,08-26 11:20:50.443  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 11:20:50.443  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 11:20:50.443  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 11:20:50.443  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 11:20:50.465  1711  4334 E MDM     : [186] SitrepService.a: Error sending sitrep.
,08-26 11:20:50.504  2825  4336 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 11:20:51.198  3883  3947 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 441)
,08-26 11:20:51.199  3883  3947 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 441)
,08-26 11:20:51.208  3883  3947 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 446)
,08-26 11:20:51.210  3883  3947 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 11:20:51.211  3883  3947 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 447)
,08-26 11:20:51.215  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 11:20:51.215  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@218c56b added. We now have 2 listener(s)
,08-26 11:20:51.217  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 11:20:51.217  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:51.217  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:51.218  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:51.218  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c74d8c8 added. We now have 9 listener(s)
,08-26 11:20:51.218  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:51.218  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 11:20:51.222  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 11:20:51.228  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:51.228  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:51.228  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:51.228  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:51.228  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:51.228  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:51.228  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:51.228  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 11:20:51.231  3883  3947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 11:20:51.231  3883  3947 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 11:20:51.232  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:51.232  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c15086 added. We now have 3 listener(s)
08-26 11:20:51.233  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 11:20:51.234  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 11:20:51.234  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:51.234  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:51.234  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7c4d47 added. We now have 10 listener(s)
08-26 11:20:51.234  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 11:20:51.234  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:51.234  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:51.234  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:51.235  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:51.235  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.235  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 11:20:51.235  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:51.235  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@218c56b removed from the list
08-26 11:20:51.235  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:51.235  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c74d8c8 removed from the list
08-26 11:20:51.237  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:51.239  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:51.240  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 11:20:51.240  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:51.240  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:51.240  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:51.241  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:51.241  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:51.241  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:51.242  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c74d8c8 not in the list
,08-26 11:20:51.242  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.242  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:51.243  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:51.243  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:51.243  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:51.243  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7c4d47 removed from the list
08-26 11:20:51.243  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:51.243  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.243  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:51.244  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:51.244  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c15086 removed from the list
,08-26 11:20:51.244  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:51.245  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662b974 added. We now have 2 listener(s)
08-26 11:20:51.246  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 11:20:51.246  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:51.247  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:51.247  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:51.247  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@427e9d added. We now have 9 listener(s)
08-26 11:20:51.247  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:51.247  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 11:20:51.255  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 11:20:51.260  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:51.260  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:51.260  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:51.260  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:51.260  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:51.260  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:51.260  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:51.260  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 11:20:51.262  3883  3947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 11:20:51.263  3883  3947 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 11:20:51.263   872  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-26 11:20:51.263  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:51.263  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a676e3 added. We now have 3 listener(s)
08-26 11:20:51.265  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 11:20:51.265  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 11:20:51.265  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:51.265  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:51.265  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dabf8e0 added. We now have 10 listener(s)
08-26 11:20:51.265  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:51.266  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 11:20:51.266  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 11:20:51.266  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:51.266  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 11:20:51.266  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:51.266  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 11:20:51.268  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:51.270  3883  3947 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 11:20:51.270  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 11:20:51.274  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 11:20:51.275  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 11:20:51.275  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 11:20:51.278  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 11:20:51.278  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 11:20:51.278  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 11:20:51.279  3883  3947 D BluetoothAdapter: STATE_ON
,08-26 11:20:51.282  4258  4270 D BtGatt.GattService: registerClient() - UUID=d70241d7-57da-4525-818f-62dff0195c3a
,08-26 11:20:51.283  4258  4275 D BtGatt.GattService: onClientRegistered() - UUID=d70241d7-57da-4525-818f-62dff0195c3a, clientIf=5
,08-26 11:20:51.284  3883  3894 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 11:20:51.286  4258  4268 D BtGatt.GattService: start scan with filters
,08-26 11:20:51.289  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 11:20:51.289  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 11:20:51.289  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 11:20:51.289  4258  4278 D BtGatt.ScanManager: handling starting scan
,08-26 11:20:51.290  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 11:20:51.292  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 11:20:51.293  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 11:20:51.293  3883  3883 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 11:20:51.293  4258  4278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae9dc31
,08-26 11:20:51.294  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 11:20:51.297  3883  3947 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 11:20:51.298  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:51.298  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 11:20:51.298  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.298  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 11:20:51.298  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 11:20:51.298  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 11:20:51.298  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 11:20:51.298  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 11:20:51.298  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 11:20:51.298  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 11:20:51.299  3883  3947 D BluetoothAdapter: STATE_ON
08-26 11:20:51.300  4258  4268 D BtGatt.GattService: stopScan() - queue size =1
,08-26 11:20:51.300  4258  4275 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 11:20:51.300  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:51.301  4258  4303 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 11:20:51.301  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:51.301  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 11:20:51.301  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 11:20:51.301  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 11:20:51.302  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 11:20:51.303  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 11:20:51.303  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 11:20:51.303  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 11:20:51.303  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 11:20:51.303  4258  4278 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 11:20:51.303  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 11:20:51.305  3883  3883 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 11:20:51.305  3883  3883 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 11:20:51.305  3883  3883 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 11:20:51.308  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 11:20:51.308  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 11:20:51.308  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 11:20:51.309  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:51.309  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.310  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:51.310  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:51.310  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662b974 removed from the list
,08-26 11:20:51.310  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:51.310  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@427e9d removed from the list
,08-26 11:20:51.310  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:51.310  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:51.311  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:51.311  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:51.313  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 11:20:51.313  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 11:20:51.313  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:51.313  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@427e9d not in the list
,08-26 11:20:51.313  4258  4275 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 11:20:51.313  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.313  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:51.313  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:51.314  4258  4278 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 11:20:51.314  4258  4278 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 11:20:51.314  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:51.314  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 11:20:51.314  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:51.315  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dabf8e0 removed from the list
,08-26 11:20:51.315  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:51.315  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.315  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 11:20:51.315  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:51.315  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a676e3 removed from the list
,08-26 11:20:51.316  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 11:20:51.316  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@487c30c added. We now have 2 listener(s)
08-26 11:20:51.318  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 11:20:51.318  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 11:20:51.318  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:51.318  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-26 11:20:51.318  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@283e455 added. We now have 9 listener(s)
08-26 11:20:51.318  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 11:20:51.319  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 11:20:51.321  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:51.326  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-26 11:20:51.326  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:51.326  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:51.326  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:51.326  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:51.326  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:51.326  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:51.326  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 11:20:51.329  3883  3947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 11:20:51.329  3883  3947 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 11:20:51.330  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:51.330  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b19df5b added. We now have 3 listener(s)
,08-26 11:20:51.332  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:51.333  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 11:20:51.334  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:51.334  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:51.334  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:51.334  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:51.335  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77403f8 added. We now have 10 listener(s)
08-26 11:20:51.335  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:51.335  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 11:20:51.336  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 11:20:51.336  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 11:20:51.336  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 11:20:51.336  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:51.337  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 11:20:51.337  4258  4275 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 11:20:51.337  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:51.340  3883  3947 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 11:20:51.340  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 11:20:51.344  4258  4275 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 11:20:51.344  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:51.344  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 11:20:51.345  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 11:20:51.345  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 11:20:51.349  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 11:20:51.349  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 11:20:51.349  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 11:20:51.350  3883  3947 D BluetoothAdapter: STATE_ON
,08-26 11:20:51.352  4258  4270 D BtGatt.GattService: registerClient() - UUID=30d69a3a-442a-43a1-9a61-1d3dcb41f314
,08-26 11:20:51.352  4258  4275 D BtGatt.GattService: onClientRegistered() - UUID=30d69a3a-442a-43a1-9a61-1d3dcb41f314, clientIf=5
08-26 11:20:51.352  4258  4275 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 11:20:51.352  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:51.353  3883  3994 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 11:20:51.353  4258  4278 D BtGatt.ScanManager: stopping BLe Batch
08-26 11:20:51.353  4258  4292 D BtGatt.GattService: start scan with filters
,08-26 11:20:51.356  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 11:20:51.356  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 11:20:51.356  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 11:20:51.356  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 11:20:51.360  4258  4275 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 11:20:51.360  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:51.360  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 11:20:51.361  4258  4278 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 11:20:51.361  3883  3883 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 11:20:51.361  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 11:20:51.364  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 11:20:51.367  4258  4275 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 11:20:51.367  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:51.367  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 11:20:51.367  3883  3947 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 11:20:51.368  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 11:20:51.368  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 11:20:51.368  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:51.368  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:51.368  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.368  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 11:20:51.368  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:51.368  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@487c30c removed from the list
,08-26 11:20:51.369  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:51.369  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@283e455 removed from the list
08-26 11:20:51.369  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:51.369  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 11:20:51.369  4258  4278 D BtGatt.ScanManager: handling starting scan
08-26 11:20:51.369  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.369  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-26 11:20:51.369  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.370  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 11:20:51.370  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:51.371  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 11:20:51.371  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:51.371  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@283e455 not in the list
08-26 11:20:51.371  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 11:20:51.372  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 11:20:51.372  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 11:20:51.372  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 11:20:51.372  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 11:20:51.373  3883  3947 D BluetoothAdapter: STATE_ON
08-26 11:20:51.373  4258  4303 D BtGatt.GattService: stopScan() - queue size =1
08-26 11:20:51.374  4258  4268 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 11:20:51.374  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 11:20:51.374  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 11:20:51.374  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 11:20:51.375  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 11:20:51.375  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 11:20:51.376  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 11:20:51.376  4258  4275 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 11:20:51.376  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 11:20:51.376  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 11:20:51.376  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:51.376  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 11:20:51.376  4258  4278 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 11:20:51.376  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:51.377  3883  3883 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 11:20:51.378  3883  3883 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 11:20:51.378  3883  3883 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 11:20:51.378  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:51.378  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:51.378  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:51.378  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77403f8 removed from the list
08-26 11:20:51.378  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:51.378  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.378  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:51.378  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:51.378  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b19df5b removed from the list
08-26 11:20:51.379  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:51.379  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae167a4 added. We now have 2 listener(s)
,08-26 11:20:51.381  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 11:20:51.381  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:51.381  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:51.382  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:51.382  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c65490d added. We now have 9 listener(s)
,08-26 11:20:51.382  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:51.382  4258  4275 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 11:20:51.382  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:51.382  4258  4278 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 11:20:51.382  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 11:20:51.382  4258  4278 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 11:20:51.389  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 11:20:51.393  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:51.393  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:51.393  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:51.393  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:51.393  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:51.393  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:51.393  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:51.393  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 11:20:51.395  4258  4275 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 11:20:51.395  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:51.396  3883  3947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:51.397  3883  3947 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 11:20:51.398  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 11:20:51.398  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b92ded3 added. We now have 3 listener(s)
,08-26 11:20:51.399  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:51.401  4258  4275 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 11:20:51.401  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:51.402  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:51.404  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 11:20:51.404  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 11:20:51.404  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:51.404  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 11:20:51.405  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79f5a10 added. We now have 10 listener(s)
08-26 11:20:51.405  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:51.405  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 11:20:51.405  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 11:20:51.405  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 11:20:51.405  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 11:20:51.405  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 11:20:51.408  3883  3947 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 11:20:51.408  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 11:20:51.408  4258  4275 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 11:20:51.409  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:51.409  4258  4278 D BtGatt.ScanManager: stopping BLe Batch
,08-26 11:20:51.412  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 11:20:51.413  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 11:20:51.413  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 11:20:51.415  4258  4275 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 11:20:51.415  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:51.415  4258  4278 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 11:20:51.416  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 11:20:51.416  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 11:20:51.416  3883  3947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 11:20:51.417  3883  3947 D BluetoothAdapter: STATE_ON
,08-26 11:20:51.419  4258  4303 D BtGatt.GattService: registerClient() - UUID=b528ae75-9303-4168-8d70-418440ea2ad1
,08-26 11:20:51.419  4258  4275 D BtGatt.GattService: onClientRegistered() - UUID=b528ae75-9303-4168-8d70-418440ea2ad1, clientIf=5
08-26 11:20:51.420  3883  3994 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 11:20:51.420  4258  4292 D BtGatt.GattService: start scan with filters
,08-26 11:20:51.421  4258  4275 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 11:20:51.421  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:51.423  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 11:20:51.423  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 11:20:51.423  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 11:20:51.423  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 11:20:51.423  4258  4278 D BtGatt.ScanManager: handling starting scan
,08-26 11:20:51.427  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 11:20:51.428  3883  3883 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 11:20:51.428  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 11:20:51.429  4258  4275 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 11:20:51.430  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:51.430  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 11:20:51.430  4258  4278 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 11:20:51.435  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 11:20:51.435  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:51.435  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 11:20:51.435  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:51.435  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.435  4258  4275 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 11:20:51.435  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 11:20:51.435  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:51.435  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:51.435  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae167a4 removed from the list
08-26 11:20:51.435  4258  4278 D BtGatt.ScanManager: Starting BLE batch scan
08-26 11:20:51.435  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:51.436  4258  4278 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 11:20:51.436  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c65490d removed from the list
08-26 11:20:51.436  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:51.436  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 11:20:51.436  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.436  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 11:20:51.436  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.436  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:51.437  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:51.437  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 11:20:51.437  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:51.437  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c65490d not in the list
08-26 11:20:51.438  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 11:20:51.438  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 11:20:51.438  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 11:20:51.438  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 11:20:51.438  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 11:20:51.439  3883  3947 D BluetoothAdapter: STATE_ON
08-26 11:20:51.439  4258  4292 D BtGatt.GattService: stopScan() - queue size =1
,08-26 11:20:51.440  4258  4268 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 11:20:51.440  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 11:20:51.440  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 11:20:51.440  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 11:20:51.440  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 11:20:51.440  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 11:20:51.444  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 11:20:51.444  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 11:20:51.444  3883  3947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 11:20:51.444  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 11:20:51.445  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:51.446  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 11:20:51.446  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:51.446  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:51.447  3883  3883 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 11:20:51.447  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79f5a10 removed from the list
08-26 11:20:51.447  3883  3883 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 11:20:51.447  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:51.447  3883  3883 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 11:20:51.447  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:51.447  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:51.447  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:51.447  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b92ded3 removed from the list
08-26 11:20:51.448  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:51.448  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208073c added. We now have 2 listener(s)
,08-26 11:20:51.450  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 11:20:51.450  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 11:20:51.450  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:51.451  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 11:20:51.451  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4078cc5 added. We now have 9 listener(s)
08-26 11:20:51.451  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 11:20:51.451  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 11:20:51.454  4258  4275 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 11:20:51.454  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:51.455  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 11:20:51.458  3883  3947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 11:20:51.458  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 11:20:51.458  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 11:20:51.458  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 11:20:51.458  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 11:20:51.458  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:51.458  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 11:20:51.458  3883  3947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 11:20:51.461  4258  4275 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 11:20:51.461  3883  3947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 11:20:51.461  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:51.461  3883  3947 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 11:20:51.461  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 11:20:51.461  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44d554b added. We now have 3 listener(s)
,08-26 11:20:51.463  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 11:20:51.463  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 11:20:51.464  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 11:20:51.464  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 11:20:51.464  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 11:20:51.464  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ec5b28 added. We now have 10 listener(s)
08-26 11:20:51.464  3883  3947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 11:20:51.464  3883  3947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 11:20:51.464  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 11:20:51.464  3883  3947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 11:20:51.464  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 11:20:51.464  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 11:20:51.464  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 11:20:51.464  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 11:20:51.465  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208073c removed from the list
08-26 11:20:51.465  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:51.465  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4078cc5 removed from the list
08-26 11:20:51.465  3883  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 11:20:51.466  3883  3947 D io.jxcore.node.ConnectivityMonitor: stop
08-26 11:20:51.466  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:51.466  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.466  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:51.467  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:51.467  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 11:20:51.467  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 11:20:51.468  3883  3947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4078cc5 not in the list
08-26 11:20:51.468  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.468  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 11:20:51.469  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 11:20:51.469  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 11:20:51.469  3883  3947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 11:20:51.469  3883  3947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ec5b28 removed from the list
08-26 11:20:51.469  3883  3947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 11:20:51.469  3883  3947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 11:20:51.470  3883  3947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 11:20:51.470  3883  3947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 11:20:51.470  3883  3947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44d554b removed from the list
08-26 11:20:51.470  4258  4275 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 11:20:51.470  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 11:20:51.470  4258  4278 D BtGatt.ScanManager: stopping BLe Batch
08-26 11:20:51.470  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 11:20:51.471  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-26 11:20:51.471  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 11:20:51.471  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 11:20:51.471  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 11:20:51.471  3883  3947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 11:20:51.476  3883  4343 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 454, name: My test thread name)
,08-26 11:20:51.477  3883  4343 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 454, thread name: My test thread name)
08-26 11:20:51.477  3883  4343 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 454, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 11:20:51.480  3883  4344 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: My test thread name)
,08-26 11:20:51.480  4258  4275 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 11:20:51.480  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:51.480  3883  4344 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 456, thread name: My test thread name)
08-26 11:20:51.480  3883  4344 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 456, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 11:20:51.480  4258  4278 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 11:20:51.484  3883  3947 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-26 11:20:51.484  3883  3947 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 11:20:51.484  3883  3947 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 11:20:51.484  3883  3947 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 11:20:51.484  3883  3947 D com.test.thalitest.ThaliTestRunner: Total duration: 22811 ms
08-26 11:20:51.486  3883  3947 I jxcore-log: Total number of executed tests:  80
08-26 11:20:51.486  3883  3947 I jxcore-log: 
,08-26 11:20:51.486  3883  3947 I jxcore-log: Number of passed tests:  80
08-26 11:20:51.486  3883  3947 I jxcore-log: 
08-26 11:20:51.486  3883  3947 I jxcore-log: Number of failed tests:  0
08-26 11:20:51.486  3883  3947 I jxcore-log: 
08-26 11:20:51.487  3883  3947 I jxcore-log: Number of ignored tests:  0
08-26 11:20:51.487  3883  3947 I jxcore-log: 
08-26 11:20:51.487  3883  3947 I jxcore-log: Total duration:  22811
08-26 11:20:51.487  3883  3947 I jxcore-log: 
,08-26 11:20:51.487  3883  3947 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 11:20:51.487  3883  3947 I jxcore-log: 
,08-26 11:20:51.490  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.490  3883  3947 I jxcore-log: 
08-26 11:20:51.494  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.494  3883  3947 I jxcore-log: 
08-26 11:20:51.494  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.494  3883  3947 I jxcore-log: 
08-26 11:20:51.495  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.495  3883  3947 I jxcore-log: 
08-26 11:20:51.495  3883  3883 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 11:20:51.495  4258  4275 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 11:20:51.495  4258  4275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 11:20:51.496  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.496  3883  3947 I jxcore-log: 
08-26 11:20:51.498  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.498  3883  3947 I jxcore-log: 
08-26 11:20:51.500  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.500  3883  3947 I jxcore-log: 
08-26 11:20:51.502  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 11:20:51.502  3883  3947 I jxcore-log: 
08-26 11:20:51.502  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 11:20:51.502  3883  3947 I jxcore-log: 
08-26 11:20:51.503  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 11:20:51.503  3883  3947 I jxcore-log: 
08-26 11:20:51.504  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 11:20:51.504  3883  3947 I jxcore-log: 
08-26 11:20:51.505  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 11:20:51.505  3883  3947 I jxcore-log: 
08-26 11:20:51.506  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.506  3883  3947 I jxcore-log: 
08-26 11:20:51.506  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.506  3883  3947 I jxcore-log: 
08-26 11:20:51.507  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 11:20:51.507  3883  3947 I jxcore-log: 
08-26 11:20:51.507  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 11:20:51.507  3883  3947 I jxcore-log: 
08-26 11:20:51.508  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 11:20:51.508  3883  3947 I jxcore-log: 
08-26 11:20:51.509  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 11:20:51.509  3883  3947 I jxcore-log: 
08-26 11:20:51.509  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 11:20:51.509  3883  3947 I jxcore-log: 
08-26 11:20:51.510  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 11:20:51.510  3883  3947 I jxcore-log: 
08-26 11:20:51.510  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 11:20:51.510  3883  3947 I jxcore-log: 
,08-26 11:20:51.511  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 11:20:51.511  3883  3947 I jxcore-log: 
,08-26 11:20:51.512  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 11:20:51.512  3883  3947 I jxcore-log: 
08-26 11:20:51.513  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 11:20:51.513  3883  3947 I jxcore-log: 
,08-26 11:20:51.513  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 11:20:51.513  3883  3947 I jxcore-log: 
,08-26 11:20:51.514  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.514  3883  3947 I jxcore-log: 
08-26 11:20:51.515  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.515  3883  3947 I jxcore-log: 
08-26 11:20:51.515  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.515  3883  3947 I jxcore-log: 
08-26 11:20:51.515  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.515  3883  3947 I jxcore-log: 
08-26 11:20:51.516  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.516  3883  3947 I jxcore-log: 
08-26 11:20:51.516  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 11:20:51.516  3883  3947 I jxcore-log: 
,08-26 11:20:51.806  3883  3883 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 11:20:51.808  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 11:20:51.808  3883  3947 I jxcore-log: 
,08-26 11:20:51.879  3883  3883 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 11:20:51.881  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 11:20:51.881  3883  3947 I jxcore-log: 
,08-26 11:20:51.948  3883  3883 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 11:20:51.950  3883  3947 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 11:20:51.950  3883  3947 I jxcore-log: 
,08-26 11:20:52.195  4345  4345 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-26 11:20:52.201  4345  4345 D AndroidRuntime: CheckJNI is OFF
,08-26 11:20:52.244  4345  4345 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-26 11:20:52.293  4345  4345 I Radio-JNI: register_android_hardware_Radio DONE
,08-26 11:20:52.316  4345  4345 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 11:20:52.329   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-26 11:20:52.329   872   885 I ActivityManager: Killing 3883:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-26 11:20:52.453   872  1972 D GraphicsStats: Buffer count: 2
,08-26 11:20:52.453   872  1379 I WindowState: WIN DEATH: Window{bed449 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 11:20:52.456   872  1316 D WifiService: Client connection lost with reason: 4
,08-26 11:20:52.476   872   895 W PackageSettings: Skipping PackageSetting{391511a com.example.hello/10273} due to missing metadata
,08-26 11:20:52.515   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-26 11:20:52.517   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-26 11:20:52.518   872   895 I art     : Starting a blocking GC Explicit
,08-26 11:20:52.522   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-26 11:20:52.522   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-26 11:20:52.522   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:52.522   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:52.522   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 11:20:52.522   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-26 11:20:52.524   872   885 I ActivityManager:   Force finishing activity ActivityRecord{9ab4a7 u0 com.test.thalitest/.MainActivity t2}
,08-26 11:20:52.537   872   882 W ActivityManager: Spurious death for ProcessRecord{3e6cc92 0:com.test.thalitest/u0a0}, curProc for 3883: null
,08-26 11:20:52.574   872   895 I art     : Explicit concurrent mark sweep GC freed 13745(949KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.133ms total 55.011ms
,08-26 11:20:52.610   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-26 11:20:52.613  4345  4345 I art     : System.exit called, status: 0
,08-26 11:20:52.613  4345  4345 I AndroidRuntime: VM exiting with result code 0.
,08-26 11:20:52.625   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-26 11:20:52.645   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-26 11:20:52.654   872  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 11:20:52.656  4258  4258 D BluetoothMapAppObserver: onReceive
,08-26 11:20:52.657  4258  4258 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-26 11:20:52.664  1876  1876 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-26 11:20:52.664  1889  2230 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 11:20:52.674  3724  3724 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-26 11:20:52.683  1876  4358 I Keyboard.Facilitator.DecoderInitializer: run()
,08-26 11:20:52.686  1876  4358 I Decoder : createOrResetDecoder
,08-26 11:20:52.698  1952  1952 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-26 11:20:52.707   872  1408 I ActivityManager: Start proc 4360:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-26 11:20:52.729  1510  1510 I ConfigService: onCreate
,08-26 11:20:52.749   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 11:20:52.759  1876  4358 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 11:20:52.772  4360  4360 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-26 11:20:52.776   872  1998 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3883 uid 10000
,08-26 11:20:52.777  1876  1876 I Keyboard.Facilitator: onFinishInput()
,08-26 11:20:52.788   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-26 11:20:52.788  1967  2066 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-26 11:20:52.789   872   884 E PackageManager: Failed to write settings, restoring backup
08-26 11:20:52.789   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-26 11:20:52.789   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-26 11:20:52.789   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-26 11:20:52.789   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-26 11:20:52.789   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-26 11:20:52.789   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:52.789   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:52.789   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 11:20:52.793   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-26 11:20:52.793   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 11:20:52.793   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 11:20:52.793   872   885 E DropBoxManagerService: 	... 13 more
,08-26 11:20:52.801  1876  4358 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-26 11:20:52.803  1876  4358 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-26 11:20:52.803  1876  4358 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-26 11:20:52.806   872  1379 I ActivityManager: Start proc 4376:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-26 11:20:52.806  1967  2066 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-26 11:20:52.806  1967  2066 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1967
08-26 11:20:52.806  1967  2066 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 11:20:52.806  1967  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 11:20:52.806  1967  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 11:20:52.806  1967  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 11:20:52.806  1967  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 11:20:52.806  1967  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 11:20:52.806  1967  2066 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-26 11:20:52.806  1967  2066 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-26 11:20:52.806  1967  2066 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 11:20:52.806  1967  2066 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 11:20:52.806  1967  2066 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:52.806  1967  2066 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 11:20:52.809   872  1965 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 11:20:52.809   872  4382 E DropBoxManagerService: Can't write: system_app_crash
08-26 11:20:52.809   872  4382 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-26 11:20:52.809   872  4382 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 11:20:52.809   872  4382 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 11:20:52.809   872  4382 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 11:20:52.809   872  4382 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 11:20:52.809   872  4382 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 11:20:52.809   872  4382 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 11:20:52.809   872  4382 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 11:20:52.809   872  4382 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 11:20:52.809   872  4382 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 11:20:52.809   872  4382 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 11:20:52.809   872  4382 E DropBoxManagerService: 	... 5 more
08-26 11:20:52.813  1967  2066 I Process : Sending signal. PID: 1967 SIG: 9,
,08-26 11:20:52.817  1876  4358 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-26 11:20:52.817  1876  4358 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-26 11:20:52.819  1876  4358 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-26 11:20:52.819  1876  4358 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-26 11:20:52.820  1876  4358 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-26 11:20:52.820  1876  4358 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-26 11:20:52.820  1876  4358 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-26 11:20:52.820  1876  4358 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-26 11:20:52.820  1876  4358 I StatsUtilsManager: startPeriodStatsRecorder() : Success,
08-26 11:20:52.820  1876  4358 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-26 11:20:52.900  4360  4360 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-26 11:20:52.933   872  1965 I ActivityManager: Start proc 4393:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-26 11:20:52.935  4360  4392 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 11:20:52.965  4360  4392 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:52.965  4360  4392 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 11:20:52.968  4360  4392 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 11:20:52.968  4360  4392 E AndroidRuntime: Process: android.process.acore, PID: 4360
08-26 11:20:52.968  4360  4392 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:52.968  4360  4392 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 11:20:52.972  4360  4392 I Process : Sending signal. PID: 4360 SIG: 9
,08-26 11:20:52.976   872  4406 E DropBoxManagerService: Can't write: system_app_crash
08-26 11:20:52.976   872  4406 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-26 11:20:52.976   872  4406 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 11:20:52.976   872  4406 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 11:20:52.976   872  4406 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 11:20:52.976   872  4406 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 11:20:52.976   872  4406 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 11:20:52.976   872  4406 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 11:20:52.976   872  4406 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 11:20:52.976   872  4406 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 11:20:52.976   872  4406 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 11:20:52.976   872  4406 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 11:20:52.976   872  4406 E DropBoxManagerService: 	... 5 more
,08-26 11:20:52.990   872  1408 D GraphicsStats: Buffer count: 1
,08-26 11:20:52.990   872  1408 I WindowState: WIN DEATH: Window{837c667 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-26 11:20:53.006   872  1998 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1967) has died
,08-26 11:20:53.007   872  1998 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-26 11:20:53.009   872  1998 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 11:20:53.012   278   278 E lowmemorykiller: Error writing /proc/4360/oom_score_adj; errno=22
,08-26 11:20:53.033  4393  4393 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-26 11:20:53.039   872  1315 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-26 11:20:53.041   872   885 I ActivityManager: Start proc 4408:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 11:20:53.044   278   278 E lowmemorykiller: Error writing /proc/4360/oom_score_adj; errno=22
,08-26 11:20:53.052   278   278 E lowmemorykiller: Error writing /proc/4360/oom_score_adj; errno=22
,08-26 11:20:53.079  1510  1510 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-26 11:20:53.079  1510  1510 D AndroidRuntime: Shutting down VM
08-26 11:20:53.080  1510  1510 E AndroidRuntime: FATAL EXCEPTION: main
08-26 11:20:53.080  1510  1510 E AndroidRuntime: Process: com.google.process.gapps, PID: 1510
08-26 11:20:53.080  1510  1510 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754),
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 11:20:53.080  1510  1510 E AndroidRuntime: 	... 8 more
08-26 11:20:53.081   278   278 E lowmemorykiller: Error writing /proc/4360/oom_score_adj; errno=22
,08-26 11:20:53.081   278   278 E lowmemorykiller: Error writing /proc/4360/oom_score_adj; errno=22
08-26 11:20:53.084   872  4423 E DropBoxManagerService: Can't write: system_app_crash
,08-26 11:20:53.084   872  4423 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-26 11:20:53.084   872  4423 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 11:20:53.084   872  4423 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 11:20:53.084   872  4423 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 11:20:53.084   872  4423 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 11:20:53.084   872  4423 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 11:20:53.084   872  4423 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 11:20:53.084   872  4423 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 11:20:53.084   872  4423 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 11:20:53.084   872  4423 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 11:20:53.084   872  4423 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 11:20:53.084   872  4423 E DropBoxManagerService: 	... 5 more
08-26 11:20:53.085  1510  1510 I Process : Sending signal. PID: 1510 SIG: 9
,08-26 11:20:53.102  4408  4408 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 11:20:53.102  4408  4408 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 11:20:53.102  4408  4408 D AndroidRuntime: Shutting down VM
,08-26 11:20:53.110  4408  4408 E AndroidRuntime: FATAL EXCEPTION: main
08-26 11:20:53.110  4408  4408 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4408
08-26 11:20:53.110  4408  4408 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 11:20:53.110  4408  4408 E AndroidRuntime: 	... 10 more
08-26 11:20:53.111   872  1379 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 11:20:53.112  4408  4408 I Process : Sending signal. PID: 4408 SIG: 9
08-26 11:20:53.112   872  4424 E DropBoxManagerService: Can't write: system_app_crash
08-26 11:20:53.112   872  4424 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-26 11:20:53.112   872  4424 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 11:20:53.112   872  4424 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 11:20:53.112   872  4424 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 11:20:53.112   872  4424 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 11:20:53.112   872  4424 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 11:20:53.112   872  4424 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 11:20:53.112   872  4424 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 11:20:53.112   872  4424 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 11:20:53.112   872  4424 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 11:20:53.112   872  4424 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 11:20:53.112   872  4424 E DropBoxManagerService: 	... 5 more
08-26 11:20:53.115   872  1408 I ActivityManager: Process android.process.acore (pid 4360) has died
08-26 11:20:53.115   872  1408 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-26 11:20:53.122   872  1316 D WifiService: Client connection lost with reason: 4
,08-26 11:20:53.124  1711  4407 W BulkCursor: Remote process exception when closing
,08-26 11:20:53.127   872  2003 I ActivityManager: Process com.google.process.gapps (pid 1510) has died
,08-26 11:20:53.127   872  2003 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,08-26 11:20:53.128   872  2003 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-26 11:20:53.128   872  2003 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
08-26 11:20:53.128   872  2003 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 30999ms
08-26 11:20:53.128   872  2003 I ActivityManager: Killing 1711:com.google.android.gms/u0a11 (adj 5): depends on provider com.google.android.gsf/.gservices.GservicesProvider in dying proc com.google.process.gapps,
,08-26 11:20:53.140   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
