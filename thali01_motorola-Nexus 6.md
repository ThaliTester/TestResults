#### Test 80912877ea0a40f_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-11 12:02:08.742  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:02:08.755  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 12:02:08.759  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 12:02:08.819  1490  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-11 12:02:08.819  1490  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-11 12:02:08.820  1490  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:02:08.820  1490  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-11 12:02:08.864  3380  3380 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-11 12:02:08.865  3380  3380 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-11 12:02:08.866  3380  3380 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-11 12:02:09.426  3649  3649 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 12:02:09.430  3649  3649 D AndroidRuntime: CheckJNI is OFF
08-11 12:02:09.466  3649  3649 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 12:02:09.508  3649  3649 I Radio-JNI: register_android_hardware_Radio DONE
08-11 12:02:09.528  3649  3649 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 12:02:09.532   870  1842 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 12:02:09.577  1795  1807 W SearchService: Abort, client detached.
08-11 12:02:09.579  3649  3649 D AndroidRuntime: Shutting down VM
08-11 12:02:09.592  1795  2118 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@b2e6435
08-11 12:02:09.592  1795  1795 I HotwordDetector: Closing mic
08-11 12:02:09.592  1795  2131 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-11 12:02:09.608   870  1956 I ActivityManager: Start proc 3659:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-11 12:02:09.660   374  2133 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-11 12:02:09.662   374  2133 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-11 12:02:09.674   374  1271 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-11 12:02:09.676  1795  2124 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-11 12:02:09.676  1795  2130 I MicroRecognitionRnrImpl: Detection finished
08-11 12:02:09.687  3659  3659 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-11 12:02:09.707  3659  3659 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-11 12:02:09.714  3659  3659 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 76-79)
08-11 12:02:09.714  3659  3659 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 12:02:09.727  3659  3659 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dc6b509}
08-11 12:02:09.728  3659  3659 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 12:02:09.728  3659  3659 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 12:02:09.743  3659  3659 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-11 12:02:09.747  3659  3659 E SysUtils: ApplicationContext is null in ApplicationStatus
08-11 12:02:09.768  3659  3659 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-11 12:02:09.782  3659  3659 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 12:02:09.782  3659  3659 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 12:02:09.782  3659  3659 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 12:02:09.782  3659  3659 I Adreno  : Build Date                       : 10/20/15
08-11 12:02:09.782  3659  3659 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 12:02:09.782  3659  3659 I Adreno  : Local Branch                     : M14
08-11 12:02:09.782  3659  3659 I Adreno  : Remote Branch                    : 
08-11 12:02:09.782  3659  3659 I Adreno  : Remote Branch                    : 
08-11 12:02:09.782  3659  3659 I Adreno  : Reconstruct Branch               : 
,08-11 12:02:09.873   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@710305b:true
,08-11 12:02:09.958  3659  3659 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 12:02:09.982  3659  3659 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-11 12:02:10.097  3659  3699 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 12:02:10.118  3659  3685 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-11 12:02:10.171  3659  3699 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 12:02:10.233   870   888 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +645ms
,08-11 12:02:10.249  1655  1655 I Keyboard.Facilitator: onFinishInput()
,08-11 12:02:10.314  3659  3659 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3659
,08-11 12:02:10.417   870  1956 I ActivityManager: Killing 3070:com.google.android.gm/u0a78 (adj 15): empty #17
,08-11 12:02:10.460   870  1956 I ActivityManager: Killing 2932:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-11 12:02:10.465  3659  3659 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 12:02:10.659  3659  3701 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1699022544
,08-11 12:02:10.679  3659  3701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 12:02:10.679  3659  3701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 12:02:10.679  3659  3701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 12:02:10.679  3659  3701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 12:02:10.679  3659  3701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-11 12:02:10.680  3659  3701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9ede94 added. We now have 1 listener(s)
,08-11 12:02:10.693  3659  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-11 12:02:10.702  3659  3701 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 12:02:10.702  3659  3701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 12:02:10.703  3659  3701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-11 12:02:10.709  3659  3701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed55000 added. We now have 1 listener(s)
08-11 12:02:10.710  3659  3701 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 12:02:10.713   870  1303 D WifiService: New client listening to asynchronous messages
,08-11 12:02:10.714  3659  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 12:02:10.714  3659  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-11 12:02:10.715  3659  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-11 12:02:10.716  3659  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 12:02:10.716  3659  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-11 12:02:10.722  3659  3701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 12:02:10.723  3659  3701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-11 12:02:10.729  3659  3701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-11 12:02:10.729  3659  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:02:10.729  3659  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:02:10.729  3659  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:02:10.729  3659  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:02:10.729  3659  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:02:10.729  3659  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:02:10.729  3659  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:02:10.729  3659  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:02:10.729  3659  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 12:02:10.729  3659  3701 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 12:02:10.731  3659  3701 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 12:02:10.915  3659  3659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:02:10.921  3659  3659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:02:10.927  3659  3659 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 12:02:11.572  3659  3711 W jxcore-log: Initializing JXcore engine
,08-11 12:02:11.573  3659  3711 W jxcore-log: JXcore engine is ready
,08-11 12:02:11.647  3711  3711 W Thread-330: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8934 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-11 12:02:11.647  3711  3711 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10678]" dev="sockfs" ino=10678 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-11 12:02:11.647  3711  3711 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-11 12:02:11.647  3711  3711 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24849]" dev="sockfs" ino=24849 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-11 12:02:11.663  3659  3711 W jxcore-log: Starting JXcore engine
,08-11 12:02:11.743  3659  3711 W jxcore-log: Platform android
08-11 12:02:11.743  3659  3711 W jxcore-log: 
,08-11 12:02:11.743  3659  3711 W jxcore-log: Process ARCH arm
08-11 12:02:11.743  3659  3711 W jxcore-log: 
,08-11 12:02:11.967  3659  3711 I jxcore-log: JXcore Cordova bridge is ready!
08-11 12:02:11.967  3659  3711 I jxcore-log: 
,08-11 12:02:11.967  3659  3711 W jxcore-log: JXcore engine is started
,08-11 12:02:11.974  3659  3701 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-11 12:02:11.980  3659  3659 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 12:02:12.564   870  1302 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-11 12:02:15.725  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:02:15.730  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:02:15.761  1490  2840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 12:02:15.761  1490  2840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 12:02:15.761  1490  2840 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:02:15.761  1490  2840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:02:15.785  2857  3719 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 12:02:15.785  2857  3719 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at blb.a(PG:3937)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at czp.a(PG:18188)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:02:15.785  2857  3719 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	... 12 more
08-11 12:02:15.785  2857  3719 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at fal.a(PG:38)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:02:15.785  2857  3719 E HttpOperation: 	... 14 more
,08-11 12:02:15.831  1490  1889 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 12:02:15.831  1490  1889 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 12:02:15.831  1490  1889 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:02:15.831  1490  1889 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:02:15.847  2857  3719 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 12:02:15.847  2857  3719 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at hec.a(PG:42)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at hee.a(PG:102)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at czr.a(PG:65)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at kka.a(PG:108)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at czp.a(PG:19176)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:02:15.847  2857  3719 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	... 15 more
08-11 12:02:15.847  2857  3719 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at fal.a(PG:38)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:02:15.847  2857  3719 E HttpOperation: 	... 17 more
,08-11 12:02:15.847  2857  3719 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 12:02:15.847  2857  3719 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at hec.a(PG:42)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at hee.a(PG:102)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at czr.a(PG:65)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at kka.a(PG:108)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	... 15 more
08-11 12:02:15.847  2857  3719 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at fal.a(PG:38)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 12:02:15.847  2857  3719 E ExperimentLoader: 	... 17 more
,08-11 12:02:15.925   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 125669, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:02:22.192  3659  3711 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 12:02:22.192  3659  3711 I jxcore-log: 
,08-11 12:02:22.195  3659  3711 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 12:02:22.195  3659  3711 I jxcore-log: 
,08-11 12:02:22.206  3659  3711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:02:22.206  3659  3711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:02:22.206  3659  3711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:02:22.206  3659  3711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:02:22.206  3659  3711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:02:22.206  3659  3711 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:02:22.206  3659  3711 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:02:22.206  3659  3711 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:02:22.211  3659  3711 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:02:22.213  3659  3711 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 12:02:22.213  3659  3711 I jxcore-log: 
,08-11 12:02:22.215  3659  3711 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 12:02:22.215  3659  3711 I jxcore-log: 
,08-11 12:02:22.539  3659  3711 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-11 12:02:22.539  3659  3711 I jxcore-log: Failed to execute UT.
08-11 12:02:22.539  3659  3711 I jxcore-log: 
08-11 12:02:22.539  3659  3711 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 12:02:22.539  3659  3711 I jxcore-log: 
,08-11 12:02:22.545  3659  3711 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:02:22.545  3659  3711 I jxcore-log: 
08-11 12:02:22.549  3659  3659 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 12:02:23.191  3724  3724 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-11 12:02:23.196  3724  3724 D AndroidRuntime: CheckJNI is OFF
,08-11 12:02:23.232  3724  3724 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-11 12:02:23.274  3724  3724 I Radio-JNI: register_android_hardware_Radio DONE
,08-11 12:02:23.295  3724  3724 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 12:02:23.314   870   883 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-11 12:02:23.315   870   883 I ActivityManager: Killing 3659:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-11 12:02:23.366   870  1291 W InputDispatcher: channel '6f9e64b com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,08-11 12:02:23.366   870  1291 E InputDispatcher: channel '6f9e64b com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-11 12:02:23.392   870   881 D GraphicsStats: Buffer count: 2
,08-11 12:02:23.392   870  1597 I WindowState: WIN DEATH: Window{6f9e64b u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 12:02:23.393   870  1597 W InputDispatcher: Attempted to unregister already unregistered input channel '6f9e64b com.test.thalitest/com.test.thalitest.MainActivity (server)'
,08-11 12:02:23.393   870  1303 D WifiService: Client connection lost with reason: 4
,08-11 12:02:23.407   870   883 W ActivityManager: Force removing ActivityRecord{316e0b0 u0 com.test.thalitest/.MainActivity t8}: app died, no saved state
,08-11 12:02:23.431   870   893 W PackageSettings: Skipping PackageSetting{683f78c com.example.hello/10273} due to missing metadata
,08-11 12:02:23.462   870   893 I art     : Starting a blocking GC Explicit
,08-11 12:02:23.476   870   881 W ActivityManager: Spurious death for ProcessRecord{8d96fa3 0:com.test.thalitest/u0a0}, curProc for 3659: null
,08-11 12:02:23.510   870   893 I art     : Explicit concurrent mark sweep GC freed 50713(3MB) AllocSpace objects, 16(344KB) LOS objects, 33% free, 29MB/43MB, paused 835us total 48.092ms
,08-11 12:02:23.521   870  1597 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3659 uid 10000
,08-11 12:02:23.522  1655  1655 I Keyboard.Facilitator: onFinishInput()
,08-11 12:02:23.532   870   893 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-11 12:02:23.539  3724  3724 I art     : System.exit called, status: 0
08-11 12:02:23.539  3724  3724 I AndroidRuntime: VM exiting with result code 0.
,08-11 12:02:23.550   870   893 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-11 12:02:23.573  2549  2549 D BluetoothMapAppObserver: onReceive
,08-11 12:02:23.573  2549  2549 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-11 12:02:23.579   870  1292 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 12:02:23.584  3477  3477 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-11 12:02:23.585  1826  2011 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-11 12:02:23.585  1795  1795 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,08-11 12:02:23.614  1655  1655 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-11 12:02:23.617  1655  3740 I Keyboard.Facilitator.DecoderInitializer: run()
,08-11 12:02:23.633  1655  3740 I Decoder : createOrResetDecoder
,08-11 12:02:23.640  1720  1720 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-11 12:02:23.683  1795  3744 I MicroRecognitionRnrImpl: Starting detection.
,08-11 12:02:23.690  1795  3745 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@8c22f6b
,08-11 12:02:23.692   374  3748 I AudioFlinger: AudioFlinger's thread 0xb1d40000 ready to run
,08-11 12:02:23.693  1490  1490 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-11 12:02:23.693  1490  1490 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
08-11 12:02:23.694  1490  1490 E AndroidRuntime: FATAL EXCEPTION: main
08-11 12:02:23.694  1490  1490 E AndroidRuntime: Process: com.google.process.gapps, PID: 1490
08-11 12:02:23.694  1490  1490 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at android.dat,abase.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-11 12:02:23.694  1490  1490 E AndroidRuntime: 	... 8 more
08-11 12:02:23.696   374  1271 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-11 12:02:23.699  1795  3745 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@8c22f6b
,08-11 12:02:23.701   870   870 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-11 12:02:23.703   870  3749 E DropBoxManagerService: Can't write: system_app_crash
08-11 12:02:23.703   870  3749 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
08-11 12:02:23.703   870  3749 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 12:02:23.703   870  3749 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 12:02:23.703   870  3749 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 12:02:23.703   870  3749 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 12:02:23.703   870  3749 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 12:02:23.703   870  3749 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 12:02:23.703   870  3749 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 12:02:23.703   870  3749 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 12:02:23.703   870  3749 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 12:02:23.703   870  3749 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 12:02:23.703   870  3749 E DropBoxManagerService: 	... 5 more
,08-11 12:02:23.707   374  3748 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-11 12:02:23.707   374  3748 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-11 12:02:23.708   374  3748 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
08-11 12:02:23.710  2902  3741 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-11 12:02:23.715   374  3748 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-11 12:02:23.719   870  3750 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 12:02:23.719  2902  2948 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-11 12:02:23.720  2902  2948 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-11 12:02:23.720  2902  2948 E AndroidRuntime: Process: android.process.acore, PID: 2902
08-11 12:02:23.720  2902  2948 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 12:02:23.720  2902  2948 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 12:02:23.720  2902  2948 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-11 12:02:23.720  2902  2948 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-11 12:02:23.720  2902  2948 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-11 12:02:23.720  2902  2948 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-11 12:02:23.720  2902  2948 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-11 12:02:23.720  2902  2948 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
08-11 12:02:23.720  2902  2948 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
08-11 12:02:23.720  2902  2948 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
08-11 12:02:23.720  2902  2948 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-11 12:02:23.720  2902  2948 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:02:23.720  2902  2948 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:02:23.720  2902  2948 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 12:02:23.730   870  3751 E DropBoxManagerService: Can't write: system_app_crash
08-11 12:02:23.730   870  3751 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-11 12:02:23.730   870  3751 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 12:02:23.730   870  3751 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 12:02:23.730   870  3751 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 12:02:23.730   870  3751 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 12:02:23.730   870  3751 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 12:02:23.730   870  3751 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 12:02:23.730   870  3751 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 12:02:23.730   870  3751 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 12:02:23.730   870  3751 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 12:02:23.730   870  3751 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 12:02:23.730   870  3751 E DropBoxManagerService: 	... 5 more
,08-11 12:02:23.737  2902  3741 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-11 12:02:23.737  2902  3741 I Process : Sending signal. PID: 2902 SIG: 9
,08-11 12:02:23.751  1735  1837 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-11 12:02:23.752   870   882 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-11 12:02:23.752   870   882 E PackageManager: Failed to write settings, restoring backup
08-11 12:02:23.752   870   882 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-11 12:02:23.752   870   882 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-11 12:02:23.752   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-11 12:02:23.752   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-11 12:02:23.752   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-11 12:02:23.752   870   882 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:02:23.752   870   882 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:02:23.752   870   882 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 12:02:23.754   870   883 E DropBoxManagerService: Can't write: system_server_wtf
08-11 12:02:23.754   870   883 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 12:02:23.754   870   883 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 12:02:23.754   870   883 E DropBoxManagerService: 	... 13 more
,08-11 12:02:23.766   870  3750 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 12:02:23.766   870  3750 I Adreno  : Build Date                       : 10/20/15
08-11 12:02:23.766   870  3750 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 12:02:23.766   870  3750 I Adreno  : Local Branch                     : M14
08-11 12:02:23.766   870  3750 I Adreno  : Remote Branch                    : 
08-11 12:02:23.766   870  3750 I Adreno  : Remote Branch                    : 
08-11 12:02:23.766   870  3750 I Adreno  : Reconstruct Branch               : 
08-11 12:02:23.766   870  1714 I ActivityManager: Start proc 3752:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-11 12:02:23.767  1735  1837 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-11 12:02:23.767  1735  1837 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1735
08-11 12:02:23.767  1735  1837 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 12:02:23.767  1735  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 12:02:23.767  1735  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 12:02:23.767  1735  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 12:02:23.767  1735  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 12:02:23.767  1735  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 12:02:23.767  1735  1837 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-11 12:02:23.767  1735  1837 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-11 12:02:23.767  1735  1837 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 12:02:23.767  1735  1837 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 12:02:23.767  1735  1837 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:02:23.767  1735  1837 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 12:02:23.768   870  1731 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 12:02:23.771   870  3750 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 12:02:23.771  1795  1807 W SearchService: Abort, client detached.
08-11 12:02:23.773  1795  1795 I HotwordDetector: Closing mic
08-11 12:02:23.774  1795  2118 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@8c22f6b
08-11 12:02:23.775  1795  3745 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-11 12:02:23.780   870  3761 E DropBoxManagerService: Can't write: system_app_crash
08-11 12:02:23.780   870  3761 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-11 12:02:23.780   870  3761 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 12:02:23.780   870  3761 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 12:02:23.780   870  3761 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 12:02:23.780   870  3761 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 12:02:23.780   870  3761 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 12:02:23.780   870  3761 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 12:02:23.780   870  3761 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 12:02:23.780   870  3761 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 12:02:23.780   870  3761 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 12:02:23.780   870  3761 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 12:02:23.780   870  3761 E DropBoxManagerService: 	... 5 more
08-11 12:02:23.782  1795  3764 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-11 12:02:23.787   870  1955 I ActivityManager: Process android.process.acore (pid 2902) has died
08-11 12:02:23.788   870  1955 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-11 12:02:23.834   374  3748 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-11 12:02:23.834   374  3748 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,08-11 12:02:23.838   374  1271 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-11 12:02:23.839  1795  3744 I MicroRecognitionRnrImpl: Detection finished
08-11 12:02:23.840  1795  2124 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-11 12:02:23.884  1877  3771 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-11 12:02:23.885  1877  3771 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-11 12:02:24.066   281   281 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-11 12:02:24.066   281   281 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-11 12:02:24.066   281   281 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-11 12:02:24.066   281   281 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-11 12:02:24.066   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-11 12:02:24.066   281   281 E qdoverlay: MdpCtrl close error in unset
,08-11 12:02:24.347   281   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-11 12:02:24.349   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,08-11 12:02:24.349   281   281 E qdoverlay: MdpCtrl close error in unset
```
