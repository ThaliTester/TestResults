#### Test 797510151e03ec5_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-12 16:29:04.436   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:29:05.089  3776  3776 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 16:29:05.093  3776  3776 D AndroidRuntime: CheckJNI is OFF
08-12 16:29:05.210  3776  3776 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 16:29:05.266  3776  3776 I Radio-JNI: register_android_hardware_Radio DONE
08-12 16:29:05.295  3776  3776 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 16:29:05.304   871  2146 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 16:29:05.354  2007  2109 W SearchService: Abort, client detached.
08-12 16:29:05.358  3776  3776 D AndroidRuntime: Shutting down VM
08-12 16:29:05.363  2007  2007 I HotwordDetector: Closing mic
08-12 16:29:05.363  2007  2365 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e55ca10
08-12 16:29:05.364  2007  2375 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 16:29:05.377   871  1919 I ActivityManager: Start proc 3787:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-12 16:29:05.423   375  2378 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 16:29:05.424   375  2378 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 16:29:05.430   375  1284 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 16:29:05.433  2007  2374 I MicroRecognitionRnrImpl: Detection finished
08-12 16:29:05.434  2007  2371 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-12 16:29:05.465  3787  3787 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-12 16:29:05.486  3787  3787 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-12 16:29:05.492  3787  3787 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9077-9080)
08-12 16:29:05.492  3787  3787 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 16:29:05.510  3787  3787 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3a03586}
08-12 16:29:05.510  3787  3787 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 16:29:05.510  3787  3787 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 16:29:05.516  3787  3787 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 16:29:05.517  3787  3787 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 16:29:05.531  3787  3787 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-12 16:29:05.540  3787  3787 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 16:29:05.540  3787  3787 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 16:29:05.540  3787  3787 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 16:29:05.540  3787  3787 I Adreno  : Build Date                       : 10/20/15
08-12 16:29:05.540  3787  3787 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 16:29:05.540  3787  3787 I Adreno  : Local Branch                     : M14
08-12 16:29:05.540  3787  3787 I Adreno  : Remote Branch                    : 
08-12 16:29:05.540  3787  3787 I Adreno  : Remote Branch                    : 
08-12 16:29:05.540  3787  3787 I Adreno  : Reconstruct Branch               : 
,08-12 16:29:05.611   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@89cbd38:true
08-12 16:29:05.653  3787  3787 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 16:29:05.669  3787  3787 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-12 16:29:05.745  3787  3826 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-12 16:29:05.755  3787  3812 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-12 16:29:05.804  3787  3826 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 16:29:05.866   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +503ms
08-12 16:29:05.868  1865  1865 I Keyboard.Facilitator: onFinishInput()
08-12 16:29:05.962  3787  3787 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3787
08-12 16:29:06.094  3787  3787 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-12 16:29:06.198   871  1950 I ActivityManager: Killing 2967:com.google.android.calendar/u0a37 (adj 15): empty #17
08-12 16:29:06.235   871  1950 I ActivityManager: Killing 3192:com.google.android.gm/u0a78 (adj 15): empty #18
08-12 16:29:06.396  3787  3828 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1697973968
08-12 16:29:06.417  3787  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 16:29:06.417  3787  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 16:29:06.417  3787  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 16:29:06.417  3787  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 16:29:06.417  3787  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 16:29:06.417  3787  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ce4a2a added. We now have 1 listener(s)
08-12 16:29:06.423  3787  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-12 16:29:06.424  3787  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 16:29:06.425  3787  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 16:29:06.426  3787  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 16:29:06.434  3787  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d76f91 added. We now have 1 listener(s)
08-12 16:29:06.434  3787  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 16:29:06.438   871  1312 D WifiService: New client listening to asynchronous messages
08-12 16:29:06.440  3787  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 16:29:06.440  3787  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 16:29:06.440  3787  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 16:29:06.440  3787  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 16:29:06.440  3787  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 16:29:06.444  3787  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 16:29:06.444  3787  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-12 16:29:06.454  3787  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-12 16:29:06.455  3787  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 16:29:06.455  3787  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 16:29:06.455  3787  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 16:29:06.455  3787  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 16:29:06.455  3787  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 16:29:06.455  3787  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 16:29:06.455  3787  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 16:29:06.455  3787  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 16:29:06.455  3787  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 16:29:06.455  3787  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 16:29:06.456  3787  3828 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 16:29:06.513  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 16:29:06.515  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 16:29:06.517  3787  3787 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 16:29:07.763  3787  3836 W jxcore-log: Initializing JXcore engine
,08-12 16:29:07.763  3787  3836 W jxcore-log: JXcore engine is ready
,08-12 16:29:07.796  3836  3836 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-12 16:29:07.796  3836  3836 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9731]" dev="sockfs" ino=9731 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 16:29:07.796  3836  3836 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 16:29:07.796  3836  3836 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24965]" dev="sockfs" ino=24965 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-12 16:29:07.812  3787  3836 W jxcore-log: Starting JXcore engine
,08-12 16:29:07.890  3787  3836 W jxcore-log: Platform android
08-12 16:29:07.890  3787  3836 W jxcore-log: 
,08-12 16:29:07.890  3787  3836 W jxcore-log: Process ARCH arm
08-12 16:29:07.890  3787  3836 W jxcore-log: 
,08-12 16:29:08.106  3787  3836 I jxcore-log: JXcore Cordova bridge is ready!
08-12 16:29:08.106  3787  3836 I jxcore-log: 
,08-12 16:29:08.106  3787  3836 W jxcore-log: JXcore engine is started
,08-12 16:29:08.117  3787  3828 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 16:29:08.120  3787  3787 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 16:29:08.196   871  1310 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-12 16:29:13.002  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:29:13.005  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:29:13.051  1513  2099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 16:29:13.051  1513  2099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-12 16:29:13.051  1513  2099 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 16:29:13.051  1513  2099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:29:13.089  3543  3844 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 16:29:13.089  3543  3844 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at jdm.a(PG:82)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at jcs.o(PG:406)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at jcn.a(PG:1379)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at jcs.i(PG:143)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at blb.a(PG:3937)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at czp.a(PG:18188)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at czp.a(PG:9081)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at czq.run(PG:1686)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 16:29:13.089  3543  3844 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at jdj.a(PG:4091)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at jdj.a(PG:1125)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at jdm.a(PG:77)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	... 12 more
08-12 16:29:13.089  3543  3844 E HttpOperation: Caused by: faj: BadAuthentication
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at fal.a(PG:38)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	at jdj.a(PG:4089)
08-12 16:29:13.089  3543  3844 E HttpOperation: 	... 14 more
,08-12 16:29:13.183  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-12 16:29:13.183  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 16:29:13.183  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:29:13.183  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:29:13.211  3543  3844 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 16:29:13.211  3543  3844 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at jdm.a(PG:82)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at jcs.o(PG:406)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at jcn.a(PG:1379)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at jcs.i(PG:143)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at hec.a(PG:42)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at hee.a(PG:102)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at czr.a(PG:65)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at kka.a(PG:108)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at czp.a(PG:19176)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at czp.a(PG:9081)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at czq.run(PG:1686)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 16:29:13.211  3543  3844 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at jdj.a(PG:4091)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at jdj.a(PG:1125)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at jdm.a(PG:77)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	... 15 more
08-12 16:29:13.211  3543  3844 E HttpOperation: Caused by: faj: BadAuthentication
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at fal.a(PG:38)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	at jdj.a(PG:4089)
08-12 16:29:13.211  3543  3844 E HttpOperation: 	... 17 more
,08-12 16:29:13.212  3543  3844 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 16:29:13.212  3543  3844 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at hec.a(PG:42)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at hee.a(PG:102)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at czr.a(PG:65)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at kka.a(PG:108)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	... 15 more
08-12 16:29:13.212  3543  3844 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at fal.a(PG:38)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 16:29:13.212  3543  3844 E ExperimentLoader: 	... 17 more
,08-12 16:29:13.336   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 96489, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 16:29:15.591  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:29:15.614  1513  2099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 16:29:15.614  1513  2099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 16:29:15.614  1513  2099 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:29:15.614  1513  2099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:29:15.646  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 16:29:15.646  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 16:29:15.646  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-12 16:29:24.109  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 16:29:24.109  3787  3836 I jxcore-log: 
,08-12 16:29:24.111  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 16:29:24.111  3787  3836 I jxcore-log: 
,08-12 16:29:24.124  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 16:29:24.124  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 16:29:24.124  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 16:29:24.124  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 16:29:24.124  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 16:29:24.124  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 16:29:24.124  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 16:29:24.124  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 16:29:24.131  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 16:29:24.134  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 16:29:24.134  3787  3836 I jxcore-log: 
,08-12 16:29:24.136  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 16:29:24.136  3787  3836 I jxcore-log: 
,08-12 16:29:24.483  3787  3836 I jxcore-log: Unit Test app is loaded
08-12 16:29:24.483  3787  3836 I jxcore-log: 
,08-12 16:29:24.498  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 16:29:24.498  3787  3836 I jxcore-log: 
,08-12 16:29:24.499  3787  3787 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 16:29:24.512  3787  3836 I jxcore-log: My device name is: motorola-Nexus 6
08-12 16:29:24.512  3787  3836 I jxcore-log: 
,08-12 16:29:24.524  3787  3836 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 16:29:24.524  3787  3836 I jxcore-log: 
,08-12 16:29:26.826  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 16:29:26.826  3787  3836 I jxcore-log: 
,08-12 16:29:27.439  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 16:29:27.439  3787  3836 I jxcore-log: 
,08-12 16:29:27.464  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 16:29:27.464  3787  3836 I jxcore-log: 
,08-12 16:29:28.813  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 16:29:28.813  3787  3836 I jxcore-log: 
,08-12 16:29:29.040  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 16:29:29.040  3787  3836 I jxcore-log: 
,08-12 16:29:29.046  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 16:29:29.046  3787  3836 I jxcore-log: 
,08-12 16:29:29.052  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 16:29:29.052  3787  3836 I jxcore-log: 
,08-12 16:29:29.068  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 16:29:29.068  3787  3836 I jxcore-log: 
,08-12 16:29:29.073  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 16:29:29.073  3787  3836 I jxcore-log: 
,08-12 16:29:29.745  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 16:29:29.745  3787  3836 I jxcore-log: 
,08-12 16:29:29.757  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 16:29:29.757  3787  3836 I jxcore-log: 
,08-12 16:29:29.767  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 16:29:29.767  3787  3836 I jxcore-log: 
,08-12 16:29:29.774  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 16:29:29.774  3787  3836 I jxcore-log: 
,08-12 16:29:29.826  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 16:29:29.826  3787  3836 I jxcore-log: 
,08-12 16:29:29.882  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 16:29:29.882  3787  3836 I jxcore-log: 
,08-12 16:29:29.889  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 16:29:29.889  3787  3836 I jxcore-log: 
,08-12 16:29:30.054  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 16:29:30.054  3787  3836 I jxcore-log: 
,08-12 16:29:30.080  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 16:29:30.080  3787  3836 I jxcore-log: 
,08-12 16:29:30.085  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 16:29:30.085  3787  3836 I jxcore-log: 
,08-12 16:29:30.091  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 16:29:30.091  3787  3836 I jxcore-log: 
,08-12 16:29:30.109  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 16:29:30.109  3787  3836 I jxcore-log: 
,08-12 16:29:30.192  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 16:29:30.192  3787  3836 I jxcore-log: 
,08-12 16:29:30.204  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 16:29:30.204  3787  3836 I jxcore-log: 
,08-12 16:29:30.232  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 16:29:30.232  3787  3836 I jxcore-log: 
,08-12 16:29:30.244  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 16:29:30.244  3787  3836 I jxcore-log: 
,08-12 16:29:30.263  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 16:29:30.263  3787  3836 I jxcore-log: 
,08-12 16:29:30.300  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 16:29:30.300  3787  3836 I jxcore-log: 
,08-12 16:29:30.306  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 16:29:30.306  3787  3836 I jxcore-log: 
,08-12 16:29:30.507  3787  3836 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 16:29:30.507  3787  3836 I jxcore-log: 
,08-12 16:29:30.520  3787  3836 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-12 16:29:30.521  3787  3836 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-12 16:29:30.521  3787  3836 I jxcore-log: 
,08-12 16:29:35.570   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=149157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 16:29:36.719   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-12 16:29:36.741  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-12 16:29:36.750   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 16:29:36.750   871   891 I Adreno  : Build Date                       : 10/20/15
08-12 16:29:36.750   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 16:29:36.750   871   891 I Adreno  : Local Branch                     : M14
08-12 16:29:36.750   871   891 I Adreno  : Remote Branch                    : 
08-12 16:29:36.750   871   891 I Adreno  : Remote Branch                    : 
08-12 16:29:36.750   871   891 I Adreno  : Reconstruct Branch               : 
,08-12 16:29:36.780   279   370 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (538 us)
,08-12 16:29:37.398  3787  3787 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-12 16:29:37.399  3787  3787 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-12 16:29:37.433   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-12 16:29:37.436  3787  3787 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9e6500c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@a6bb4eb, 16908290=android.view.AbsSavedState$1@a6bb4eb}, android:focusedViewId=100}]}]
,08-12 16:29:37.436  3787  3787 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-12 16:29:37.436  3787  3787 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-12 16:29:37.436  3787  3787 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-12 16:29:37.445   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-12 16:29:37.451   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-12 16:29:37.451   279   279 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,08-12 16:29:37.453   279   279 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-12 16:29:37.466   871   880 I art     : Background partial concurrent mark sweep GC freed 26354(1824KB) AllocSpace objects, 11(240KB) LOS objects, 33% free, 28MB/43MB, paused 1.785ms total 104.727ms
,08-12 16:29:37.680   279   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 16:29:37.683   279   279 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-12 16:29:37.684   871  1337 D SurfaceControl: Excessive delay in setPowerMode(): 233ms
,08-12 16:29:37.691   871   891 I DreamManagerService: Entering dreamland.
,08-12 16:29:37.695   871   891 I PowerManagerService: Dozing...
,08-12 16:29:37.695   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-12 16:29:37.752   375  1321 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-12 16:29:37.752   375  1321 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-12 16:29:37.757   871  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 16:29:37.767   871  1310 E native  : do suspend false
,08-12 16:29:37.772  1923  3855 D NfcService: Discovery configuration equal, not updating.
,08-12 16:29:37.774   871  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,08-12 16:29:37.799   871  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 16:29:37.803   871  1310 E native  : do suspend true
,08-12 16:29:37.887   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-12 16:29:37.888   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-12 16:29:38.263   871  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-12 16:29:41.839  2056  2639 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 16:29:42.063  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:29:42.074  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:29:42.077  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:29:42.113  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 16:29:42.114  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 16:29:42.114  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 16:29:42.114  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:29:42.145  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 16:29:42.145  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 16:29:42.146  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-12 16:29:43.416  3594  3860 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 16:29:43.454  3594  3861 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 16:29:43.513  1513  2099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 16:29:43.514  1513  2099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 16:29:43.514  1513  2099 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:29:43.514  1513  2099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:29:43.605  1513  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 16:29:43.606  1513  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 16:29:43.606  1513  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 16:29:43.606  1513  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:29:43.644  3594  3861 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 16:29:43.646  3594  3860 E BooksSync: Soft error
08-12 16:29:43.646  3594  3860 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 16:29:43.646  3594  3860 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 16:29:43.646  3594  3860 E BooksSync: Sync error
08-12 16:29:43.646  3594  3860 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 16:29:43.646  3594  3860 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 16:29:43.646  3594  3860 I BooksSync: Finished books sync
,08-12 16:29:43.658   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 129390, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 16:29:48.211   871  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-12 16:30:06.196   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=179783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:30:08.009  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:30:08.183  1513  3867 I VacuumService: Vacuum at: now=1471012208183 tag=VacuumService
,08-12 16:30:08.424  1513  3868 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-12 16:30:08.429  1513  3868 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 16:30:08.463  1513  3868 W Uploader:  no longer exists, so no auth token.
,08-12 16:30:09.246  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:30:09.251  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:30:09.277  1513  3868 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 16:30:09.278  1513  3868 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-12 16:30:09.278  1513  3868 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:30:09.278  1513  3868 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:30:09.294  1513  3868 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 16:30:09.294  1513  3868 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 16:30:09.294  1513  3868 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 16:30:09.294  1513  3868 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 16:30:09.294  1513  3868 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 16:30:09.294  1513  3868 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 16:30:09.294  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 16:30:09.294  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 16:30:09.294  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 16:30:09.294  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 16:30:09.294  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 16:30:09.294  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 16:30:09.294  1513  3868 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 16:30:09.606  1513  3868 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 16:30:09.607  1513  3868 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-12 16:30:09.607  1513  3868 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 16:30:09.607  1513  3868 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:30:09.628  1513  3868 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 16:30:09.628  1513  3868 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 16:30:09.628  1513  3868 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 16:30:09.628  1513  3868 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 16:30:09.628  1513  3868 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 16:30:09.628  1513  3868 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 16:30:09.628  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 16:30:09.628  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 16:30:09.628  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 16:30:09.628  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 16:30:09.628  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 16:30:09.628  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 16:30:09.628  1513  3868 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 16:30:10.209  1513  3868 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 16:30:10.209  1513  3868 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-12 16:30:10.210  1513  3868 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:30:10.210  1513  3868 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:30:10.230  1513  3868 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 16:30:10.230  1513  3868 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 16:30:10.230  1513  3868 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 16:30:10.230  1513  3868 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 16:30:10.230  1513  3868 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 16:30:10.230  1513  3868 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 16:30:10.230  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 16:30:10.230  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 16:30:10.230  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 16:30:10.230  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 16:30:10.230  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 16:30:10.230  1513  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 16:30:10.230  1513  3868 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 16:30:13.023   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=186610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 16:30:13.827  3128  3881 V KeepSync: Connecting to GoogleApiClient
,08-12 16:30:13.829   871  2145 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 16:30:13.888  1513  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-12 16:30:13.888  1513  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-12 16:30:13.888  1513  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:30:13.889  1513  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:30:13.902  1722  3882 V BaseAuthAsyncOperation: access token request failed
,08-12 16:30:13.903  3128  3881 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 16:30:13.948  1513  3623 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 16:30:13.948  1513  3623 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-12 16:30:13.948  1513  3623 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:30:13.948  1513  3623 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:30:13.962  3128  3881 E KeepSync: IOException
08-12 16:30:13.962  3128  3881 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 16:30:13.962  3128  3881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 16:30:13.962  3128  3881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 16:30:13.962  3128  3881 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 16:30:13.962  3128  3881 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 16:30:13.962  3128  3881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 16:30:13.962  3128  3881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 16:30:13.962  3128  3881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 16:30:13.962  3128  3881 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 16:30:13.962  3128  3881 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 16:30:13.962  3128  3881 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 16:30:13.962  3128  3881 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 16:30:13.962  3128  3881 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 16:30:13.962  3128  3881 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 16:30:13.962  3128  3881 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 16:30:13.962  3128  3881 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 16:30:13.962  3128  3881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 16:30:13.962  3128  3881 E KeepSync: 	... 10 more
08-12 16:30:13.962  3128  3881 W KeepSync: Sync result 2
,08-12 16:30:13.971   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 160583, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 16:30:36.782  1865  1981 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-12 16:30:36.783  1865  1981 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-12 16:30:36.815  1513  1513 I ConfigService: onCreate
,08-12 16:30:40.562   871  2143 I ActivityManager: Start proc 3884:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-12 16:30:40.601  3884  3884 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-12 16:30:40.628   871  1944 I ActivityManager: Start proc 3897:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,08-12 16:30:40.677  3884  3896 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-12 16:30:40.717  3897  3897 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-12 16:30:40.825  3897  3897 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-12 16:30:40.858  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:30:40.861  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:30:40.903  3897  3929 V GoogleAuthProtoRequest: [325] a.<init>: mAccountName set to: thalitester@gmail.com
,08-12 16:30:40.915  3884  3896 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-12 16:30:41.007  3884  3896 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-12 16:30:41.029  1513  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-12 16:30:41.029  1513  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-12 16:30:41.030  1513  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:30:41.030  1513  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:30:41.066  3884  3884 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-12 16:30:41.105  3897  3929 W ExperimentUpdateService: [325] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-12 16:30:41.106  3897  3929 W ExperimentUpdateService: [325] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 16:30:41.106  3897  3929 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 16:30:41.106  3897  3929 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-12 16:30:41.106  3897  3929 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-12 16:30:41.106  3897  3929 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-12 16:30:41.106  3897  3929 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-12 16:30:41.106  3897  3929 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-12 16:30:41.106  3897  3929 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-12 16:30:41.106  3897  3929 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-12 16:30:41.106  3897  3929 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-12 16:30:41.106  3897  3929 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-12 16:30:41.110   871  2146 I ActivityManager: Killing 3369:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-12 16:30:41.303  3949  3949 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1026669291.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1026669291.dex
,08-12 16:30:41.383  3884  3884 W InstanceID/Rpc: Found 10011
,08-12 16:30:41.486   871  1402 I ActivityManager: Killing 2397:com.google.android.talk/u0a61 (adj 15): empty #17
,08-12 16:30:41.556  3949  3949 I dex2oat : dex2oat took 264.763ms (threads: 4) arena alloc=245KB java alloc=29KB native alloc=1643KB free=1684KB
,08-12 16:30:41.885  1513  1513 I ConfigService: onDestroy
,08-12 16:30:44.283  1513  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 16:30:44.283  1513  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 16:30:44.283  1513  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:30:44.283  1513  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:30:44.304  3543  3993 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 16:30:44.304  3543  3993 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at jdm.a(PG:82)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at jcs.o(PG:406)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at jcn.a(PG:1379)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at jcs.i(PG:143)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at blb.a(PG:3937)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at czp.a(PG:18188)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at czp.a(PG:9081)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at czq.run(PG:1686)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 16:30:44.304  3543  3993 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at jdj.a(PG:4091)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at jdj.a(PG:1125)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at jdm.a(PG:77)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	... 12 more
08-12 16:30:44.304  3543  3993 E HttpOperation: Caused by: faj: BadAuthentication
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at fal.a(PG:38)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	at jdj.a(PG:4089)
08-12 16:30:44.304  3543  3993 E HttpOperation: 	... 14 more
,08-12 16:30:44.357  1513  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-12 16:30:44.357  1513  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 16:30:44.357  1513  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:30:44.357  1513  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:30:44.377  3543  3993 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 16:30:44.377  3543  3993 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at jdm.a(PG:82)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at jcs.o(PG:406)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at jcn.a(PG:1379)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at jcs.i(PG:143)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at hec.a(PG:42)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at hee.a(PG:102)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at czr.a(PG:65)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at kka.a(PG:108)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at czp.a(PG:19176)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at czp.a(PG:9081)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at czq.run(PG:1686)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 16:30:44.377  3543  3993 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at jdj.a(PG:4091)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at jdj.a(PG:1125)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at jdm.a(PG:77)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	... 15 more
08-12 16:30:44.377  3543  3993 E HttpOperation: Caused by: faj: BadAuthentication
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at fal.a(PG:38)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	at jdj.a(PG:4089)
08-12 16:30:44.377  3543  3993 E HttpOperation: 	... 17 more
,08-12 16:30:44.378  3543  3993 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 16:30:44.378  3543  3993 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at hec.a(PG:42)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at hee.a(PG:102)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at czr.a(PG:65)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at kka.a(PG:108)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	... 15 more
08-12 16:30:44.378  3543  3993 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at fal.a(PG:38)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 16:30:44.378  3543  3993 E ExperimentLoader: 	... 17 more
,08-12 16:30:44.528   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 190259, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 16:31:11.592  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:31:11.593  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:31:11.607  3897  3996 V GoogleAuthProtoRequest: [326] a.<init>: mAccountName set to: thalitester@gmail.com
,08-12 16:31:11.664  1513  2305 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-12 16:31:11.664  1513  2305 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-12 16:31:11.664  1513  2305 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:31:11.664  1513  2305 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:31:11.681  3897  3996 W ExperimentUpdateService: [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-12 16:31:11.681  3897  3996 W ExperimentUpdateService: [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 16:31:11.681  3897  3996 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 16:31:11.681  3897  3996 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-12 16:31:11.681  3897  3996 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
,08-12 16:31:11.681  3897  3996 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-12 16:31:11.681  3897  3996 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-12 16:31:11.681  3897  3996 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-12 16:31:11.681  3897  3996 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-12 16:31:11.681  3897  3996 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-12 16:31:11.681  3897  3996 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-12 16:31:11.681  3897  3996 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-12 16:31:28.063   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=261650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:31:33.956   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 16:31:51.356  3594  4000 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 16:31:51.388  3594  4001 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 16:31:51.403  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:31:51.405  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:31:51.437  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-12 16:31:51.437  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 16:31:51.437  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:31:51.437  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:31:51.475  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:31:51.476  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:31:51.503  1513  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 16:31:51.503  1513  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 16:31:51.504  1513  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 16:31:51.504  1513  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:31:51.524  3594  4001 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 16:31:51.525  3594  4000 E BooksSync: Soft error
08-12 16:31:51.525  3594  4000 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 16:31:51.525  3594  4000 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 16:31:51.525  3594  4000 E BooksSync: Sync error
08-12 16:31:51.525  3594  4000 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 16:31:51.525  3594  4000 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 16:31:51.525  3594  4000 I BooksSync: Finished books sync
,08-12 16:31:51.531   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284782, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 16:32:08.543   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=302130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:32:11.780  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:32:11.783  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:32:11.795  3897  4007 V GoogleAuthProtoRequest: [327] a.<init>: mAccountName set to: thalitester@gmail.com
,08-12 16:32:11.825  1513  2305 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-12 16:32:11.825  1513  2305 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-12 16:32:11.826  1513  2305 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:32:11.826  1513  2305 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-12 16:32:11.844  3897  4007 W ExperimentUpdateService: [327] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-12 16:32:11.844  3897  4007 W ExperimentUpdateService: [327] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 16:32:11.844  3897  4007 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 16:32:11.844  3897  4007 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-12 16:32:11.844  3897  4007 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-12 16:32:11.844  3897  4007 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-12 16:32:11.844  3897  4007 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-12 16:32:11.844  3897  4007 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-12 16:32:11.844  3897  4007 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-12 16:32:11.844  3897  4007 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-12 16:32:11.844  3897  4007 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-12 16:32:11.844  3897  4007 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-12 16:32:14.383   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 16:32:22.680  3128  4018 V KeepSync: Connecting to GoogleApiClient
08-12 16:32:22.680   871  2143 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 16:32:22.716  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:32:22.717  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:32:22.733  1513  2305 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-12 16:32:22.733  1513  2305 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-12 16:32:22.733  1513  2305 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 16:32:22.734  1513  2305 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:32:22.746  1722  4019 V BaseAuthAsyncOperation: access token request failed
,08-12 16:32:22.747  3128  4018 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 16:32:22.781  1513  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 16:32:22.781  1513  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-12 16:32:22.781  1513  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 16:32:22.781  1513  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:32:22.798  3128  4018 E KeepSync: IOException
08-12 16:32:22.798  3128  4018 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 16:32:22.798  3128  4018 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 16:32:22.798  3128  4018 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 16:32:22.798  3128  4018 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 16:32:22.798  3128  4018 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 16:32:22.798  3128  4018 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 16:32:22.798  3128  4018 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 16:32:22.798  3128  4018 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 16:32:22.798  3128  4018 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 16:32:22.798  3128  4018 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 16:32:22.798  3128  4018 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 16:32:22.798  3128  4018 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 16:32:22.798  3128  4018 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 16:32:22.798  3128  4018 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 16:32:22.798  3128  4018 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 16:32:22.798  3128  4018 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 16:32:22.798  3128  4018 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 16:32:22.798  3128  4018 E KeepSync: 	... 10 more
,08-12 16:32:22.798  3128  4018 W KeepSync: Sync result 2
,08-12 16:32:22.829   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 316099, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 16:32:48.288  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:32:48.296  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 16:32:48.297  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:32:48.343  1513  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-12 16:32:48.343  1513  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-12 16:32:48.344  1513  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:32:48.344  1513  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:32:48.377  1513  2294 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 16:32:48.377  1513  2294 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 16:32:48.377  1513  2294 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 16:32:48.377  1513  2294 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-12 16:32:48.377  1513  2294 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-12 16:32:48.377  1513  2294 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-12 16:32:48.377  1513  2294 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 16:32:48.389  3504  3533 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 16:32:48.389  3504  3533 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-12 16:32:48.389  3504  3533 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-12 16:32:48.389  3504  3533 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-12 16:32:48.389  3504  3533 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-12 16:32:48.389  3504  3533 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-12 16:32:48.389  3504  3533 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 16:32:51.474  3787  3836 I jxcore-log: TAP version 13
08-12 16:32:51.474  3787  3836 I jxcore-log: 
,08-12 16:32:51.485  3787  3836 I jxcore-log: # setup
08-12 16:32:51.485  3787  3836 I jxcore-log: 
,08-12 16:32:51.785  3787  3836 I jxcore-log: # 1. calling createNativeListener directly rejects
08-12 16:32:51.785  3787  3836 I jxcore-log: 
,08-12 16:32:51.993  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:32:51.993  3787  3836 I jxcore-log: 
,08-12 16:32:51.998  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 46921
08-12 16:32:51.998  3787  3836 I jxcore-log: 
,08-12 16:32:52.010  3787  3836 I jxcore-log: ok 1 Should throw
08-12 16:32:52.010  3787  3836 I jxcore-log: 
,08-12 16:32:52.014  3787  3836 I jxcore-log: # teardown
08-12 16:32:52.014  3787  3836 I jxcore-log: 
,08-12 16:32:52.178  3787  3836 I jxcore-log: # setup
08-12 16:32:52.178  3787  3836 I jxcore-log: 
,08-12 16:32:52.402  3787  3836 I jxcore-log: # 2. emits incomingConnectionState
08-12 16:32:52.402  3787  3836 I jxcore-log: 
,08-12 16:32:52.524  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:32:52.524  3787  3836 I jxcore-log: 
,08-12 16:32:52.537  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 45967
08-12 16:32:52.537  3787  3836 I jxcore-log: 
,08-12 16:32:52.547  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:52.547  3787  3836 I jxcore-log: 
,08-12 16:32:52.551  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:52.551  3787  3836 I jxcore-log: 
,08-12 16:32:52.561  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:52.561  3787  3836 I jxcore-log: 
,08-12 16:32:52.568  3787  3836 I jxcore-log: ok 2 initial connection state should be CONNECTED
08-12 16:32:52.568  3787  3836 I jxcore-log: 
,08-12 16:32:52.588  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:52.588  3787  3836 I jxcore-log: 
,08-12 16:32:52.589  3787  3836 I jxcore-log: ok 3 final connection state should be DISCONNECTED
08-12 16:32:52.589  3787  3836 I jxcore-log: 
,08-12 16:32:52.596  3787  3836 I jxcore-log: # teardown
08-12 16:32:52.596  3787  3836 I jxcore-log: 
,08-12 16:32:52.713  3787  3836 I jxcore-log: # setup
08-12 16:32:52.713  3787  3836 I jxcore-log: 
,08-12 16:32:52.923  3787  3836 I jxcore-log: # 3. emits routerPortConnectionFailed
08-12 16:32:52.923  3787  3836 I jxcore-log: 
,08-12 16:32:53.077  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:32:53.077  3787  3836 I jxcore-log: 
,08-12 16:32:53.083  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 39116
08-12 16:32:53.083  3787  3836 I jxcore-log: 
,08-12 16:32:53.090  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 16:32:53.090  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 16:32:53.090  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 16:32:53.090  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:32:53.094  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:53.094  3787  3836 I jxcore-log: 
,08-12 16:32:53.095  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:53.095  3787  3836 I jxcore-log: 
,08-12 16:32:53.096  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:53.096  3787  3836 I jxcore-log: 
,08-12 16:32:53.108  3543  4026 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 16:32:53.108  3543  4026 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at jdm.a(PG:82)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at jcs.o(PG:406)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at jcn.a(PG:1379)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at jcs.i(PG:143)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at blb.a(PG:3937)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at czp.a(PG:18188)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at czp.a(PG:9081)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at czq.run(PG:1686)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 16:32:53.108  3543  4026 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at jdj.a(PG:4091)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at jdj.a(PG:1125)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at jdm.a(PG:77)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	... 12 more
08-12 16:32:53.108  3543  4026 E HttpOperation: Caused by: faj: BadAuthentication
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at fal.a(PG:38)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	at jdj.a(PG:4089)
08-12 16:32:53.108  3543  4026 E HttpOperation: 	... 14 more
,08-12 16:32:53.125  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:53.125  3787  3836 I jxcore-log: 
,08-12 16:32:53.127  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:53.127  3787  3836 I jxcore-log: 
,08-12 16:32:53.131  3787  3836 I jxcore-log: DEBUG createNativeListener: 
08-12 16:32:53.131  3787  3836 I jxcore-log: 
08-12 16:32:53.132  3787  3836 I jxcore-log: ok 4 tried to connect to right port
08-12 16:32:53.132  3787  3836 I jxcore-log: 
,08-12 16:32:53.133  3787  3836 I jxcore-log: ok 5 failed due to refused connection
08-12 16:32:53.133  3787  3836 I jxcore-log: 
08-12 16:32:53.133  3787  3836 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
08-12 16:32:53.133  3787  3836 I jxcore-log: 
,08-12 16:32:53.136  3787  3836 I jxcore-log: # teardown
08-12 16:32:53.136  3787  3836 I jxcore-log: 
,08-12 16:32:53.137  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:53.137  3787  3836 I jxcore-log: 
,08-12 16:32:53.151  1513  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 16:32:53.151  1513  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 16:32:53.151  1513  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:32:53.151  1513  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:32:53.168  3543  4026 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 16:32:53.168  3543  4026 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at jdm.a(PG:82)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at jcs.o(PG:406)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at jcn.a(PG:1379)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at jcs.i(PG:143)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at hec.a(PG:42)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at hee.a(PG:102)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at czr.a(PG:65)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at kka.a(PG:108)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at czp.a(PG:19176)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at czp.a(PG:9081)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at czq.run(PG:1686)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 16:32:53.168  3543  4026 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at jdj.a(PG:4091)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at jdj.a(PG:1125)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at jdm.a(PG:77)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	... 15 more
08-12 16:32:53.168  3543  4026 E HttpOperation: Caused by: faj: BadAuthentication
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at fal.a(PG:38)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	at jdj.a(PG:4089)
08-12 16:32:53.168  3543  4026 E HttpOperation: 	... 17 more
,08-12 16:32:53.168  3543  4026 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 16:32:53.168  3543  4026 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at hec.a(PG:42)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at hee.a(PG:102)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at czr.a(PG:65)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at kka.a(PG:108)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	... 15 more
08-12 16:32:53.168  3543  4026 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at fal.a(PG:38)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 16:32:53.168  3543  4026 E ExperimentLoader: 	... 17 more
,08-12 16:32:53.290  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:53.290  3787  3836 I jxcore-log: 
,08-12 16:32:53.299  3787  3836 I jxcore-log: # setup
08-12 16:32:53.299  3787  3836 I jxcore-log: 
08-12 16:32:53.301  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:53.301  3787  3836 I jxcore-log: 
,08-12 16:32:53.315   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 344788, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 16:32:53.454  3787  3836 I jxcore-log: # 4. native server connections all up
08-12 16:32:53.454  3787  3836 I jxcore-log: 
,08-12 16:32:53.619  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:32:53.619  3787  3836 I jxcore-log: 
,08-12 16:32:53.629  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 38521
08-12 16:32:53.629  3787  3836 I jxcore-log: 
,08-12 16:32:53.643  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:53.643  3787  3836 I jxcore-log: 
,08-12 16:32:53.645  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:53.645  3787  3836 I jxcore-log: 
,08-12 16:32:53.646  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:53.646  3787  3836 I jxcore-log: 
,08-12 16:32:53.703  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:53.703  3787  3836 I jxcore-log: 
,08-12 16:32:53.705  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:53.705  3787  3836 I jxcore-log: 
,08-12 16:32:53.709  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:53.709  3787  3836 I jxcore-log: 
,08-12 16:32:53.711  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:53.711  3787  3836 I jxcore-log: 
,08-12 16:32:53.735  3787  3836 I jxcore-log: ok 7 Send/recvd #1 should be equal length
08-12 16:32:53.735  3787  3836 I jxcore-log: 
,08-12 16:32:53.735  3787  3836 I jxcore-log: ok 8 Send/recvd #1 should be same
08-12 16:32:53.735  3787  3836 I jxcore-log: 
,08-12 16:32:53.738  3787  3836 I jxcore-log: ok 9 Send/recvd #2 should be equal length
08-12 16:32:53.738  3787  3836 I jxcore-log: 
,08-12 16:32:53.739  3787  3836 I jxcore-log: ok 10 Send/recvd #2 should be same
08-12 16:32:53.739  3787  3836 I jxcore-log: 
08-12 16:32:53.743  3787  3836 I jxcore-log: ok 11 Should be exactly 2 client sockets
08-12 16:32:53.743  3787  3836 I jxcore-log: 
,08-12 16:32:53.750  3787  3836 I jxcore-log: # teardown
08-12 16:32:53.750  3787  3836 I jxcore-log: 
,08-12 16:32:53.994  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:53.994  3787  3836 I jxcore-log: 
,08-12 16:32:54.001  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:54.001  3787  3836 I jxcore-log: 
,08-12 16:32:54.003  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:54.003  3787  3836 I jxcore-log: 
,08-12 16:32:54.007  3787  3836 I jxcore-log: # setup
08-12 16:32:54.007  3787  3836 I jxcore-log: 
08-12 16:32:54.008  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:54.008  3787  3836 I jxcore-log: 
,08-12 16:32:54.171  3787  3836 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
08-12 16:32:54.171  3787  3836 I jxcore-log: 
,08-12 16:32:54.338  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:32:54.338  3787  3836 I jxcore-log: 
,08-12 16:32:54.342  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 43657
08-12 16:32:54.342  3787  3836 I jxcore-log: 
,08-12 16:32:54.349  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:54.349  3787  3836 I jxcore-log: 
,08-12 16:32:54.350  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:54.350  3787  3836 I jxcore-log: 
08-12 16:32:54.352  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:54.352  3787  3836 I jxcore-log: 
,08-12 16:32:54.367  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:54.367  3787  3836 I jxcore-log: 
,08-12 16:32:54.370  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:54.370  3787  3836 I jxcore-log: 
,08-12 16:32:54.384  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:54.384  3787  3836 I jxcore-log: 
,08-12 16:32:54.398  3787  3836 I jxcore-log: ok 12 socket shouldn't close until after stream
08-12 16:32:54.398  3787  3836 I jxcore-log: 
,08-12 16:32:54.399  3787  3836 I jxcore-log: ok 13 incoming remains open
08-12 16:32:54.399  3787  3836 I jxcore-log: 
,08-12 16:32:54.402  3787  3836 I jxcore-log: # teardown
08-12 16:32:54.402  3787  3836 I jxcore-log: 
,08-12 16:32:54.575  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:54.575  3787  3836 I jxcore-log: 
,08-12 16:32:54.584  3787  3836 I jxcore-log: # setup
08-12 16:32:54.584  3787  3836 I jxcore-log: 
,08-12 16:32:54.585  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:54.585  3787  3836 I jxcore-log: 
,08-12 16:32:54.984  3787  3836 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
08-12 16:32:54.984  3787  3836 I jxcore-log: 
,08-12 16:32:55.066  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:32:55.066  3787  3836 I jxcore-log: 
,08-12 16:32:55.075  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 40176
08-12 16:32:55.075  3787  3836 I jxcore-log: 
,08-12 16:32:55.085  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:55.085  3787  3836 I jxcore-log: 
,08-12 16:32:55.087  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:55.087  3787  3836 I jxcore-log: 
,08-12 16:32:55.088  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:55.088  3787  3836 I jxcore-log: 
,08-12 16:32:55.099  3787  3836 I jxcore-log: ok 14 we should not have gotten an error
08-12 16:32:55.099  3787  3836 I jxcore-log: 
,08-12 16:32:55.107  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:55.107  3787  3836 I jxcore-log: 
,08-12 16:32:55.110  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:55.110  3787  3836 I jxcore-log: 
,08-12 16:32:55.121  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:55.121  3787  3836 I jxcore-log: 
,08-12 16:32:55.124  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:55.124  3787  3836 I jxcore-log: 
,08-12 16:32:55.132  3787  3836 I jxcore-log: ok 15 socket shouldn't close until after incoming
08-12 16:32:55.132  3787  3836 I jxcore-log: 
,08-12 16:32:55.132  3787  3836 I jxcore-log: ok 16 incoming is cleaned up
08-12 16:32:55.132  3787  3836 I jxcore-log: 
,08-12 16:32:55.135  3787  3836 I jxcore-log: # teardown
08-12 16:32:55.135  3787  3836 I jxcore-log: 
,08-12 16:32:55.267  3787  3836 I jxcore-log: # setup
08-12 16:32:55.267  3787  3836 I jxcore-log: 
,08-12 16:32:55.342  3787  3836 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
08-12 16:32:55.342  3787  3836 I jxcore-log: 
,08-12 16:32:55.378  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:32:55.378  3787  3836 I jxcore-log: 
,08-12 16:32:55.381  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 48176
08-12 16:32:55.381  3787  3836 I jxcore-log: 
,08-12 16:32:55.392  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:55.392  3787  3836 I jxcore-log: 
,08-12 16:32:55.396  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:55.396  3787  3836 I jxcore-log: 
,08-12 16:32:55.403  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:55.403  3787  3836 I jxcore-log: 
,08-12 16:32:55.423  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:55.423  3787  3836 I jxcore-log: 
,08-12 16:32:55.426  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:55.426  3787  3836 I jxcore-log: 
,08-12 16:32:55.443  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:55.443  3787  3836 I jxcore-log: 
,08-12 16:32:55.453  3787  3836 I jxcore-log: ok 17 stream was closed
08-12 16:32:55.453  3787  3836 I jxcore-log: 
,08-12 16:32:55.454  3787  3836 I jxcore-log: ok 18 incoming should survive
08-12 16:32:55.454  3787  3836 I jxcore-log: 
08-12 16:32:55.454  3787  3836 I jxcore-log: ok 19 mux should have no streams
08-12 16:32:55.454  3787  3836 I jxcore-log: 
,08-12 16:32:55.458  3787  3836 I jxcore-log: # teardown
08-12 16:32:55.458  3787  3836 I jxcore-log: 
,08-12 16:32:55.496  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:55.496  3787  3836 I jxcore-log: 
,08-12 16:32:55.507  3787  3836 I jxcore-log: # setup
08-12 16:32:55.507  3787  3836 I jxcore-log: 
,08-12 16:32:55.510  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:55.510  3787  3836 I jxcore-log: 
,08-12 16:32:55.594  3787  3836 I jxcore-log: # 8. native server - closing the whole server cleans everything up
08-12 16:32:55.594  3787  3836 I jxcore-log: 
,08-12 16:32:55.629  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:32:55.629  3787  3836 I jxcore-log: 
,08-12 16:32:55.631  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 38985
08-12 16:32:55.631  3787  3836 I jxcore-log: 
,08-12 16:32:55.638  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:55.638  3787  3836 I jxcore-log: 
,08-12 16:32:55.639  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:55.639  3787  3836 I jxcore-log: 
,08-12 16:32:55.641  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:55.641  3787  3836 I jxcore-log: 
,08-12 16:32:55.650  3787  3836 I jxcore-log: ok 20 we should not have gotten an error
08-12 16:32:55.650  3787  3836 I jxcore-log: 
,08-12 16:32:55.660  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:55.660  3787  3836 I jxcore-log: 
,08-12 16:32:55.663  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:55.663  3787  3836 I jxcore-log: 
,08-12 16:32:55.673  3787  3836 I jxcore-log: ok 21 Buffers are identical
08-12 16:32:55.673  3787  3836 I jxcore-log: 
,08-12 16:32:55.675  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:55.675  3787  3836 I jxcore-log: 
,08-12 16:32:55.677  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:55.677  3787  3836 I jxcore-log: 
,08-12 16:32:55.680  3787  3836 I jxcore-log: ok 22 native server is nulled out
08-12 16:32:55.680  3787  3836 I jxcore-log: 
,08-12 16:32:55.680  3787  3836 I jxcore-log: ok 23 native server should be closed
08-12 16:32:55.680  3787  3836 I jxcore-log: 
08-12 16:32:55.680  3787  3836 I jxcore-log: ok 24 incoming has been removed
08-12 16:32:55.680  3787  3836 I jxcore-log: 
,08-12 16:32:55.681  3787  3836 I jxcore-log: ok 25 Incoming should be done
08-12 16:32:55.681  3787  3836 I jxcore-log: 
08-12 16:32:55.681  3787  3836 I jxcore-log: ok 26 The mux object should be closed
08-12 16:32:55.681  3787  3836 I jxcore-log: 
08-12 16:32:55.681  3787  3836 I jxcore-log: ok 27 The mux stream should be closed
08-12 16:32:55.681  3787  3836 I jxcore-log: 
08-12 16:32:55.682  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:55.682  3787  3836 I jxcore-log: 
,08-12 16:32:55.695  3787  3836 I jxcore-log: # teardown
08-12 16:32:55.695  3787  3836 I jxcore-log: 
,08-12 16:32:55.781  3787  3836 I jxcore-log: # setup
08-12 16:32:55.781  3787  3836 I jxcore-log: 
,08-12 16:32:55.829  3787  3836 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
08-12 16:32:55.829  3787  3836 I jxcore-log: 
,08-12 16:32:55.883  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:32:55.883  3787  3836 I jxcore-log: 
,08-12 16:32:55.886  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 49191
08-12 16:32:55.886  3787  3836 I jxcore-log: 
,08-12 16:32:55.911  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:55.911  3787  3836 I jxcore-log: 
,08-12 16:32:55.912  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:55.912  3787  3836 I jxcore-log: 
,08-12 16:32:55.914  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:55.914  3787  3836 I jxcore-log: 
,08-12 16:32:55.917  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:55.917  3787  3836 I jxcore-log: 
,08-12 16:32:55.918  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:55.918  3787  3836 I jxcore-log: 
08-12 16:32:55.919  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:55.919  3787  3836 I jxcore-log: 
,08-12 16:32:55.922  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:55.922  3787  3836 I jxcore-log: 
,08-12 16:32:55.923  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:55.923  3787  3836 I jxcore-log: 
,08-12 16:32:55.924  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:55.924  3787  3836 I jxcore-log: 
,08-12 16:32:55.928  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:55.928  3787  3836 I jxcore-log: 
,08-12 16:32:55.929  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:55.929  3787  3836 I jxcore-log: 
,08-12 16:32:55.930  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:55.930  3787  3836 I jxcore-log: 
,08-12 16:32:55.933  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:55.933  3787  3836 I jxcore-log: 
,08-12 16:32:55.934  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:55.934  3787  3836 I jxcore-log: 
08-12 16:32:55.935  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:55.935  3787  3836 I jxcore-log: 
,08-12 16:32:55.938  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:55.938  3787  3836 I jxcore-log: 
,08-12 16:32:55.939  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:55.939  3787  3836 I jxcore-log: 
08-12 16:32:55.940  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:55.940  3787  3836 I jxcore-log: 
,08-12 16:32:55.948  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:55.948  3787  3836 I jxcore-log: 
,08-12 16:32:55.951  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:55.951  3787  3836 I jxcore-log: 
,08-12 16:32:55.952  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:55.952  3787  3836 I jxcore-log: 
,08-12 16:32:55.956  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:55.956  3787  3836 I jxcore-log: 
,08-12 16:32:55.957  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:55.957  3787  3836 I jxcore-log: 
,08-12 16:32:55.957  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:55.957  3787  3836 I jxcore-log: 
08-12 16:32:55.959  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:55.959  3787  3836 I jxcore-log: 
,08-12 16:32:55.959  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:55.959  3787  3836 I jxcore-log: 
08-12 16:32:55.960  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:55.960  3787  3836 I jxcore-log: 
,08-12 16:32:55.962  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:55.962  3787  3836 I jxcore-log: 
,08-12 16:32:55.962  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:55.962  3787  3836 I jxcore-log: 
08-12 16:32:55.963  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:55.963  3787  3836 I jxcore-log: 
,08-12 16:32:56.052  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.052  3787  3836 I jxcore-log: 
,08-12 16:32:56.054  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.054  3787  3836 I jxcore-log: 
,08-12 16:32:56.057  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.057  3787  3836 I jxcore-log: 
,08-12 16:32:56.058  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.058  3787  3836 I jxcore-log: 
,08-12 16:32:56.060  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.060  3787  3836 I jxcore-log: 
,08-12 16:32:56.061  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.061  3787  3836 I jxcore-log: 
,08-12 16:32:56.063  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.063  3787  3836 I jxcore-log: 
,08-12 16:32:56.065  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.065  3787  3836 I jxcore-log: 
,08-12 16:32:56.068  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.068  3787  3836 I jxcore-log: 
,08-12 16:32:56.069  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.069  3787  3836 I jxcore-log: 
,08-12 16:32:56.071  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.071  3787  3836 I jxcore-log: 
,08-12 16:32:56.072  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.072  3787  3836 I jxcore-log: 
,08-12 16:32:56.073  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.073  3787  3836 I jxcore-log: 
,08-12 16:32:56.075  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.075  3787  3836 I jxcore-log: 
,08-12 16:32:56.076  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.076  3787  3836 I jxcore-log: 
,08-12 16:32:56.077  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.077  3787  3836 I jxcore-log: 
,08-12 16:32:56.082  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.082  3787  3836 I jxcore-log: 
,08-12 16:32:56.084  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.084  3787  3836 I jxcore-log: 
,08-12 16:32:56.085  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.085  3787  3836 I jxcore-log: 
,08-12 16:32:56.087  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.087  3787  3836 I jxcore-log: 
,08-12 16:32:56.088  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.088  3787  3836 I jxcore-log: 
,08-12 16:32:56.089  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.089  3787  3836 I jxcore-log: 
,08-12 16:32:56.090  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.090  3787  3836 I jxcore-log: 
,08-12 16:32:56.092  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.092  3787  3836 I jxcore-log: 
,08-12 16:32:56.094  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.094  3787  3836 I jxcore-log: 
,08-12 16:32:56.097  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.097  3787  3836 I jxcore-log: 
,08-12 16:32:56.098  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.098  3787  3836 I jxcore-log: 
,08-12 16:32:56.100  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.100  3787  3836 I jxcore-log: 
,08-12 16:32:56.101  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.101  3787  3836 I jxcore-log: 
,08-12 16:32:56.102  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.102  3787  3836 I jxcore-log: 
,08-12 16:32:56.104  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.104  3787  3836 I jxcore-log: 
,08-12 16:32:56.106  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.106  3787  3836 I jxcore-log: 
,08-12 16:32:56.107  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.107  3787  3836 I jxcore-log: 
,08-12 16:32:56.109  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.109  3787  3836 I jxcore-log: 
,08-12 16:32:56.110  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.110  3787  3836 I jxcore-log: 
,08-12 16:32:56.112  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.112  3787  3836 I jxcore-log: 
,08-12 16:32:56.113  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.113  3787  3836 I jxcore-log: 
,08-12 16:32:56.114  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.114  3787  3836 I jxcore-log: 
,08-12 16:32:56.121  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.121  3787  3836 I jxcore-log: 
,08-12 16:32:56.123  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.123  3787  3836 I jxcore-log: 
,08-12 16:32:56.125  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.125  3787  3836 I jxcore-log: 
,08-12 16:32:56.127  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.127  3787  3836 I jxcore-log: 
,08-12 16:32:56.128  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.128  3787  3836 I jxcore-log: 
,08-12 16:32:56.129  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.129  3787  3836 I jxcore-log: 
,08-12 16:32:56.130  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.130  3787  3836 I jxcore-log: 
,08-12 16:32:56.132  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.132  3787  3836 I jxcore-log: 
,08-12 16:32:56.133  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.133  3787  3836 I jxcore-log: 
,08-12 16:32:56.134  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.134  3787  3836 I jxcore-log: 
,08-12 16:32:56.136  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.136  3787  3836 I jxcore-log: 
,08-12 16:32:56.137  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.137  3787  3836 I jxcore-log: 
,08-12 16:32:56.138  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.138  3787  3836 I jxcore-log: 
,08-12 16:32:56.140  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.140  3787  3836 I jxcore-log: 
,08-12 16:32:56.141  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.141  3787  3836 I jxcore-log: 
,08-12 16:32:56.142  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.142  3787  3836 I jxcore-log: 
,08-12 16:32:56.143  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.143  3787  3836 I jxcore-log: 
,08-12 16:32:56.145  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.145  3787  3836 I jxcore-log: 
,08-12 16:32:56.151  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.151  3787  3836 I jxcore-log: 
,08-12 16:32:56.152  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.152  3787  3836 I jxcore-log: 
,08-12 16:32:56.154  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.154  3787  3836 I jxcore-log: 
,08-12 16:32:56.155  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.155  3787  3836 I jxcore-log: 
,08-12 16:32:56.156  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.156  3787  3836 I jxcore-log: 
,08-12 16:32:56.157  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.157  3787  3836 I jxcore-log: 
,08-12 16:32:56.158  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.158  3787  3836 I jxcore-log: 
,08-12 16:32:56.160  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.160  3787  3836 I jxcore-log: 
,08-12 16:32:56.162  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.162  3787  3836 I jxcore-log: 
,08-12 16:32:56.163  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.163  3787  3836 I jxcore-log: 
,08-12 16:32:56.164  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.164  3787  3836 I jxcore-log: 
,08-12 16:32:56.166  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.166  3787  3836 I jxcore-log: 
,08-12 16:32:56.167  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.167  3787  3836 I jxcore-log: 
,08-12 16:32:56.168  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.168  3787  3836 I jxcore-log: 
,08-12 16:32:56.169  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.169  3787  3836 I jxcore-log: 
,08-12 16:32:56.170  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.170  3787  3836 I jxcore-log: 
08-12 16:32:56.172  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.172  3787  3836 I jxcore-log: 
08-12 16:32:56.174  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.174  3787  3836 I jxcore-log: 
08-12 16:32:56.175  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.175  3787  3836 I jxcore-log: 
08-12 16:32:56.176  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.176  3787  3836 I jxcore-log: 
08-12 16:32:56.177  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.177  3787  3836 I jxcore-log: 
08-12 16:32:56.179  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.179  3787  3836 I jxcore-log: 
08-12 16:32:56.180  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:56.180  3787  3836 I jxcore-log: 
,08-12 16:32:56.181  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:56.181  3787  3836 I jxcore-log: 
,08-12 16:32:56.255  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.255  3787  3836 I jxcore-log: 
,08-12 16:32:56.257  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.257  3787  3836 I jxcore-log: 
,08-12 16:32:56.258  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.258  3787  3836 I jxcore-log: 
,08-12 16:32:56.260  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.260  3787  3836 I jxcore-log: 
,08-12 16:32:56.261  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:56.261  3787  3836 I jxcore-log: 
,08-12 16:32:56.263  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.263  3787  3836 I jxcore-log: 
,08-12 16:32:56.264  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.264  3787  3836 I jxcore-log: 
,08-12 16:32:56.265  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.265  3787  3836 I jxcore-log: 
,08-12 16:32:56.266  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.266  3787  3836 I jxcore-log: 
,08-12 16:32:56.267  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:56.267  3787  3836 I jxcore-log: 
08-12 16:32:56.268  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.268  3787  3836 I jxcore-log: 
,08-12 16:32:56.271  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.271  3787  3836 I jxcore-log: 
,08-12 16:32:56.272  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.272  3787  3836 I jxcore-log: 
,08-12 16:32:56.273  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.273  3787  3836 I jxcore-log: 
,08-12 16:32:56.275  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:56.275  3787  3836 I jxcore-log: 
,08-12 16:32:56.280  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.280  3787  3836 I jxcore-log: 
,08-12 16:32:56.281  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.281  3787  3836 I jxcore-log: 
,08-12 16:32:56.282  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.282  3787  3836 I jxcore-log: 
,08-12 16:32:56.283  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.283  3787  3836 I jxcore-log: 
,08-12 16:32:56.284  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:56.284  3787  3836 I jxcore-log: 
08-12 16:32:56.286  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.286  3787  3836 I jxcore-log: 
,08-12 16:32:56.287  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.287  3787  3836 I jxcore-log: 
,08-12 16:32:56.288  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.288  3787  3836 I jxcore-log: 
08-12 16:32:56.289  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.289  3787  3836 I jxcore-log: 
,08-12 16:32:56.290  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:56.290  3787  3836 I jxcore-log: 
,08-12 16:32:56.292  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.292  3787  3836 I jxcore-log: 
,08-12 16:32:56.293  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.293  3787  3836 I jxcore-log: 
08-12 16:32:56.294  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.294  3787  3836 I jxcore-log: 
,08-12 16:32:56.295  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.295  3787  3836 I jxcore-log: 
,08-12 16:32:56.296  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:56.296  3787  3836 I jxcore-log: 
,08-12 16:32:56.298  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.298  3787  3836 I jxcore-log: 
,08-12 16:32:56.299  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.299  3787  3836 I jxcore-log: 
08-12 16:32:56.300  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.300  3787  3836 I jxcore-log: 
,08-12 16:32:56.301  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.301  3787  3836 I jxcore-log: 
,08-12 16:32:56.302  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:56.302  3787  3836 I jxcore-log: 
08-12 16:32:56.303  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.303  3787  3836 I jxcore-log: 
,08-12 16:32:56.304  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.304  3787  3836 I jxcore-log: 
,08-12 16:32:56.305  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.305  3787  3836 I jxcore-log: 
,08-12 16:32:56.310  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.310  3787  3836 I jxcore-log: 
,08-12 16:32:56.311  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:56.311  3787  3836 I jxcore-log: 
,08-12 16:32:56.312  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.312  3787  3836 I jxcore-log: 
,08-12 16:32:56.313  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.313  3787  3836 I jxcore-log: 
08-12 16:32:56.314  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.314  3787  3836 I jxcore-log: 
,08-12 16:32:56.316  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.316  3787  3836 I jxcore-log: 
,08-12 16:32:56.317  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:56.317  3787  3836 I jxcore-log: 
08-12 16:32:56.318  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.318  3787  3836 I jxcore-log: 
,08-12 16:32:56.319  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.319  3787  3836 I jxcore-log: 
,08-12 16:32:56.320  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.320  3787  3836 I jxcore-log: 
08-12 16:32:56.321  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:56.321  3787  3836 I jxcore-log: 
,08-12 16:32:56.322  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:56.322  3787  3836 I jxcore-log: 
,08-12 16:32:56.326  3787  3836 I jxcore-log: ok 28 native server is nulled out
08-12 16:32:56.326  3787  3836 I jxcore-log: 
,08-12 16:32:56.326  3787  3836 I jxcore-log: ok 29 native server should be closed
08-12 16:32:56.326  3787  3836 I jxcore-log: 
08-12 16:32:56.326  3787  3836 I jxcore-log: ok 30 incoming has been removed
08-12 16:32:56.326  3787  3836 I jxcore-log: 
,08-12 16:32:56.327  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:56.327  3787  3836 I jxcore-log: 
08-12 16:32:56.328  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:56.328  3787  3836 I jxcore-log: 
,08-12 16:32:56.329  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:56.329  3787  3836 I jxcore-log: 
08-12 16:32:56.329  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:56.329  3787  3836 I jxcore-log: 
,08-12 16:32:56.330  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:56.330  3787  3836 I jxcore-log: 
08-12 16:32:56.330  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:56.330  3787  3836 I jxcore-log: 
,08-12 16:32:56.331  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:56.331  3787  3836 I jxcore-log: 
08-12 16:32:56.331  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:56.331  3787  3836 I jxcore-log: 
08-12 16:32:56.331  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:56.331  3787  3836 I jxcore-log: 
08-12 16:32:56.332  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:56.332  3787  3836 I jxcore-log: 
,08-12 16:32:56.446  3787  3836 I jxcore-log: # teardown
08-12 16:32:56.446  3787  3836 I jxcore-log: 
,08-12 16:32:56.822  3787  3836 I jxcore-log: # setup
08-12 16:32:56.822  3787  3836 I jxcore-log: 
,08-12 16:32:58.054  3787  3836 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
08-12 16:32:58.054  3787  3836 I jxcore-log: 
,08-12 16:32:58.118  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:32:58.118  3787  3836 I jxcore-log: 
,08-12 16:32:58.124  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 44913
08-12 16:32:58.124  3787  3836 I jxcore-log: 
,08-12 16:32:58.132  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:58.132  3787  3836 I jxcore-log: 
,08-12 16:32:58.133  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:58.133  3787  3836 I jxcore-log: 
,08-12 16:32:58.135  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:58.135  3787  3836 I jxcore-log: 
,08-12 16:32:58.142  3787  3836 I jxcore-log: ok 31 we should not have gotten an error
08-12 16:32:58.142  3787  3836 I jxcore-log: 
,08-12 16:32:58.149  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:58.149  3787  3836 I jxcore-log: 
,08-12 16:32:58.152  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:58.152  3787  3836 I jxcore-log: 
,08-12 16:32:58.159  3787  3836 I jxcore-log: ok 32 Buffers are identical
08-12 16:32:58.159  3787  3836 I jxcore-log: 
,08-12 16:32:58.160  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:58.160  3787  3836 I jxcore-log: 
,08-12 16:32:58.162  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:58.162  3787  3836 I jxcore-log: 
,08-12 16:32:58.179  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:58.179  3787  3836 I jxcore-log: 
,08-12 16:32:58.180  3787  3836 I jxcore-log: ok 33 server should be fine
08-12 16:32:58.180  3787  3836 I jxcore-log: 
,08-12 16:32:58.180  3787  3836 I jxcore-log: ok 34 server should be open
08-12 16:32:58.180  3787  3836 I jxcore-log: 
08-12 16:32:58.181  3787  3836 I jxcore-log: ok 35 incoming has been removed
08-12 16:32:58.181  3787  3836 I jxcore-log: 
,08-12 16:32:58.181  3787  3836 I jxcore-log: ok 36 The mux object should be closed
08-12 16:32:58.181  3787  3836 I jxcore-log: 
08-12 16:32:58.181  3787  3836 I jxcore-log: ok 37 The mux stream should be closed
08-12 16:32:58.181  3787  3836 I jxcore-log: 
,08-12 16:32:58.186  3787  3836 I jxcore-log: # teardown
08-12 16:32:58.186  3787  3836 I jxcore-log: 
,08-12 16:32:59.383  3787  3836 I jxcore-log: # setup
08-12 16:32:59.383  3787  3836 I jxcore-log: 
,08-12 16:32:59.427  3787  3836 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
08-12 16:32:59.427  3787  3836 I jxcore-log: 
,08-12 16:32:59.538  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:32:59.538  3787  3836 I jxcore-log: 
,08-12 16:32:59.547  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 45966
08-12 16:32:59.547  3787  3836 I jxcore-log: 
,08-12 16:32:59.554  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:32:59.554  3787  3836 I jxcore-log: 
,08-12 16:32:59.555  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:32:59.555  3787  3836 I jxcore-log: 
,08-12 16:32:59.556  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:32:59.556  3787  3836 I jxcore-log: 
,08-12 16:32:59.563  3787  3836 I jxcore-log: ok 38 we should not have gotten an error
08-12 16:32:59.563  3787  3836 I jxcore-log: 
,08-12 16:32:59.569  3787  3836 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 16:32:59.569  3787  3836 I jxcore-log: 
,08-12 16:32:59.572  3787  3836 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 16:32:59.572  3787  3836 I jxcore-log: 
,08-12 16:32:59.579  3787  3836 I jxcore-log: ok 39 Buffers are identical
08-12 16:32:59.579  3787  3836 I jxcore-log: 
,08-12 16:32:59.583  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
08-12 16:32:59.583  3787  3836 I jxcore-log: 
,08-12 16:32:59.584  3787  3836 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 16:32:59.584  3787  3836 I jxcore-log: 
,08-12 16:32:59.587  3787  3836 I jxcore-log: DEBUG createNativeListener: mux close
08-12 16:32:59.587  3787  3836 I jxcore-log: 
,08-12 16:32:59.592  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:32:59.592  3787  3836 I jxcore-log: 
,08-12 16:32:59.593  3787  3836 I jxcore-log: ok 40 server should be fine
08-12 16:32:59.593  3787  3836 I jxcore-log: 
08-12 16:32:59.593  3787  3836 I jxcore-log: ok 41 server should be open
08-12 16:32:59.593  3787  3836 I jxcore-log: 
,08-12 16:32:59.594  3787  3836 I jxcore-log: ok 42 incoming has been removed
08-12 16:32:59.594  3787  3836 I jxcore-log: 
08-12 16:32:59.594  3787  3836 I jxcore-log: ok 43 The mux object should be closed
08-12 16:32:59.594  3787  3836 I jxcore-log: 
,08-12 16:32:59.594  3787  3836 I jxcore-log: ok 44 The mux stream should be closed
08-12 16:32:59.594  3787  3836 I jxcore-log: 
,08-12 16:32:59.601  3787  3836 I jxcore-log: # teardown
08-12 16:32:59.601  3787  3836 I jxcore-log: 
,08-12 16:32:59.729  3787  3836 I jxcore-log: # setup
08-12 16:32:59.729  3787  3836 I jxcore-log: 
,08-12 16:32:59.769  3787  3836 I jxcore-log: # 12. #_doImmediateSeqUpdate - server is not there
08-12 16:32:59.769  3787  3836 I jxcore-log: 
,08-12 16:32:59.935  3787  3836 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
08-12 16:32:59.935  3787  3836 I jxcore-log: 
,08-12 16:32:59.936  3787  3836 I jxcore-log: ok 45 Got right error
08-12 16:32:59.936  3787  3836 I jxcore-log: 
,08-12 16:32:59.941  3787  3836 I jxcore-log: # teardown
08-12 16:32:59.941  3787  3836 I jxcore-log: 
,08-12 16:33:00.095  3787  3836 I jxcore-log: # setup
08-12 16:33:00.095  3787  3836 I jxcore-log: 
,08-12 16:33:00.147  3787  3836 I jxcore-log: # 13. #_doImmediateSeqUpdate - server accepts & closes connection
08-12 16:33:00.147  3787  3836 I jxcore-log: 
,08-12 16:33:00.264  3787  3836 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
08-12 16:33:00.264  3787  3836 I jxcore-log: 
,08-12 16:33:00.266  3787  3836 I jxcore-log: ok 46 Got socket hang up
08-12 16:33:00.266  3787  3836 I jxcore-log: 
,08-12 16:33:00.269  3787  3836 I jxcore-log: # teardown
08-12 16:33:00.269  3787  3836 I jxcore-log: 
,08-12 16:33:00.375  3787  3836 I jxcore-log: # setup
08-12 16:33:00.375  3787  3836 I jxcore-log: 
,08-12 16:33:00.424  3787  3836 I jxcore-log: # 14. #_doImmediateSeqUpdate - server always returns 500
08-12 16:33:00.424  3787  3836 I jxcore-log: 
,08-12 16:33:00.590  3787  3836 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq []
08-12 16:33:00.590  3787  3836 I jxcore-log: 
,08-12 16:33:00.591  3787  3836 I jxcore-log: ok 47 Got 500 as expected
08-12 16:33:00.591  3787  3836 I jxcore-log: 
,08-12 16:33:00.594  3787  3836 I jxcore-log: # teardown
08-12 16:33:00.594  3787  3836 I jxcore-log: 
,08-12 16:33:00.691  3787  3836 I jxcore-log: # setup
08-12 16:33:00.691  3787  3836 I jxcore-log: 
,08-12 16:33:00.743  3787  3836 I jxcore-log: # 15. #_doImmediateSeqUpdate - create new seq doc
08-12 16:33:00.743  3787  3836 I jxcore-log: 
,08-12 16:33:02.728  3787  3836 I jxcore-log: ok 48 should be equal
08-12 16:33:02.728  3787  3836 I jxcore-log: 
,08-12 16:33:02.728  3787  3836 I jxcore-log: ok 49 revs are equal
08-12 16:33:02.728  3787  3836 I jxcore-log: 
,08-12 16:33:02.732  3787  3836 I jxcore-log: # teardown
08-12 16:33:02.732  3787  3836 I jxcore-log: 
,08-12 16:33:02.824  3787  3836 I jxcore-log: # setup
08-12 16:33:02.824  3787  3836 I jxcore-log: 
,08-12 16:33:02.894  3787  3836 I jxcore-log: # 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update
08-12 16:33:02.894  3787  3836 I jxcore-log: 
,08-12 16:33:03.597  3787  3836 I jxcore-log: ok 50 should be equal
08-12 16:33:03.597  3787  3836 I jxcore-log: 
,08-12 16:33:03.598  3787  3836 I jxcore-log: ok 51 revs are equal
08-12 16:33:03.598  3787  3836 I jxcore-log: 
,08-12 16:33:03.602  3787  3836 I jxcore-log: # teardown
08-12 16:33:03.602  3787  3836 I jxcore-log: 
,08-12 16:33:03.645  3787  3836 I jxcore-log: # setup
08-12 16:33:03.645  3787  3836 I jxcore-log: 
,08-12 16:33:03.755  3787  3836 I jxcore-log: # 17. #_doImmediateSeqUpdate - update seq three times
08-12 16:33:03.755  3787  3836 I jxcore-log: 
,08-12 16:33:04.301  3787  3836 I jxcore-log: ok 52 should be equal
08-12 16:33:04.301  3787  3836 I jxcore-log: 
,08-12 16:33:04.302  3787  3836 I jxcore-log: ok 53 revs are equal
08-12 16:33:04.302  3787  3836 I jxcore-log: 
,08-12 16:33:04.444  3787  3836 I jxcore-log: ok 54 should be equal
08-12 16:33:04.444  3787  3836 I jxcore-log: 
,08-12 16:33:04.444  3787  3836 I jxcore-log: ok 55 revs are equal
08-12 16:33:04.444  3787  3836 I jxcore-log: 
,08-12 16:33:04.586  3787  3836 I jxcore-log: ok 56 should be equal
08-12 16:33:04.586  3787  3836 I jxcore-log: 
,08-12 16:33:04.587  3787  3836 I jxcore-log: ok 57 revs are equal
08-12 16:33:04.587  3787  3836 I jxcore-log: 
,08-12 16:33:04.591  3787  3836 I jxcore-log: # teardown
08-12 16:33:04.591  3787  3836 I jxcore-log: 
,08-12 16:33:04.788  3787  3836 I jxcore-log: # setup
08-12 16:33:04.788  3787  3836 I jxcore-log: 
,08-12 16:33:04.850  3787  3836 I jxcore-log: # 18. #_doImmediateSeqUpdate - rev got changed under us
08-12 16:33:04.850  3787  3836 I jxcore-log: 
,08-12 16:33:05.624  3787  3836 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}
08-12 16:33:05.624  3787  3836 I jxcore-log: 
,08-12 16:33:05.626  3787  3836 I jxcore-log: ok 58 Our rev is old so we should fail
08-12 16:33:05.626  3787  3836 I jxcore-log: 
,08-12 16:33:05.631  3787  3836 I jxcore-log: # teardown
08-12 16:33:05.631  3787  3836 I jxcore-log: 
,08-12 16:33:05.674  3787  3836 I jxcore-log: # setup
08-12 16:33:05.674  3787  3836 I jxcore-log: 
,08-12 16:33:05.837  3787  3836 I jxcore-log: # 19. #_doImmediateSeqUpdate - fail if stop is called
08-12 16:33:05.837  3787  3836 I jxcore-log: 
,08-12 16:33:05.933  3787  3836 I jxcore-log: ok 59 confirm stop caused failure
08-12 16:33:05.933  3787  3836 I jxcore-log: 
,08-12 16:33:05.940  3787  3836 I jxcore-log: # teardown
08-12 16:33:05.940  3787  3836 I jxcore-log: 
,08-12 16:33:06.032  3787  3836 I jxcore-log: # setup
08-12 16:33:06.032  3787  3836 I jxcore-log: 
,08-12 16:33:06.088  3787  3836 I jxcore-log: # 20. #_doImmediateSeqUpdate - stop after get but before put fails right
08-12 16:33:06.088  3787  3836 I jxcore-log: 
,08-12 16:33:06.440  3787  3836 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
08-12 16:33:06.440  3787  3836 I jxcore-log: 
,08-12 16:33:06.442  3787  3836 I jxcore-log: ok 60 stop caused us to fail
08-12 16:33:06.442  3787  3836 I jxcore-log: 
08-12 16:33:06.442  3787  3836 I jxcore-log: ok 61 We specifically failed on a stop before put
08-12 16:33:06.442  3787  3836 I jxcore-log: 
,08-12 16:33:06.445  3787  3836 I jxcore-log: # teardown
08-12 16:33:06.445  3787  3836 I jxcore-log: 
,08-12 16:33:06.721  3787  3836 I jxcore-log: # setup
08-12 16:33:06.721  3787  3836 I jxcore-log: 
,08-12 16:33:06.810  3787  3836 I jxcore-log: # 21. #update - fail if stop is called
08-12 16:33:06.810  3787  3836 I jxcore-log: 
,08-12 16:33:07.347  3787  3836 I jxcore-log: ok 62 failed due to stop
08-12 16:33:07.347  3787  3836 I jxcore-log: 
,08-12 16:33:07.348  3787  3836 I jxcore-log: ok 63 failed due to stop
08-12 16:33:07.348  3787  3836 I jxcore-log: 
,08-12 16:33:07.355  3787  3836 I jxcore-log: # teardown
08-12 16:33:07.355  3787  3836 I jxcore-log: 
,08-12 16:33:07.601  3787  3836 I jxcore-log: # setup
08-12 16:33:07.601  3787  3836 I jxcore-log: 
,08-12 16:33:08.689  3787  3836 I jxcore-log: # 22. #update - set seq for first time
08-12 16:33:08.689  3787  3836 I jxcore-log: 
,08-12 16:33:09.273  3787  3836 I jxcore-log: ok 64 should be equal
08-12 16:33:09.273  3787  3836 I jxcore-log: 
,08-12 16:33:09.277  3787  3836 I jxcore-log: # teardown
08-12 16:33:09.277  3787  3836 I jxcore-log: 
,08-12 16:33:09.513  3787  3836 I jxcore-log: # setup
08-12 16:33:09.513  3787  3836 I jxcore-log: 
,08-12 16:33:09.910  3787  3836 I jxcore-log: # 23. #update - Fail on bad seq value
08-12 16:33:09.910  3787  3836 I jxcore-log: 
,08-12 16:33:11.026  3787  3836 I jxcore-log: DEBUG localSeqManager: Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10
08-12 16:33:11.026  3787  3836 I jxcore-log: 
,08-12 16:33:11.028  3787  3836 I jxcore-log: ok 65 Expected bad seq error
08-12 16:33:11.028  3787  3836 I jxcore-log: 
,08-12 16:33:11.031  3787  3836 I jxcore-log: # teardown
08-12 16:33:11.031  3787  3836 I jxcore-log: 
,08-12 16:33:11.871  3787  3836 I jxcore-log: # setup
08-12 16:33:11.871  3787  3836 I jxcore-log: 
,08-12 16:33:13.206  3787  3836 I jxcore-log: # 24. #update - do we cancel timer properly on an immediate?
08-12 16:33:13.206  3787  3836 I jxcore-log: 
,08-12 16:33:15.379  3787  3836 I jxcore-log: ok 66 Different promises
08-12 16:33:15.379  3787  3836 I jxcore-log: 
,08-12 16:33:15.382  3787  3836 I jxcore-log: ok 67 Timer was cancelled
08-12 16:33:15.382  3787  3836 I jxcore-log: 
,08-12 16:33:15.592  3787  3836 I jxcore-log: ok 68 should be equal
08-12 16:33:15.592  3787  3836 I jxcore-log: 
,08-12 16:33:15.598  3787  3836 I jxcore-log: # teardown
08-12 16:33:15.598  3787  3836 I jxcore-log: 
,08-12 16:33:16.297  3787  3836 I jxcore-log: # setup
08-12 16:33:16.297  3787  3836 I jxcore-log: 
,08-12 16:33:17.411  3787  3836 I jxcore-log: # 25. #update - do we wait for blocked update
08-12 16:33:17.411  3787  3836 I jxcore-log: 
,08-12 16:33:19.231  3787  3836 I jxcore-log: ok 69 One go and one blocked
08-12 16:33:19.231  3787  3836 I jxcore-log: 
,08-12 16:33:19.231  3787  3836 I jxcore-log: ok 70 All blocked
08-12 16:33:19.231  3787  3836 I jxcore-log: 
08-12 16:33:19.232  3787  3836 I jxcore-log: ok 71 Still blocked
08-12 16:33:19.232  3787  3836 I jxcore-log: 
,08-12 16:33:19.696  3787  3836 I jxcore-log: ok 72 should be equal
08-12 16:33:19.696  3787  3836 I jxcore-log: 
,08-12 16:33:19.702  3787  3836 I jxcore-log: # teardown
08-12 16:33:19.702  3787  3836 I jxcore-log: 
,08-12 16:33:19.747  3787  3836 I jxcore-log: # setup
08-12 16:33:19.747  3787  3836 I jxcore-log: 
,08-12 16:33:19.892  3787  3836 I jxcore-log: # 26. #update - test that we wait long enough
08-12 16:33:19.892  3787  3836 I jxcore-log: 
,08-12 16:33:21.101  3787  3836 I jxcore-log: ok 73 We waited long enough
08-12 16:33:21.101  3787  3836 I jxcore-log: 
,08-12 16:33:21.262  3787  3836 I jxcore-log: ok 74 should be equal
08-12 16:33:21.262  3787  3836 I jxcore-log: 
,08-12 16:33:21.267  3787  3836 I jxcore-log: # teardown
08-12 16:33:21.267  3787  3836 I jxcore-log: 
,08-12 16:33:22.122  3787  3836 I jxcore-log: # setup
08-12 16:33:22.122  3787  3836 I jxcore-log: 
,08-12 16:33:22.189  3787  3836 I jxcore-log: # 27. #update - test that we pick up new sequences while we wait
08-12 16:33:22.189  3787  3836 I jxcore-log: 
,08-12 16:33:23.595  3787  3836 I jxcore-log: ok 75 Should have gotten same timer promise
08-12 16:33:23.595  3787  3836 I jxcore-log: 
08-12 16:33:23.595  3787  3836 I jxcore-log: ok 76 Still same timer promise
08-12 16:33:23.595  3787  3836 I jxcore-log: 
,08-12 16:33:24.406  3787  3836 I jxcore-log: ok 77 We waited long enough
08-12 16:33:24.406  3787  3836 I jxcore-log: 
,08-12 16:33:24.501  3787  3836 I jxcore-log: ok 78 should be equal
08-12 16:33:24.501  3787  3836 I jxcore-log: 
,08-12 16:33:24.506  3787  3836 I jxcore-log: # teardown
08-12 16:33:24.506  3787  3836 I jxcore-log: 
,08-12 16:33:24.544  3787  3836 I jxcore-log: # setup
08-12 16:33:24.544  3787  3836 I jxcore-log: 
,08-12 16:33:24.771  3787  3836 I jxcore-log: # 28. Coordinated seq test
08-12 16:33:24.771  3787  3836 I jxcore-log: 
,08-12 16:33:24.933  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:33:24.933  3787  3836 I jxcore-log: 
,08-12 16:33:24.935  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 49024
08-12 16:33:24.935  3787  3836 I jxcore-log: 
,08-12 16:33:24.940  3787  3836 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-12 16:33:24.946  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,08-12 16:33:24.946  3787  3836 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 16:33:24.947  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 16:33:24.947  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-12 16:33:24.947  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-12 16:33:24.947  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 16:33:24.947  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-12 16:33:24.955  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-12 16:33:24.955  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-12 16:33:24.963  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 16:33:24.966  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-12 16:33:24.967  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 16:33:24.975  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-12 16:33:24.981  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-12 16:33:24.981  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-12 16:33:24.981  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-12 16:33:24.981  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-12 16:33:24.983  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:33:24.988  2697  2893 D BtGatt.GattService: registerClient() - UUID=29c2c6af-85c9-4d06-9c12-b134c4f76924
08-12 16:33:24.989  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=29c2c6af-85c9-4d06-9c12-b134c4f76924, clientIf=5
,08-12 16:33:24.990  3787  3799 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 16:33:24.991  2697  2711 D BtGatt.GattService: start scan with filters
,08-12 16:33:24.994  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 16:33:24.995  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-12 16:33:24.995  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-12 16:33:24.995  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-12 16:33:24.996  2697  2752 D BtGatt.ScanManager: handling starting scan
08-12 16:33:24.997  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 16:33:24.997  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 16:33:24.998  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-12 16:33:24.999  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-12 16:33:25.000  2697  2752 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4bb5e0
08-12 16:33:25.001  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 16:33:25.008  2697  2748 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-12 16:33:25.008  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:33:25.011  2697  2752 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 16:33:25.024  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-12 16:33:25.024  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:33:25.025  2697  2752 D BtGatt.ScanManager: Starting BLE batch scan
08-12 16:33:25.026  2697  2752 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 16:33:25.049  2697  2748 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-12 16:33:25.049  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:33:25.064  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-12 16:33:25.064  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:33:25.499  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-12 16:33:25.500  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 16:33:25.500  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:33:25.531  3787  3836 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-12 16:33:25.537  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 49024, start advertisements: true
08-12 16:33:25.537  3787  3836 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 16:33:25.538  3787  3836 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-12 16:33:25.538  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-12 16:33:25.538  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-12 16:33:25.538  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-12 16:33:25.538  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-12 16:33:25.538  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 1
08-12 16:33:25.538  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-12 16:33:25.538  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-12 16:33:25.538  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-12 16:33:25.538  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-12 16:33:25.538  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
08-12 16:33:25.538  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-12 16:33:25.538  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-12 16:33:25.540  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:33:25.542  2697  2708 D BtGatt.GattService: stopScan() - queue size =1
,08-12 16:33:25.544  2697  2893 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 16:33:25.544  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 16:33:25.544  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 16:33:25.544  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-12 16:33:25.544  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-12 16:33:25.545  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-12 16:33:25.545  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-12 16:33:25.546  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:33:25.551  2697  2711 D BtGatt.GattService: registerClient() - UUID=41a301e2-344b-4328-a2ce-352fcce8c89e
,08-12 16:33:25.552  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=41a301e2-344b-4328-a2ce-352fcce8c89e, clientIf=5
,08-12 16:33:25.554  3787  3798 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 16:33:25.556  2697  2708 D BtGatt.GattService: start scan with filters
,08-12 16:33:25.562  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 16:33:25.562  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-12 16:33:25.562  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-12 16:33:25.563  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-12 16:33:25.563  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-12 16:33:25.564  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 16:33:25.564  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-12 16:33:25.565  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-12 16:33:25.565  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:33:25.565  2697  2752 D BtGatt.ScanManager: stopping BLe Batch
,08-12 16:33:25.569  2697  2697 D BtGatt.ScanManager: awakened up at time 379157
,08-12 16:33:25.572  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-12 16:33:25.572  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-12 16:33:25.572  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-12 16:33:25.572  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-12 16:33:25.572  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 16:33:25.573  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-12 16:33:25.573  3787  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-12 16:33:25.573  3787  3836 D BluetoothAdapter: STATE_ON
08-12 16:33:25.574  2697  2893 D BtGatt.GattService: stopScan() - queue size =0
08-12 16:33:25.575  2697  2711 D BtGatt.GattService: unregisterClient() - clientIf=5
08-12 16:33:25.576  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 16:33:25.576  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-12 16:33:25.576  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-12 16:33:25.577  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-12 16:33:25.577  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:33:25.577  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-12 16:33:25.577  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-12 16:33:25.578  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-12 16:33:25.579  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 16:33:25.580  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 16:33:25.583  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-12 16:33:25.583  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 16:33:25.583  3787  4029 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-12 16:33:25.584  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-12 16:33:25.585  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 16:33:25.585  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 16:33:25.585  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-12 16:33:25.586  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:33:25.589  3787  4029 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-12 16:33:25.592  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-12 16:33:25.592  2697  2708 D BtGatt.GattService: registerClient() - UUID=707ca335-d654-49ee-9fd3-68f852881496
,08-12 16:33:25.592  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:33:25.593  2697  2748 D BtGatt.GattService: current time is 379180785907
08-12 16:33:25.593  2697  2748 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -86, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 16:33:25.594  2697  2752 D BtGatt.ScanManager: handling starting scan
08-12 16:33:25.596  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 16:33:25.597  2697  2748 E BtGatt.ContextMap: Context not found for ID 5
,08-12 16:33:25.598  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=707ca335-d654-49ee-9fd3-68f852881496, clientIf=5
08-12 16:33:25.599  3787  3799 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-12 16:33:25.602  2697  2751 D BtGatt.AdvertiseManager: message : 0
,08-12 16:33:25.605  2697  2751 D BtGatt.AdvertiseManager: starting multi advertising
,08-12 16:33:25.606  2697  2748 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-12 16:33:25.606  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:33:25.606  2697  2752 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 16:33:25.619  2697  2748 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-12 16:33:25.626  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-12 16:33:25.626  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:33:25.626  2697  2752 D BtGatt.ScanManager: Starting BLE batch scan
,08-12 16:33:25.626  2697  2752 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 16:33:25.630  2697  2748 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-12 16:33:25.631  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-12 16:33:25.632  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 16:33:25.634  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 16:33:25.635  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-12 16:33:25.635  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 16:33:25.635  3787  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-12 16:33:25.635  3787  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-12 16:33:25.636  3787  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true,
08-12 16:33:25.636  3787  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-12 16:33:25.636  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-12 16:33:25.637  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 16:33:25.638  3787  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-12 16:33:25.638  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-12 16:33:25.641  2697  2748 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-12 16:33:25.641  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:33:25.649  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-12 16:33:25.649  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:33:25.653  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-12 16:33:25.653  3787  3836 I jxcore-log: 
,08-12 16:33:25.658  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-12 16:33:25.658  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:33:25.658  2697  2752 D BtGatt.ScanManager: stopping BLe Batch
,08-12 16:33:25.673  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 16:33:25.674  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:33:25.674  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:33:25.688  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:33:25.688  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:33:26.140  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-12 16:33:26.140  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-12 16:33:26.141  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:33:26.147  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-12 16:33:26.147  3787  3836 I jxcore-log: 
,08-12 16:34:11.985  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:34:11.987  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:34:11.997  3897  4032 V GoogleAuthProtoRequest: [328] a.<init>: mAccountName set to: thalitester@gmail.com
,08-12 16:34:12.019  1513  2305 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-12 16:34:12.019  1513  2305 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-12 16:34:12.019  1513  2305 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 16:34:12.019  1513  2305 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:34:12.033  3897  4032 W ExperimentUpdateService: [328] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-12 16:34:12.033  3897  4032 W ExperimentUpdateService: [328] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 16:34:12.033  3897  4032 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 16:34:12.033  3897  4032 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-12 16:34:12.033  3897  4032 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-12 16:34:12.033  3897  4032 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-12 16:34:12.033  3897  4032 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-12 16:34:12.033  3897  4032 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-12 16:34:12.033  3897  4032 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-12 16:34:12.033  3897  4032 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-12 16:34:12.033  3897  4032 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-12 16:34:12.033  3897  4032 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-12 16:34:22.836  1513  2157 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 16:36:06.708  3594  4039 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 16:36:06.736  3594  4040 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 16:36:06.747  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:36:06.750  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:36:06.779  1513  2099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-12 16:36:06.779  1513  2099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 16:36:06.779  1513  2099 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:36:06.779  1513  2099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:36:06.812  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:36:06.814  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:36:06.846  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 16:36:06.846  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 16:36:06.847  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 16:36:06.847  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:36:06.869  3594  4040 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 16:36:06.870  3594  4039 E BooksSync: Soft error
08-12 16:36:06.870  3594  4039 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 16:36:06.870  3594  4039 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 16:36:06.871  3594  4039 E BooksSync: Sync error
08-12 16:36:06.871  3594  4039 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 16:36:06.871  3594  4039 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 16:36:06.871  3594  4039 I BooksSync: Finished books sync
,08-12 16:36:06.884   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 540190, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 16:36:40.116  3128  4042 V KeepSync: Connecting to GoogleApiClient
08-12 16:36:40.117   871  1950 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 16:36:40.178  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:36:40.181  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:36:40.212  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-12 16:36:40.213  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-12 16:36:40.213  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:36:40.213  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:36:40.232  1722  4043 V BaseAuthAsyncOperation: access token request failed
,08-12 16:36:40.233  3128  4042 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 16:36:40.290  1513  2305 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 16:36:40.290  1513  2305 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-12 16:36:40.290  1513  2305 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:36:40.290  1513  2305 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:36:40.325  3128  4042 E KeepSync: IOException
08-12 16:36:40.325  3128  4042 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 16:36:40.325  3128  4042 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 16:36:40.325  3128  4042 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 16:36:40.325  3128  4042 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 16:36:40.325  3128  4042 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 16:36:40.325  3128  4042 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 16:36:40.325  3128  4042 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 16:36:40.325  3128  4042 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 16:36:40.325  3128  4042 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 16:36:40.325  3128  4042 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 16:36:40.325  3128  4042 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 16:36:40.325  3128  4042 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 16:36:40.325  3128  4042 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 16:36:40.325  3128  4042 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 16:36:40.325  3128  4042 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 16:36:40.325  3128  4042 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 16:36:40.325  3128  4042 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 16:36:40.325  3128  4042 E KeepSync: 	... 10 more
,08-12 16:36:40.325  3128  4042 W KeepSync: Sync result 2
,08-12 16:36:40.330   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 573497, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 16:37:10.624  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:37:10.629  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:37:10.689  1513  2099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 16:37:10.689  1513  2099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 16:37:10.689  1513  2099 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:37:10.689  1513  2099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:37:10.716  3543  4047 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 16:37:10.716  3543  4047 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at jdm.a(PG:82)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at jcs.o(PG:406)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at jcn.a(PG:1379)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at jcs.i(PG:143)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at blb.a(PG:3937)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at czp.a(PG:18188)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at czp.a(PG:9081)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at czq.run(PG:1686)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 16:37:10.716  3543  4047 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at jdj.a(PG:4091)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at jdj.a(PG:1125)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at jdm.a(PG:77)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	... 12 more
08-12 16:37:10.716  3543  4047 E HttpOperation: Caused by: faj: BadAuthentication
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at fal.a(PG:38)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	at jdj.a(PG:4089)
08-12 16:37:10.716  3543  4047 E HttpOperation: 	... 14 more
,08-12 16:37:10.833  1513  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 16:37:10.833  1513  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 16:37:10.833  1513  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:37:10.833  1513  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:37:10.860  3543  4047 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 16:37:10.860  3543  4047 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at jdm.a(PG:82)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at jcs.o(PG:406)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at jcn.a(PG:1379)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at jcs.i(PG:143)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at hec.a(PG:42)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at hee.a(PG:102)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at czr.a(PG:65)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at kka.a(PG:108)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at czp.a(PG:19176)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at czp.a(PG:9081)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at czq.run(PG:1686)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 16:37:10.860  3543  4047 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at jdj.a(PG:4091)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at jdj.a(PG:1125)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at jdm.a(PG:77)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	... 15 more
08-12 16:37:10.860  3543  4047 E HttpOperation: Caused by: faj: BadAuthentication
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at fal.a(PG:38)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	at jdj.a(PG:4089)
08-12 16:37:10.860  3543  4047 E HttpOperation: 	... 17 more
,08-12 16:37:10.861  3543  4047 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 16:37:10.861  3543  4047 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at hec.a(PG:42)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at hee.a(PG:102)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at czr.a(PG:65)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at kka.a(PG:108)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	... 15 more
08-12 16:37:10.861  3543  4047 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at fal.a(PG:38)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 16:37:10.861  3543  4047 E ExperimentLoader: 	... 17 more
,08-12 16:37:10.983   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 600247, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 16:38:11.908  3504  3504 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-12 16:38:12.086  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:38:12.107  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:38:12.112  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:38:12.180  3897  4057 V GoogleAuthProtoRequest: [329] a.<init>: mAccountName set to: thalitester@gmail.com
,08-12 16:38:12.207  1513  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-12 16:38:12.208  1513  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-12 16:38:12.208  1513  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:38:12.208  1513  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:38:12.220  1513  3623 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-12 16:38:12.220  1513  3623 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-12 16:38:12.221  1513  3623 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:38:12.221  1513  3623 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:38:12.224  3897  4057 W ExperimentUpdateService: [329] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-12 16:38:12.224  3897  4057 W ExperimentUpdateService: [329] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 16:38:12.224  3897  4057 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 16:38:12.224  3897  4057 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-12 16:38:12.224  3897  4057 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-12 16:38:12.224  3897  4057 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-12 16:38:12.224  3897  4057 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-12 16:38:12.224  3897  4057 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-12 16:38:12.224  3897  4057 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-12 16:38:12.224  3897  4057 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-12 16:38:12.224  3897  4057 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-12 16:38:12.224  3897  4057 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-12 16:38:12.297  3504  3504 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-12 16:38:12.325  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:38:12.421  1513  2099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-12 16:38:12.422  1513  2099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-12 16:38:12.423  1513  2099 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:38:12.423  1513  2099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:38:12.516  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:38:12.582  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-12 16:38:12.583  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-12 16:38:12.583  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:38:12.583  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:38:12.640  3504  3504 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-12 16:38:13.106  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:38:13.170  1513  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-12 16:38:13.171  1513  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-12 16:38:13.171  1513  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:38:13.171  1513  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:38:13.221  3504  3504 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-12 16:38:13.222  3504  3504 D Finsky  : [1] WearSupportService.startHygiene: disabled
,08-12 16:38:13.225  3504  3504 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-12 16:38:13.234  3504  3580 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-12 16:38:13.237  3504  3504 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,08-12 16:38:24.860  3787  3836 I jxcore-log: not ok 79 We failed - Error: Test timed out
08-12 16:38:24.860  3787  3836 I jxcore-log: 
08-12 16:38:24.860  3787  3836 I jxcore-log:   ---
08-12 16:38:24.860  3787  3836 I jxcore-log: 
,08-12 16:38:24.861  3787  3836 I jxcore-log:     operator: fail
08-12 16:38:24.861  3787  3836 I jxcore-log: 
08-12 16:38:24.861  3787  3836 I jxcore-log:   ...
08-12 16:38:24.861  3787  3836 I jxcore-log: 
,08-12 16:38:24.883  3787  3836 I jxcore-log: # teardown
08-12 16:38:24.883  3787  3836 I jxcore-log: 
,08-12 16:38:24.928  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 16:38:24.929  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 16:38:24.929  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-12 16:38:24.929  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-12 16:38:24.930  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-12 16:38:24.930  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-12 16:38:24.930  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-12 16:38:24.930  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-12 16:38:24.930  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-12 16:38:24.930  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-12 16:38:24.932  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-12 16:38:24.930  3787  4029 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-12 16:38:24.932  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-12 16:38:24.931  3787  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-12 16:38:24.932  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-12 16:38:24.932  3787  4029 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-12 16:38:24.933  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-12 16:38:24.933  3787  4029 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-12 16:38:24.934  3787  3836 D BluetoothAdapter: STATE_ON
08-12 16:38:24.934  3787  3836 D BluetoothLeScanner: could not find callback wrapper
08-12 16:38:24.935  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 16:38:24.935  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-12 16:38:24.937  2697  2751 D BtGatt.AdvertiseManager: message : 1
,08-12 16:38:24.938  2697  2751 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-12 16:38:24.954  2697  2748 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-12 16:38:24.954  2697  2748 D BtGatt.GattService: Client app is not null!
,08-12 16:38:24.955  2697  2893 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 16:38:24.955  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-12 16:38:24.955  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-12 16:38:24.956  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-12 16:38:24.957  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-12 16:38:24.958  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-12 16:38:24.960  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 16:38:24.960  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-12 16:38:24.961  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-12 16:38:24.962  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 16:38:24.967  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 16:38:24.967  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,08-12 16:38:24.968  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 16:38:24.968  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 16:38:24.969  3787  3787 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-12 16:38:24.969  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 16:38:24.984  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 16:38:24.984  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 16:38:24.984  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 16:38:24.984  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:38:24.988  3787  3836 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-12 16:38:24.988  3787  3836 I jxcore-log: 
,08-12 16:38:24.994  3787  3836 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-12 16:38:24.995  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 16:38:24.995  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 16:38:24.995  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:38:25.007  3787  3836 I jxcore-log: # setup
08-12 16:38:25.007  3787  3836 I jxcore-log: 
,08-12 16:38:25.220  3787  3836 I jxcore-log: # 29. closeAll can close even when connections open
08-12 16:38:25.220  3787  3836 I jxcore-log: 
,08-12 16:38:25.399  3787  3836 I jxcore-log: ok 80 not possible to connect to the server anymore
08-12 16:38:25.399  3787  3836 I jxcore-log: 
,08-12 16:38:25.402  3787  3836 I jxcore-log: # teardown
08-12 16:38:25.402  3787  3836 I jxcore-log: 
,08-12 16:38:25.471  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 16:38:25.476  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 16:38:25.476  3787  3836 I jxcore-log: 
,08-12 16:38:25.510  3787  3836 I jxcore-log: # setup
08-12 16:38:25.510  3787  3836 I jxcore-log: 
,08-12 16:38:25.574  3787  3836 I jxcore-log: # 30. closeAll with promise
08-12 16:38:25.574  3787  3836 I jxcore-log: 
,08-12 16:38:25.822  3787  3836 I jxcore-log: ok 81 not possible to connect to the server anymore
08-12 16:38:25.822  3787  3836 I jxcore-log: 
,08-12 16:38:25.834  3787  3836 I jxcore-log: # teardown
08-12 16:38:25.834  3787  3836 I jxcore-log: 
,08-12 16:38:25.897  3787  3836 I jxcore-log: # setup,
08-12 16:38:25.897  3787  3836 I jxcore-log: 
,08-12 16:38:25.973  3787  3836 I jxcore-log: # 31. closeAll properly throws when closing a non open server with eatNotRunning set to false
08-12 16:38:25.973  3787  3836 I jxcore-log: 
,08-12 16:38:26.144  3787  3836 I jxcore-log: ok 82 Got the right error
08-12 16:38:26.144  3787  3836 I jxcore-log: 
,08-12 16:38:26.156  3787  3836 I jxcore-log: # teardown
08-12 16:38:26.156  3787  3836 I jxcore-log: 
,08-12 16:38:26.223  3787  3836 I jxcore-log: # setup
08-12 16:38:26.223  3787  3836 I jxcore-log: 
,08-12 16:38:26.317  3787  3836 I jxcore-log: # 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true
08-12 16:38:26.317  3787  3836 I jxcore-log: 
,08-12 16:38:26.529  3787  3836 I jxcore-log: # teardown
08-12 16:38:26.529  3787  3836 I jxcore-log: 
,08-12 16:38:26.583  3787  3836 I jxcore-log: # setup
08-12 16:38:26.583  3787  3836 I jxcore-log: 
,08-12 16:38:26.676  3787  3836 I jxcore-log: # 33. onPeerLost calls jxcore
08-12 16:38:26.676  3787  3836 I jxcore-log: 
,08-12 16:38:26.721  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-12 16:38:26.722  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dceb4c7 added. We now have 2 listener(s)
,08-12 16:38:26.724  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 16:38:26.724  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 16:38:26.724  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 16:38:26.725  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-12 16:38:26.725  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@501caf4 added. We now have 2 listener(s)
08-12 16:38:26.725  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 16:38:26.726  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 16:38:26.733  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 16:38:26.747  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 16:38:26.747  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 16:38:26.747  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 16:38:26.747  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 16:38:26.747  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 16:38:26.747  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 16:38:26.747  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 16:38:26.747  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 16:38:26.756  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 16:38:26.756  3787  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 16:38:26.759  3787  3836 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
,08-12 16:38:26.759  3787  3836 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,08-12 16:38:26.765  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 16:38:26.773  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 16:38:28.010  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:38:28.022  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:38:28.027  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:38:28.067  1513  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 16:38:28.068  1513  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 16:38:28.068  1513  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:38:28.069  1513  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:38:28.115  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-12 16:38:28.116  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 16:38:28.117  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-12 16:38:28.763  3787  3836 I jxcore-log: onPeerLost
08-12 16:38:28.763  3787  3836 I jxcore-log: 
,08-12 16:38:28.767  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 16:38:28.767  3787  3836 I jxcore-log: 
,08-12 16:38:28.780  3787  3836 I jxcore-log: # teardown
08-12 16:38:28.780  3787  3836 I jxcore-log: 
,08-12 16:38:28.786  3787  3836 I jxcore-log: ok 83 check if callback was fired by onPeerLost
08-12 16:38:28.786  3787  3836 I jxcore-log: 
,08-12 16:38:28.787  3787  3836 I jxcore-log: ok 84 check if peerAvailable is false
08-12 16:38:28.787  3787  3836 I jxcore-log: 
,08-12 16:38:28.911  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 16:38:28.911  3787  3836 I jxcore-log: 
,08-12 16:38:28.915  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 16:38:28.915  3787  3836 I jxcore-log: 
,08-12 16:38:28.927  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 16:38:28.927  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 16:38:28.927  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 16:38:28.927  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 16:38:28.927  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 16:38:28.927  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 16:38:28.927  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 16:38:28.927  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 16:38:28.930  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 16:38:28.932  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 16:38:28.932  3787  3836 I jxcore-log: 
,08-12 16:38:28.934  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 16:38:28.934  3787  3836 I jxcore-log: 
,08-12 16:38:28.937  3787  3836 I jxcore-log: # setup
08-12 16:38:28.937  3787  3836 I jxcore-log: 
,08-12 16:38:28.938  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 16:38:28.938  3787  3836 I jxcore-log: 
,08-12 16:38:28.995  3787  3836 I jxcore-log: # 34. onPeerDiscovered calls jxcore
08-12 16:38:28.995  3787  3836 I jxcore-log: 
,08-12 16:38:29.044  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-12 16:38:29.044  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c171c92 added. We now have 3 listener(s)
,08-12 16:38:29.048  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 16:38:29.048  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 16:38:29.048  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 16:38:29.049  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-12 16:38:29.049  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b77d663 added. We now have 3 listener(s)
08-12 16:38:29.049  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 16:38:29.050  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 16:38:29.055  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 16:38:29.064  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 16:38:29.064  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 16:38:29.064  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 16:38:29.064  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 16:38:29.064  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 16:38:29.064  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 16:38:29.064  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 16:38:29.064  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 16:38:29.068  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 16:38:29.068  3787  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 16:38:29.068  3787  3836 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,08-12 16:38:29.072  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 16:38:29.075  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 16:38:31.071  3787  3836 I jxcore-log: onPeerDiscovered
08-12 16:38:31.071  3787  3836 I jxcore-log: 
,08-12 16:38:31.075  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 16:38:31.075  3787  3836 I jxcore-log: 
,08-12 16:38:31.090  3787  3836 I jxcore-log: # teardown
08-12 16:38:31.090  3787  3836 I jxcore-log: 
,08-12 16:38:31.096  3787  3836 I jxcore-log: ok 85 check if callback was fired by onPeerDiscovered
08-12 16:38:31.096  3787  3836 I jxcore-log: 
,08-12 16:38:31.096  3787  3836 I jxcore-log: ok 86 check if peerAvailable is true
08-12 16:38:31.096  3787  3836 I jxcore-log: 
,08-12 16:38:31.216  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 16:38:31.216  3787  3836 I jxcore-log: 
,08-12 16:38:31.221  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 16:38:31.221  3787  3836 I jxcore-log: 
,08-12 16:38:31.237  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 16:38:31.237  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 16:38:31.237  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 16:38:31.237  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 16:38:31.237  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 16:38:31.237  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 16:38:31.237  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 16:38:31.237  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 16:38:31.244  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 16:38:31.249  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 16:38:31.249  3787  3836 I jxcore-log: 
,08-12 16:38:31.255  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 16:38:31.255  3787  3836 I jxcore-log: 
,08-12 16:38:31.264  3787  3836 I jxcore-log: # setup
08-12 16:38:31.264  3787  3836 I jxcore-log: 
,08-12 16:38:31.269  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 16:38:31.269  3787  3836 I jxcore-log: 
,08-12 16:38:31.312  3787  3836 I jxcore-log: # 35. enqueue and run in order
08-12 16:38:31.312  3787  3836 I jxcore-log: 
,08-12 16:38:31.468  3787  3836 I jxcore-log: ok 87 firstPromise setTimeout
08-12 16:38:31.468  3787  3836 I jxcore-log: 
,08-12 16:38:31.473  3787  3836 I jxcore-log: ok 88 firstPromise result
08-12 16:38:31.473  3787  3836 I jxcore-log: 
,08-12 16:38:31.476  3787  3836 I jxcore-log: ok 89 firstPromise testValue
08-12 16:38:31.476  3787  3836 I jxcore-log: 
,08-12 16:38:31.580  3787  3836 I jxcore-log: ok 90 secondPromise setTimeout
08-12 16:38:31.580  3787  3836 I jxcore-log: 
,08-12 16:38:31.584  3787  3836 I jxcore-log: ok 91 secondPromise result
08-12 16:38:31.584  3787  3836 I jxcore-log: 
,08-12 16:38:31.587  3787  3836 I jxcore-log: ok 92 secondPromise testValue
08-12 16:38:31.587  3787  3836 I jxcore-log: 
,08-12 16:38:31.591  3787  3836 I jxcore-log: ok 93 thirdPromise in promise
08-12 16:38:31.591  3787  3836 I jxcore-log: 
,08-12 16:38:31.596  3787  3836 I jxcore-log: ok 94 thirdPromise result
08-12 16:38:31.596  3787  3836 I jxcore-log: 
,08-12 16:38:31.597  3787  3836 I jxcore-log: ok 95 thirdPromise testValue
08-12 16:38:31.597  3787  3836 I jxcore-log: 
,08-12 16:38:31.601  3787  3836 I jxcore-log: # teardown
08-12 16:38:31.601  3787  3836 I jxcore-log: 
,08-12 16:38:31.684  3787  3836 I jxcore-log: # setup
08-12 16:38:31.684  3787  3836 I jxcore-log: 
,08-12 16:38:31.730  3787  3836 I jxcore-log: # 36. enqueueAtTop and run backwards
08-12 16:38:31.730  3787  3836 I jxcore-log: 
,08-12 16:38:31.814  3787  3836 I jxcore-log: ok 96 thirdPromise - first to run
08-12 16:38:31.814  3787  3836 I jxcore-log: 
,08-12 16:38:31.817  3787  3836 I jxcore-log: ok 97 thirdPromise - in resolve
08-12 16:38:31.817  3787  3836 I jxcore-log: 
,08-12 16:38:31.818  3787  3836 I jxcore-log: ok 98 secondPromise - second to run
08-12 16:38:31.818  3787  3836 I jxcore-log: 
,08-12 16:38:31.820  3787  3836 I jxcore-log: ok 99 secondPromise - in catch
08-12 16:38:31.820  3787  3836 I jxcore-log: 
,08-12 16:38:31.821  3787  3836 I jxcore-log: ok 100 firstPromise - third to run
08-12 16:38:31.821  3787  3836 I jxcore-log: 
,08-12 16:38:31.822  3787  3836 I jxcore-log: ok 101 firstPromise - in then
08-12 16:38:31.822  3787  3836 I jxcore-log: 
,08-12 16:38:31.823  3787  3836 I jxcore-log: ok 102 testing promises
08-12 16:38:31.823  3787  3836 I jxcore-log: 
,08-12 16:38:31.827  3787  3836 I jxcore-log: # teardown
08-12 16:38:31.827  3787  3836 I jxcore-log: 
,08-12 16:38:31.916  3787  3836 I jxcore-log: # setup
08-12 16:38:31.916  3787  3836 I jxcore-log: 
,08-12 16:38:31.952  3787  3836 I jxcore-log: # 37. mix enqueue and enqueueAtTop
08-12 16:38:31.952  3787  3836 I jxcore-log: 
,08-12 16:38:32.027  3787  3836 I jxcore-log: ok 103 fourth
08-12 16:38:32.027  3787  3836 I jxcore-log: 
08-12 16:38:32.028  3787  3836 I jxcore-log: ok 104 fourth
08-12 16:38:32.028  3787  3836 I jxcore-log: 
,08-12 16:38:32.029  3787  3836 I jxcore-log: ok 105 second
08-12 16:38:32.029  3787  3836 I jxcore-log: 
08-12 16:38:32.030  3787  3836 I jxcore-log: ok 106 secondPromise - in then
08-12 16:38:32.030  3787  3836 I jxcore-log: 
,08-12 16:38:32.133  3787  3836 I jxcore-log: ok 107 first
08-12 16:38:32.133  3787  3836 I jxcore-log: 
,08-12 16:38:32.147  3787  3836 I jxcore-log: ok 108 firstPromise - in catch
08-12 16:38:32.147  3787  3836 I jxcore-log: 
,08-12 16:38:32.150  3787  3836 I jxcore-log: ok 109 third
08-12 16:38:32.150  3787  3836 I jxcore-log: 
,08-12 16:38:32.154  3787  3836 I jxcore-log: ok 110 thirdPromise - in then
08-12 16:38:32.154  3787  3836 I jxcore-log: 
,08-12 16:38:32.157  3787  3836 I jxcore-log: ok 111 testingPromises
08-12 16:38:32.157  3787  3836 I jxcore-log: 
,08-12 16:38:32.167  3787  3836 I jxcore-log: # teardown
08-12 16:38:32.167  3787  3836 I jxcore-log: 
,08-12 16:38:32.232  3787  3836 I jxcore-log: # setup
08-12 16:38:32.232  3787  3836 I jxcore-log: 
,08-12 16:38:32.293  3787  3836 I jxcore-log: # 38. queues handled independently
08-12 16:38:32.293  3787  3836 I jxcore-log: 
,08-12 16:38:32.382  3787  3836 I jxcore-log: ok 112 all short operations completed before the long resolves
08-12 16:38:32.382  3787  3836 I jxcore-log: 
,08-12 16:38:32.387  3787  3836 I jxcore-log: # teardown
08-12 16:38:32.387  3787  3836 I jxcore-log: 
,08-12 16:38:32.459  3787  3836 I jxcore-log: # setup
08-12 16:38:32.459  3787  3836 I jxcore-log: 
,08-12 16:38:32.528  3787  3836 I jxcore-log: # 39. basic
08-12 16:38:32.528  3787  3836 I jxcore-log: 
,08-12 16:38:32.574  3787  3836 I jxcore-log: ok 113 sane
08-12 16:38:32.574  3787  3836 I jxcore-log: 
,08-12 16:38:32.576  3787  3836 I jxcore-log: # teardown
08-12 16:38:32.576  3787  3836 I jxcore-log: 
,08-12 16:38:32.623  3787  3836 I jxcore-log: # setup
08-12 16:38:32.623  3787  3836 I jxcore-log: 
,08-12 16:38:32.734  3787  3836 I jxcore-log: # 40. another
08-12 16:38:32.734  3787  3836 I jxcore-log: 
,08-12 16:38:32.795  3787  3836 I jxcore-log: ok 114 sane
08-12 16:38:32.795  3787  3836 I jxcore-log: 
,08-12 16:38:32.800  3787  3836 I jxcore-log: # teardown
08-12 16:38:32.800  3787  3836 I jxcore-log: 
,08-12 16:38:32.844  3787  3836 I jxcore-log: # setup
08-12 16:38:32.844  3787  3836 I jxcore-log: 
,08-12 16:38:32.930  3787  3836 I jxcore-log: # 41. can pass data in setup
08-12 16:38:32.930  3787  3836 I jxcore-log: 
,08-12 16:38:32.996  3787  3836 I jxcore-log: [{"uuid":"55c36816-efcf-481c-b52f-23b7ab6c0bd6","data":"custom data"},{"uuid":"4dc3ebdd-3f57-481a-a922-07137f0e0959","data":"custom data"}]
08-12 16:38:32.996  3787  3836 I jxcore-log: 
,08-12 16:38:32.998  3787  3836 I jxcore-log: ok 115 test participant has uuid
08-12 16:38:32.998  3787  3836 I jxcore-log: 
,08-12 16:38:32.999  3787  3836 I jxcore-log: ok 116 participant data matches
08-12 16:38:32.999  3787  3836 I jxcore-log: 
,08-12 16:38:32.999  3787  3836 I jxcore-log: ok 117 test participant has uuid
08-12 16:38:32.999  3787  3836 I jxcore-log: 
,08-12 16:38:33.000  3787  3836 I jxcore-log: ok 118 participant data matches
08-12 16:38:33.000  3787  3836 I jxcore-log: 
,08-12 16:38:33.000  3787  3836 I jxcore-log: ok 119 own UUID is found from the participants list
08-12 16:38:33.000  3787  3836 I jxcore-log: 
08-12 16:38:33.003  3787  3836 I jxcore-log: # teardown
08-12 16:38:33.003  3787  3836 I jxcore-log: 
,08-12 16:38:33.069  3787  3836 I jxcore-log: # setup
08-12 16:38:33.069  3787  3836 I jxcore-log: 
,08-12 16:38:33.106  3787  3836 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
08-12 16:38:33.106  3787  3836 I jxcore-log: 
,08-12 16:38:33.161  3787  3836 I jxcore-log: ok 120 specific error should be returned
08-12 16:38:33.161  3787  3836 I jxcore-log: 
,08-12 16:38:33.164  3787  3836 I jxcore-log: # teardown
08-12 16:38:33.164  3787  3836 I jxcore-log: 
,08-12 16:38:33.215  3787  3836 I jxcore-log: ok 121 error should be null
08-12 16:38:33.215  3787  3836 I jxcore-log: 
08-12 16:38:33.216  3787  3836 I jxcore-log: ok 122 error should be null
08-12 16:38:33.216  3787  3836 I jxcore-log: 
08-12 16:38:33.218  3787  3836 I jxcore-log: # setup
08-12 16:38:33.218  3787  3836 I jxcore-log: 
,08-12 16:38:33.319  3787  3836 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
08-12 16:38:33.319  3787  3836 I jxcore-log: 
,08-12 16:38:33.358  3787  3836 I jxcore-log: ok 123 specific error should be returned
08-12 16:38:33.358  3787  3836 I jxcore-log: 
,08-12 16:38:33.360  3787  3836 I jxcore-log: # teardown
08-12 16:38:33.360  3787  3836 I jxcore-log: 
,08-12 16:38:33.418  3787  3836 I jxcore-log: ok 124 error should be null
08-12 16:38:33.418  3787  3836 I jxcore-log: 
,08-12 16:38:33.419  3787  3836 I jxcore-log: ok 125 error should be null
08-12 16:38:33.419  3787  3836 I jxcore-log: 
,08-12 16:38:33.422  3787  3836 I jxcore-log: # setup
08-12 16:38:33.422  3787  3836 I jxcore-log: 
,08-12 16:38:33.503  3787  3836 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
08-12 16:38:33.503  3787  3836 I jxcore-log: 
,08-12 16:38:33.586  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:38:33.586  3787  3836 I jxcore-log: 
,08-12 16:38:33.588  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 46744
08-12 16:38:33.588  3787  3836 I jxcore-log: 
,08-12 16:38:33.592  3787  3836 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-12 16:38:33.593  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-12 16:38:33.593  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-12 16:38:33.593  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:38:33.596  3787  3836 I jxcore-log: ok 126 error should be null
08-12 16:38:33.596  3787  3836 I jxcore-log: 
08-12 16:38:33.597  3787  3836 I jxcore-log: ok 127 error should be null
08-12 16:38:33.597  3787  3836 I jxcore-log: 
08-12 16:38:33.599  3787  3836 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 16:38:33.599  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 16:38:33.599  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 16:38:33.599  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:38:33.602  3787  3836 I jxcore-log: ok 128 error should be null
08-12 16:38:33.602  3787  3836 I jxcore-log: 
,08-12 16:38:33.603  3787  3836 I jxcore-log: ok 129 error should be null
08-12 16:38:33.603  3787  3836 I jxcore-log: 
,08-12 16:38:33.608  3787  3836 I jxcore-log: # teardown
08-12 16:38:33.608  3787  3836 I jxcore-log: 
,08-12 16:38:33.711  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 16:38:33.711  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 16:38:33.712  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 16:38:33.712  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 16:38:33.713  3787  3836 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 16:38:33.713  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 16:38:33.714  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-12 16:38:33.714  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:38:33.732  3787  3836 I jxcore-log: ok 130 error should be null
08-12 16:38:33.732  3787  3836 I jxcore-log: 
,08-12 16:38:33.734  3787  3836 I jxcore-log: ok 131 error should be null
08-12 16:38:33.734  3787  3836 I jxcore-log: 
,08-12 16:38:33.748  3787  3836 I jxcore-log: # setup
08-12 16:38:33.748  3787  3836 I jxcore-log: 
,08-12 16:38:33.787  3787  3836 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
08-12 16:38:33.787  3787  3836 I jxcore-log: 
,08-12 16:38:33.879  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:38:33.879  3787  3836 I jxcore-log: 
,08-12 16:38:33.882  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 49599
08-12 16:38:33.882  3787  3836 I jxcore-log: 
,08-12 16:38:33.886  3787  3836 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-12 16:38:33.890  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 49024, start advertisements: false
08-12 16:38:33.890  3787  3836 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-12 16:38:33.890  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-12 16:38:33.890  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-12 16:38:33.890  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-12 16:38:33.890  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 16:38:33.890  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-12 16:38:33.894  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-12 16:38:33.894  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-12 16:38:33.900  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 16:38:33.902  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-12 16:38:33.902  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 16:38:33.907  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-12 16:38:33.907  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-12 16:38:33.907  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-12 16:38:33.908  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:38:33.911  2697  2893 D BtGatt.GattService: registerClient() - UUID=6db6db90-34d1-41e2-9d57-0d27b3feeb64
,08-12 16:38:33.912  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=6db6db90-34d1-41e2-9d57-0d27b3feeb64, clientIf=5
08-12 16:38:33.913  3787  3798 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 16:38:33.914  2697  2711 D BtGatt.GattService: start scan with filters
,08-12 16:38:33.918  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 16:38:33.918  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-12 16:38:33.918  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-12 16:38:33.919  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-12 16:38:33.919  2697  2752 D BtGatt.ScanManager: handling starting scan
,08-12 16:38:33.922  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 16:38:33.922  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-12 16:38:33.922  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 16:38:33.924  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 16:38:33.927  2697  2748 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-12 16:38:33.927  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:33.928  2697  2752 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 16:38:33.932  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 16:38:33.937  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-12 16:38:33.937  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:33.938  2697  2752 D BtGatt.ScanManager: Starting BLE batch scan
08-12 16:38:33.938  2697  2752 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 16:38:33.964  2697  2748 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-12 16:38:33.964  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:33.978  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-12 16:38:33.978  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:34.424  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-12 16:38:34.424  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-12 16:38:34.424  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:38:34.430  3787  3836 I jxcore-log: ok 132 error should be null
08-12 16:38:34.430  3787  3836 I jxcore-log: 
,08-12 16:38:34.432  3787  3836 I jxcore-log: ok 133 error should be null
08-12 16:38:34.432  3787  3836 I jxcore-log: 
,08-12 16:38:34.442  3787  3836 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-12 16:38:34.449  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 49024, start advertisements: false
,08-12 16:38:34.449  3787  3836 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-12 16:38:34.450  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-12 16:38:34.450  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 16:38:34.450  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 16:38:34.456  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-12 16:38:34.456  3787  3836 I jxcore-log: 
,08-12 16:38:34.461  3787  3836 I jxcore-log: ok 134 error should be null
08-12 16:38:34.461  3787  3836 I jxcore-log: 
,08-12 16:38:34.463  3787  3836 I jxcore-log: ok 135 error should be null
08-12 16:38:34.463  3787  3836 I jxcore-log: 
,08-12 16:38:34.474  3787  3836 I jxcore-log: # teardown
08-12 16:38:34.474  3787  3836 I jxcore-log: 
,08-12 16:38:35.483  2697  2697 D BtGatt.ScanManager: awakened up at time 689070
,08-12 16:38:35.485  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:38:35.534  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-12 16:38:35.534  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:35.535  2697  2748 D BtGatt.GattService: current time is 689122927929
,08-12 16:38:35.537  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -86, 0, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -91, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -83, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -85, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -81, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -86, 0, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0]
,08-12 16:38:35.538  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:38:35.539  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:38:35.540  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-12 16:38:35.541  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 16:38:35.541  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-12 16:38:35.543  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:38:35.543  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,08-12 16:38:35.760  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 16:38:35.760  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 16:38:35.760  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-12 16:38:35.760  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-12 16:38:35.761  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 16:38:35.761  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-12 16:38:35.761  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-12 16:38:35.761  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-12 16:38:35.761  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-12 16:38:35.761  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-12 16:38:35.761  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-12 16:38:35.761  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-12 16:38:35.762  3787  3836 D BluetoothAdapter: STATE_ON
08-12 16:38:35.763  2697  2711 D BtGatt.GattService: stopScan() - queue size =1
,08-12 16:38:35.765  2697  2708 D BtGatt.GattService: unregisterClient() - clientIf=5
08-12 16:38:35.766  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 16:38:35.766  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 16:38:35.767  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-12 16:38:35.767  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-12 16:38:35.767  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-12 16:38:35.770  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 16:38:35.770  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-12 16:38:35.771  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-12 16:38:35.771  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-12 16:38:35.772  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-12 16:38:35.780  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 16:38:35.781  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 16:38:35.781  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 16:38:35.785  3787  3836 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-12 16:38:35.785  3787  3836 I jxcore-log: 
,08-12 16:38:35.786  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-12 16:38:35.786  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:35.787  2697  2752 D BtGatt.ScanManager: stopping BLe Batch
,08-12 16:38:35.798  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 16:38:35.798  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:35.798  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:38:35.814  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-12 16:38:35.815  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:35.815  2697  2748 D BtGatt.GattService: current time is 689402979884
08-12 16:38:35.815  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, -128, -86, 3, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, -46, -4, -117, 6, 105, -37, 1, -128, -81, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 16:38:35.816  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,08-12 16:38:35.816  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-12 16:38:35.817  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 16:38:36.282  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 16:38:36.283  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 16:38:36.283  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:38:36.287  3787  3836 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 16:38:36.287  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-12 16:38:36.288  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-12 16:38:36.288  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:38:36.292  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 16:38:36.292  3787  3836 I jxcore-log: 
,08-12 16:38:36.308  3787  3836 I jxcore-log: ok 136 error should be null
08-12 16:38:36.308  3787  3836 I jxcore-log: 
,08-12 16:38:36.310  3787  3836 I jxcore-log: ok 137 error should be null
08-12 16:38:36.310  3787  3836 I jxcore-log: 
,08-12 16:38:36.320  3787  3836 I jxcore-log: # setup
08-12 16:38:36.320  3787  3836 I jxcore-log: 
,08-12 16:38:37.503  3787  3836 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
08-12 16:38:37.503  3787  3836 I jxcore-log: 
,08-12 16:38:37.556  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:38:37.556  3787  3836 I jxcore-log: 
,08-12 16:38:37.559  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 43064
08-12 16:38:37.559  3787  3836 I jxcore-log: 
,08-12 16:38:37.572  3787  3836 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-12 16:38:37.576  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 43064, start advertisements: true
,08-12 16:38:37.576  3787  3836 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 16:38:37.576  3787  3836 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
08-12 16:38:37.577  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,08-12 16:38:37.577  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-12 16:38:37.577  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-12 16:38:37.577  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-12 16:38:37.577  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 16:38:37.579  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-12 16:38:37.580  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
,08-12 16:38:37.580  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-12 16:38:37.580  3787  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-12 16:38:37.580  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-12 16:38:37.581  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-12 16:38:37.581  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 16:38:37.581  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-12 16:38:37.583  3787  4059 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-12 16:38:37.590  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-12 16:38:37.590  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-12 16:38:37.590  3787  4059 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-12 16:38:37.600  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 16:38:37.601  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings,
08-12 16:38:37.601  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 16:38:37.604  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-12 16:38:37.604  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 16:38:37.604  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
08-12 16:38:37.604  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-12 16:38:37.605  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 16:38:37.605  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-12 16:38:37.606  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:38:37.609  2697  2708 D BtGatt.GattService: registerClient() - UUID=aa81eb12-c765-4014-bb5a-45e2a4ce146a
,08-12 16:38:37.610  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=aa81eb12-c765-4014-bb5a-45e2a4ce146a, clientIf=5
08-12 16:38:37.611  3787  3799 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-12 16:38:37.612  2697  2751 D BtGatt.AdvertiseManager: message : 0
,08-12 16:38:37.617  2697  2751 D BtGatt.AdvertiseManager: starting multi advertising
,08-12 16:38:37.633  2697  2748 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-12 16:38:37.644  2697  2748 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-12 16:38:37.645  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-12 16:38:37.645  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 16:38:37.648  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 16:38:37.649  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 16:38:37.650  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-12 16:38:37.650  3787  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-12 16:38:37.650  3787  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-12 16:38:37.651  3787  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-12 16:38:37.651  3787  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-12 16:38:37.651  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-12 16:38:37.660  3787  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-12 16:38:37.661  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
,08-12 16:38:38.162  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-12 16:38:38.163  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-12 16:38:38.163  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:38:38.169  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-12 16:38:38.169  3787  3836 I jxcore-log: 
,08-12 16:38:38.174  3787  3836 I jxcore-log: ok 138 error should be null
08-12 16:38:38.174  3787  3836 I jxcore-log: 
,08-12 16:38:38.176  3787  3836 I jxcore-log: ok 139 error should be null
08-12 16:38:38.176  3787  3836 I jxcore-log: 
,08-12 16:38:38.188  3787  3836 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-12 16:38:38.195  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 43064, start advertisements: true
,08-12 16:38:38.195  3787  3836 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 16:38:38.195  3787  3836 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,08-12 16:38:38.196  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,08-12 16:38:38.202  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-12 16:38:38.202  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-12 16:38:38.202  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-12 16:38:38.202  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
08-12 16:38:38.202  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-12 16:38:38.202  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-12 16:38:38.202  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-12 16:38:38.202  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-12 16:38:38.202  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,08-12 16:38:38.204  2697  2751 D BtGatt.AdvertiseManager: message : 1
,08-12 16:38:38.206  2697  2751 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-12 16:38:38.233  2697  2748 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-12 16:38:38.234  2697  2748 D BtGatt.GattService: Client app is not null!
,08-12 16:38:38.236  2697  2893 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 16:38:38.237  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-12 16:38:38.237  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-12 16:38:38.238  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-12 16:38:38.238  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-12 16:38:38.238  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 16:38:38.239  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
08-12 16:38:38.240  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 16:38:38.240  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 16:38:38.240  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-12 16:38:38.243  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:38:38.252  2697  2708 D BtGatt.GattService: registerClient() - UUID=818b830e-1aa0-4180-ac79-6ce8a61f5b86
,08-12 16:38:38.253  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=818b830e-1aa0-4180-ac79-6ce8a61f5b86, clientIf=5
,08-12 16:38:38.254  3787  3798 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-12 16:38:38.258  2697  2751 D BtGatt.AdvertiseManager: message : 0
,08-12 16:38:38.265  2697  2751 D BtGatt.AdvertiseManager: starting multi advertising
,08-12 16:38:38.296  2697  2748 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-12 16:38:38.313  2697  2748 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-12 16:38:38.315  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-12 16:38:38.315  3787  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-12 16:38:38.315  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-12 16:38:38.315  3787  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-12 16:38:38.316  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-12 16:38:38.316  3787  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-12 16:38:38.316  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-12 16:38:38.316  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 16:38:38.317  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 16:38:38.334  3787  3836 I jxcore-log: ok 140 error should be null
08-12 16:38:38.334  3787  3836 I jxcore-log: 
,08-12 16:38:38.335  3787  3836 I jxcore-log: ok 141 error should be null
08-12 16:38:38.335  3787  3836 I jxcore-log: 
,08-12 16:38:38.347  3787  3836 I jxcore-log: # teardown
08-12 16:38:38.347  3787  3836 I jxcore-log: 
,08-12 16:38:38.906  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 16:38:38.907  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 16:38:38.907  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-12 16:38:38.907  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-12 16:38:38.907  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-12 16:38:38.907  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-12 16:38:38.907  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-12 16:38:38.908  3787  4059 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-12 16:38:38.908  3787  4059 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-12 16:38:38.908  3787  4059 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-12 16:38:38.909  3787  3787 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-12 16:38:38.909  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-12 16:38:38.909  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-12 16:38:38.909  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-12 16:38:38.910  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-12 16:38:38.910  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-12 16:38:38.910  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-12 16:38:38.910  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-12 16:38:38.910  3787  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-12 16:38:38.911  3787  3836 D BluetoothAdapter: STATE_ON
08-12 16:38:38.911  3787  3836 D BluetoothLeScanner: could not find callback wrapper
,08-12 16:38:38.911  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 16:38:38.911  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-12 16:38:38.912  2697  2751 D BtGatt.AdvertiseManager: message : 1
08-12 16:38:38.912  2697  2751 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-12 16:38:38.926  2697  2748 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-12 16:38:38.927  2697  2748 D BtGatt.GattService: Client app is not null!
,08-12 16:38:38.929  2697  2711 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 16:38:38.931  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-12 16:38:38.931  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-12 16:38:38.931  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-12 16:38:38.932  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-12 16:38:38.932  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-12 16:38:38.937  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 16:38:38.937  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-12 16:38:38.937  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-12 16:38:38.937  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-12 16:38:38.939  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 16:38:38.939  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-12 16:38:38.939  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 16:38:38.940  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 16:38:38.940  3787  3836 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-12 16:38:38.940  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 16:38:38.940  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 16:38:38.941  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 16:38:38.941  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 16:38:38.945  3787  3836 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-12 16:38:38.945  3787  3836 I jxcore-log: 
,08-12 16:38:38.953  3787  3836 I jxcore-log: ok 142 error should be null
08-12 16:38:38.953  3787  3836 I jxcore-log: 
,08-12 16:38:38.954  3787  3836 I jxcore-log: ok 143 error should be null
08-12 16:38:38.954  3787  3836 I jxcore-log: 
,08-12 16:38:38.960  3787  3836 I jxcore-log: # setup
08-12 16:38:38.960  3787  3836 I jxcore-log: 
,08-12 16:38:38.989  3787  3836 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
08-12 16:38:38.989  3787  3836 I jxcore-log: 
,08-12 16:38:39.047  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:38:39.047  3787  3836 I jxcore-log: 
,08-12 16:38:39.049  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 37441
08-12 16:38:39.049  3787  3836 I jxcore-log: 
,08-12 16:38:39.053  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 16:38:39.053  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 16:38:39.053  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 16:38:39.054  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:38:39.057  3787  3836 I jxcore-log: ok 144 error should be null
08-12 16:38:39.057  3787  3836 I jxcore-log: 
,08-12 16:38:39.057  3787  3836 I jxcore-log: ok 145 error should be null
08-12 16:38:39.057  3787  3836 I jxcore-log: 
,08-12 16:38:39.060  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 16:38:39.060  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 16:38:39.060  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 16:38:39.060  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 16:38:39.063  3787  3836 I jxcore-log: ok 146 error should be null
08-12 16:38:39.063  3787  3836 I jxcore-log: 
08-12 16:38:39.063  3787  3836 I jxcore-log: ok 147 error should be null
08-12 16:38:39.063  3787  3836 I jxcore-log: 
,08-12 16:38:39.070  3787  3836 I jxcore-log: # teardown
08-12 16:38:39.070  3787  3836 I jxcore-log: 
,08-12 16:38:39.160  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
08-12 16:38:39.160  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 16:38:39.160  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 16:38:39.161  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:38:39.168  3787  3836 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-12 16:38:39.169  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 16:38:39.169  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-12 16:38:39.169  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:38:39.174  3787  3836 I jxcore-log: ok 148 error should be null
08-12 16:38:39.174  3787  3836 I jxcore-log: 
,08-12 16:38:39.175  3787  3836 I jxcore-log: ok 149 error should be null
08-12 16:38:39.175  3787  3836 I jxcore-log: 
,08-12 16:38:39.181  3787  3836 I jxcore-log: # setup
08-12 16:38:39.181  3787  3836 I jxcore-log: 
,08-12 16:38:39.218  3787  3836 I jxcore-log: # 48. #start should fail if called twice in a row
08-12 16:38:39.218  3787  3836 I jxcore-log: 
,08-12 16:38:39.273  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:38:39.273  3787  3836 I jxcore-log: 
,08-12 16:38:39.276  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 46721
08-12 16:38:39.276  3787  3836 I jxcore-log: 
,08-12 16:38:39.279  3787  3836 I jxcore-log: ok 150 first call should succeed
08-12 16:38:39.279  3787  3836 I jxcore-log: 
,08-12 16:38:39.279  3787  3836 I jxcore-log: ok 151 first call should succeed
08-12 16:38:39.279  3787  3836 I jxcore-log: 
,08-12 16:38:39.282  3787  3836 I jxcore-log: ok 152 specific error should be returned
08-12 16:38:39.282  3787  3836 I jxcore-log: 
,08-12 16:38:39.284  3787  3836 I jxcore-log: # teardown
08-12 16:38:39.284  3787  3836 I jxcore-log: 
,08-12 16:38:39.360  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 16:38:39.360  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 16:38:39.360  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 16:38:39.360  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 16:38:39.363  3787  3836 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 16:38:39.363  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 16:38:39.363  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-12 16:38:39.364  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:38:39.370  3787  3836 I jxcore-log: ok 153 error should be null
08-12 16:38:39.370  3787  3836 I jxcore-log: 
,08-12 16:38:39.370  3787  3836 I jxcore-log: ok 154 error should be null
08-12 16:38:39.370  3787  3836 I jxcore-log: 
,08-12 16:38:39.377  3787  3836 I jxcore-log: # setup
08-12 16:38:39.377  3787  3836 I jxcore-log: 
,08-12 16:38:39.440  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 16:38:39.458  3787  3836 I jxcore-log: # 49. does not emit duplicate discoveryAdvertisingStateUpdate
08-12 16:38:39.458  3787  3836 I jxcore-log: 
,08-12 16:38:39.464  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 16:38:39.464  3787  3836 I jxcore-log: 
,08-12 16:38:39.523  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:38:39.523  3787  3836 I jxcore-log: 
,08-12 16:38:39.525  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 48173
08-12 16:38:39.525  3787  3836 I jxcore-log: 
,08-12 16:38:39.529  3787  3836 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-12 16:38:39.533  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 43064, start advertisements: false
,08-12 16:38:39.533  3787  3836 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 16:38:39.533  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 16:38:39.533  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-12 16:38:39.534  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-12 16:38:39.534  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 16:38:39.534  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-12 16:38:39.539  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-12 16:38:39.539  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-12 16:38:39.543  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 16:38:39.544  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-12 16:38:39.544  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 16:38:39.549  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-12 16:38:39.549  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-12 16:38:39.549  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-12 16:38:39.550  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:38:39.553  2697  2711 D BtGatt.GattService: registerClient() - UUID=15d6af89-9ff7-4206-b9ad-8f6cc0eb7751
,08-12 16:38:39.554  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=15d6af89-9ff7-4206-b9ad-8f6cc0eb7751, clientIf=5
08-12 16:38:39.554  3787  3798 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 16:38:39.554  2697  2708 D BtGatt.GattService: start scan with filters
,08-12 16:38:39.558  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 16:38:39.558  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-12 16:38:39.558  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-12 16:38:39.558  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,08-12 16:38:39.559  2697  2752 D BtGatt.ScanManager: handling starting scan
,08-12 16:38:39.561  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 16:38:39.562  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 16:38:39.562  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 16:38:39.564  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 16:38:39.567  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 16:38:39.577  2697  2748 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-12 16:38:39.577  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:39.578  2697  2752 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 16:38:39.592  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-12 16:38:39.592  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:39.592  2697  2752 D BtGatt.ScanManager: Starting BLE batch scan
08-12 16:38:39.592  2697  2752 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 16:38:39.622  2697  2748 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-12 16:38:39.623  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:39.644  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-12 16:38:39.644  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:40.061  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-12 16:38:40.062  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-12 16:38:40.062  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:38:40.068  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-12 16:38:40.068  3787  3836 I jxcore-log: 
,08-12 16:38:40.092  3787  3836 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-12 16:38:40.095  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 48173, start advertisements: true
,08-12 16:38:40.095  3787  3836 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-12 16:38:40.095  3787  3836 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,08-12 16:38:40.095  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,08-12 16:38:40.096  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-12 16:38:40.096  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-12 16:38:40.096  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-12 16:38:40.096  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 4
08-12 16:38:40.096  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-12 16:38:40.096  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-12 16:38:40.096  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-12 16:38:40.096  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-12 16:38:40.096  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
08-12 16:38:40.096  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-12 16:38:40.096  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-12 16:38:40.097  3787  3836 D BluetoothAdapter: STATE_ON
08-12 16:38:40.097  2697  2893 D BtGatt.GattService: stopScan() - queue size =1
,08-12 16:38:40.098  2697  2711 D BtGatt.GattService: unregisterClient() - clientIf=5
08-12 16:38:40.099  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 16:38:40.099  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 16:38:40.099  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-12 16:38:40.099  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-12 16:38:40.099  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-12 16:38:40.099  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-12 16:38:40.100  3787  3836 D BluetoothAdapter: STATE_ON
08-12 16:38:40.104  2697  2708 D BtGatt.GattService: registerClient() - UUID=955d483f-6167-4185-9c0f-5ed7f00b14b3
08-12 16:38:40.106  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=955d483f-6167-4185-9c0f-5ed7f00b14b3, clientIf=5
08-12 16:38:40.107  3787  3799 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-12 16:38:40.108  2697  2893 D BtGatt.GattService: start scan with filters
,08-12 16:38:40.113  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 16:38:40.113  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-12 16:38:40.114  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-12 16:38:40.114  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-12 16:38:40.114  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-12 16:38:40.115  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 16:38:40.116  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-12 16:38:40.116  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:40.117  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-12 16:38:40.118  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-12 16:38:40.119  2697  2752 D BtGatt.ScanManager: stopping BLe Batch
08-12 16:38:40.119  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-12 16:38:40.119  3787  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-12 16:38:40.119  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-12 16:38:40.120  3787  4060 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-12 16:38:40.120  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-12 16:38:40.120  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-12 16:38:40.120  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-12 16:38:40.122  3787  3836 D BluetoothAdapter: STATE_ON
08-12 16:38:40.123  3787  4060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-12 16:38:40.124  2697  2711 D BtGatt.GattService: stopScan() - queue size =0
08-12 16:38:40.126  2697  2711 D BtGatt.GattService: unregisterClient() - clientIf=5
08-12 16:38:40.127  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-12 16:38:40.127  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 16:38:40.127  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-12 16:38:40.127  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-12 16:38:40.127  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-12 16:38:40.129  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 16:38:40.130  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-12 16:38:40.131  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-12 16:38:40.131  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:40.131  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:38:40.133  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-12 16:38:40.133  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 16:38:40.134  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
08-12 16:38:40.134  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-12 16:38:40.134  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 16:38:40.134  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-12 16:38:40.135  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:38:40.139  2697  2711 D BtGatt.GattService: registerClient() - UUID=5c6cf17d-5a48-457f-b81d-ab538a00d877
,08-12 16:38:40.139  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=5c6cf17d-5a48-457f-b81d-ab538a00d877, clientIf=5
08-12 16:38:40.140  3787  3798 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-12 16:38:40.141  2697  2751 D BtGatt.AdvertiseManager: message : 0
,08-12 16:38:40.144  2697  2751 D BtGatt.AdvertiseManager: starting multi advertising
,08-12 16:38:40.147  2697  2697 D BtGatt.ScanManager: awakened up at time 693735
,08-12 16:38:40.179  2697  2748 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-12 16:38:40.189  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-12 16:38:40.190  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:40.190  2697  2748 D BtGatt.GattService: current time is 693777837820
,08-12 16:38:40.190  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -89, 1, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -80, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -90, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:38:40.191  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:38:40.191  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 16:38:40.192  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:38:40.192  2697  2752 D BtGatt.ScanManager: handling starting scan
08-12 16:38:40.192  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 16:38:40.192  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:38:40.202  2697  2748 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
08-12 16:38:40.203  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-12 16:38:40.203  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-12 16:38:40.205  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-12 16:38:40.207  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-12 16:38:40.207  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 16:38:40.207  3787  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-12 16:38:40.207  3787  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-12 16:38:40.207  3787  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-12 16:38:40.208  3787  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-12 16:38:40.208  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-12 16:38:40.208  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
08-12 16:38:40.212  3787  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-12 16:38:40.213  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
08-12 16:38:40.214  2697  2748 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-12 16:38:40.214  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:40.215  2697  2752 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-12 16:38:40.228  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-12 16:38:40.228  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:40.229  2697  2752 D BtGatt.ScanManager: Starting BLE batch scan
08-12 16:38:40.229  2697  2752 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 16:38:40.254  2697  2748 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-12 16:38:40.254  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:40.265  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-12 16:38:40.266  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:40.280  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-12 16:38:40.281  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:40.281  2697  2752 D BtGatt.ScanManager: stopping BLe Batch
,08-12 16:38:40.296  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 16:38:40.297  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:40.297  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:38:40.323  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-12 16:38:40.324  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:40.324  2697  2748 D BtGatt.GattService: current time is 693912255333
,08-12 16:38:40.325  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -86, 1, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:38:40.325  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:38:40.714  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-12 16:38:40.714  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-12 16:38:40.715  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:38:40.720  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-12 16:38:40.720  3787  3836 I jxcore-log: 
,08-12 16:38:40.738  3787  3836 I jxcore-log: ok 155 called only once
08-12 16:38:40.738  3787  3836 I jxcore-log: 
,08-12 16:38:40.739  3787  3836 I jxcore-log: ok 156 discovery state matches
08-12 16:38:40.739  3787  3836 I jxcore-log: 
08-12 16:38:40.739  3787  3836 I jxcore-log: ok 157 advertising state matches
08-12 16:38:40.739  3787  3836 I jxcore-log: 
,08-12 16:38:40.745  3787  3836 I jxcore-log: # teardown
08-12 16:38:40.745  3787  3836 I jxcore-log: 
,08-12 16:38:41.284  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 16:38:41.284  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 16:38:41.285  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-12 16:38:41.286  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-12 16:38:41.287  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-12 16:38:41.287  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-12 16:38:41.288  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-12 16:38:41.288  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-12 16:38:41.289  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-12 16:38:41.289  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-12 16:38:41.290  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-12 16:38:41.290  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-12 16:38:41.290  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-12 16:38:41.291  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-12 16:38:41.292  3787  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-12 16:38:41.293  3787  4060 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-12 16:38:41.293  3787  4060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-12 16:38:41.293  3787  3836 D BluetoothAdapter: STATE_ON
08-12 16:38:41.293  3787  4060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-12 16:38:41.293  3787  3836 D BluetoothLeScanner: could not find callback wrapper
08-12 16:38:41.293  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-12 16:38:41.293  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-12 16:38:41.295  2697  2751 D BtGatt.AdvertiseManager: message : 1
,08-12 16:38:41.295  2697  2751 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-12 16:38:41.311  2697  2748 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-12 16:38:41.311  2697  2748 D BtGatt.GattService: Client app is not null!
,08-12 16:38:41.313  2697  2708 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 16:38:41.313  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-12 16:38:41.314  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-12 16:38:41.314  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-12 16:38:41.314  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-12 16:38:41.314  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-12 16:38:41.316  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 16:38:41.316  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-12 16:38:41.316  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-12 16:38:41.319  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-12 16:38:41.321  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 16:38:41.321  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-12 16:38:41.321  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 16:38:41.321  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-12 16:38:41.321  3787  3787 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-12 16:38:41.322  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 16:38:41.323  3787  3836 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 16:38:41.323  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 16:38:41.323  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 16:38:41.323  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:38:41.329  3787  3836 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
08-12 16:38:41.329  3787  3836 I jxcore-log: 
08-12 16:38:41.329  3787  3836 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-12 16:38:41.329  3787  3836 I jxcore-log: 
,08-12 16:38:41.332  3787  3836 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-12 16:38:41.332  3787  3836 I jxcore-log: 
,08-12 16:38:41.337  3787  3836 I jxcore-log: ok 158 error should be null
08-12 16:38:41.337  3787  3836 I jxcore-log: 
,08-12 16:38:41.338  3787  3836 I jxcore-log: ok 159 error should be null
08-12 16:38:41.338  3787  3836 I jxcore-log: 
,08-12 16:38:41.344  3787  3836 I jxcore-log: # setup
08-12 16:38:41.344  3787  3836 I jxcore-log: 
,08-12 16:38:41.433  3787  3836 I jxcore-log: # 50. does not send duplicate availability changes
08-12 16:38:41.433  3787  3836 I jxcore-log: 
,08-12 16:38:41.505  3787  3836 I jxcore-log: ok 160 should be called once
08-12 16:38:41.505  3787  3836 I jxcore-log: 
,08-12 16:38:41.508  3787  3836 I jxcore-log: ok 161 should not have been called more than once
08-12 16:38:41.508  3787  3836 I jxcore-log: 
,08-12 16:38:41.512  3787  3836 I jxcore-log: # teardown
08-12 16:38:41.512  3787  3836 I jxcore-log: 
,08-12 16:38:41.553  3787  3836 I jxcore-log: ok 162 error should be null
08-12 16:38:41.553  3787  3836 I jxcore-log: 
,08-12 16:38:41.553  3787  3836 I jxcore-log: ok 163 error should be null
08-12 16:38:41.553  3787  3836 I jxcore-log: 
,08-12 16:38:41.556  3787  3836 I jxcore-log: # setup
08-12 16:38:41.556  3787  3836 I jxcore-log: 
,08-12 16:38:41.615  3787  3836 I jxcore-log: # 51. can get the network status
08-12 16:38:41.615  3787  3836 I jxcore-log: 
,08-12 16:38:41.660  3787  3836 I jxcore-log: ok 164 network status should have certain non-empty properties
08-12 16:38:41.660  3787  3836 I jxcore-log: 
,08-12 16:38:41.663  3787  3836 I jxcore-log: # teardown
08-12 16:38:41.663  3787  3836 I jxcore-log: 
,08-12 16:38:41.719  3787  3836 I jxcore-log: ok 165 error should be null
08-12 16:38:41.719  3787  3836 I jxcore-log: 
,08-12 16:38:41.720  3787  3836 I jxcore-log: ok 166 error should be null
08-12 16:38:41.720  3787  3836 I jxcore-log: 
,08-12 16:38:41.725  3787  3836 I jxcore-log: # setup
08-12 16:38:41.725  3787  3836 I jxcore-log: 
,08-12 16:38:41.770  3787  3836 I jxcore-log: # 52. wifi peer is marked unavailable if announcements stop
08-12 16:38:41.770  3787  3836 I jxcore-log: 
,08-12 16:38:41.822  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 16:38:41.827  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 16:38:41.827  3787  3836 I jxcore-log: 
,08-12 16:38:41.854  3787  3836 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
08-12 16:38:41.854  3787  3836 I jxcore-log: 
,08-12 16:38:41.882  3787  3836 I jxcore-log: ok 167 host address should match
08-12 16:38:41.882  3787  3836 I jxcore-log: 
,08-12 16:38:41.883  3787  3836 I jxcore-log: ok 168 port should match
08-12 16:38:41.883  3787  3836 I jxcore-log: 
,08-12 16:38:43.859  3787  3836 I jxcore-log: ok 169 host address should be null
08-12 16:38:43.859  3787  3836 I jxcore-log: 
,08-12 16:38:43.860  3787  3836 I jxcore-log: ok 170 port should should be null
08-12 16:38:43.860  3787  3836 I jxcore-log: 
,08-12 16:38:43.876  3787  3836 I jxcore-log: # teardown
08-12 16:38:43.876  3787  3836 I jxcore-log: 
,08-12 16:38:43.975  3787  3836 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-12 16:38:43.975  3787  3836 I jxcore-log: 
,08-12 16:38:43.980  3787  3836 I jxcore-log: ok 171 error should be null
08-12 16:38:43.980  3787  3836 I jxcore-log: 
,08-12 16:38:43.982  3787  3836 I jxcore-log: ok 172 error should be null
08-12 16:38:43.982  3787  3836 I jxcore-log: 
,08-12 16:38:43.987  3787  3836 I jxcore-log: # setup
08-12 16:38:43.987  3787  3836 I jxcore-log: 
,08-12 16:38:44.049  3787  3836 I jxcore-log: # 53. Can call start/stopListeningForAdvertisements
08-12 16:38:44.049  3787  3836 I jxcore-log: 
,08-12 16:38:44.106  3787  3836 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-12 16:38:44.113  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 48173, start advertisements: false
,08-12 16:38:44.113  3787  3836 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 16:38:44.114  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 16:38:44.114  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-12 16:38:44.115  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-12 16:38:44.115  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 16:38:44.115  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-12 16:38:44.125  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-12 16:38:44.126  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-12 16:38:44.139  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 16:38:44.141  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-12 16:38:44.142  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 16:38:44.153  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-12 16:38:44.153  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-12 16:38:44.154  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-12 16:38:44.156  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:38:44.163  2697  2711 D BtGatt.GattService: registerClient() - UUID=c596e3c8-6459-4557-9107-740526b08387
08-12 16:38:44.164  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=c596e3c8-6459-4557-9107-740526b08387, clientIf=5
,08-12 16:38:44.165  3787  3799 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 16:38:44.166  2697  2708 D BtGatt.GattService: start scan with filters
,08-12 16:38:44.176  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 16:38:44.177  2697  2752 D BtGatt.ScanManager: handling starting scan
,08-12 16:38:44.177  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-12 16:38:44.177  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-12 16:38:44.178  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-12 16:38:44.187  2697  2748 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-12 16:38:44.188  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:44.188  2697  2752 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 16:38:44.195  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 16:38:44.197  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 16:38:44.198  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 16:38:44.203  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-12 16:38:44.204  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:44.204  2697  2752 D BtGatt.ScanManager: Starting BLE batch scan
,08-12 16:38:44.204  2697  2752 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 16:38:44.206  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 16:38:44.215  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 16:38:44.225  2697  2748 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-12 16:38:44.225  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:44.234  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-12 16:38:44.234  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:44.699  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-12 16:38:44.699  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 16:38:44.700  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:38:44.704  3787  3836 I jxcore-log: ok 173 Can call startListeningForAdvertisements without error
08-12 16:38:44.704  3787  3836 I jxcore-log: 
,08-12 16:38:44.707  3787  3836 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-12 16:38:44.707  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 16:38:44.707  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-12 16:38:44.708  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should affect listening to advertisements only
08-12 16:38:44.708  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 16:38:44.708  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-12 16:38:44.712  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:38:44.714  2697  2893 D BtGatt.GattService: stopScan() - queue size =1
,08-12 16:38:44.719  2697  2711 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 16:38:44.720  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 16:38:44.721  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-12 16:38:44.721  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-12 16:38:44.721  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-12 16:38:44.722  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-12 16:38:44.726  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 16:38:44.727  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 16:38:44.733  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-12 16:38:44.733  3787  3836 I jxcore-log: 
,08-12 16:38:44.737  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-12 16:38:44.737  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:44.738  2697  2752 D BtGatt.ScanManager: stopping BLe Batch
,08-12 16:38:44.738  2697  2697 D BtGatt.ScanManager: awakened up at time 698326
,08-12 16:38:44.758  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 16:38:44.758  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:44.758  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:38:44.790  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-12 16:38:44.790  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:44.791  2697  2748 D BtGatt.GattService: current time is 698378833018
,08-12 16:38:44.791  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -92, 1, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 116, -43, -111, -91, -20, -29, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -81, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 16:38:44.792  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:38:44.793  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 16:38:44.793  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-12 16:38:44.794  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 16:38:45.229  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 16:38:45.229  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 16:38:45.230  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:38:45.236  3787  3836 I jxcore-log: ok 174 Can call stopListeningForAdvertisements without error
08-12 16:38:45.236  3787  3836 I jxcore-log: 
,08-12 16:38:45.261  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 16:38:45.261  3787  3836 I jxcore-log: 
,08-12 16:38:45.266  3787  3836 I jxcore-log: # teardown
08-12 16:38:45.266  3787  3836 I jxcore-log: 
,08-12 16:38:45.693  3787  3836 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-12 16:38:45.694  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 16:38:45.694  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 16:38:45.694  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:38:45.698  3787  3836 I jxcore-log: ok 175 Should be able to call stopListeningForAdvertisements in teardown
08-12 16:38:45.698  3787  3836 I jxcore-log: 
08-12 16:38:45.700  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 16:38:45.700  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 16:38:45.701  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 16:38:45.702  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:38:45.709  3787  3836 I jxcore-log: ok 176 Should be able to call stopAdvertisingAndListening in teardown
08-12 16:38:45.709  3787  3836 I jxcore-log: 
,08-12 16:38:45.718  3787  3836 I jxcore-log: # setup
08-12 16:38:45.718  3787  3836 I jxcore-log: 
,08-12 16:38:45.764  3787  3836 I jxcore-log: # 54. Client to server request coordinated
08-12 16:38:45.764  3787  3836 I jxcore-log: 
,08-12 16:38:45.924  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:38:45.924  3787  3836 I jxcore-log: 
,08-12 16:38:45.929  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 38068
08-12 16:38:45.929  3787  3836 I jxcore-log: 
,08-12 16:38:45.932  3787  3836 I jxcore-log: ok 177 error should be null
08-12 16:38:45.932  3787  3836 I jxcore-log: 
,08-12 16:38:45.932  3787  3836 I jxcore-log: ok 178 error should be null
08-12 16:38:45.932  3787  3836 I jxcore-log: 
,08-12 16:38:45.981  3787  3836 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-12 16:38:45.984  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 38068, start advertisements: true
,08-12 16:38:45.984  3787  3836 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 16:38:45.985  3787  3836 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,08-12 16:38:45.985  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,08-12 16:38:45.985  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
08-12 16:38:45.985  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-12 16:38:45.985  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-12 16:38:45.985  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
08-12 16:38:45.985  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-12 16:38:45.985  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-12 16:38:45.985  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-12 16:38:45.985  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-12 16:38:45.985  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
08-12 16:38:45.985  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-12 16:38:45.985  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-12 16:38:45.985  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-12 16:38:45.985  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-12 16:38:45.985  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-12 16:38:45.985  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-12 16:38:45.985  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 16:38:45.986  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-12 16:38:45.986  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-12 16:38:45.986  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-12 16:38:45.986  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-12 16:38:45.986  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-12 16:38:45.987  3787  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-12 16:38:45.987  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-12 16:38:45.988  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-12 16:38:45.989  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 16:38:45.989  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
08-12 16:38:45.989  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-12 16:38:45.989  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 16:38:45.989  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-12 16:38:45.990  3787  3836 D BluetoothAdapter: STATE_ON
08-12 16:38:45.991  3787  4062 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-12 16:38:45.993  2697  2708 D BtGatt.GattService: registerClient() - UUID=3244e3f0-a49d-4489-b591-3e3bb52b0dc5
08-12 16:38:45.994  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=3244e3f0-a49d-4489-b591-3e3bb52b0dc5, clientIf=5
08-12 16:38:45.995  3787  3798 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-12 16:38:45.996  3787  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-12 16:38:45.996  2697  2751 D BtGatt.AdvertiseManager: message : 0
,08-12 16:38:46.001  2697  2751 D BtGatt.AdvertiseManager: starting multi advertising
,08-12 16:38:46.012  2697  2748 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-12 16:38:46.018  2697  2748 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-12 16:38:46.019  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-12 16:38:46.019  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 16:38:46.025  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 16:38:46.026  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 16:38:46.026  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-12 16:38:46.027  3787  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-12 16:38:46.027  3787  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
08-12 16:38:46.027  3787  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-12 16:38:46.027  3787  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-12 16:38:46.028  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-12 16:38:46.036  3787  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-12 16:38:46.036  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-12 16:38:46.537  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-12 16:38:46.538  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-12 16:38:46.538  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:38:46.554  3787  3836 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-12 16:38:46.561  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 38068, start advertisements: false
,08-12 16:38:46.561  3787  3836 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-12 16:38:46.562  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should affect listening to advertisements only
,08-12 16:38:46.562  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-12 16:38:46.562  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-12 16:38:46.563  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-12 16:38:46.563  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-12 16:38:46.565  2697  2751 D BtGatt.AdvertiseManager: message : 1
,08-12 16:38:46.567  2697  2751 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-12 16:38:46.589  2697  2748 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-12 16:38:46.590  2697  2748 D BtGatt.GattService: Client app is not null!
,08-12 16:38:46.592  2697  2708 D BtGatt.GattService: unregisterClient() - clientIf=5
08-12 16:38:46.593  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-12 16:38:46.594  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-12 16:38:46.594  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-12 16:38:46.594  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-12 16:38:46.595  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-12 16:38:46.598  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 16:38:46.599  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 16:38:46.603  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 16:38:46.615  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-12 16:38:46.616  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-12 16:38:46.616  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-12 16:38:46.620  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:38:46.628  2697  2893 D BtGatt.GattService: registerClient() - UUID=87dc9119-f213-4726-800d-150e7e8c05a7
,08-12 16:38:46.629  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=87dc9119-f213-4726-800d-150e7e8c05a7, clientIf=5
,08-12 16:38:46.630  3787  3799 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 16:38:46.631  2697  2708 D BtGatt.GattService: start scan with filters
,08-12 16:38:46.638  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 16:38:46.638  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-12 16:38:46.638  2697  2752 D BtGatt.ScanManager: handling starting scan
,08-12 16:38:46.638  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-12 16:38:46.639  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-12 16:38:46.644  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 16:38:46.644  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-12 16:38:46.645  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 16:38:46.646  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 16:38:46.651  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 16:38:46.656  2697  2748 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-12 16:38:46.656  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:46.656  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-12 16:38:46.656  3787  3836 I jxcore-log: 
,08-12 16:38:46.657  2697  2752 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 16:38:46.670  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-12 16:38:46.670  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:46.670  2697  2752 D BtGatt.ScanManager: Starting BLE batch scan
08-12 16:38:46.671  2697  2752 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 16:38:46.690  2697  2748 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-12 16:38:46.690  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:46.698  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-12 16:38:46.698  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:47.145  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false,
08-12 16:38:47.145  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-12 16:38:47.146  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:38:47.153  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-12 16:38:47.153  3787  3836 I jxcore-log: 
,08-12 16:38:47.158  3787  3836 I jxcore-log: INFO testThaliNotification: startListeningForAdvertisements
08-12 16:38:47.158  3787  3836 I jxcore-log: 
,08-12 16:38:48.204  2697  2697 D BtGatt.ScanManager: awakened up at time 701792
,08-12 16:38:48.207  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:38:48.323  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
08-12 16:38:48.323  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:48.323  2697  2748 D BtGatt.GattService: current time is 701911548422
,08-12 16:38:48.324  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -93, 0, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -91, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -80, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -85, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -81, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -93, 0, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 85, -113, -37, 31, -33, 8, 0, 4, -93, 0, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:38:48.324  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:38:48.324  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:38:48.324  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 16:38:48.324  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 16:38:48.325  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 16:38:48.325  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 16:38:48.325  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 16:38:48.325  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:38:48.325  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:38:48.384  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:38:48.391  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:38:48.393  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:38:48.427  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 16:38:48.427  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 16:38:48.428  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:38:48.428  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:38:48.456  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 16:38:48.456  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 16:38:48.457  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-12 16:38:49.830  2697  2697 D BtGatt.ScanManager: awakened up at time 703418
,08-12 16:38:49.832  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:38:49.861  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-12 16:38:49.862  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:49.862  2697  2748 D BtGatt.GattService: current time is 703450421075
,08-12 16:38:49.863  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -93, 29, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:38:49.864  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:38:51.365  2697  2697 D BtGatt.ScanManager: awakened up at time 704953
,08-12 16:38:51.367  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:38:51.380  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:38:51.380  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:52.883  2697  2697 D BtGatt.ScanManager: awakened up at time 706470
,08-12 16:38:52.885  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:38:52.940  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-12 16:38:52.940  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:52.941  2697  2748 D BtGatt.GattService: current time is 706528559507
,08-12 16:38:52.942  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -91, 4, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -91, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -74, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -64, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -63, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -82, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
08-12 16:38:52.943  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:38:52.947  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 16:38:52.949  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-12 16:38:52.953  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-12 16:38:52.953  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:38:52.954  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:38:52.954  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-12 16:38:54.437  2697  2697 D BtGatt.ScanManager: awakened up at time 708025,
,08-12 16:38:54.440  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:38:54.468  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-12 16:38:54.468  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:54.469  2697  2748 D BtGatt.GattService: current time is 708056794451
08-12 16:38:54.469  2697  2748 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:38:54.470  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:38:55.972  2697  2697 D BtGatt.ScanManager: awakened up at time 709560
,08-12 16:38:55.974  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:38:55.984  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:38:55.984  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:57.487  2697  2697 D BtGatt.ScanManager: awakened up at time 711075
,08-12 16:38:57.491  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:38:57.573  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
08-12 16:38:57.573  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:38:57.573  2697  2748 D BtGatt.GattService: current time is 711161501114
08-12 16:38:57.574  2697  2748 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -85, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -70, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -100, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, 4, -94, 9, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -91, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -82, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -83, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
,08-12 16:38:57.575  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 16:38:57.576  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 16:38:57.577  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:38:57.578  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:38:57.579  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:38:57.580  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:38:57.581  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 16:38:57.582  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-12 16:38:59.076  2697  2697 D BtGatt.ScanManager: awakened up at time 712664
,08-12 16:38:59.080  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:38:59.113  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-12 16:38:59.113  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:38:59.113  2697  2748 D BtGatt.GattService: current time is 712701499184
08-12 16:38:59.114  2697  2748 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -85, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 85, -113, -37, 31, -33, 8, 0, -128, -94, 29, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, -46, -4, -117, 6, 105, -37, 1, -128, -69, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -65, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -101, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:38:59.115  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-12 16:38:59.116  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
08-12 16:38:59.118  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:38:59.119  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 16:38:59.121  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 16:39:00.612  2697  2697 D BtGatt.ScanManager: awakened up at time 714199
,08-12 16:39:00.614  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:00.627  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:39:00.628  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:02.132  2697  2697 D BtGatt.ScanManager: awakened up at time 715720
,08-12 16:39:02.136  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:02.208  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,08-12 16:39:02.208  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:02.209  2697  2748 D BtGatt.GattService: current time is 715796581263
,08-12 16:39:02.210  2697  2748 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -65, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -86, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -71, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, 4, -91, 3, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -83, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
08-12 16:39:02.211  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 16:39:02.212  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 16:39:02.213  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-12 16:39:02.213  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 16:39:02.214  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 16:39:02.215  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:39:02.216  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:39:02.217  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-12 16:39:03.712  2697  2697 D BtGatt.ScanManager: awakened up at time 717300
,08-12 16:39:03.715  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:03.743  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-12 16:39:03.743  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:03.745  2697  2748 D BtGatt.GattService: current time is 717332877979
,08-12 16:39:03.746  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, -128, -87, 23, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 35, 97, 126, -92, 22, -56, 1, -128, -81, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -82, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -74, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
08-12 16:39:03.747  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,08-12 16:39:03.747  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-12 16:39:03.748  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 16:39:03.749  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 16:39:05.246  2697  2697 D BtGatt.ScanManager: awakened up at time 718834
,08-12 16:39:05.249  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:05.260  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:39:05.260  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:06.764  2697  2697 D BtGatt.ScanManager: awakened up at time 720352
,08-12 16:39:06.767  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:06.781  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:39:06.781  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:08.283  2697  2697 D BtGatt.ScanManager: awakened up at time 721871
,08-12 16:39:08.286  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:08.338  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-12 16:39:08.338  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:08.339  2697  2748 D BtGatt.GattService: current time is 721927311770
08-12 16:39:08.340  2697  2748 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -81, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -80, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -73, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -72, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 85, -113, -37, 31, -33, 8, 0, -128, -98, 5, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0]
08-12 16:39:08.341  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-12 16:39:08.342  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:39:08.343  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:39:08.344  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-12 16:39:08.345  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 16:39:08.346  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:39:08.347  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,08-12 16:39:09.858  2697  2697 D BtGatt.ScanManager: awakened up at time 723446
,08-12 16:39:09.861  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:09.895  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:39:09.895  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:10.185  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:39:10.197  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:39:10.203  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:39:10.265  1513  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 16:39:10.266  1513  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-12 16:39:10.266  1513  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:39:10.266  1513  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:39:10.322  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 16:39:10.323  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 16:39:10.326  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-12 16:39:11.402  2697  2697 D BtGatt.ScanManager: awakened up at time 724989
,08-12 16:39:11.404  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:11.418  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:39:11.419  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:12.921  2697  2697 D BtGatt.ScanManager: awakened up at time 726509
,08-12 16:39:12.926  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:12.979  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-12 16:39:12.979  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:12.980  2697  2748 D BtGatt.GattService: current time is 726567973274
,08-12 16:39:12.981  2697  2748 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -85, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -90, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -91, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, -128, -81, 10, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 37, -47, 14, -113, 116, -46, 1, -128, -102, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 16:39:12.982  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 16:39:12.983  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 16:39:12.984  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-12 16:39:12.984  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:39:12.985  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
08-12 16:39:12.986  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 16:39:12.987  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 16:39:14.482  2697  2697 D BtGatt.ScanManager: awakened up at time 728069
,08-12 16:39:14.484  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:14.518  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-12 16:39:14.518  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:39:14.519  2697  2748 D BtGatt.GattService: current time is 728107035927
,08-12 16:39:14.520  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, -128, -101, 29, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 37, -47, 14, -113, 116, -46, 1, -128, -103, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:39:14.520  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
08-12 16:39:14.522  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 16:39:16.021  2697  2697 D BtGatt.ScanManager: awakened up at time 729609
,08-12 16:39:16.024  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:16.036  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:39:16.037  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:17.539  2697  2697 D BtGatt.ScanManager: awakened up at time 731127
,08-12 16:39:17.542  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:17.598  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-12 16:39:17.599  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:17.599  2697  2748 D BtGatt.GattService: current time is 731187419515
,08-12 16:39:17.600  2697  2748 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -66, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 85, -113, -37, 31, -33, 8, 0, 4, -92, 13, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -81, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -73, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
08-12 16:39:17.603  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-12 16:39:17.604  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:39:17.605  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 16:39:17.606  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 16:39:17.607  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-12 16:39:19.102  2697  2697 D BtGatt.ScanManager: awakened up at time 732689
,08-12 16:39:19.106  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:19.159  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-12 16:39:19.159  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:19.160  2697  2748 D BtGatt.GattService: current time is 732747964514
08-12 16:39:19.161  2697  2748 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -85, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -81, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -83, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -84, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -82, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -72, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 85, -113, -37, 31, -33, 8, 0, 4, -92, 23, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:39:19.162  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 16:39:19.163  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 16:39:19.164  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:39:19.165  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-12 16:39:19.166  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 16:39:19.166  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 16:39:19.167  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:39:20.663  2697  2697 D BtGatt.ScanManager: awakened up at time 734250
08-12 16:39:20.666  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:20.676  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 16:39:20.676  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:22.179  2697  2697 D BtGatt.ScanManager: awakened up at time 735767
,08-12 16:39:22.183  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:22.242  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-12 16:39:22.242  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:39:22.243  2697  2748 D BtGatt.GattService: current time is 735830810759
,08-12 16:39:22.244  2697  2748 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -89, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 85, -113, -37, 31, -33, 8, 0, 4, -98, 7, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -63, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -65, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,08-12 16:39:22.245  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:39:22.246  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-12 16:39:22.246  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:39:22.247  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-12 16:39:22.248  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 16:39:23.746  2697  2697 D BtGatt.ScanManager: awakened up at time 737333
,08-12 16:39:23.748  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:23.792  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-12 16:39:23.793  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:39:23.794  2697  2748 D BtGatt.GattService: current time is 737381814820
,08-12 16:39:23.794  2697  2748 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -64, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -91, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -72, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -65, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -80, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -65, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
08-12 16:39:23.796  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 16:39:23.796  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-12 16:39:23.797  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:39:23.797  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:39:23.798  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:39:23.799  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 16:39:25.297  2697  2697 D BtGatt.ScanManager: awakened up at time 738885
,08-12 16:39:25.300  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:25.311  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:39:25.311  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:26.814  2697  2697 D BtGatt.ScanManager: awakened up at time 740401
,08-12 16:39:26.816  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:26.850  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-12 16:39:26.850  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:39:26.852  2697  2748 D BtGatt.GattService: current time is 740440041479
,08-12 16:39:26.853  2697  2748 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -64, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -88, 1, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -90, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
,08-12 16:39:26.857  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-12 16:39:26.859  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 16:39:26.861  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:39:26.865  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:39:28.354  2697  2697 D BtGatt.ScanManager: awakened up at time 741942
,08-12 16:39:28.357  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:28.410  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-12 16:39:28.411  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:39:28.413  2697  2748 D BtGatt.GattService: current time is 742000645540
,08-12 16:39:28.414  2697  2748 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -91, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -80, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -65, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 85, -113, -37, 31, -33, 8, 0, 4, -89, 10, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -90, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 16:39:28.415  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-12 16:39:28.416  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-12 16:39:28.417  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 16:39:28.418  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:39:28.419  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-12 16:39:28.420  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:39:28.421  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 16:39:29.913  2697  2697 D BtGatt.ScanManager: awakened up at time 743501
,08-12 16:39:29.915  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:29.929  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:39:29.929  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:31.444  2697  2697 D BtGatt.ScanManager: awakened up at time 745032
,08-12 16:39:31.449  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:31.474  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:39:31.474  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:31.833  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:39:31.862  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:39:31.867  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:39:31.924  1513  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 16:39:31.924  1513  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 16:39:31.924  1513  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 16:39:31.924  1513  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:39:31.956  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 16:39:31.956  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 16:39:31.957  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-12 16:39:32.962  2697  2697 D BtGatt.ScanManager: awakened up at time 746550
,08-12 16:39:32.965  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:33.017  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-12 16:39:33.018  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:39:33.018  2697  2748 D BtGatt.GattService: current time is 746606195374
,08-12 16:39:33.019  2697  2748 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, 4, -84, 3, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 81, 34, 97, 112, -14, -5, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -91, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -81, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 16:39:33.020  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 16:39:33.021  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:39:33.021  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 16:39:33.022  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:39:33.023  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:39:33.024  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 16:39:33.024  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 16:39:34.522  2697  2697 D BtGatt.ScanManager: awakened up at time 748109
08-12 16:39:34.524  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:34.536  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:39:34.536  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:36.038  2697  2697 D BtGatt.ScanManager: awakened up at time 749625
,08-12 16:39:36.041  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:36.055  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:39:36.056  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:37.561  2697  2697 D BtGatt.ScanManager: awakened up at time 751148
,08-12 16:39:37.564  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:37.615  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-12 16:39:37.616  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:37.616  2697  2748 D BtGatt.GattService: current time is 751204160832
,08-12 16:39:37.618  2697  2748 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -94, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -88, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -81, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -66, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
08-12 16:39:37.619  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-12 16:39:37.620  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 16:39:37.621  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 16:39:37.622  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:39:37.623  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:39:37.624  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 16:39:39.119  2697  2697 D BtGatt.ScanManager: awakened up at time 752707
,08-12 16:39:39.123  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:39.174  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
08-12 16:39:39.174  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:39.176  2697  2748 D BtGatt.GattService: current time is 752763937863
,08-12 16:39:39.177  2697  2748 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -72, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, 4, -87, 27, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 81, 34, 97, 112, -14, -5, 1, -128, -82, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -81, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 16:39:39.178  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 16:39:39.179  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:39:39.180  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:39:39.181  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 16:39:40.678  2697  2697 D BtGatt.ScanManager: awakened up at time 754266
,08-12 16:39:40.683  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:40.692  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:39:40.692  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:42.197  2697  2697 D BtGatt.ScanManager: awakened up at time 755785
,08-12 16:39:42.200  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:42.252  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 16:39:42.252  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:42.253  2697  2748 D BtGatt.GattService: current time is 755840852961
,08-12 16:39:42.254  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, -128, -101, 1, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 35, 97, 126, -92, 22, -56, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -89, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -90, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -91, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:39:42.255  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,08-12 16:39:42.256  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-12 16:39:42.256  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:39:42.257  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-12 16:39:42.258  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 16:39:42.259  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:39:43.755  2697  2697 D BtGatt.ScanManager: awakened up at time 757343
,08-12 16:39:43.758  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:43.813  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 16:39:43.813  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:39:43.813  2697  2748 D BtGatt.GattService: current time is 757401453637
,08-12 16:39:43.814  2697  2748 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -66, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -82, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -83, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -91, 21, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -69, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -92, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:39:43.816  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 16:39:43.818  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 16:39:43.820  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 16:39:43.822  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:39:43.824  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:39:43.826  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:39:45.316  2697  2697 D BtGatt.ScanManager: awakened up at time 758904
,08-12 16:39:45.318  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:45.331  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:39:45.331  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:46.834  2697  2697 D BtGatt.ScanManager: awakened up at time 760422
,08-12 16:39:46.837  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:46.871  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-12 16:39:46.871  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:46.873  2697  2748 D BtGatt.GattService: current time is 760460761338
08-12 16:39:46.873  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, -128, -88, 5, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, -46, -4, -117, 6, 105, -37, 1, -128, -81, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
,08-12 16:39:46.874  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
08-12 16:39:46.875  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:39:48.376  2697  2697 D BtGatt.ScanManager: awakened up at time 761963
,08-12 16:39:48.382  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:48.432  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-12 16:39:48.432  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:48.436  2697  2748 D BtGatt.GattService: current time is 762023859775
,08-12 16:39:48.437  2697  2748 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -64, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -89, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, -128, -69, 14, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 116, -43, -111, -91, -20, -29, 1, -128, -86, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -81, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 16:39:48.438  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:39:48.439  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:39:48.440  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:39:48.441  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,08-12 16:39:48.442  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 16:39:48.443  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 16:39:48.444  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 16:39:49.935  2697  2697 D BtGatt.ScanManager: awakened up at time 763523
,08-12 16:39:49.938  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:49.952  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 16:39:49.953  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:51.454  2697  2697 D BtGatt.ScanManager: awakened up at time 765041
,08-12 16:39:51.458  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:51.470  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:39:51.471  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:52.986  2697  2697 D BtGatt.ScanManager: awakened up at time 766574
,08-12 16:39:52.988  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:53.061  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,08-12 16:39:53.061  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:39:53.062  2697  2748 D BtGatt.GattService: current time is 766649574558
,08-12 16:39:53.063  2697  2748 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -92, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -82, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -72, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -66, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -81, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, 4, -103, 8, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -81, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:39:53.064  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 16:39:53.065  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 16:39:53.066  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 16:39:53.067  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-12 16:39:53.067  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 16:39:53.068  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:39:53.069  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:39:53.069  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 16:39:53.308  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:39:53.330  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:39:53.338  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:39:53.436  1513  3623 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 16:39:53.437  1513  3623 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 16:39:53.438  1513  3623 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:39:53.438  1513  3623 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:39:53.505  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 16:39:53.506  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 16:39:53.508  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-12 16:39:54.564  2697  2697 D BtGatt.ScanManager: awakened up at time 768151
,08-12 16:39:54.567  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:54.577  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 16:39:54.577  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:56.080  2697  2697 D BtGatt.ScanManager: awakened up at time 769667
,08-12 16:39:56.082  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:56.094  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 16:39:56.094  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:57.597  2697  2697 D BtGatt.ScanManager: awakened up at time 771185
,08-12 16:39:57.600  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:57.654  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-12 16:39:57.654  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:57.654  2697  2748 D BtGatt.GattService: current time is 771242545849
08-12 16:39:57.656  2697  2748 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -89, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -91, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, -128, -104, 11, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 116, -43, -111, -91, -20, -29, 1, -128, -66, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 85, -113, -37, 31, -33, 8, 0, -128, -105, 0, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0]
08-12 16:39:57.656  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-12 16:39:57.657  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:39:57.658  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:39:57.659  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
08-12 16:39:57.660  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 16:39:57.661  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-12 16:39:57.662  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,08-12 16:39:59.156  2697  2697 D BtGatt.ScanManager: awakened up at time 772743
,08-12 16:39:59.161  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:39:59.191  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-12 16:39:59.191  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:39:59.191  2697  2748 D BtGatt.GattService: current time is 772779536992
08-12 16:39:59.192  2697  2748 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -89, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -83, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -71, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,08-12 16:39:59.194  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-12 16:39:59.195  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:39:59.197  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:39:59.198  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 16:40:00.700  2697  2697 D BtGatt.ScanManager: awakened up at time 774287
,08-12 16:40:00.703  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:00.714  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:40:00.714  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:02.216  2697  2697 D BtGatt.ScanManager: awakened up at time 775804
,08-12 16:40:02.219  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:02.272  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-12 16:40:02.273  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:02.274  2697  2748 D BtGatt.GattService: current time is 775862120788
,08-12 16:40:02.275  2697  2748 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -66, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 85, -113, -37, 31, -33, 8, 0, 4, -92, 4, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -90, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:40:02.276  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 16:40:02.277  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:40:02.278  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-12 16:40:02.279  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:40:02.280  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:40:03.775  2697  2697 D BtGatt.ScanManager: awakened up at time 777363
,08-12 16:40:03.778  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:03.826  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-12 16:40:03.826  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:03.827  2697  2748 D BtGatt.GattService: current time is 777414850162
08-12 16:40:03.828  2697  2748 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -68, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -80, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, 4, -92, 24, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 81, 34, 97, 112, -14, -5, 1, -128, -82, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -81, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -65, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -92, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:40:03.829  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 16:40:03.830  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 16:40:03.831  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:40:03.832  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 16:40:03.833  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 16:40:03.833  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-12 16:40:03.834  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:40:05.333  2697  2697 D BtGatt.ScanManager: awakened up at time 778921
08-12 16:40:05.336  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:05.346  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 16:40:05.346  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:06.846  2697  2697 D BtGatt.ScanManager: awakened up at time 780434
,08-12 16:40:06.850  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:06.874  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-12 16:40:06.874  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:40:06.874  2697  2748 D BtGatt.GattService: current time is 780462159111
,08-12 16:40:06.874  2697  2748 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -64, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -89, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -91, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
,08-12 16:40:06.875  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 16:40:06.875  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-12 16:40:06.875  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:40:08.381  2697  2697 D BtGatt.ScanManager: awakened up at time 781968
,08-12 16:40:08.386  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:08.432  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-12 16:40:08.432  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:40:08.433  2697  2748 D BtGatt.GattService: current time is 782020849787
,08-12 16:40:08.434  2697  2748 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, 4, -93, 6, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -81, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -81, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -64, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -92, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -91, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
08-12 16:40:08.435  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:40:08.436  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:40:08.437  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:40:08.437  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 16:40:08.438  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 16:40:08.439  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 16:40:08.440  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:40:09.936  2697  2697 D BtGatt.ScanManager: awakened up at time 783524
,08-12 16:40:09.938  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:09.952  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:40:09.952  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:11.452  2697  2697 D BtGatt.ScanManager: awakened up at time 785040
,08-12 16:40:11.455  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:11.465  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:40:11.466  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:12.973  2697  2697 D BtGatt.ScanManager: awakened up at time 786561
,08-12 16:40:12.976  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:13.027  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-12 16:40:13.027  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:40:13.028  2697  2748 D BtGatt.GattService: current time is 786616005297
08-12 16:40:13.029  2697  2748 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -85, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -99, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, -128, -75, 10, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 71, -122, -77, 84, 69, -12, 1, -128, -71, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -85, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -83, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -90, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
,08-12 16:40:13.030  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:40:13.031  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:40:13.032  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
08-12 16:40:13.033  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 16:40:13.034  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 16:40:13.035  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-12 16:40:13.036  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:40:14.550  2697  2697 D BtGatt.ScanManager: awakened up at time 788137
,08-12 16:40:14.593  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:14.616  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-12 16:40:14.616  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:14.616  2697  2748 D BtGatt.GattService: current time is 788204015456
08-12 16:40:14.616  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -94, 31, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:40:14.616  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:40:14.910  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:40:14.928  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:40:14.934  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 16:40:15.017  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 16:40:15.018  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-12 16:40:15.018  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 16:40:15.019  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 16:40:15.082  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 16:40:15.083  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 16:40:15.087  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-12 16:40:16.122  2697  2697 D BtGatt.ScanManager: awakened up at time 789710
08-12 16:40:16.124  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:16.136  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:40:16.136  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:17.641  2697  2697 D BtGatt.ScanManager: awakened up at time 791228
,08-12 16:40:17.643  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:17.697  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 16:40:17.697  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:17.698  2697  2748 D BtGatt.GattService: current time is 791285629877
,08-12 16:40:17.699  2697  2748 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -85, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -76, 4, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 37, -47, 14, -113, 116, -46, 1, -128, -66, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -92, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:40:17.700  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 16:40:17.701  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 16:40:17.701  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:40:17.703  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
08-12 16:40:17.703  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-12 16:40:17.704  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:40:19.200  2697  2697 D BtGatt.ScanManager: awakened up at time 792787
08-12 16:40:19.202  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:19.235  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
08-12 16:40:19.236  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:40:19.236  2697  2748 D BtGatt.GattService: current time is 792824102374
08-12 16:40:19.237  2697  2748 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -82, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -82, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 16:40:19.238  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 16:40:19.239  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 16:40:19.239  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 16:40:20.738  2697  2697 D BtGatt.ScanManager: awakened up at time 794325
,08-12 16:40:20.741  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:20.753  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:40:20.753  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:22.255  2697  2697 D BtGatt.ScanManager: awakened up at time 795843
,08-12 16:40:22.260  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:22.311  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-12 16:40:22.311  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:22.312  2697  2748 D BtGatt.GattService: current time is 795899741535
,08-12 16:40:22.313  2697  2748 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -73, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -80, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -91, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -63, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, -128, -88, 9, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 71, -122, -77, 84, 69, -12, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -82, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,08-12 16:40:22.314  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-12 16:40:22.314  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 16:40:22.315  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 16:40:22.316  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 16:40:22.317  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
08-12 16:40:22.318  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:40:22.319  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-12 16:40:23.816  2697  2697 D BtGatt.ScanManager: awakened up at time 797404
,08-12 16:40:23.818  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:23.873  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-12 16:40:23.873  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:23.874  2697  2748 D BtGatt.GattService: current time is 797461759659
08-12 16:40:23.875  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -91, 18, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -92, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -81, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -72, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -84, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:40:23.876  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:40:23.877  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 16:40:23.878  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 16:40:23.879  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-12 16:40:23.880  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:40:25.377  2697  2697 D BtGatt.ScanManager: awakened up at time 798964
,08-12 16:40:25.381  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:25.391  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:40:25.391  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:26.895  2697  2697 D BtGatt.ScanManager: awakened up at time 800482
,08-12 16:40:26.902  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:26.931  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-12 16:40:26.931  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:26.932  2697  2748 D BtGatt.GattService: current time is 800519850693
,08-12 16:40:26.933  2697  2748 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -101, 2, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -90, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
08-12 16:40:26.934  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 16:40:26.935  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:40:26.936  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:40:28.433  2697  2697 D BtGatt.ScanManager: awakened up at time 802021
,08-12 16:40:28.436  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:28.485  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-12 16:40:28.485  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:28.486  2697  2748 D BtGatt.GattService: current time is 802073741004
,08-12 16:40:28.487  2697  2748 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -100, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -91, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -64, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 85, -113, -37, 31, -33, 8, 0, 4, -101, 10, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 116, -43, -111, -91, -20, -29, 1, -128, -83, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -89, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 16:40:28.487  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 16:40:28.489  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-12 16:40:28.490  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-12 16:40:28.490  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:40:28.491  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 16:40:28.492  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 16:40:28.493  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 16:40:29.989  2697  2697 D BtGatt.ScanManager: awakened up at time 803576
,08-12 16:40:29.992  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:30.003  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 16:40:30.004  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:31.506  2697  2697 D BtGatt.ScanManager: awakened up at time 805094
,08-12 16:40:31.509  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:31.521  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:40:31.521  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:33.025  2697  2697 D BtGatt.ScanManager: awakened up at time 806612
,08-12 16:40:33.028  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:33.076  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-12 16:40:33.076  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:33.077  2697  2748 D BtGatt.GattService: current time is 806664591982
08-12 16:40:33.078  2697  2748 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -85, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -81, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 85, -113, -37, 31, -33, 8, 0, 4, -72, 3, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -72, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -84, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -82, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
,08-12 16:40:33.079  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:40:33.080  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 16:40:33.081  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:40:33.082  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:40:33.083  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:40:33.084  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 16:40:33.085  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-12 16:40:34.582  2697  2697 D BtGatt.ScanManager: awakened up at time 808169
,08-12 16:40:34.584  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:34.597  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:40:34.597  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:36.102  2697  2697 D BtGatt.ScanManager: awakened up at time 809689
,08-12 16:40:36.104  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:36.114  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:40:36.115  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:37.618  2697  2697 D BtGatt.ScanManager: awakened up at time 811205
,08-12 16:40:37.621  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:37.673  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-12 16:40:37.674  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:37.674  2697  2748 D BtGatt.GattService: current time is 811262186659
,08-12 16:40:37.675  2697  2748 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -92, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -81, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 85, -113, -37, 31, -33, 8, 0, 4, -73, 7, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -81, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -80, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -81, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:40:37.676  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 16:40:37.677  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 16:40:37.678  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-12 16:40:37.679  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:40:37.680  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:40:37.681  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 16:40:37.682  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 16:40:39.176  2697  2697 D BtGatt.ScanManager: awakened up at time 812764
,08-12 16:40:39.179  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:39.215  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-12 16:40:39.215  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:40:39.216  2697  2748 D BtGatt.GattService: current time is 812803575979
,08-12 16:40:39.216  2697  2748 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, -128, -90, 27, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, -46, -4, -117, 6, 105, -37, 1, -128, -91, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -83, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:40:39.217  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
08-12 16:40:39.218  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-12 16:40:39.219  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 16:40:40.718  2697  2697 D BtGatt.ScanManager: awakened up at time 814305
,08-12 16:40:40.721  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:40.731  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:40:40.732  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:42.237  2697  2697 D BtGatt.ScanManager: awakened up at time 815824
,08-12 16:40:42.239  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:42.292  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 16:40:42.292  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:42.293  2697  2748 D BtGatt.GattService: current time is 815881003421
08-12 16:40:42.294  2697  2748 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -85, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 85, -113, -37, 31, -33, 8, 0, 4, -101, 0, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -89, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -99, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -71, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
08-12 16:40:42.295  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 16:40:42.296  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-12 16:40:42.297  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-12 16:40:42.298  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 16:40:42.298  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:40:42.299  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 16:40:43.795  2697  2697 D BtGatt.ScanManager: awakened up at time 817383
08-12 16:40:43.798  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:43.829  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-12 16:40:43.830  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:43.830  2697  2748 D BtGatt.GattService: current time is 817418049772
08-12 16:40:43.830  2697  2748 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -69, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -64, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0],
08-12 16:40:43.831  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-12 16:40:43.833  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 16:40:43.833  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-12 16:40:45.332  2697  2697 D BtGatt.ScanManager: awakened up at time 818920
08-12 16:40:45.335  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:45.347  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 16:40:45.347  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:46.851  2697  2697 D BtGatt.ScanManager: awakened up at time 820438
,08-12 16:40:46.853  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:46.887  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-12 16:40:46.887  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:40:46.888  2697  2748 D BtGatt.GattService: current time is 820475620858
,08-12 16:40:46.888  2697  2748 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -84, 5, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0]
08-12 16:40:46.889  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-12 16:40:46.890  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 16:40:46.891  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:40:46.892  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,08-12 16:40:48.391  2697  2697 D BtGatt.ScanManager: awakened up at time 821978
,08-12 16:40:48.393  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:48.447  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-12 16:40:48.447  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:40:48.448  2697  2748 D BtGatt.GattService: current time is 822035848253
,08-12 16:40:48.449  2697  2748 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -73, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -83, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, -128, -66, 13, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 35, 97, 126, -92, 22, -56, 1, -128, -63, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -81, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -82, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 16:40:48.451  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-12 16:40:48.452  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 16:40:48.453  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
08-12 16:40:48.454  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-12 16:40:48.455  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 16:40:48.456  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:40:48.457  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 16:40:49.952  2697  2697 D BtGatt.ScanManager: awakened up at time 823539
08-12 16:40:49.954  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:40:49.965  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:40:49.965  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:50.954  3787  3836 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-12 16:40:50.954  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 16:40:50.955  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 16:40:50.955  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should affect listening to advertisements only
08-12 16:40:50.955  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 16:40:50.956  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-12 16:40:50.959  3787  3836 D BluetoothAdapter: STATE_ON
08-12 16:40:50.962  2697  2708 D BtGatt.GattService: stopScan() - queue size =1
08-12 16:40:50.965  2697  4066 D BtGatt.GattService: unregisterClient() - clientIf=5
08-12 16:40:50.966  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 16:40:50.967  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 16:40:50.967  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-12 16:40:50.967  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-12 16:40:50.967  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-12 16:40:50.971  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 16:40:50.972  2697  2697 D BtGatt.ScanManager: awakened up at time 824560
08-12 16:40:50.972  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 16:40:50.983  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-12 16:40:50.983  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:40:50.984  2697  2752 D BtGatt.ScanManager: stopping BLe Batch
08-12 16:40:50.997  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-12 16:40:50.998  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:40:50.998  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-12 16:40:51.007  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 16:40:51.008  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:40:51.474  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 16:40:51.474  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 16:40:51.475  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:40:51.481  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 16:40:51.481  3787  3836 I jxcore-log: 
,08-12 16:40:51.495  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 16:40:51.496  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 16:40:51.496  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 16:40:51.497  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-12 16:40:51.497  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-12 16:40:51.497  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-12 16:40:51.497  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-12 16:40:51.499  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-12 16:40:51.500  3787  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-12 16:40:51.500  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-12 16:40:51.500  3787  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-12 16:40:51.501  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-12 16:40:51.501  3787  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-12 16:40:51.501  3787  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-12 16:40:51.501  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-12 16:40:51.502  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-12 16:40:51.509  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 16:40:51.509  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-12 16:40:51.509  3787  3787 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-12 16:40:51.535  3787  3836 I jxcore-log: not ok 179 Peer made successful https requests to all peers
08-12 16:40:51.535  3787  3836 I jxcore-log: 
,08-12 16:40:51.536  3787  3836 I jxcore-log:   ---
08-12 16:40:51.536  3787  3836 I jxcore-log: 
08-12 16:40:51.536  3787  3836 I jxcore-log:     operator: ok
08-12 16:40:51.536  3787  3836 I jxcore-log: 
08-12 16:40:51.537  3787  3836 I jxcore-log:     expected: true
08-12 16:40:51.537  3787  3836 I jxcore-log: 
,08-12 16:40:51.537  3787  3836 I jxcore-log:     actual:   false
08-12 16:40:51.537  3787  3836 I jxcore-log: 
08-12 16:40:51.537  3787  3836 I jxcore-log:   ...
08-12 16:40:51.537  3787  3836 I jxcore-log: 
,08-12 16:40:51.539  3787  3836 I jxcore-log: ok 180 Peer received right amount of https requests
08-12 16:40:51.539  3787  3836 I jxcore-log: 
,08-12 16:40:51.540  3787  3836 I jxcore-log: ok 181 HTTPS server received zero PSK Identities. Count:0
08-12 16:40:51.540  3787  3836 I jxcore-log: 
,08-12 16:40:51.544  3787  3836 I jxcore-log: # teardown
08-12 16:40:51.544  3787  3836 I jxcore-log: 
,08-12 16:40:51.958  3787  3836 I jxcore-log: INFO testThaliNotification: Participants:2 Peers Replied to us:0 Peers requested to:1
08-12 16:40:51.958  3787  3836 I jxcore-log: 
,08-12 16:40:51.982  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
08-12 16:40:51.982  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 16:40:51.982  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 16:40:51.983  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:40:51.985  3787  3836 I jxcore-log: # setup
08-12 16:40:51.985  3787  3836 I jxcore-log: 
,08-12 16:40:51.986  3787  3836 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 16:40:51.986  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 16:40:51.986  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 16:40:51.986  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:40:52.104  3787  3836 I jxcore-log: # 55. Test BEACONS_RETRIEVED_AND_PARSED locally
08-12 16:40:52.104  3787  3836 I jxcore-log: 
,08-12 16:40:52.433  3787  3836 I jxcore-log: ok 182 peerIdentifier should be identifier
08-12 16:40:52.433  3787  3836 I jxcore-log: 
,08-12 16:40:52.434  3787  3836 I jxcore-log: ok 183 Response should be BEACONS_RETRIEVED_AND_PARSED
08-12 16:40:52.434  3787  3836 I jxcore-log: 
08-12 16:40:52.435  3787  3836 I jxcore-log: ok 184 good beacon
08-12 16:40:52.435  3787  3836 I jxcore-log: 
,08-12 16:40:52.435  3787  3836 I jxcore-log: ok 185 good preAmble
08-12 16:40:52.435  3787  3836 I jxcore-log: 
08-12 16:40:52.437  3787  3836 I jxcore-log: ok 186 public keys match!
08-12 16:40:52.437  3787  3836 I jxcore-log: 
,08-12 16:40:52.441  3787  3836 I jxcore-log: ok 187 must return null after successful call
08-12 16:40:52.441  3787  3836 I jxcore-log: 
,08-12 16:40:52.442  3787  3836 I jxcore-log: ok 188 Once start returns the action should be in KILLED state
08-12 16:40:52.442  3787  3836 I jxcore-log: 
,08-12 16:40:52.455  3787  3836 I jxcore-log: # teardown
08-12 16:40:52.455  3787  3836 I jxcore-log: 
,08-12 16:40:52.479  3787  3836 I jxcore-log: # setup
08-12 16:40:52.479  3787  3836 I jxcore-log: 
,08-12 16:40:52.624  3787  3836 I jxcore-log: # 56. Test HTTP_BAD_RESPONSE locally
08-12 16:40:52.624  3787  3836 I jxcore-log: 
,08-12 16:40:52.821  3787  3836 I jxcore-log: ok 189 Response should be HTTP_BAD_RESPONSE
08-12 16:40:52.821  3787  3836 I jxcore-log: 
,08-12 16:40:52.824  3787  3836 I jxcore-log: ok 190 must return null after successful call
08-12 16:40:52.824  3787  3836 I jxcore-log: 
,08-12 16:40:52.840  3787  3836 I jxcore-log: # teardown
08-12 16:40:52.840  3787  3836 I jxcore-log: 
,08-12 16:40:52.866  3787  3836 I jxcore-log: # setup
08-12 16:40:52.866  3787  3836 I jxcore-log: 
,08-12 16:40:53.014  3787  3836 I jxcore-log: # 57. Test NETWORK_PROBLEM locally
08-12 16:40:53.014  3787  3836 I jxcore-log: 
,08-12 16:40:53.154  3787  3836 I jxcore-log: ok 191 Response should be NETWORK_PROBLEM
08-12 16:40:53.154  3787  3836 I jxcore-log: 
,08-12 16:40:53.164  3787  3836 I jxcore-log: ok 192 reject reason should be: Could not establish TCP connection
08-12 16:40:53.164  3787  3836 I jxcore-log: 
,08-12 16:40:53.189  3787  3836 I jxcore-log: # teardown
08-12 16:40:53.189  3787  3836 I jxcore-log: 
,08-12 16:40:53.220  3787  3836 I jxcore-log: # setup
08-12 16:40:53.220  3787  3836 I jxcore-log: 
,08-12 16:40:53.381  3787  3836 I jxcore-log: # 58. Call the start two times
08-12 16:40:53.381  3787  3836 I jxcore-log: 
,08-12 16:40:53.513  3787  3836 I jxcore-log: ok 193 Call start once
08-12 16:40:53.513  3787  3836 I jxcore-log: 
,08-12 16:40:53.643  3787  3836 I jxcore-log: ok 194 Response should be BEACONS_RETRIEVED_AND_PARSED
08-12 16:40:53.643  3787  3836 I jxcore-log: 
,08-12 16:40:53.645  3787  3836 I jxcore-log: ok 195 must return null after successful call.
08-12 16:40:53.645  3787  3836 I jxcore-log: 
,08-12 16:40:53.658  3787  3836 I jxcore-log: # teardown
08-12 16:40:53.658  3787  3836 I jxcore-log: 
,08-12 16:40:53.684  3787  3836 I jxcore-log: # setup
08-12 16:40:53.684  3787  3836 I jxcore-log: 
,08-12 16:40:53.824  3787  3836 I jxcore-log: # 59. Call the kill before calling the start
08-12 16:40:53.824  3787  3836 I jxcore-log: 
,08-12 16:40:53.921  3787  3836 I jxcore-log: ok 196 Should be Killed
08-12 16:40:53.921  3787  3836 I jxcore-log: 
,08-12 16:40:53.923  3787  3836 I jxcore-log: ok 197 Start after killed
08-12 16:40:53.923  3787  3836 I jxcore-log: 
,08-12 16:40:53.928  3787  3836 I jxcore-log: # teardown
08-12 16:40:53.928  3787  3836 I jxcore-log: 
,08-12 16:40:53.968  3787  3836 I jxcore-log: # setup
08-12 16:40:53.968  3787  3836 I jxcore-log: 
,08-12 16:40:54.097  3787  3836 I jxcore-log: # 60. Call the kill immediately after the start
08-12 16:40:54.097  3787  3836 I jxcore-log: 
,08-12 16:40:54.185  3787  3836 I jxcore-log: ok 198 Should be KILLED
08-12 16:40:54.185  3787  3836 I jxcore-log: 
,08-12 16:40:54.186  3787  3836 I jxcore-log: ok 199 must return null after successful kill
08-12 16:40:54.186  3787  3836 I jxcore-log: 
,08-12 16:40:54.190  3787  3836 I jxcore-log: # teardown
08-12 16:40:54.190  3787  3836 I jxcore-log: 
,08-12 16:40:54.222  3787  3836 I jxcore-log: # setup
08-12 16:40:54.222  3787  3836 I jxcore-log: 
,08-12 16:40:54.353  3787  3836 I jxcore-log: # 61. Call the kill while waiting a response from the server
08-12 16:40:54.353  3787  3836 I jxcore-log: 
,08-12 16:40:56.470  3787  3836 I jxcore-log: ok 200 Should be KILLED
08-12 16:40:56.470  3787  3836 I jxcore-log: 
,08-12 16:40:56.483  3787  3836 I jxcore-log: ok 201 must return null after successful kill
08-12 16:40:56.483  3787  3836 I jxcore-log: 
,08-12 16:40:56.503  3787  3836 I jxcore-log: # teardown
08-12 16:40:56.503  3787  3836 I jxcore-log: 
,08-12 16:40:56.580  3787  3836 I jxcore-log: # setup
08-12 16:40:56.580  3787  3836 I jxcore-log: 
,08-12 16:40:56.733  3787  3836 I jxcore-log: # 62. Test to exceed the max content size locally
08-12 16:40:56.733  3787  3836 I jxcore-log: 
,08-12 16:40:56.968  3787  3836 I jxcore-log: ok 202 HTTP_BAD_RESPONSE should be response when content size is exceeded
08-12 16:40:56.968  3787  3836 I jxcore-log: 
,08-12 16:40:56.977  3787  3836 I jxcore-log: ok 203 must return null after successful call
08-12 16:40:56.977  3787  3836 I jxcore-log: 
,08-12 16:40:56.990  3787  3836 I jxcore-log: # teardown
08-12 16:40:56.990  3787  3836 I jxcore-log: 
,08-12 16:40:57.059  3787  3836 I jxcore-log: # setup
08-12 16:40:57.059  3787  3836 I jxcore-log: 
,08-12 16:40:57.184  3787  3836 I jxcore-log: # 63. Close the server socket while the client is waiting a response from the server. Local test.
08-12 16:40:57.184  3787  3836 I jxcore-log: 
,08-12 16:40:59.317  3787  3836 I jxcore-log: ok 204 Should be NETWORK_PROBLEM caused closing server socket
08-12 16:40:59.317  3787  3836 I jxcore-log: 
,08-12 16:40:59.324  3787  3836 I jxcore-log: ok 205 Should be Could not establish TCP connection
08-12 16:40:59.324  3787  3836 I jxcore-log: 
,08-12 16:40:59.331  3787  3836 I jxcore-log: # teardown
08-12 16:40:59.331  3787  3836 I jxcore-log: 
,08-12 16:40:59.447  3787  3836 I jxcore-log: # setup
08-12 16:40:59.447  3787  3836 I jxcore-log: 
,08-12 16:40:59.584  3787  3836 I jxcore-log: # 64. Close the client socket while the client is waiting a response from the server. Local test.
08-12 16:40:59.584  3787  3836 I jxcore-log: 
,08-12 16:41:01.728  3787  3836 I jxcore-log: ok 206 Should be NETWORK_PROBLEM caused closing client socket
08-12 16:41:01.728  3787  3836 I jxcore-log: 
,08-12 16:41:01.742  3787  3836 I jxcore-log: ok 207 Should be Could not establish TCP connection
08-12 16:41:01.742  3787  3836 I jxcore-log: 
,08-12 16:41:01.756  3787  3836 I jxcore-log: # teardown
08-12 16:41:01.756  3787  3836 I jxcore-log: 
,08-12 16:41:01.829  3787  3836 I jxcore-log: # setup
08-12 16:41:01.829  3787  3836 I jxcore-log: 
,08-12 16:41:01.884  3787  3836 I jxcore-log: # 65. #generatePreambleAndBeacons bad args
08-12 16:41:01.884  3787  3836 I jxcore-log: 
,08-12 16:41:01.965  3787  3836 I jxcore-log: ok 208 publicKeysToNotify cannot be null
08-12 16:41:01.965  3787  3836 I jxcore-log: 
,08-12 16:41:01.969  3787  3836 I jxcore-log: ok 209 ecdh for local device cannot be null
08-12 16:41:01.969  3787  3836 I jxcore-log: 
,08-12 16:41:01.970  3787  3836 I jxcore-log: ok 210 milliseconds cannot be less than 0
08-12 16:41:01.970  3787  3836 I jxcore-log: 
,08-12 16:41:01.972  3787  3836 I jxcore-log: ok 211 milliseconds cannot be 0
08-12 16:41:01.972  3787  3836 I jxcore-log: 
,08-12 16:41:01.974  3787  3836 I jxcore-log: ok 212 milliseconds cannot be greater than one_day
08-12 16:41:01.974  3787  3836 I jxcore-log: 
08-12 16:41:01.976  3787  3836 I jxcore-log: # teardown
08-12 16:41:01.976  3787  3836 I jxcore-log: 
,08-12 16:41:02.030  3787  3836 I jxcore-log: # setup
08-12 16:41:02.030  3787  3836 I jxcore-log: 
,08-12 16:41:02.078  3787  3836 I jxcore-log: # 66. #generatePreambleAndBeacons empty keys to notify
08-12 16:41:02.078  3787  3836 I jxcore-log: 
,08-12 16:41:02.170  3787  3836 I jxcore-log: ok 213 should be equal
08-12 16:41:02.170  3787  3836 I jxcore-log: 
,08-12 16:41:02.173  3787  3836 I jxcore-log: # teardown
08-12 16:41:02.173  3787  3836 I jxcore-log: 
,08-12 16:41:02.211  3787  3836 I jxcore-log: # setup
08-12 16:41:02.211  3787  3836 I jxcore-log: 
,08-12 16:41:02.274  3787  3836 I jxcore-log: # 67. #generatePreambleAndBeacons multiple keys to notify
08-12 16:41:02.274  3787  3836 I jxcore-log: 
,08-12 16:41:02.438  3787  3836 I jxcore-log: ok 214 should be equal
08-12 16:41:02.438  3787  3836 I jxcore-log: 
,08-12 16:41:02.438  3787  3836 I jxcore-log: ok 215 should be equal
08-12 16:41:02.438  3787  3836 I jxcore-log: 
08-12 16:41:02.439  3787  3836 I jxcore-log: ok 216 (unnamed assert)
08-12 16:41:02.439  3787  3836 I jxcore-log: 
08-12 16:41:02.439  3787  3836 I jxcore-log: ok 217 should be equal
08-12 16:41:02.439  3787  3836 I jxcore-log: 
08-12 16:41:02.441  3787  3836 I jxcore-log: # teardown
08-12 16:41:02.441  3787  3836 I jxcore-log: 
,08-12 16:41:02.573  3787  3836 I jxcore-log: # setup
08-12 16:41:02.573  3787  3836 I jxcore-log: 
,08-12 16:41:02.627  3787  3836 I jxcore-log: # 68. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
08-12 16:41:02.627  3787  3836 I jxcore-log: 
,08-12 16:41:02.699  3787  3836 I jxcore-log: ok 218 should throw
08-12 16:41:02.699  3787  3836 I jxcore-log: 
,08-12 16:41:02.702  3787  3836 I jxcore-log: # teardown
08-12 16:41:02.702  3787  3836 I jxcore-log: 
,08-12 16:41:02.780  3787  3836 I jxcore-log: # setup
08-12 16:41:02.780  3787  3836 I jxcore-log: 
,08-12 16:41:02.842  3787  3836 I jxcore-log: # 69. #parseBeacons invalid expiration in beaconStreamWithPreAmble
08-12 16:41:02.842  3787  3836 I jxcore-log: 
,08-12 16:41:02.923  3787  3836 I jxcore-log: ok 219 Preamble expiration must be a 64 bit integer
08-12 16:41:02.923  3787  3836 I jxcore-log: 
,08-12 16:41:02.925  3787  3836 I jxcore-log: # teardown
08-12 16:41:02.925  3787  3836 I jxcore-log: 
,08-12 16:41:03.009  3787  3836 I jxcore-log: # setup
08-12 16:41:03.009  3787  3836 I jxcore-log: 
,08-12 16:41:03.058  3787  3836 I jxcore-log: # 70. #parseBeacons expiration out of range lower
08-12 16:41:03.058  3787  3836 I jxcore-log: 
,08-12 16:41:03.149  3787  3836 I jxcore-log: ok 220 Expiration out of range
08-12 16:41:03.149  3787  3836 I jxcore-log: 
,08-12 16:41:03.151  3787  3836 I jxcore-log: # teardown
08-12 16:41:03.151  3787  3836 I jxcore-log: 
,08-12 16:41:03.219  3787  3836 I jxcore-log: # setup
08-12 16:41:03.219  3787  3836 I jxcore-log: 
,08-12 16:41:03.287  3787  3836 I jxcore-log: # 71. #parseBeacons expiration out of range lower
08-12 16:41:03.287  3787  3836 I jxcore-log: 
,08-12 16:41:03.410  3787  3836 I jxcore-log: ok 221 Expiration out of range
08-12 16:41:03.410  3787  3836 I jxcore-log: 
,08-12 16:41:03.412  3787  3836 I jxcore-log: # teardown
08-12 16:41:03.412  3787  3836 I jxcore-log: 
,08-12 16:41:03.469  3787  3836 I jxcore-log: # setup
08-12 16:41:03.469  3787  3836 I jxcore-log: 
,08-12 16:41:03.518  3787  3836 I jxcore-log: # 72. #parseBeacons no beacons returns null
08-12 16:41:03.518  3787  3836 I jxcore-log: 
,08-12 16:41:03.583  3787  3836 I jxcore-log: ok 222 should be equal
08-12 16:41:03.583  3787  3836 I jxcore-log: 
,08-12 16:41:03.585  3787  3836 I jxcore-log: # teardown
08-12 16:41:03.585  3787  3836 I jxcore-log: 
,08-12 16:41:03.645  3787  3836 I jxcore-log: # setup
08-12 16:41:03.645  3787  3836 I jxcore-log: 
,08-12 16:41:03.698  3787  3836 I jxcore-log: # 73. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
08-12 16:41:03.698  3787  3836 I jxcore-log: 
,08-12 16:41:03.778  3787  3836 I jxcore-log: ok 223 Malformed encrypted beacon key ID
08-12 16:41:03.778  3787  3836 I jxcore-log: 
,08-12 16:41:03.780  3787  3836 I jxcore-log: # teardown
08-12 16:41:03.780  3787  3836 I jxcore-log: 
,08-12 16:41:03.860  3787  3836 I jxcore-log: # setup
08-12 16:41:03.860  3787  3836 I jxcore-log: 
,08-12 16:41:03.927  3787  3836 I jxcore-log: # 74. #parseBeacons addressBookCallback fails decrypt
08-12 16:41:03.927  3787  3836 I jxcore-log: 
,08-12 16:41:04.116  3787  3836 I jxcore-log: ok 224 should be equal
08-12 16:41:04.116  3787  3836 I jxcore-log: 
,08-12 16:41:04.118  3787  3836 I jxcore-log: # teardown
08-12 16:41:04.118  3787  3836 I jxcore-log: 
,08-12 16:41:04.346  3787  3836 I jxcore-log: # setup
08-12 16:41:04.346  3787  3836 I jxcore-log: 
,08-12 16:41:04.392  3787  3836 I jxcore-log: # 75. #parseBeacons addressBookCallback returns no matches
08-12 16:41:04.392  3787  3836 I jxcore-log: 
,08-12 16:41:04.594  3787  3836 I jxcore-log: ok 225 should be equal
08-12 16:41:04.594  3787  3836 I jxcore-log: 
08-12 16:41:04.595  3787  3836 I jxcore-log: ok 226 should be equal
08-12 16:41:04.595  3787  3836 I jxcore-log: 
,08-12 16:41:04.596  3787  3836 I jxcore-log: # teardown
08-12 16:41:04.596  3787  3836 I jxcore-log: 
,08-12 16:41:04.758  3787  3836 I jxcore-log: # setup
08-12 16:41:04.758  3787  3836 I jxcore-log: 
,08-12 16:41:04.821  3787  3836 I jxcore-log: # 76. #parseBeacons addressBookCallback returns spurious match
08-12 16:41:04.821  3787  3836 I jxcore-log: 
,08-12 16:41:05.006  3787  3836 I jxcore-log: ok 227 should be equal
08-12 16:41:05.006  3787  3836 I jxcore-log: 
08-12 16:41:05.007  3787  3836 I jxcore-log: ok 228 should be equal
08-12 16:41:05.007  3787  3836 I jxcore-log: 
,08-12 16:41:05.008  3787  3836 I jxcore-log: # teardown
08-12 16:41:05.008  3787  3836 I jxcore-log: 
,08-12 16:41:05.370  3787  3836 I jxcore-log: # setup
08-12 16:41:05.370  3787  3836 I jxcore-log: 
,08-12 16:41:05.442  3787  3836 I jxcore-log: # 77. #parseBeacons addressBookCallback returns public key
08-12 16:41:05.442  3787  3836 I jxcore-log: 
,08-12 16:41:06.507  3787  3836 I jxcore-log: ok 229 right number of calls to address book
08-12 16:41:06.507  3787  3836 I jxcore-log: 
,08-12 16:41:06.507  3787  3836 I jxcore-log: ok 230 good preAmble
08-12 16:41:06.507  3787  3836 I jxcore-log: 
08-12 16:41:06.508  3787  3836 I jxcore-log: ok 231 good unencryptedKeyId
08-12 16:41:06.508  3787  3836 I jxcore-log: 
08-12 16:41:06.508  3787  3836 I jxcore-log: ok 232 good beacon
08-12 16:41:06.508  3787  3836 I jxcore-log: 
,08-12 16:41:06.510  3787  3836 I jxcore-log: # teardown
08-12 16:41:06.510  3787  3836 I jxcore-log: 
,08-12 16:41:06.647  3787  3836 I jxcore-log: # setup
08-12 16:41:06.647  3787  3836 I jxcore-log: 
,08-12 16:41:06.713  3787  3836 I jxcore-log: # 78. validate generatePskIdentityField
08-12 16:41:06.713  3787  3836 I jxcore-log: 
,08-12 16:41:06.793  3787  3836 I jxcore-log: ok 233 decoded buffers match
08-12 16:41:06.793  3787  3836 I jxcore-log: 
,08-12 16:41:06.795  3787  3836 I jxcore-log: # teardown
08-12 16:41:06.795  3787  3836 I jxcore-log: 
,08-12 16:41:06.828  3787  3836 I jxcore-log: # setup
08-12 16:41:06.828  3787  3836 I jxcore-log: 
,08-12 16:41:06.889  3787  3836 I jxcore-log: # 79. validate generatePskSecret
08-12 16:41:06.889  3787  3836 I jxcore-log: 
,08-12 16:41:07.004  3787  3836 I jxcore-log: ok 234 secrets match
08-12 16:41:07.004  3787  3836 I jxcore-log: 
,08-12 16:41:07.006  3787  3836 I jxcore-log: # teardown
08-12 16:41:07.006  3787  3836 I jxcore-log: 
,08-12 16:41:07.100  3787  3836 I jxcore-log: # setup
08-12 16:41:07.100  3787  3836 I jxcore-log: 
,08-12 16:41:07.140  3787  3836 I jxcore-log: # 80. validate generatePskSecrets
08-12 16:41:07.140  3787  3836 I jxcore-log: 
,08-12 16:41:07.318  3787  3836 I jxcore-log: ok 235 Matching numbers
08-12 16:41:07.318  3787  3836 I jxcore-log: 
,08-12 16:41:07.326  3787  3836 I jxcore-log: ok 236 We have an entry!
08-12 16:41:07.326  3787  3836 I jxcore-log: 
,08-12 16:41:07.326  3787  3836 I jxcore-log: ok 237 keys match
08-12 16:41:07.326  3787  3836 I jxcore-log: 
08-12 16:41:07.326  3787  3836 I jxcore-log: ok 238 secrets match
08-12 16:41:07.326  3787  3836 I jxcore-log: 
,08-12 16:41:07.333  3787  3836 I jxcore-log: ok 239 We have an entry!
08-12 16:41:07.333  3787  3836 I jxcore-log: 
,08-12 16:41:07.334  3787  3836 I jxcore-log: ok 240 keys match
08-12 16:41:07.334  3787  3836 I jxcore-log: 
08-12 16:41:07.334  3787  3836 I jxcore-log: ok 241 secrets match
08-12 16:41:07.334  3787  3836 I jxcore-log: 
,08-12 16:41:07.341  3787  3836 I jxcore-log: ok 242 We have an entry!
08-12 16:41:07.341  3787  3836 I jxcore-log: 
,08-12 16:41:07.342  3787  3836 I jxcore-log: ok 243 keys match
08-12 16:41:07.342  3787  3836 I jxcore-log: 
08-12 16:41:07.342  3787  3836 I jxcore-log: ok 244 secrets match
08-12 16:41:07.342  3787  3836 I jxcore-log: 
,08-12 16:41:07.344  3787  3836 I jxcore-log: # teardown
08-12 16:41:07.344  3787  3836 I jxcore-log: 
,08-12 16:41:07.498  3787  3836 I jxcore-log: # setup
08-12 16:41:07.498  3787  3836 I jxcore-log: 
,08-12 16:41:07.554  3787  3836 I jxcore-log: # 81. validate generateBeaconStreamAndSecrets
08-12 16:41:07.554  3787  3836 I jxcore-log: 
,08-12 16:41:07.707  3787  3836 I jxcore-log: ok 245 Streams have same length
08-12 16:41:07.707  3787  3836 I jxcore-log: 
,08-12 16:41:07.715  3787  3836 I jxcore-log: ok 246 matching size
08-12 16:41:07.715  3787  3836 I jxcore-log: 
,08-12 16:41:07.715  3787  3836 I jxcore-log: ok 247 keys match
08-12 16:41:07.715  3787  3836 I jxcore-log: 
08-12 16:41:07.716  3787  3836 I jxcore-log: ok 248 secrets match
08-12 16:41:07.716  3787  3836 I jxcore-log: 
,08-12 16:41:07.718  3787  3836 I jxcore-log: # teardown
08-12 16:41:07.718  3787  3836 I jxcore-log: 
,08-12 16:41:07.805  3787  3836 I jxcore-log: # setup
08-12 16:41:07.805  3787  3836 I jxcore-log: 
,08-12 16:41:07.921  3787  3836 I jxcore-log: # 82. Add two Peers.
08-12 16:41:07.921  3787  3836 I jxcore-log: 
,08-12 16:41:08.030  3787  3836 I jxcore-log: ok 249 should be equal
08-12 16:41:08.030  3787  3836 I jxcore-log: 
,08-12 16:41:08.032  3787  3836 I jxcore-log: ok 250 should be equal
08-12 16:41:08.032  3787  3836 I jxcore-log: 
08-12 16:41:08.032  3787  3836 I jxcore-log: ok 251 should be equal
08-12 16:41:08.032  3787  3836 I jxcore-log: 
,08-12 16:41:08.033  3787  3836 I jxcore-log: ok 252 should be equal
08-12 16:41:08.033  3787  3836 I jxcore-log: 
08-12 16:41:08.035  3787  3836 I jxcore-log: ok 253 should be equal
08-12 16:41:08.035  3787  3836 I jxcore-log: 
,08-12 16:41:08.042  3787  3836 I jxcore-log: # teardown
08-12 16:41:08.042  3787  3836 I jxcore-log: 
,08-12 16:41:08.089  3787  3836 I jxcore-log: # setup
08-12 16:41:08.089  3787  3836 I jxcore-log: 
,08-12 16:41:08.240  3787  3836 I jxcore-log: # 83. TCP_NATIVE peer loses DNS
08-12 16:41:08.240  3787  3836 I jxcore-log: 
,08-12 16:41:08.329  3787  3836 I jxcore-log: ok 254 should be equal
08-12 16:41:08.329  3787  3836 I jxcore-log: 
,08-12 16:41:08.330  3787  3836 I jxcore-log: ok 255 should be equal
08-12 16:41:08.330  3787  3836 I jxcore-log: 
08-12 16:41:08.331  3787  3836 I jxcore-log: # teardown
08-12 16:41:08.331  3787  3836 I jxcore-log: 
,08-12 16:41:08.371  3787  3836 I jxcore-log: # setup
08-12 16:41:08.371  3787  3836 I jxcore-log: 
,08-12 16:41:08.470  3787  3836 I jxcore-log: # 84. Received beacons with no values for us
08-12 16:41:08.470  3787  3836 I jxcore-log: 
,08-12 16:41:08.746  3787  3836 I jxcore-log: ok 256 entry exists
08-12 16:41:08.746  3787  3836 I jxcore-log: 
,08-12 16:41:08.747  3787  3836 I jxcore-log: ok 257 entry is resolved
08-12 16:41:08.747  3787  3836 I jxcore-log: 
,08-12 16:41:08.759  3787  3836 I jxcore-log: # teardown
08-12 16:41:08.759  3787  3836 I jxcore-log: 
,08-12 16:41:08.792  3787  3836 I jxcore-log: # setup
08-12 16:41:08.792  3787  3836 I jxcore-log: 
,08-12 16:41:08.951  3787  3836 I jxcore-log: # 85. Resolves an action locally
08-12 16:41:08.951  3787  3836 I jxcore-log: 
,08-12 16:41:09.146  3787  3836 I jxcore-log: ok 258 Host address must match
08-12 16:41:09.146  3787  3836 I jxcore-log: 
,08-12 16:41:09.147  3787  3836 I jxcore-log: ok 259 suggestedTCPTimeout must match
08-12 16:41:09.147  3787  3836 I jxcore-log: 
,08-12 16:41:09.147  3787  3836 I jxcore-log: ok 260 connectionType must match
08-12 16:41:09.147  3787  3836 I jxcore-log: 
08-12 16:41:09.148  3787  3836 I jxcore-log: ok 261 portNumber must match
08-12 16:41:09.148  3787  3836 I jxcore-log: 
,08-12 16:41:09.154  3787  3836 I jxcore-log: # teardown
08-12 16:41:09.154  3787  3836 I jxcore-log: 
,08-12 16:41:09.242  3787  3836 I jxcore-log: # setup
08-12 16:41:09.242  3787  3836 I jxcore-log: 
,08-12 16:41:09.338  3787  3836 I jxcore-log: # 86. Resolves an action locally using ThaliPeerPoolDefault
08-12 16:41:09.338  3787  3836 I jxcore-log: 
,08-12 16:41:09.610  3787  3836 I jxcore-log: ok 262 Host address must match
08-12 16:41:09.610  3787  3836 I jxcore-log: 
,08-12 16:41:09.611  3787  3836 I jxcore-log: ok 263 suggestedTCPTimeout must match
08-12 16:41:09.611  3787  3836 I jxcore-log: 
08-12 16:41:09.611  3787  3836 I jxcore-log: ok 264 connectionType must match
08-12 16:41:09.611  3787  3836 I jxcore-log: 
08-12 16:41:09.612  3787  3836 I jxcore-log: ok 265 portNumber must match
08-12 16:41:09.612  3787  3836 I jxcore-log: 
,08-12 16:41:09.620  3787  3836 I jxcore-log: # teardown
08-12 16:41:09.620  3787  3836 I jxcore-log: 
,08-12 16:41:09.660  3787  3836 I jxcore-log: # setup
08-12 16:41:09.660  3787  3836 I jxcore-log: 
,08-12 16:41:09.760  3787  3836 I jxcore-log: # 87. Action fails because of a bad hostname.
08-12 16:41:09.760  3787  3836 I jxcore-log: 
,08-12 16:41:14.909  3787  3836 I jxcore-log: ok 266 should be equal
08-12 16:41:14.909  3787  3836 I jxcore-log: 
,08-12 16:41:14.911  3787  3836 I jxcore-log: ok 267 should be equal
08-12 16:41:14.911  3787  3836 I jxcore-log: 
,08-12 16:41:14.913  3787  3836 I jxcore-log: ok 268 should be equal
08-12 16:41:14.913  3787  3836 I jxcore-log: 
,08-12 16:41:14.927  3787  3836 I jxcore-log: # teardown
08-12 16:41:14.927  3787  3836 I jxcore-log: 
,08-12 16:41:14.983  3787  3836 I jxcore-log: # setup
08-12 16:41:14.983  3787  3836 I jxcore-log: 
,08-12 16:41:15.153  3787  3836 I jxcore-log: # 88. hostaddress is removed when the action is running. 
08-12 16:41:15.153  3787  3836 I jxcore-log: 
,08-12 16:41:17.248  3787  3836 I jxcore-log: ok 269 should be equal
08-12 16:41:17.248  3787  3836 I jxcore-log: 
,08-12 16:41:17.278  3787  3836 I jxcore-log: # teardown
08-12 16:41:17.278  3787  3836 I jxcore-log: 
,08-12 16:41:17.358  3787  3836 I jxcore-log: # setup
08-12 16:41:17.358  3787  3836 I jxcore-log: 
,08-12 16:41:17.505  3787  3836 I jxcore-log: # 89. Client to server request locally
08-12 16:41:17.505  3787  3836 I jxcore-log: 
,08-12 16:41:17.702  3787  3836 I jxcore-log: ok 270 secrets are equal
08-12 16:41:17.702  3787  3836 I jxcore-log: 
,08-12 16:41:17.702  3787  3836 I jxcore-log: ok 271 Public key matches with the server key
08-12 16:41:17.702  3787  3836 I jxcore-log: 
08-12 16:41:17.703  3787  3836 I jxcore-log: ok 272 Host address must match
08-12 16:41:17.703  3787  3836 I jxcore-log: 
08-12 16:41:17.703  3787  3836 I jxcore-log: ok 273 suggestedTCPTimeout must match
08-12 16:41:17.703  3787  3836 I jxcore-log: 
,08-12 16:41:17.703  3787  3836 I jxcore-log: ok 274 connectionType must match
08-12 16:41:17.703  3787  3836 I jxcore-log: 
08-12 16:41:17.703  3787  3836 I jxcore-log: ok 275 portNumber must match
08-12 16:41:17.703  3787  3836 I jxcore-log: 
,08-12 16:41:17.714  3787  3836 I jxcore-log: # teardown
08-12 16:41:17.714  3787  3836 I jxcore-log: 
,08-12 16:41:17.828  3787  3836 I jxcore-log: # setup
08-12 16:41:17.828  3787  3836 I jxcore-log: 
,08-12 16:41:17.902  3787  3836 I jxcore-log: # 90. Test ThaliPskMapCache clean and expiration
08-12 16:41:17.902  3787  3836 I jxcore-log: 
,08-12 16:41:17.964  3787  3836 I jxcore-log: ok 276 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
08-12 16:41:17.964  3787  3836 I jxcore-log: 
08-12 16:41:17.965  3787  3836 I jxcore-log: ok 277 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
08-12 16:41:17.965  3787  3836 I jxcore-log: 
,08-12 16:41:18.967  3787  3836 I jxcore-log: ok 278 All entries should be expired after 1 second
08-12 16:41:18.967  3787  3836 I jxcore-log: 
,08-12 16:41:18.979  3787  3836 I jxcore-log: # teardown
08-12 16:41:18.979  3787  3836 I jxcore-log: 
,08-12 16:41:19.052  3787  3836 I jxcore-log: # setup
08-12 16:41:19.052  3787  3836 I jxcore-log: 
,08-12 16:41:19.157  3787  3836 I jxcore-log: # 91. Test ThaliPskMapCache getSecret and getPublic
08-12 16:41:19.157  3787  3836 I jxcore-log: 
,08-12 16:41:19.323  3787  3836 I jxcore-log: ok 279 All keys need to be available in the cache
08-12 16:41:19.323  3787  3836 I jxcore-log: 
,08-12 16:41:20.327  3787  3836 I jxcore-log: ok 280 All entries should be expired after 1 second
08-12 16:41:20.327  3787  3836 I jxcore-log: 
,08-12 16:41:20.338  3787  3836 I jxcore-log: # teardown
08-12 16:41:20.338  3787  3836 I jxcore-log: 
,08-12 16:41:20.438  3787  3836 I jxcore-log: # setup
08-12 16:41:20.438  3787  3836 I jxcore-log: 
,08-12 16:41:20.549  3787  3836 I jxcore-log: # 92. Test ThaliPskMapCache multiple entries
08-12 16:41:20.549  3787  3836 I jxcore-log: 
,08-12 16:41:21.992  3787  3836 I jxcore-log: ok 281 Size of the cache should be 2
08-12 16:41:21.992  3787  3836 I jxcore-log: 
,08-12 16:41:21.997  3787  3836 I jxcore-log: ok 282 Cache doesn't contain dictionary1
08-12 16:41:21.997  3787  3836 I jxcore-log: 
,08-12 16:41:23.210  3787  3836 I jxcore-log: ok 283 Size of the cache should be 1
08-12 16:41:23.210  3787  3836 I jxcore-log: 
,08-12 16:41:23.213  3787  3836 I jxcore-log: ok 284 Cache doesn't contain beaconStreamAndSecretDictionary2
08-12 16:41:23.213  3787  3836 I jxcore-log: 
,08-12 16:41:23.228  3787  3836 I jxcore-log: # teardown
08-12 16:41:23.228  3787  3836 I jxcore-log: 
,08-12 16:41:23.351  3787  3836 I jxcore-log: # setup
08-12 16:41:23.351  3787  3836 I jxcore-log: 
,08-12 16:41:23.437  3787  3836 I jxcore-log: # 93. Start and stop ThaliNotificationServer
08-12 16:41:23.437  3787  3836 I jxcore-log: 
,08-12 16:41:23.629  3787  3836 I jxcore-log: ok 285 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
08-12 16:41:23.629  3787  3836 I jxcore-log: 
,08-12 16:41:23.629  3787  3836 I jxcore-log: ok 286 ThaliMobile.StopAdvertisingAndListeningshould be called once
08-12 16:41:23.629  3787  3836 I jxcore-log: 
08-12 16:41:23.631  3787  3836 I jxcore-log: # teardown
08-12 16:41:23.631  3787  3836 I jxcore-log: 
,08-12 16:41:23.691  3787  3836 I jxcore-log: # setup
08-12 16:41:23.691  3787  3836 I jxcore-log: 
,08-12 16:41:23.757  3787  3836 I jxcore-log: # 94. Pass an empty array to ThaliNotificationServer.start
08-12 16:41:23.757  3787  3836 I jxcore-log: 
,08-12 16:41:23.822  3787  3836 I jxcore-log: ok 287 StartUpdateAdvertisingAndListening should not be called
08-12 16:41:23.822  3787  3836 I jxcore-log: 
,08-12 16:41:23.835  3787  3836 I jxcore-log: ok 288 ThaliMobile.StopAdvertisingAndListening should be called once
08-12 16:41:23.835  3787  3836 I jxcore-log: 
,08-12 16:41:23.879  3787  3836 I jxcore-log: ok 289 no error
08-12 16:41:23.879  3787  3836 I jxcore-log: 
08-12 16:41:23.880  3787  3836 I jxcore-log: ok 290 should be 204
08-12 16:41:23.880  3787  3836 I jxcore-log: 
,08-12 16:41:23.884  3787  3836 I jxcore-log: # teardown
08-12 16:41:23.884  3787  3836 I jxcore-log: 
,08-12 16:41:23.956  3787  3836 I jxcore-log: # setup
08-12 16:41:23.956  3787  3836 I jxcore-log: 
,08-12 16:41:24.056  3787  3836 I jxcore-log: # 95. Pass a string to ThaliNotificationServer.start
08-12 16:41:24.056  3787  3836 I jxcore-log: 
,08-12 16:41:24.108  3787  3836 I jxcore-log: ok 291 StartUpdateAdvertisingAndListening should not be called
08-12 16:41:24.108  3787  3836 I jxcore-log: 
,08-12 16:41:24.111  3787  3836 I jxcore-log: # teardown
08-12 16:41:24.111  3787  3836 I jxcore-log: 
,08-12 16:41:24.158  3787  3836 I jxcore-log: # setup
08-12 16:41:24.158  3787  3836 I jxcore-log: 
,08-12 16:41:24.231  3787  3836 I jxcore-log: # 96. Pass an empty parameter to ThaliNotificationServer.start
08-12 16:41:24.231  3787  3836 I jxcore-log: 
,08-12 16:41:24.340  3787  3836 I jxcore-log: ok 292 StartUpdateAdvertisingAndListening should not be called
08-12 16:41:24.340  3787  3836 I jxcore-log: 
,08-12 16:41:24.348  3787  3836 I jxcore-log: # teardown
08-12 16:41:24.348  3787  3836 I jxcore-log: 
,08-12 16:41:24.387  3787  3836 I jxcore-log: # setup
08-12 16:41:24.387  3787  3836 I jxcore-log: 
,08-12 16:41:24.478  3787  3836 I jxcore-log: # 97. Make an HTTP request to /NotificationBeacons
08-12 16:41:24.478  3787  3836 I jxcore-log: 
,08-12 16:41:24.671  3787  3836 I jxcore-log: ok 293 no error
08-12 16:41:24.671  3787  3836 I jxcore-log: 
,08-12 16:41:24.671  3787  3836 I jxcore-log: ok 294 should be 200
08-12 16:41:24.671  3787  3836 I jxcore-log: 
08-12 16:41:24.672  3787  3836 I jxcore-log: ok 295 should be equal
08-12 16:41:24.672  3787  3836 I jxcore-log: 
08-12 16:41:24.672  3787  3836 I jxcore-log: ok 296 should be equal
08-12 16:41:24.672  3787  3836 I jxcore-log: 
,08-12 16:41:24.694  3787  3836 I jxcore-log: ok 297 (unnamed assert)
08-12 16:41:24.694  3787  3836 I jxcore-log: 
,08-12 16:41:24.732  3787  3836 I jxcore-log: ok 298 no error
08-12 16:41:24.732  3787  3836 I jxcore-log: 
,08-12 16:41:24.732  3787  3836 I jxcore-log: ok 299 should be 204
08-12 16:41:24.732  3787  3836 I jxcore-log: 
,08-12 16:41:24.736  3787  3836 I jxcore-log: # teardown
08-12 16:41:24.736  3787  3836 I jxcore-log: 
,08-12 16:41:24.862  3787  3836 I jxcore-log: # setup
08-12 16:41:24.862  3787  3836 I jxcore-log: 
,08-12 16:41:24.927  3787  3836 I jxcore-log: # 98. Make an HTTP request to /NotificationBeacons (no keys)
08-12 16:41:24.927  3787  3836 I jxcore-log: 
,08-12 16:41:25.040  3787  3836 I jxcore-log: ok 300 error should be null
08-12 16:41:25.040  3787  3836 I jxcore-log: 
,08-12 16:41:25.041  3787  3836 I jxcore-log: ok 301 should be 204
08-12 16:41:25.041  3787  3836 I jxcore-log: 
,08-12 16:41:25.045  3787  3836 I jxcore-log: # teardown
08-12 16:41:25.045  3787  3836 I jxcore-log: 
,08-12 16:41:25.079  3787  3836 I jxcore-log: # setup
08-12 16:41:25.079  3787  3836 I jxcore-log: 
,08-12 16:41:25.166  3787  3836 I jxcore-log: # 99. Make an HTTP request to /NotificationBeaconsbefore calling start
08-12 16:41:25.166  3787  3836 I jxcore-log: 
,08-12 16:41:25.303  3787  3836 I jxcore-log: ok 302 should be 404
08-12 16:41:25.303  3787  3836 I jxcore-log: 
,08-12 16:41:25.307  3787  3836 I jxcore-log: # teardown
08-12 16:41:25.307  3787  3836 I jxcore-log: 
,08-12 16:41:25.348  3787  3836 I jxcore-log: # setup
08-12 16:41:25.348  3787  3836 I jxcore-log: 
,08-12 16:41:25.394  3787  3836 I jxcore-log: # 100. #testThaliPeerAction - test getters
08-12 16:41:25.394  3787  3836 I jxcore-log: 
,08-12 16:41:25.514  3787  3836 I jxcore-log: ok 303 getPeerIdentifier
08-12 16:41:25.514  3787  3836 I jxcore-log: 
,08-12 16:41:25.516  3787  3836 I jxcore-log: ok 304 getConnectionType
08-12 16:41:25.516  3787  3836 I jxcore-log: 
,08-12 16:41:25.519  3787  3836 I jxcore-log: ok 305 getActionType
08-12 16:41:25.519  3787  3836 I jxcore-log: 
,08-12 16:41:25.522  3787  3836 I jxcore-log: ok 306 getActionState
08-12 16:41:25.522  3787  3836 I jxcore-log: 
,08-12 16:41:25.524  3787  3836 I jxcore-log: ok 307 getPskIdentity
08-12 16:41:25.524  3787  3836 I jxcore-log: 
,08-12 16:41:25.526  3787  3836 I jxcore-log: ok 308 getPskKey
08-12 16:41:25.526  3787  3836 I jxcore-log: 
,08-12 16:41:25.533  3787  3836 I jxcore-log: # teardown
08-12 16:41:25.533  3787  3836 I jxcore-log: 
,08-12 16:41:25.568  3787  3836 I jxcore-log: # setup
08-12 16:41:25.568  3787  3836 I jxcore-log: 
,08-12 16:41:25.617  3787  3836 I jxcore-log: # 101. #testThaliPeerAction - start and kill
08-12 16:41:25.617  3787  3836 I jxcore-log: 
,08-12 16:41:25.700  3787  3836 I jxcore-log: ok 309 initial state
08-12 16:41:25.700  3787  3836 I jxcore-log: 
,08-12 16:41:25.704  3787  3836 I jxcore-log: ok 310 after start
08-12 16:41:25.704  3787  3836 I jxcore-log: 
,08-12 16:41:25.706  3787  3836 I jxcore-log: ok 311 after kill
08-12 16:41:25.706  3787  3836 I jxcore-log: 
,08-12 16:41:25.712  3787  3836 I jxcore-log: # teardown
08-12 16:41:25.712  3787  3836 I jxcore-log: 
,08-12 16:41:25.751  3787  3836 I jxcore-log: # setup
08-12 16:41:25.751  3787  3836 I jxcore-log: 
,08-12 16:41:25.840  3787  3836 I jxcore-log: # 102. #testThaliPeerAction - double start
08-12 16:41:25.840  3787  3836 I jxcore-log: 
,08-12 16:41:25.882  3787  3836 I jxcore-log: ok 312 should be equal
08-12 16:41:25.882  3787  3836 I jxcore-log: 
,08-12 16:41:25.884  3787  3836 I jxcore-log: # teardown
08-12 16:41:25.884  3787  3836 I jxcore-log: 
,08-12 16:41:26.072  3787  3836 I jxcore-log: # setup
08-12 16:41:26.072  3787  3836 I jxcore-log: 
,08-12 16:41:26.109  3787  3836 I jxcore-log: # 103. #testThaliPeerAction - start after kill
08-12 16:41:26.109  3787  3836 I jxcore-log: 
,08-12 16:41:26.155  3787  3836 I jxcore-log: ok 313 clean kill
08-12 16:41:26.155  3787  3836 I jxcore-log: 
,08-12 16:41:26.158  3787  3836 I jxcore-log: ok 314 should be equal
08-12 16:41:26.158  3787  3836 I jxcore-log: 
,08-12 16:41:26.161  3787  3836 I jxcore-log: # teardown
08-12 16:41:26.161  3787  3836 I jxcore-log: 
,08-12 16:41:26.219  3787  3836 I jxcore-log: # setup
08-12 16:41:26.219  3787  3836 I jxcore-log: 
,08-12 16:41:26.261  3787  3836 I jxcore-log: # 104. #testThaliPeerAction - make sure ids are unique
08-12 16:41:26.261  3787  3836 I jxcore-log: 
,08-12 16:41:26.306  3787  3836 I jxcore-log: ok 315 should not be equal
08-12 16:41:26.306  3787  3836 I jxcore-log: 
,08-12 16:41:26.309  3787  3836 I jxcore-log: # teardown
08-12 16:41:26.309  3787  3836 I jxcore-log: 
,08-12 16:41:26.364  3787  3836 I jxcore-log: # setup
08-12 16:41:26.364  3787  3836 I jxcore-log: 
,08-12 16:41:26.407  3787  3836 I jxcore-log: # 105. Test PeerConnectionInformation basics
08-12 16:41:26.407  3787  3836 I jxcore-log: 
,08-12 16:41:26.483  3787  3836 I jxcore-log: ok 316 connection type works
08-12 16:41:26.483  3787  3836 I jxcore-log: 
,08-12 16:41:26.484  3787  3836 I jxcore-log: ok 317 getHostAddress works
08-12 16:41:26.484  3787  3836 I jxcore-log: 
,08-12 16:41:26.485  3787  3836 I jxcore-log: ok 318 getPortNumber works
08-12 16:41:26.485  3787  3836 I jxcore-log: 
,08-12 16:41:26.487  3787  3836 I jxcore-log: ok 319 getSuggestedTCPTimeout works
08-12 16:41:26.487  3787  3836 I jxcore-log: 
,08-12 16:41:26.492  3787  3836 I jxcore-log: # teardown
08-12 16:41:26.492  3787  3836 I jxcore-log: 
,08-12 16:41:26.535  3787  3836 I jxcore-log: # setup
08-12 16:41:26.535  3787  3836 I jxcore-log: 
,08-12 16:41:26.590  3787  3836 I jxcore-log: # 106. Test PeerDictionary basic functionality
08-12 16:41:26.590  3787  3836 I jxcore-log: 
,08-12 16:41:26.673  3787  3836 I jxcore-log: ok 320 Entry counter must be 1
08-12 16:41:26.673  3787  3836 I jxcore-log: 
,08-12 16:41:26.673  3787  3836 I jxcore-log: ok 321 Size must be 1
08-12 16:41:26.673  3787  3836 I jxcore-log: 
,08-12 16:41:26.674  3787  3836 I jxcore-log: ok 322 Entry counter must be 2
08-12 16:41:26.674  3787  3836 I jxcore-log: 
08-12 16:41:26.675  3787  3836 I jxcore-log: ok 323 Size must be 2
08-12 16:41:26.675  3787  3836 I jxcore-log: 
,08-12 16:41:26.676  3787  3836 I jxcore-log: ok 324 Entry2 should not be found
08-12 16:41:26.676  3787  3836 I jxcore-log: 
,08-12 16:41:26.676  3787  3836 I jxcore-log: ok 325 Size must be 1
08-12 16:41:26.676  3787  3836 I jxcore-log: 
08-12 16:41:26.677  3787  3836 I jxcore-log: ok 326 Size must be 0
08-12 16:41:26.677  3787  3836 I jxcore-log: 
,08-12 16:41:26.679  3787  3836 I jxcore-log: # teardown
08-12 16:41:26.679  3787  3836 I jxcore-log: 
,08-12 16:41:26.761  3787  3836 I jxcore-log: # setup
08-12 16:41:26.761  3787  3836 I jxcore-log: 
,08-12 16:41:26.811  3787  3836 I jxcore-log: # 107. Test PeerDictionary with multiple entries.
08-12 16:41:26.811  3787  3836 I jxcore-log: 
,08-12 16:41:27.628  3787  3836 I jxcore-log: ok 327 Size must be100
08-12 16:41:27.628  3787  3836 I jxcore-log: 
,08-12 16:41:27.631  3787  3836 I jxcore-log: ok 328 Entries between 20 and MAXSIZE + 20 should exist
08-12 16:41:27.631  3787  3836 I jxcore-log: 
,08-12 16:41:28.348  3787  3836 I jxcore-log: ok 329 WAITING state entry should not be removed
08-12 16:41:28.348  3787  3836 I jxcore-log: 
,08-12 16:41:28.350  3787  3836 I jxcore-log: # teardown
08-12 16:41:28.350  3787  3836 I jxcore-log: 
,08-12 16:41:28.817  3787  3836 I jxcore-log: # setup
08-12 16:41:28.817  3787  3836 I jxcore-log: 
,08-12 16:41:28.859  3787  3836 I jxcore-log: # 108. RESOLVED entries are removed before WAITING state entry.
08-12 16:41:28.859  3787  3836 I jxcore-log: 
,08-12 16:41:29.564  3787  3836 I jxcore-log: ok 330 Entries between 6 and MAXSIZE + 4 should exist
08-12 16:41:29.564  3787  3836 I jxcore-log: 
,08-12 16:41:29.564  3787  3836 I jxcore-log: ok 331 Size should be MAXSIZE
08-12 16:41:29.564  3787  3836 I jxcore-log: 
,08-12 16:41:29.564  3787  3836 I jxcore-log: ok 332 Size should be MAXSIZE+6
08-12 16:41:29.564  3787  3836 I jxcore-log: 
08-12 16:41:29.566  3787  3836 I jxcore-log: # teardown
08-12 16:41:29.566  3787  3836 I jxcore-log: 
,08-12 16:41:29.640  3787  3836 I jxcore-log: # setup
08-12 16:41:29.640  3787  3836 I jxcore-log: 
,08-12 16:41:29.707  3787  3836 I jxcore-log: # 109. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
08-12 16:41:29.707  3787  3836 I jxcore-log: 
,08-12 16:41:30.416  3787  3836 I jxcore-log: ok 333 WAITING state entry should not be removed
08-12 16:41:30.416  3787  3836 I jxcore-log: 
,08-12 16:41:30.417  3787  3836 I jxcore-log: ok 334 Waiting entries between 6 and MAXSIZE + 4 should exist
08-12 16:41:30.417  3787  3836 I jxcore-log: 
08-12 16:41:30.418  3787  3836 I jxcore-log: ok 335 Size should be MAXSIZE
08-12 16:41:30.418  3787  3836 I jxcore-log: 
08-12 16:41:30.418  3787  3836 I jxcore-log: ok 336 entryCounter should be MAXSIZE+6
08-12 16:41:30.418  3787  3836 I jxcore-log: 
,08-12 16:41:30.420  3787  3836 I jxcore-log: # teardown
08-12 16:41:30.420  3787  3836 I jxcore-log: 
,08-12 16:41:30.489  3787  3836 I jxcore-log: # setup
08-12 16:41:30.489  3787  3836 I jxcore-log: 
,08-12 16:41:30.543  3787  3836 I jxcore-log: # 110. When CONTROLLED_BY_POOL entry is removed and kill is called.
08-12 16:41:30.543  3787  3836 I jxcore-log: 
,08-12 16:41:31.241  3787  3836 I jxcore-log: ok 337 Kill should be called once
08-12 16:41:31.241  3787  3836 I jxcore-log: 
,08-12 16:41:31.242  3787  3836 I jxcore-log: ok 338 Size should be 100
08-12 16:41:31.242  3787  3836 I jxcore-log: 
08-12 16:41:31.243  3787  3836 I jxcore-log: # teardown
08-12 16:41:31.243  3787  3836 I jxcore-log: 
,08-12 16:41:31.463  3787  3836 I jxcore-log: # setup
08-12 16:41:31.463  3787  3836 I jxcore-log: 
,08-12 16:41:31.532  3787  3836 I jxcore-log: # 111. #ThaliPeerPoolInterface - bad enqueues
08-12 16:41:31.532  3787  3836 I jxcore-log: 
,08-12 16:41:31.579  3787  3836 I jxcore-log: ok 339 null arg
08-12 16:41:31.579  3787  3836 I jxcore-log: 
,08-12 16:41:31.581  3787  3836 I jxcore-log: ok 340 wrong arg type
08-12 16:41:31.581  3787  3836 I jxcore-log: 
,08-12 16:41:31.584  3787  3836 I jxcore-log: ok 341 wrong state
08-12 16:41:31.584  3787  3836 I jxcore-log: 
,08-12 16:41:31.587  3787  3836 I jxcore-log: # teardown
08-12 16:41:31.587  3787  3836 I jxcore-log: 
,08-12 16:41:31.642  3787  3836 I jxcore-log: # setup
08-12 16:41:31.642  3787  3836 I jxcore-log: 
,08-12 16:41:31.704  3787  3836 I jxcore-log: # 112. #ThaliPeerPoolInterface - do not allow same object type
08-12 16:41:31.704  3787  3836 I jxcore-log: 
,08-12 16:41:31.738  3787  3836 I jxcore-log: ok 342 good enqueue
08-12 16:41:31.738  3787  3836 I jxcore-log: 
,08-12 16:41:31.740  3787  3836 I jxcore-log: ok 343 should be equal
08-12 16:41:31.740  3787  3836 I jxcore-log: 
,08-12 16:41:31.742  3787  3836 I jxcore-log: # teardown
08-12 16:41:31.742  3787  3836 I jxcore-log: 
,08-12 16:41:31.783  3787  3836 I jxcore-log: # setup
08-12 16:41:31.783  3787  3836 I jxcore-log: 
,08-12 16:41:31.880  3787  3836 I jxcore-log: # 113. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
08-12 16:41:31.880  3787  3836 I jxcore-log: 
,08-12 16:41:31.983  3787  3836 I jxcore-log: ok 344 good enqueue
08-12 16:41:31.983  3787  3836 I jxcore-log: 
,08-12 16:41:31.985  3787  3836 I jxcore-log: ok 345 2nd good enqueue
08-12 16:41:31.985  3787  3836 I jxcore-log: 
08-12 16:41:31.986  3787  3836 I jxcore-log: ok 346 we are in the pool
08-12 16:41:31.986  3787  3836 I jxcore-log: 
,08-12 16:41:31.988  3787  3836 I jxcore-log: ok 347 We are out of the pool
08-12 16:41:31.988  3787  3836 I jxcore-log: 
,08-12 16:41:31.989  3787  3836 I jxcore-log: ok 348 Action was killed
08-12 16:41:31.989  3787  3836 I jxcore-log: 
08-12 16:41:31.989  3787  3836 I jxcore-log: ok 349 The original kill was called too
08-12 16:41:31.989  3787  3836 I jxcore-log: 
,08-12 16:41:31.990  3787  3836 I jxcore-log: ok 350 second item is still in queue
08-12 16:41:31.990  3787  3836 I jxcore-log: 
08-12 16:41:31.992  3787  3836 I jxcore-log: # teardown
08-12 16:41:31.992  3787  3836 I jxcore-log: 
,08-12 16:41:32.065  3787  3836 I jxcore-log: # setup
08-12 16:41:32.065  3787  3836 I jxcore-log: 
,08-12 16:41:32.103  3787  3836 I jxcore-log: # 114. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
08-12 16:41:32.103  3787  3836 I jxcore-log: 
,08-12 16:41:32.155  3787  3836 I jxcore-log: ok 351 good enqueue
08-12 16:41:32.155  3787  3836 I jxcore-log: 
,08-12 16:41:32.155  3787  3836 I jxcore-log: ok 352 first kill
08-12 16:41:32.155  3787  3836 I jxcore-log: 
08-12 16:41:32.156  3787  3836 I jxcore-log: ok 353 second NOOP kill
08-12 16:41:32.156  3787  3836 I jxcore-log: 
,08-12 16:41:32.158  3787  3836 I jxcore-log: # teardown
08-12 16:41:32.158  3787  3836 I jxcore-log: 
,08-12 16:41:32.211  3787  3836 I jxcore-log: # setup
08-12 16:41:32.211  3787  3836 I jxcore-log: 
,08-12 16:41:32.264  3787  3836 I jxcore-log: # 115. Make sure peerDictionaryKey is reasonable
08-12 16:41:32.264  3787  3836 I jxcore-log: 
,08-12 16:41:32.357  3787  3836 I jxcore-log: ok 354 equal keys
08-12 16:41:32.357  3787  3836 I jxcore-log: 
,08-12 16:41:32.360  3787  3836 I jxcore-log: ok 355 not equal connection type
08-12 16:41:32.360  3787  3836 I jxcore-log: 
,08-12 16:41:32.364  3787  3836 I jxcore-log: ok 356 same connection type, different buffer
08-12 16:41:32.364  3787  3836 I jxcore-log: 
,08-12 16:41:32.365  3787  3836 I jxcore-log: # teardown
08-12 16:41:32.365  3787  3836 I jxcore-log: 
,08-12 16:41:32.400  3787  3836 I jxcore-log: # setup
08-12 16:41:32.400  3787  3836 I jxcore-log: 
,08-12 16:41:32.487  3787  3836 I jxcore-log: # 116. Make sure start works
08-12 16:41:32.487  3787  3836 I jxcore-log: 
,08-12 16:41:32.579  3787  3836 I jxcore-log: ok 357 First start and on called correctly
08-12 16:41:32.579  3787  3836 I jxcore-log: 
,08-12 16:41:32.582  3787  3836 I jxcore-log: # teardown
08-12 16:41:32.582  3787  3836 I jxcore-log: 
,08-12 16:41:32.664  3787  3836 I jxcore-log: # setup
08-12 16:41:32.664  3787  3836 I jxcore-log: 
,08-12 16:41:32.719  3787  3836 I jxcore-log: # 117. Make sure stop works
08-12 16:41:32.719  3787  3836 I jxcore-log: 
,08-12 16:41:32.786  3787  3836 I jxcore-log: ok 358 second cleared dictionary
08-12 16:41:32.786  3787  3836 I jxcore-log: 
,08-12 16:41:32.816  3787  3836 I jxcore-log: ok 359 First start and on called correctly
08-12 16:41:32.816  3787  3836 I jxcore-log: 
,08-12 16:41:32.833  3787  3836 I jxcore-log: ok 360 First stop and removeListener called correctly
08-12 16:41:32.833  3787  3836 I jxcore-log: 
,08-12 16:41:32.834  3787  3836 I jxcore-log: ok 361 first action kill called
08-12 16:41:32.834  3787  3836 I jxcore-log: 
,08-12 16:41:32.834  3787  3836 I jxcore-log: ok 362 second action kill called
08-12 16:41:32.834  3787  3836 I jxcore-log: 
08-12 16:41:32.836  3787  3836 I jxcore-log: ok 363 first cleared dictionary
08-12 16:41:32.836  3787  3836 I jxcore-log: 
08-12 16:41:32.836  3787  3836 I jxcore-log: ok 364 second cleared dictionary
08-12 16:41:32.836  3787  3836 I jxcore-log: 
08-12 16:41:32.838  3787  3836 I jxcore-log: # teardown
08-12 16:41:32.838  3787  3836 I jxcore-log: 
,08-12 16:41:32.900  3787  3836 I jxcore-log: # setup
08-12 16:41:32.900  3787  3836 I jxcore-log: 
,08-12 16:41:32.937  3787  3836 I jxcore-log: # 118. Simple peer event
08-12 16:41:32.937  3787  3836 I jxcore-log: 
,08-12 16:41:33.010  3787  3836 I jxcore-log: ok 365 listener has been set
08-12 16:41:33.010  3787  3836 I jxcore-log: 
,08-12 16:41:33.017  3787  3836 I jxcore-log: ok 366 peer dictionary has expected number of entries
08-12 16:41:33.017  3787  3836 I jxcore-log: 
,08-12 16:41:33.018  3787  3836 I jxcore-log: ok 367 Dictionary and pool have same action
08-12 16:41:33.018  3787  3836 I jxcore-log: 
,08-12 16:41:33.018  3787  3836 I jxcore-log: ok 368 ads match
08-12 16:41:33.018  3787  3836 I jxcore-log: 
,08-12 16:41:33.019  3787  3836 I jxcore-log: ok 369 PouchDB matches
08-12 16:41:33.019  3787  3836 I jxcore-log: 
08-12 16:41:33.019  3787  3836 I jxcore-log: ok 370 DB Names match
08-12 16:41:33.019  3787  3836 I jxcore-log: 
,08-12 16:41:33.020  3787  3836 I jxcore-log: ok 371 public keys match
08-12 16:41:33.020  3787  3836 I jxcore-log: 
,08-12 16:41:33.025  3787  3836 I jxcore-log: ok 372 peer dictionary has expected number of entries
08-12 16:41:33.025  3787  3836 I jxcore-log: 
08-12 16:41:33.026  3787  3836 I jxcore-log: ok 373 Dictionary and pool have same action
08-12 16:41:33.026  3787  3836 I jxcore-log: 
,08-12 16:41:33.027  3787  3836 I jxcore-log: ok 374 ads match
08-12 16:41:33.027  3787  3836 I jxcore-log: 
08-12 16:41:33.027  3787  3836 I jxcore-log: ok 375 PouchDB matches
08-12 16:41:33.027  3787  3836 I jxcore-log: 
08-12 16:41:33.028  3787  3836 I jxcore-log: ok 376 DB Names match
08-12 16:41:33.028  3787  3836 I jxcore-log: 
08-12 16:41:33.029  3787  3836 I jxcore-log: ok 377 public keys match
08-12 16:41:33.029  3787  3836 I jxcore-log: 
,08-12 16:41:33.032  3787  3836 I jxcore-log: ok 378 start called once
08-12 16:41:33.032  3787  3836 I jxcore-log: 
,08-12 16:41:33.033  3787  3836 I jxcore-log: ok 379 kill never called
08-12 16:41:33.033  3787  3836 I jxcore-log: 
,08-12 16:41:33.033  3787  3836 I jxcore-log: ok 380 One entry left
08-12 16:41:33.033  3787  3836 I jxcore-log: 
08-12 16:41:33.034  3787  3836 I jxcore-log: ok 381 Dictionary and pool have same action
08-12 16:41:33.034  3787  3836 I jxcore-log: 
,08-12 16:41:33.036  3787  3836 I jxcore-log: ok 382 Start never called
08-12 16:41:33.036  3787  3836 I jxcore-log: 
08-12 16:41:33.036  3787  3836 I jxcore-log: ok 383 Kill called once
08-12 16:41:33.036  3787  3836 I jxcore-log: 
08-12 16:41:33.037  3787  3836 I jxcore-log: ok 384 no entries left
08-12 16:41:33.037  3787  3836 I jxcore-log: 
,08-12 16:41:33.050  3787  3836 I jxcore-log: ok 385 Third action is dead
08-12 16:41:33.050  3787  3836 I jxcore-log: 
,08-12 16:41:33.051  3787  3836 I jxcore-log: ok 386 peer dictionary has expected number of entries
08-12 16:41:33.051  3787  3836 I jxcore-log: 
08-12 16:41:33.051  3787  3836 I jxcore-log: ok 387 Dictionary and pool have same action
08-12 16:41:33.051  3787  3836 I jxcore-log: 
08-12 16:41:33.051  3787  3836 I jxcore-log: ok 388 ads match
08-12 16:41:33.051  3787  3836 I jxcore-log: 
08-12 16:41:33.051  3787  3836 I jxcore-log: ok 389 PouchDB matches
08-12 16:41:33.051  3787  3836 I jxcore-log: 
,08-12 16:41:33.052  3787  3836 I jxcore-log: ok 390 DB Names match
08-12 16:41:33.052  3787  3836 I jxcore-log: 
08-12 16:41:33.053  3787  3836 I jxcore-log: ok 391 public keys match
08-12 16:41:33.053  3787  3836 I jxcore-log: 
08-12 16:41:33.055  3787  3836 I jxcore-log: # teardown
08-12 16:41:33.055  3787  3836 I jxcore-log: 
,08-12 16:41:33.137  3787  3836 I jxcore-log: # setup
08-12 16:41:33.137  3787  3836 I jxcore-log: 
,08-12 16:41:33.214  3787  3836 I jxcore-log: # 119. Coordinated pull replication from notification test
08-12 16:41:33.214  3787  3836 I jxcore-log: 
,08-12 16:41:33.474  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:41:33.474  3787  3836 I jxcore-log: 
,08-12 16:41:33.476  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 48001
08-12 16:41:33.476  3787  3836 I jxcore-log: 
,08-12 16:41:33.480  3787  3836 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-12 16:41:33.484  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 38068, start advertisements: false
,08-12 16:41:33.484  3787  3836 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 16:41:33.484  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 16:41:33.484  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-12 16:41:33.484  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-12 16:41:33.484  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 16:41:33.484  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-12 16:41:33.487  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 16:41:33.491  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-12 16:41:33.491  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-12 16:41:33.492  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-12 16:41:33.493  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:41:33.495  2697  4066 D BtGatt.GattService: registerClient() - UUID=c1737d2c-3a17-41c2-971a-4eac6bac8c89
,08-12 16:41:33.496  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=c1737d2c-3a17-41c2-971a-4eac6bac8c89, clientIf=5
08-12 16:41:33.497  3787  3798 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 16:41:33.498  2697  2893 D BtGatt.GattService: start scan with filters
,08-12 16:41:33.501  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-12 16:41:33.501  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-12 16:41:33.501  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-12 16:41:33.502  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-12 16:41:33.502  2697  2752 D BtGatt.ScanManager: handling starting scan
,08-12 16:41:33.506  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 16:41:33.506  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 16:41:33.507  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 16:41:33.507  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 16:41:33.510  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 16:41:33.516  2697  2748 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-12 16:41:33.516  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:41:33.517  2697  2752 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 16:41:33.533  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-12 16:41:33.534  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:41:33.534  2697  2752 D BtGatt.ScanManager: Starting BLE batch scan
08-12 16:41:33.534  2697  2752 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 16:41:33.562  2697  2748 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-12 16:41:33.562  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:41:33.572  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-12 16:41:33.572  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:41:34.007  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-12 16:41:34.007  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-12 16:41:34.008  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:41:34.015  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-12 16:41:34.015  3787  3836 I jxcore-log: 
,08-12 16:41:34.050  3787  3836 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-12 16:41:34.054  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 48001, start advertisements: true
08-12 16:41:34.054  3787  3836 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-12 16:41:34.054  3787  3836 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
08-12 16:41:34.054  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
08-12 16:41:34.054  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-12 16:41:34.054  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-12 16:41:34.054  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-12 16:41:34.054  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
08-12 16:41:34.054  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-12 16:41:34.054  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-12 16:41:34.054  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-12 16:41:34.054  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-12 16:41:34.054  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,08-12 16:41:34.054  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-12 16:41:34.054  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-12 16:41:34.055  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:41:34.056  2697  4071 D BtGatt.GattService: stopScan() - queue size =1
08-12 16:41:34.057  2697  2711 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 16:41:34.059  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 16:41:34.059  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-12 16:41:34.059  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 16:41:34.059  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-12 16:41:34.059  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-12 16:41:34.060  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-12 16:41:34.061  3787  3836 D BluetoothAdapter: STATE_ON
,08-12 16:41:34.064  2697  2893 D BtGatt.GattService: registerClient() - UUID=1deb7070-a290-444b-ad34-7d85ade4c09e
,08-12 16:41:34.065  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=1deb7070-a290-444b-ad34-7d85ade4c09e, clientIf=5
08-12 16:41:34.065  3787  4063 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 16:41:34.066  2697  4071 D BtGatt.GattService: start scan with filters
08-12 16:41:34.070  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-12 16:41:34.070  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-12 16:41:34.071  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-12 16:41:34.071  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-12 16:41:34.071  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-12 16:41:34.071  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 16:41:34.072  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-12 16:41:34.072  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-12 16:41:34.073  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-12 16:41:34.073  3787  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-12 16:41:34.073  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-12 16:41:34.073  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-12 16:41:34.073  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 16:41:34.073  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-12 16:41:34.074  3787  3836 D BluetoothAdapter: STATE_ON
08-12 16:41:34.075  2697  2708 D BtGatt.GattService: stopScan() - queue size =0
08-12 16:41:34.076  2697  4066 D BtGatt.GattService: unregisterClient() - clientIf=5
08-12 16:41:34.078  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-12 16:41:34.078  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 16:41:34.078  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-12 16:41:34.079  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-12 16:41:34.079  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-12 16:41:34.080  2697  2697 D BtGatt.ScanManager: awakened up at time 867667
08-12 16:41:34.080  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-12 16:41:34.080  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:41:34.081  2697  2752 D BtGatt.ScanManager: stopping BLe Batch
08-12 16:41:34.082  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 16:41:34.083  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-12 16:41:34.088  3787  4080 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-12 16:41:34.088  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-12 16:41:34.088  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 16:41:34.089  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-12 16:41:34.089  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
08-12 16:41:34.089  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:41:34.089  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 16:41:34.089  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-12 16:41:34.089  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-12 16:41:34.089  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-12 16:41:34.091  3787  4080 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-12 16:41:34.091  3787  3836 D BluetoothAdapter: STATE_ON
08-12 16:41:34.095  2697  2893 D BtGatt.GattService: registerClient() - UUID=3ffe3f55-7ade-4695-b0ea-6e20d00150b9
08-12 16:41:34.096  2697  2748 D BtGatt.GattService: onClientRegistered() - UUID=3ffe3f55-7ade-4695-b0ea-6e20d00150b9, clientIf=5
08-12 16:41:34.096  3787  3799 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-12 16:41:34.098  2697  2751 D BtGatt.AdvertiseManager: message : 0
,08-12 16:41:34.101  2697  2751 D BtGatt.AdvertiseManager: starting multi advertising
,08-12 16:41:34.107  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-12 16:41:34.107  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:41:34.108  2697  2748 D BtGatt.GattService: current time is 867695915249
,08-12 16:41:34.109  2697  2748 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -86, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -81, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -93, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, -128, -86, 2, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 37, -47, 14, -113, 116, -46, 1, -128, -84, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 16:41:34.110  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 16:41:34.110  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-12 16:41:34.111  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 16:41:34.112  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 16:41:34.114  2697  2752 D BtGatt.ScanManager: handling starting scan
08-12 16:41:34.114  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 16:41:34.115  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,08-12 16:41:34.115  2697  2748 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 16:41:34.119  2697  2748 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-12 16:41:34.124  2697  2748 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-12 16:41:34.124  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:41:34.125  2697  2752 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 16:41:34.130  2697  2748 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
08-12 16:41:34.131  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-12 16:41:34.131  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 16:41:34.133  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 16:41:34.134  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-12 16:41:34.135  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 16:41:34.135  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 16:41:34.135  3787  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-12 16:41:34.135  3787  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-12 16:41:34.135  3787  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-12 16:41:34.135  3787  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-12 16:41:34.135  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-12 16:41:34.135  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-12 16:41:34.135  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:41:34.136  2697  2752 D BtGatt.ScanManager: Starting BLE batch scan
08-12 16:41:34.136  2697  2752 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 16:41:34.138  3787  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-12 16:41:34.138  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-12 16:41:34.150  2697  2748 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-12 16:41:34.151  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:41:34.157  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-12 16:41:34.158  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:41:34.166  2697  2748 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-12 16:41:34.167  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 16:41:34.168  2697  2752 D BtGatt.ScanManager: stopping BLe Batch
,08-12 16:41:34.175  2697  2748 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 16:41:34.175  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:41:34.176  2697  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 16:41:34.183  2697  2748 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 16:41:34.183  2697  2748 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 16:41:34.639  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-12 16:41:34.640  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-12 16:41:34.640  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:41:34.673  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-12 16:41:34.673  3787  3836 I jxcore-log: 
,08-12 16:41:49.770   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=883357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:42:01.303   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=894890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 16:42:04.143   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=897730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:42:26.423   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=920010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 16:42:29.156   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=922743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:42:51.477   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=945064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 16:42:54.216   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=947803, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:43:16.570   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=970157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 16:43:19.290   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=972877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:43:41.610   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=995197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 16:43:44.330   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=997917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:44:06.663   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1020250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 16:44:09.383   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1022970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:44:31.717   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1045304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 16:44:34.450   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1048037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:44:56.770   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1070357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 16:44:59.503   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1073090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:45:21.823   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1095410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 16:45:24.556   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1098143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:45:46.890   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1120477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 16:45:49.603   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1123190, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:46:11.930   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1145517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 16:46:14.650   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1148237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 16:46:33.312  3787  3836 I jxcore-log: not ok 392 failed with Error: We ran out of time
08-12 16:46:33.312  3787  3836 I jxcore-log: 
,08-12 16:46:33.313  3787  3836 I jxcore-log:   ---
08-12 16:46:33.313  3787  3836 I jxcore-log: 
08-12 16:46:33.313  3787  3836 I jxcore-log:     operator: fail
08-12 16:46:33.313  3787  3836 I jxcore-log: 
,08-12 16:46:33.314  3787  3836 I jxcore-log:   ...
08-12 16:46:33.314  3787  3836 I jxcore-log: 
,08-12 16:46:33.327  3787  3836 I jxcore-log: # teardown
08-12 16:46:33.327  3787  3836 I jxcore-log: 
,08-12 16:46:33.392  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 16:46:33.392  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 16:46:33.392  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-12 16:46:33.392  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-12 16:46:33.392  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-12 16:46:33.392  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-12 16:46:33.392  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-12 16:46:33.393  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-12 16:46:33.393  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-12 16:46:33.393  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-12 16:46:33.393  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-12 16:46:33.393  3787  4080 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-12 16:46:33.393  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-12 16:46:33.393  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-12 16:46:33.393  3787  4080 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-12 16:46:33.393  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-12 16:46:33.393  3787  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-12 16:46:33.394  3787  4080 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-12 16:46:33.396  3787  3836 D BluetoothAdapter: STATE_ON
08-12 16:46:33.396  3787  3836 D BluetoothLeScanner: could not find callback wrapper
,08-12 16:46:33.396  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-12 16:46:33.396  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-12 16:46:33.397  2697  2751 D BtGatt.AdvertiseManager: message : 1
08-12 16:46:33.397  2697  2751 D BtGatt.AdvertiseManager: stop advertise for client 5
08-12 16:46:33.407  2697  2748 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-12 16:46:33.408  2697  2748 D BtGatt.GattService: Client app is not null!
,08-12 16:46:33.419  2697  2708 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 16:46:33.420  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-12 16:46:33.421  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-12 16:46:33.421  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-12 16:46:33.421  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-12 16:46:33.422  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-12 16:46:33.425  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 16:46:33.425  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-12 16:46:33.425  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-12 16:46:33.427  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-12 16:46:33.430  3787  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 16:46:33.431  3787  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 16:46:33.431  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 16:46:33.431  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 16:46:33.431  3787  3787 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-12 16:46:33.432  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 16:46:33.442  3787  3836 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
08-12 16:46:33.442  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 16:46:33.442  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 16:46:33.443  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 16:46:33.445  3787  3836 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-12 16:46:33.445  3787  3836 I jxcore-log: 
,08-12 16:46:33.450  3787  3836 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 16:46:33.450  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 16:46:33.450  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-12 16:46:33.450  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 16:46:33.461  3787  3836 I jxcore-log: # setup
08-12 16:46:33.461  3787  3836 I jxcore-log: 
,08-12 16:46:33.870  3787  3836 I jxcore-log: # 120. Server is not there
08-12 16:46:33.870  3787  3836 I jxcore-log: 
,08-12 16:46:33.934  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 16:46:33.954  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 16:46:33.954  3787  3836 I jxcore-log: 
,08-12 16:46:34.144  3787  3836 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - Error: connect ECONNREFUSED
08-12 16:46:34.144  3787  3836 I jxcore-log: 
,08-12 16:46:34.147  3787  3836 I jxcore-log: ok 393 right error
08-12 16:46:34.147  3787  3836 I jxcore-log: 
,08-12 16:46:34.152  3787  3836 I jxcore-log: # teardown
08-12 16:46:34.152  3787  3836 I jxcore-log: 
,08-12 16:46:34.181  3787  3836 I jxcore-log: # setup
08-12 16:46:34.181  3787  3836 I jxcore-log: 
,08-12 16:46:34.227  3787  3836 I jxcore-log: # 121. Server accepts & closes connection
08-12 16:46:34.227  3787  3836 I jxcore-log: 
,08-12 16:46:34.391  3787  3836 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - Error: socket hang up
08-12 16:46:34.391  3787  3836 I jxcore-log: 
,08-12 16:46:34.394  3787  3836 I jxcore-log: ok 394 right error
08-12 16:46:34.394  3787  3836 I jxcore-log: 
,08-12 16:46:34.398  3787  3836 I jxcore-log: # teardown
08-12 16:46:34.398  3787  3836 I jxcore-log: 
,08-12 16:46:34.586  3787  3836 I jxcore-log: # setup
08-12 16:46:34.586  3787  3836 I jxcore-log: 
,08-12 16:46:34.648  3787  3836 I jxcore-log: # 122. Server always returns 500
08-12 16:46:34.648  3787  3836 I jxcore-log: 
,08-12 16:46:34.838  3787  3836 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - 
08-12 16:46:34.838  3787  3836 I jxcore-log: 
,08-12 16:46:34.841  3787  3836 I jxcore-log: ok 395 Got error as expected
08-12 16:46:34.841  3787  3836 I jxcore-log: 
,08-12 16:46:34.845  3787  3836 I jxcore-log: # teardown
08-12 16:46:34.845  3787  3836 I jxcore-log: 
,08-12 16:46:34.935  3787  3836 I jxcore-log: # setup
08-12 16:46:34.935  3787  3836 I jxcore-log: 
,08-12 16:46:34.979  3787  3836 I jxcore-log: # 123. Server always returns 401
08-12 16:46:34.979  3787  3836 I jxcore-log: 
,08-12 16:46:35.165  3787  3836 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - 
08-12 16:46:35.165  3787  3836 I jxcore-log: 
,08-12 16:46:35.168  3787  3836 I jxcore-log: ok 396 Got error as expected
08-12 16:46:35.168  3787  3836 I jxcore-log: 
,08-12 16:46:35.171  3787  3836 I jxcore-log: # teardown
08-12 16:46:35.171  3787  3836 I jxcore-log: 
,08-12 16:46:35.283  3787  3836 I jxcore-log: # setup
08-12 16:46:35.283  3787  3836 I jxcore-log: 
,08-12 16:46:35.363  3787  3836 I jxcore-log: # 124. Server always returns 403
08-12 16:46:35.363  3787  3836 I jxcore-log: 
,08-12 16:46:35.546  3787  3836 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - 
08-12 16:46:35.546  3787  3836 I jxcore-log: 
,08-12 16:46:35.547  3787  3836 I jxcore-log: ok 397 Got error as expected
08-12 16:46:35.547  3787  3836 I jxcore-log: 
08-12 16:46:35.550  3787  3836 I jxcore-log: # teardown
08-12 16:46:35.550  3787  3836 I jxcore-log: 
,08-12 16:46:35.606  3787  3836 I jxcore-log: # setup
08-12 16:46:35.606  3787  3836 I jxcore-log: 
,08-12 16:46:35.646  3787  3836 I jxcore-log: # 125. Make sure docs replicate
08-12 16:46:35.646  3787  3836 I jxcore-log: 
,08-12 16:46:36.832  3787  3836 I jxcore-log: DEBUG thaliReplicationPeerAction: Replication resumed
08-12 16:46:36.832  3787  3836 I jxcore-log: 
,08-12 16:46:36.983   871  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1170570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 16:46:37.540  3787  3836 I jxcore-log: ok 398 should be equal
08-12 16:46:37.540  3787  3836 I jxcore-log: 
,08-12 16:46:37.541  3787  3836 I jxcore-log: ok 399 All tests passed!
08-12 16:46:37.541  3787  3836 I jxcore-log: 
,08-12 16:46:37.545  3787  3836 I jxcore-log: # teardown
08-12 16:46:37.545  3787  3836 I jxcore-log: 
,08-12 16:46:37.585  3787  3836 I jxcore-log: # setup
08-12 16:46:37.585  3787  3836 I jxcore-log: 
,08-12 16:46:37.640  3787  3836 I jxcore-log: # 126. Do nothing and make sure we time out
08-12 16:46:37.640  3787  3836 I jxcore-log: 
,08-12 16:46:38.078  3787  3836 I jxcore-log: DEBUG thaliReplicationPeerAction: Got paused with undefined
08-12 16:46:38.078  3787  3836 I jxcore-log: 
,08-12 16:46:39.745  3787  3836 I jxcore-log: ok 400 action should be killed
08-12 16:46:39.745  3787  3836 I jxcore-log: 
,08-12 16:46:39.746  3787  3836 I jxcore-log: ok 401 Error should be timed out
08-12 16:46:39.746  3787  3836 I jxcore-log: 
,08-12 16:46:39.833  3787  3836 I jxcore-log: ok 402 No doc found
08-12 16:46:39.833  3787  3836 I jxcore-log: 
,08-12 16:46:39.839  3787  3836 I jxcore-log: # teardown
08-12 16:46:39.839  3787  3836 I jxcore-log: 
,08-12 16:46:39.948  3787  3836 I jxcore-log: # setup
08-12 16:46:39.948  3787  3836 I jxcore-log: 
,08-12 16:46:39.988  3787  3836 I jxcore-log: # 127. Do something and make sure we time out
08-12 16:46:39.988  3787  3836 I jxcore-log: 
,08-12 16:46:41.070  3787  3836 I jxcore-log: DEBUG thaliReplicationPeerAction: Replication resumed
08-12 16:46:41.070  3787  3836 I jxcore-log: 
,08-12 16:46:41.612  3787  3836 I jxcore-log: DEBUG thaliReplicationPeerAction: Got paused with undefined
08-12 16:46:41.612  3787  3836 I jxcore-log: 
,08-12 16:46:41.738  3787  3836 I jxcore-log: ok 403 should be equal
08-12 16:46:41.738  3787  3836 I jxcore-log: 
,08-12 16:46:43.312  3787  3836 I jxcore-log: ok 404 action should be killed
08-12 16:46:43.312  3787  3836 I jxcore-log: 
,08-12 16:46:43.314  3787  3836 I jxcore-log: ok 405 Error should be timed out
08-12 16:46:43.314  3787  3836 I jxcore-log: 
,08-12 16:46:43.335  3787  3836 I jxcore-log: # teardown
08-12 16:46:43.335  3787  3836 I jxcore-log: 
,08-12 16:46:43.455  3787  3836 I jxcore-log: # setup,
08-12 16:46:43.455  3787  3836 I jxcore-log: 
,08-12 16:46:43.542  3787  3836 I jxcore-log: # 128. Start replicating and then catch error when server goes
08-12 16:46:43.542  3787  3836 I jxcore-log: 
,08-12 16:46:44.090  3787  3836 I jxcore-log: ok 406 socket hung up
08-12 16:46:44.090  3787  3836 I jxcore-log: 
,08-12 16:46:44.129  3787  3836 I jxcore-log: # teardown
08-12 16:46:44.129  3787  3836 I jxcore-log: 
,08-12 16:46:44.309  3787  3836 I jxcore-log: # setup
08-12 16:46:44.309  3787  3836 I jxcore-log: 
,08-12 16:46:44.389  3787  3836 I jxcore-log: # 129. compareBufferArrays
08-12 16:46:44.389  3787  3836 I jxcore-log: 
,08-12 16:46:44.429  3787  3836 I jxcore-log: ok 407 should throw
08-12 16:46:44.429  3787  3836 I jxcore-log: 
,08-12 16:46:44.431  3787  3836 I jxcore-log: ok 408 should throw
08-12 16:46:44.431  3787  3836 I jxcore-log: 
,08-12 16:46:44.431  3787  3836 I jxcore-log: ok 409 (unnamed assert)
08-12 16:46:44.431  3787  3836 I jxcore-log: 
08-12 16:46:44.431  3787  3836 I jxcore-log: ok 410 (unnamed assert)
08-12 16:46:44.431  3787  3836 I jxcore-log: 
08-12 16:46:44.432  3787  3836 I jxcore-log: ok 411 (unnamed assert)
08-12 16:46:44.432  3787  3836 I jxcore-log: 
08-12 16:46:44.432  3787  3836 I jxcore-log: ok 412 (unnamed assert)
08-12 16:46:44.432  3787  3836 I jxcore-log: 
08-12 16:46:44.433  3787  3836 I jxcore-log: ok 413 (unnamed assert)
08-12 16:46:44.433  3787  3836 I jxcore-log: 
08-12 16:46:44.434  3787  3836 I jxcore-log: # teardown
08-12 16:46:44.434  3787  3836 I jxcore-log: 
,08-12 16:46:44.473  3787  3836 I jxcore-log: # setup
08-12 16:46:44.473  3787  3836 I jxcore-log: 
,08-12 16:46:44.507  3787  3836 I jxcore-log: # 130. Call start twice and get error
08-12 16:46:44.507  3787  3836 I jxcore-log: 
,08-12 16:46:44.538  3787  3836 I jxcore-log: ok 414 should throw
08-12 16:46:44.538  3787  3836 I jxcore-log: 
,08-12 16:46:44.539  3787  3836 I jxcore-log: # teardown
08-12 16:46:44.539  3787  3836 I jxcore-log: 
,08-12 16:46:44.592  3787  3836 I jxcore-log: # setup
08-12 16:46:44.592  3787  3836 I jxcore-log: 
,08-12 16:46:44.629  3787  3836 I jxcore-log: # 131. Start and make sure it runs
08-12 16:46:44.629  3787  3836 I jxcore-log: 
,08-12 16:46:44.714  3787  3836 I jxcore-log: # teardown
08-12 16:46:44.714  3787  3836 I jxcore-log: 
,08-12 16:46:44.798  3787  3836 I jxcore-log: # setup
08-12 16:46:44.798  3787  3836 I jxcore-log: 
,08-12 16:46:44.858  3787  3836 I jxcore-log: # 132. Make sure getTimeWhenRun is right after start
08-12 16:46:44.858  3787  3836 I jxcore-log: 
,08-12 16:46:44.959  3787  3836 I jxcore-log: ok 415 (unnamed assert)
08-12 16:46:44.959  3787  3836 I jxcore-log: 
,08-12 16:46:44.965  3787  3836 I jxcore-log: # teardown
08-12 16:46:44.965  3787  3836 I jxcore-log: 
,08-12 16:46:45.007  3787  3836 I jxcore-log: # setup
08-12 16:46:45.007  3787  3836 I jxcore-log: 
,08-12 16:46:45.098  3787  3836 I jxcore-log: # 133. Make sure getTimeWhenRun is -1 after function is called
08-12 16:46:45.098  3787  3836 I jxcore-log: 
,08-12 16:46:45.160  3787  3836 I jxcore-log: ok 416 should be equal
08-12 16:46:45.160  3787  3836 I jxcore-log: 
,08-12 16:46:45.167  3787  3836 I jxcore-log: # teardown
08-12 16:46:45.167  3787  3836 I jxcore-log: 
,08-12 16:46:45.213  3787  3836 I jxcore-log: # setup
08-12 16:46:45.213  3787  3836 I jxcore-log: 
,08-12 16:46:45.304  3787  3836 I jxcore-log: # 134. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
08-12 16:46:45.304  3787  3836 I jxcore-log: 
,08-12 16:46:45.341  3787  3836 I jxcore-log: ok 417 should be equal
08-12 16:46:45.341  3787  3836 I jxcore-log: 
08-12 16:46:45.342  3787  3836 I jxcore-log: ok 418 should be equal
08-12 16:46:45.342  3787  3836 I jxcore-log: 
,08-12 16:46:45.344  3787  3836 I jxcore-log: ok 419 should throw
08-12 16:46:45.344  3787  3836 I jxcore-log: 
,08-12 16:46:45.347  3787  3836 I jxcore-log: # teardown
08-12 16:46:45.347  3787  3836 I jxcore-log: 
,08-12 16:46:45.431  3787  3836 I jxcore-log: # setup
08-12 16:46:45.431  3787  3836 I jxcore-log: 
,08-12 16:46:45.476  3787  3836 I jxcore-log: # 135. Test TransientState
08-12 16:46:45.476  3787  3836 I jxcore-log: 
,08-12 16:46:45.529  3787  3836 I jxcore-log: ok 420 should throw
08-12 16:46:45.529  3787  3836 I jxcore-log: 
,08-12 16:46:45.532  3787  3836 I jxcore-log: ok 421 should throw
08-12 16:46:45.532  3787  3836 I jxcore-log: 
,08-12 16:46:45.533  3787  3836 I jxcore-log: ok 422 should be equal
08-12 16:46:45.533  3787  3836 I jxcore-log: 
08-12 16:46:45.534  3787  3836 I jxcore-log: ok 423 should be equal
08-12 16:46:45.534  3787  3836 I jxcore-log: 
,08-12 16:46:45.535  3787  3836 I jxcore-log: ok 424 should be equal
08-12 16:46:45.535  3787  3836 I jxcore-log: 
,08-12 16:46:45.536  3787  3836 I jxcore-log: ok 425 should be equal
08-12 16:46:45.536  3787  3836 I jxcore-log: 
08-12 16:46:45.537  3787  3836 I jxcore-log: ok 426 (unnamed assert)
08-12 16:46:45.537  3787  3836 I jxcore-log: 
,08-12 16:46:45.537  3787  3836 I jxcore-log: ok 427 (unnamed assert)
08-12 16:46:45.537  3787  3836 I jxcore-log: 
08-12 16:46:45.541  3787  3836 I jxcore-log: # teardown
08-12 16:46:45.541  3787  3836 I jxcore-log: 
,08-12 16:46:45.611  3787  3836 I jxcore-log: # setup
08-12 16:46:45.611  3787  3836 I jxcore-log: 
,08-12 16:46:45.653  3787  3836 I jxcore-log: # 136. No peers and empty database
08-12 16:46:45.653  3787  3836 I jxcore-log: 
,08-12 16:46:45.819  3787  3836 I jxcore-log: ok 428 verify failed
08-12 16:46:45.819  3787  3836 I jxcore-log: 
,08-12 16:46:45.820  3787  3836 I jxcore-log: ok 429 constructor called once
08-12 16:46:45.820  3787  3836 I jxcore-log: 
08-12 16:46:45.821  3787  3836 I jxcore-log: ok 430 constructor called with right args
08-12 16:46:45.821  3787  3836 I jxcore-log: 
,08-12 16:46:45.821  3787  3836 I jxcore-log: ok 431 match start arg
08-12 16:46:45.821  3787  3836 I jxcore-log: 
08-12 16:46:45.821  3787  3836 I jxcore-log: ok 432 start called once
08-12 16:46:45.821  3787  3836 I jxcore-log: 
08-12 16:46:45.822  3787  3836 I jxcore-log: ok 433 stop called once
08-12 16:46:45.822  3787  3836 I jxcore-log: 
,08-12 16:46:45.822  3787  3836 I jxcore-log: ok 434 stop after start
08-12 16:46:45.822  3787  3836 I jxcore-log: 
08-12 16:46:45.826  3787  3836 I jxcore-log: # teardown
08-12 16:46:45.826  3787  3836 I jxcore-log: 
,08-12 16:46:45.877  3787  3836 I jxcore-log: # setup
08-12 16:46:45.877  3787  3836 I jxcore-log: 
,08-12 16:46:45.929  3787  3836 I jxcore-log: # 137. One peer and empty DB
08-12 16:46:45.929  3787  3836 I jxcore-log: 
,08-12 16:46:46.134  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:46.134  3787  3836 I jxcore-log: 
,08-12 16:46:46.136  3787  3836 I jxcore-log: ok 435 verify failed
08-12 16:46:46.136  3787  3836 I jxcore-log: 
,08-12 16:46:46.136  3787  3836 I jxcore-log: ok 436 constructor called once
08-12 16:46:46.136  3787  3836 I jxcore-log: 
,08-12 16:46:46.137  3787  3836 I jxcore-log: ok 437 constructor called with right args
08-12 16:46:46.137  3787  3836 I jxcore-log: 
08-12 16:46:46.137  3787  3836 I jxcore-log: ok 438 match start arg
08-12 16:46:46.137  3787  3836 I jxcore-log: 
,08-12 16:46:46.138  3787  3836 I jxcore-log: ok 439 start called once
08-12 16:46:46.138  3787  3836 I jxcore-log: 
08-12 16:46:46.138  3787  3836 I jxcore-log: ok 440 stop called once
08-12 16:46:46.138  3787  3836 I jxcore-log: 
08-12 16:46:46.138  3787  3836 I jxcore-log: ok 441 stop after start
08-12 16:46:46.138  3787  3836 I jxcore-log: 
,08-12 16:46:46.145  3787  3836 I jxcore-log: # teardown
08-12 16:46:46.145  3787  3836 I jxcore-log: 
,08-12 16:46:46.209  3787  3836 I jxcore-log: # setup
08-12 16:46:46.209  3787  3836 I jxcore-log: 
,08-12 16:46:46.241  3787  3836 I jxcore-log: # 138. One peer with _Local set behind current seq
08-12 16:46:46.241  3787  3836 I jxcore-log: 
,08-12 16:46:46.459  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:46.459  3787  3836 I jxcore-log: 
,08-12 16:46:46.461  3787  3836 I jxcore-log: ok 442 verify failed
08-12 16:46:46.461  3787  3836 I jxcore-log: 
,08-12 16:46:46.462  3787  3836 I jxcore-log: ok 443 constructor called once
08-12 16:46:46.462  3787  3836 I jxcore-log: 
,08-12 16:46:46.462  3787  3836 I jxcore-log: ok 444 constructor called with right args
08-12 16:46:46.462  3787  3836 I jxcore-log: 
08-12 16:46:46.463  3787  3836 I jxcore-log: ok 445 match start arg
08-12 16:46:46.463  3787  3836 I jxcore-log: 
,08-12 16:46:46.463  3787  3836 I jxcore-log: ok 446 start called once
08-12 16:46:46.463  3787  3836 I jxcore-log: 
08-12 16:46:46.464  3787  3836 I jxcore-log: ok 447 stop called once
08-12 16:46:46.464  3787  3836 I jxcore-log: 
08-12 16:46:46.464  3787  3836 I jxcore-log: ok 448 stop after start
08-12 16:46:46.464  3787  3836 I jxcore-log: 
,08-12 16:46:46.466  3787  3836 I jxcore-log: # teardown
08-12 16:46:46.466  3787  3836 I jxcore-log: 
,08-12 16:46:46.568  3787  3836 I jxcore-log: # setup
08-12 16:46:46.568  3787  3836 I jxcore-log: 
,08-12 16:46:46.603  3787  3836 I jxcore-log: # 139. One peer with _Local set equal to current seq
08-12 16:46:46.603  3787  3836 I jxcore-log: 
,08-12 16:46:46.877  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:46.877  3787  3836 I jxcore-log: 
08-12 16:46:46.878  3787  3836 I jxcore-log: ok 449 verify failed
08-12 16:46:46.878  3787  3836 I jxcore-log: 
08-12 16:46:46.878  3787  3836 I jxcore-log: ok 450 constructor called once
08-12 16:46:46.878  3787  3836 I jxcore-log: 
08-12 16:46:46.879  3787  3836 I jxcore-log: ok 451 constructor called with right args
08-12 16:46:46.879  3787  3836 I jxcore-log: 
,08-12 16:46:46.879  3787  3836 I jxcore-log: ok 452 match start arg
08-12 16:46:46.879  3787  3836 I jxcore-log: 
08-12 16:46:46.880  3787  3836 I jxcore-log: ok 453 start called once
08-12 16:46:46.880  3787  3836 I jxcore-log: 
08-12 16:46:46.880  3787  3836 I jxcore-log: ok 454 stop called once
08-12 16:46:46.880  3787  3836 I jxcore-log: 
,08-12 16:46:46.880  3787  3836 I jxcore-log: ok 455 stop after start
08-12 16:46:46.880  3787  3836 I jxcore-log: 
,08-12 16:46:46.884  3787  3836 I jxcore-log: # teardown
08-12 16:46:46.884  3787  3836 I jxcore-log: 
,08-12 16:46:46.911  3787  3836 I jxcore-log: # setup
08-12 16:46:46.911  3787  3836 I jxcore-log: 
,08-12 16:46:46.947  3787  3836 I jxcore-log: # 140. One peer with _Local set ahead of current seq (and no this should not happen)
08-12 16:46:46.947  3787  3836 I jxcore-log: 
,08-12 16:46:47.198  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:47.198  3787  3836 I jxcore-log: 
,08-12 16:46:47.200  3787  3836 I jxcore-log: ok 456 verify failed
08-12 16:46:47.200  3787  3836 I jxcore-log: 
,08-12 16:46:47.200  3787  3836 I jxcore-log: ok 457 constructor called once
08-12 16:46:47.200  3787  3836 I jxcore-log: 
,08-12 16:46:47.201  3787  3836 I jxcore-log: ok 458 constructor called with right args
08-12 16:46:47.201  3787  3836 I jxcore-log: 
08-12 16:46:47.202  3787  3836 I jxcore-log: ok 459 match start arg
08-12 16:46:47.202  3787  3836 I jxcore-log: 
,08-12 16:46:47.202  3787  3836 I jxcore-log: ok 460 start called once
08-12 16:46:47.202  3787  3836 I jxcore-log: 
,08-12 16:46:47.203  3787  3836 I jxcore-log: ok 461 stop called once
08-12 16:46:47.203  3787  3836 I jxcore-log: 
08-12 16:46:47.203  3787  3836 I jxcore-log: ok 462 stop after start
08-12 16:46:47.203  3787  3836 I jxcore-log: 
08-12 16:46:47.208  3787  3836 I jxcore-log: # teardown
08-12 16:46:47.208  3787  3836 I jxcore-log: 
,08-12 16:46:47.270  3787  3836 I jxcore-log: # setup
08-12 16:46:47.270  3787  3836 I jxcore-log: 
,08-12 16:46:47.309  3787  3836 I jxcore-log: # 141. Three peers, one not in DB, one behind and one ahead
08-12 16:46:47.309  3787  3836 I jxcore-log: 
,08-12 16:46:47.644  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:47.644  3787  3836 I jxcore-log: 
,08-12 16:46:47.646  3787  3836 I jxcore-log: ok 463 verify failed
08-12 16:46:47.646  3787  3836 I jxcore-log: 
,08-12 16:46:47.647  3787  3836 I jxcore-log: ok 464 constructor called once
08-12 16:46:47.647  3787  3836 I jxcore-log: 
,08-12 16:46:47.648  3787  3836 I jxcore-log: ok 465 constructor called with right args
08-12 16:46:47.648  3787  3836 I jxcore-log: 
,08-12 16:46:47.649  3787  3836 I jxcore-log: ok 466 match start arg
08-12 16:46:47.649  3787  3836 I jxcore-log: 
08-12 16:46:47.649  3787  3836 I jxcore-log: ok 467 start called once
08-12 16:46:47.649  3787  3836 I jxcore-log: 
08-12 16:46:47.650  3787  3836 I jxcore-log: ok 468 stop called once
08-12 16:46:47.650  3787  3836 I jxcore-log: 
,08-12 16:46:47.651  3787  3836 I jxcore-log: ok 469 stop after start
08-12 16:46:47.651  3787  3836 I jxcore-log: 
,08-12 16:46:47.655  3787  3836 I jxcore-log: # teardown
08-12 16:46:47.655  3787  3836 I jxcore-log: 
,08-12 16:46:47.746  3787  3836 I jxcore-log: # setup
08-12 16:46:47.746  3787  3836 I jxcore-log: 
,08-12 16:46:47.801  3787  3836 I jxcore-log: # 142. More than maximum peers, make sure we only send maximum allowed
08-12 16:46:47.801  3787  3836 I jxcore-log: 
,08-12 16:46:48.440  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:48.440  3787  3836 I jxcore-log: 
,08-12 16:46:48.442  3787  3836 I jxcore-log: ok 470 verify failed
08-12 16:46:48.442  3787  3836 I jxcore-log: 
08-12 16:46:48.442  3787  3836 I jxcore-log: ok 471 constructor called once
08-12 16:46:48.442  3787  3836 I jxcore-log: 
,08-12 16:46:48.443  3787  3836 I jxcore-log: ok 472 constructor called with right args
08-12 16:46:48.443  3787  3836 I jxcore-log: 
08-12 16:46:48.444  3787  3836 I jxcore-log: ok 473 match start arg
08-12 16:46:48.444  3787  3836 I jxcore-log: 
,08-12 16:46:48.444  3787  3836 I jxcore-log: ok 474 start called once
08-12 16:46:48.444  3787  3836 I jxcore-log: 
08-12 16:46:48.445  3787  3836 I jxcore-log: ok 475 stop called once
08-12 16:46:48.445  3787  3836 I jxcore-log: 
08-12 16:46:48.445  3787  3836 I jxcore-log: ok 476 stop after start
08-12 16:46:48.445  3787  3836 I jxcore-log: 
,08-12 16:46:48.451  3787  3836 I jxcore-log: # teardown
08-12 16:46:48.451  3787  3836 I jxcore-log: 
,08-12 16:46:48.700  3787  3836 I jxcore-log: # setup
08-12 16:46:48.700  3787  3836 I jxcore-log: 
,08-12 16:46:48.740  3787  3836 I jxcore-log: # 143. two peers with empty DB, update the doc
08-12 16:46:48.740  3787  3836 I jxcore-log: 
,08-12 16:46:48.984  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:48.984  3787  3836 I jxcore-log: 
,08-12 16:46:49.020  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:49.020  3787  3836 I jxcore-log: 
,08-12 16:46:49.022  3787  3836 I jxcore-log: ok 477 verify failed
08-12 16:46:49.022  3787  3836 I jxcore-log: 
,08-12 16:46:49.022  3787  3836 I jxcore-log: ok 478 constructor called once
08-12 16:46:49.022  3787  3836 I jxcore-log: 
,08-12 16:46:49.023  3787  3836 I jxcore-log: ok 479 constructor called with right args
08-12 16:46:49.023  3787  3836 I jxcore-log: 
08-12 16:46:49.023  3787  3836 I jxcore-log: ok 480 last start before stop
08-12 16:46:49.023  3787  3836 I jxcore-log: 
,08-12 16:46:49.024  3787  3836 I jxcore-log: ok 481 empty first start
08-12 16:46:49.024  3787  3836 I jxcore-log: 
08-12 16:46:49.025  3787  3836 I jxcore-log: ok 482 full second start
08-12 16:46:49.025  3787  3836 I jxcore-log: 
08-12 16:46:49.025  3787  3836 I jxcore-log: ok 483 only 2 timers
08-12 16:46:49.025  3787  3836 I jxcore-log: 
,08-12 16:46:49.029  3787  3836 I jxcore-log: # teardown
08-12 16:46:49.029  3787  3836 I jxcore-log: 
,08-12 16:46:49.053  3787  3836 I jxcore-log: # setup
08-12 16:46:49.053  3787  3836 I jxcore-log: 
,08-12 16:46:49.113  3787  3836 I jxcore-log: # 144. add doc and make sure tokens refresh when they expire
08-12 16:46:49.113  3787  3836 I jxcore-log: 
,08-12 16:46:49.543  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:49.543  3787  3836 I jxcore-log: 
,08-12 16:46:49.671  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:49.671  3787  3836 I jxcore-log: 
,08-12 16:46:49.774  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:49.774  3787  3836 I jxcore-log: 
,08-12 16:46:49.783  3787  3836 I jxcore-log: ok 484 verify failed
08-12 16:46:49.783  3787  3836 I jxcore-log: 
,08-12 16:46:49.786  3787  3836 I jxcore-log: ok 485 constructor called once
08-12 16:46:49.786  3787  3836 I jxcore-log: 
,08-12 16:46:49.787  3787  3836 I jxcore-log: ok 486 constructor called with right args
08-12 16:46:49.787  3787  3836 I jxcore-log: 
,08-12 16:46:49.789  3787  3836 I jxcore-log: ok 487 start before stop
08-12 16:46:49.789  3787  3836 I jxcore-log: 
,08-12 16:46:49.789  3787  3836 I jxcore-log: ok 488 We got at least 3 calls to start
08-12 16:46:49.789  3787  3836 I jxcore-log: 
,08-12 16:46:49.789  3787  3836 I jxcore-log: ok 489 at least 3
08-12 16:46:49.789  3787  3836 I jxcore-log: 
08-12 16:46:49.790  3787  3836 I jxcore-log: ok 490 default 1
08-12 16:46:49.790  3787  3836 I jxcore-log: 
08-12 16:46:49.791  3787  3836 I jxcore-log: ok 491 1 run
08-12 16:46:49.791  3787  3836 I jxcore-log: 
,08-12 16:46:49.791  3787  3836 I jxcore-log: ok 492 default 2
08-12 16:46:49.791  3787  3836 I jxcore-log: 
08-12 16:46:49.792  3787  3836 I jxcore-log: ok 493 2 run
08-12 16:46:49.792  3787  3836 I jxcore-log: 
08-12 16:46:49.792  3787  3836 I jxcore-log: ok 494 default 3
08-12 16:46:49.792  3787  3836 I jxcore-log: 
,08-12 16:46:49.796  3787  3836 I jxcore-log: # teardown
08-12 16:46:49.796  3787  3836 I jxcore-log: 
,08-12 16:46:49.859  3787  3836 I jxcore-log: # setup
08-12 16:46:49.859  3787  3836 I jxcore-log: 
,08-12 16:46:49.898  3787  3836 I jxcore-log: # 145. start and stop and start and stop
08-12 16:46:49.898  3787  3836 I jxcore-log: 
,08-12 16:46:50.129  3787  3836 I jxcore-log: ok 495 start out null
08-12 16:46:50.129  3787  3836 I jxcore-log: 
,08-12 16:46:50.160  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:50.160  3787  3836 I jxcore-log: 
,08-12 16:46:50.161  3787  3836 I jxcore-log: ok 496 back to null
08-12 16:46:50.161  3787  3836 I jxcore-log: 
,08-12 16:46:50.189  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:50.189  3787  3836 I jxcore-log: 
,08-12 16:46:50.190  3787  3836 I jxcore-log: ok 497 still null
08-12 16:46:50.190  3787  3836 I jxcore-log: 
,08-12 16:46:50.191  3787  3836 I jxcore-log: ok 498 verify failed
08-12 16:46:50.191  3787  3836 I jxcore-log: 
08-12 16:46:50.192  3787  3836 I jxcore-log: ok 499 constructor called once
08-12 16:46:50.192  3787  3836 I jxcore-log: 
08-12 16:46:50.192  3787  3836 I jxcore-log: ok 500 constructor called with right args
08-12 16:46:50.192  3787  3836 I jxcore-log: 
08-12 16:46:50.193  3787  3836 I jxcore-log: ok 501 first start before first stop
08-12 16:46:50.193  3787  3836 I jxcore-log: 
,08-12 16:46:50.193  3787  3836 I jxcore-log: ok 502 first stop before second start
08-12 16:46:50.193  3787  3836 I jxcore-log: 
08-12 16:46:50.193  3787  3836 I jxcore-log: ok 503 second start before second stop
08-12 16:46:50.193  3787  3836 I jxcore-log: 
,08-12 16:46:50.200  3787  3836 I jxcore-log: # teardown
08-12 16:46:50.200  3787  3836 I jxcore-log: 
,08-12 16:46:50.272  3787  3836 I jxcore-log: # setup
08-12 16:46:50.272  3787  3836 I jxcore-log: 
,08-12 16:46:50.311  3787  3836 I jxcore-log: # 146. two identical starts in a row
08-12 16:46:50.311  3787  3836 I jxcore-log: 
,08-12 16:46:50.591  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:50.591  3787  3836 I jxcore-log: 
,08-12 16:46:50.593  3787  3836 I jxcore-log: ok 504 verify failed
08-12 16:46:50.593  3787  3836 I jxcore-log: 
,08-12 16:46:50.594  3787  3836 I jxcore-log: ok 505 constructor called once
08-12 16:46:50.594  3787  3836 I jxcore-log: 
08-12 16:46:50.594  3787  3836 I jxcore-log: ok 506 constructor called with right args
08-12 16:46:50.594  3787  3836 I jxcore-log: 
,08-12 16:46:50.595  3787  3836 I jxcore-log: ok 507 (unnamed assert)
08-12 16:46:50.595  3787  3836 I jxcore-log: 
,08-12 16:46:50.601  3787  3836 I jxcore-log: # teardown
08-12 16:46:50.601  3787  3836 I jxcore-log: 
,08-12 16:46:50.626  3787  3836 I jxcore-log: # setup
08-12 16:46:50.626  3787  3836 I jxcore-log: 
,08-12 16:46:50.663  3787  3836 I jxcore-log: # 147. two different starts in a row
08-12 16:46:50.663  3787  3836 I jxcore-log: 
,08-12 16:46:50.952  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:50.952  3787  3836 I jxcore-log: 
,08-12 16:46:50.959  3787  3836 I jxcore-log: ok 508 verify failed
08-12 16:46:50.959  3787  3836 I jxcore-log: 
,08-12 16:46:50.960  3787  3836 I jxcore-log: ok 509 constructor called once
08-12 16:46:50.960  3787  3836 I jxcore-log: 
,08-12 16:46:50.960  3787  3836 I jxcore-log: ok 510 constructor called with right args
08-12 16:46:50.960  3787  3836 I jxcore-log: 
,08-12 16:46:50.960  3787  3836 I jxcore-log: ok 511 (unnamed assert)
08-12 16:46:50.960  3787  3836 I jxcore-log: 
08-12 16:46:50.961  3787  3836 I jxcore-log: ok 512 (unnamed assert)
08-12 16:46:50.961  3787  3836 I jxcore-log: 
,08-12 16:46:50.972  3787  3836 I jxcore-log: # teardown
08-12 16:46:50.972  3787  3836 I jxcore-log: 
,08-12 16:46:50.998  3787  3836 I jxcore-log: # setup
08-12 16:46:50.998  3787  3836 I jxcore-log: 
,08-12 16:46:51.034  3787  3836 I jxcore-log: # 148. two stops and a start and two stops
08-12 16:46:51.034  3787  3836 I jxcore-log: 
,08-12 16:46:51.330  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:51.330  3787  3836 I jxcore-log: 
,08-12 16:46:51.333  3787  3836 I jxcore-log: ok 513 verify failed
08-12 16:46:51.333  3787  3836 I jxcore-log: 
,08-12 16:46:51.333  3787  3836 I jxcore-log: ok 514 constructor called once
08-12 16:46:51.333  3787  3836 I jxcore-log: 
08-12 16:46:51.334  3787  3836 I jxcore-log: ok 515 constructor called with right args
08-12 16:46:51.334  3787  3836 I jxcore-log: 
,08-12 16:46:51.335  3787  3836 I jxcore-log: ok 516 start before stop
08-12 16:46:51.335  3787  3836 I jxcore-log: 
,08-12 16:46:51.342  3787  3836 I jxcore-log: # teardown
08-12 16:46:51.342  3787  3836 I jxcore-log: 
,08-12 16:46:51.401  3787  3836 I jxcore-log: # setup
08-12 16:46:51.401  3787  3836 I jxcore-log: 
,08-12 16:46:51.435  3787  3836 I jxcore-log: # 149. we properly enqueue requests so no then needed
08-12 16:46:51.435  3787  3836 I jxcore-log: 
,08-12 16:46:51.714  3787  3836 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 16:46:51.714  3787  3836 I jxcore-log: 
,08-12 16:46:51.716  3787  3836 I jxcore-log: ok 517 verify failed
08-12 16:46:51.716  3787  3836 I jxcore-log: 
08-12 16:46:51.717  3787  3836 I jxcore-log: ok 518 constructor called once
08-12 16:46:51.717  3787  3836 I jxcore-log: 
,08-12 16:46:51.717  3787  3836 I jxcore-log: ok 519 constructor called with right args
08-12 16:46:51.717  3787  3836 I jxcore-log: 
,08-12 16:46:51.718  3787  3836 I jxcore-log: ok 520 start before stop
08-12 16:46:51.718  3787  3836 I jxcore-log: 
,08-12 16:46:51.733  3787  3836 I jxcore-log: # teardown
08-12 16:46:51.733  3787  3836 I jxcore-log: 
,08-12 16:46:51.802  3787  3836 I jxcore-log: # setup
08-12 16:46:51.802  3787  3836 I jxcore-log: 
,08-12 16:46:51.851  3787  3836 I jxcore-log: # 150. test calculateSeqPointKeyId
08-12 16:46:51.851  3787  3836 I jxcore-log: 
,08-12 16:46:51.956  3787  3836 I jxcore-log: ok 521 should be equal
08-12 16:46:51.956  3787  3836 I jxcore-log: 
,08-12 16:46:51.957  3787  3836 I jxcore-log: ok 522 should be equal
08-12 16:46:51.957  3787  3836 I jxcore-log: 
,08-12 16:46:51.960  3787  3836 I jxcore-log: # teardown
08-12 16:46:51.960  3787  3836 I jxcore-log: 
,08-12 16:46:52.029  3787  3836 I jxcore-log: # setup
08-12 16:46:52.029  3787  3836 I jxcore-log: 
,08-12 16:46:52.061  3787  3836 I jxcore-log: # 151. can create servers manager
08-12 16:46:52.061  3787  3836 I jxcore-log: 
,08-12 16:46:52.106  3787  3836 I jxcore-log: ok 523 serversManager must not be null
08-12 16:46:52.106  3787  3836 I jxcore-log: 
,08-12 16:46:52.108  3787  3836 I jxcore-log: ok 524 serversManager must be an object
08-12 16:46:52.108  3787  3836 I jxcore-log: 
,08-12 16:46:52.114  3787  3836 I jxcore-log: # teardown
08-12 16:46:52.114  3787  3836 I jxcore-log: 
,08-12 16:46:52.168  3787  3836 I jxcore-log: # setup
08-12 16:46:52.168  3787  3836 I jxcore-log: 
,08-12 16:46:52.216  3787  3836 I jxcore-log: # 152. calling stop without start causes error
08-12 16:46:52.216  3787  3836 I jxcore-log: 
,08-12 16:46:52.264  3787  3836 I jxcore-log: ok 525 We need to call start first
08-12 16:46:52.264  3787  3836 I jxcore-log: 
,08-12 16:46:52.268  3787  3836 I jxcore-log: # teardown
08-12 16:46:52.268  3787  3836 I jxcore-log: 
,08-12 16:46:52.337  3787  3836 I jxcore-log: # setup
08-12 16:46:52.337  3787  3836 I jxcore-log: 
,08-12 16:46:52.385  3787  3836 I jxcore-log: # 153. can start/stop servers manager
08-12 16:46:52.385  3787  3836 I jxcore-log: 
,08-12 16:46:52.440  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:46:52.440  3787  3836 I jxcore-log: 
,08-12 16:46:52.450  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 46409
08-12 16:46:52.450  3787  3836 I jxcore-log: 
,08-12 16:46:52.452  3787  3836 I jxcore-log: ok 526 port must be in range
08-12 16:46:52.452  3787  3836 I jxcore-log: 
,08-12 16:46:52.454  3787  3836 I jxcore-log: # teardown
08-12 16:46:52.454  3787  3836 I jxcore-log: 
,08-12 16:46:52.493  3787  3836 I jxcore-log: # setup
08-12 16:46:52.493  3787  3836 I jxcore-log: 
,08-12 16:46:52.546  3787  3836 I jxcore-log: # 154. starting twice resolves with listening port
08-12 16:46:52.546  3787  3836 I jxcore-log: 
,08-12 16:46:52.604  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:46:52.604  3787  3836 I jxcore-log: 
,08-12 16:46:52.611  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 40497
08-12 16:46:52.611  3787  3836 I jxcore-log: 
,08-12 16:46:52.613  3787  3836 I jxcore-log: ok 527 second start should return same port
08-12 16:46:52.613  3787  3836 I jxcore-log: 
,08-12 16:46:52.615  3787  3836 I jxcore-log: # teardown
08-12 16:46:52.615  3787  3836 I jxcore-log: 
,08-12 16:46:52.659  3787  3836 I jxcore-log: # setup
08-12 16:46:52.659  3787  3836 I jxcore-log: 
,08-12 16:46:52.707  3787  3836 I jxcore-log: # 155. terminateIncomingConnection will terminate a connection
08-12 16:46:52.707  3787  3836 I jxcore-log: 
,08-12 16:46:52.785  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:46:52.785  3787  3836 I jxcore-log: 
,08-12 16:46:52.789  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 45304
08-12 16:46:52.789  3787  3836 I jxcore-log: 
,08-12 16:46:52.797  3787  3836 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 16:46:52.797  3787  3836 I jxcore-log: 
,08-12 16:46:52.798  3787  3836 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 16:46:52.798  3787  3836 I jxcore-log: 
,08-12 16:46:52.800  3787  3836 I jxcore-log: DEBUG createNativeListener: new mux
08-12 16:46:52.800  3787  3836 I jxcore-log: 
,08-12 16:46:52.803  3787  3836 I jxcore-log: ok 528 we should be connected
08-12 16:46:52.803  3787  3836 I jxcore-log: 
,08-12 16:46:52.807  3787  3836 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 16:46:52.807  3787  3836 I jxcore-log: 
,08-12 16:46:52.808  3787  3836 I jxcore-log: ok 529 now we are disconnected
08-12 16:46:52.808  3787  3836 I jxcore-log: 
,08-12 16:46:52.822  3787  3836 I jxcore-log: # teardown
08-12 16:46:52.822  3787  3836 I jxcore-log: 
,08-12 16:46:52.890  3787  3836 I jxcore-log: # setup
08-12 16:46:52.890  3787  3836 I jxcore-log: 
,08-12 16:46:52.926  3787  3836 I jxcore-log: # 156. terminate an Outgoing connection will terminate the server
,08-12 16:46:52.926  3787  3836 I jxcore-log: 
,08-12 16:46:52.972  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:46:52.972  3787  3836 I jxcore-log: 
,08-12 16:46:52.976  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 37257
08-12 16:46:52.976  3787  3836 I jxcore-log: 
,08-12 16:46:52.978  3787  3836 I jxcore-log: # teardown
08-12 16:46:52.978  3787  3836 I jxcore-log: 
,08-12 16:46:53.032  3787  3836 I jxcore-log: # setup
08-12 16:46:53.032  3787  3836 I jxcore-log: 
,08-12 16:46:53.110  3787  3836 I jxcore-log: # 157. terminate an Outgoing connection with wrong arguments is not harmful
08-12 16:46:53.110  3787  3836 I jxcore-log: 
,08-12 16:46:53.150  3787  3836 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 16:46:53.150  3787  3836 I jxcore-log: 
,08-12 16:46:53.153  3787  3836 I jxcore-log: DEBUG createNativeListener: listening 44503
08-12 16:46:53.153  3787  3836 I jxcore-log: 
,08-12 16:46:53.156  3787  3836 I jxcore-log: # teardown
08-12 16:46:53.156  3787  3836 I jxcore-log: 
,08-12 16:46:53.208  3787  3836 I jxcore-log: # setup
08-12 16:46:53.208  3787  3836 I jxcore-log: 
,08-12 16:46:53.264  3787  3836 I jxcore-log: ok 530 should be in started state
08-12 16:46:53.264  3787  3836 I jxcore-log: 
,08-12 16:46:53.266  3787  3836 I jxcore-log: # 158. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
08-12 16:46:53.266  3787  3836 I jxcore-log: 
,08-12 16:46:53.359  3787  3836 I jxcore-log: ok 531 peer identifier should match
08-12 16:46:53.359  3787  3836 I jxcore-log: 
,08-12 16:46:53.360  3787  3836 I jxcore-log: ok 532 host address should match
08-12 16:46:53.360  3787  3836 I jxcore-log: 
08-12 16:46:53.360  3787  3836 I jxcore-log: ok 533 port should match
08-12 16:46:53.360  3787  3836 I jxcore-log: 
,08-12 16:46:53.368  3787  3836 I jxcore-log: ok 534 host address should be null
08-12 16:46:53.368  3787  3836 I jxcore-log: 
,08-12 16:46:53.369  3787  3836 I jxcore-log: ok 535 port should should be null
08-12 16:46:53.369  3787  3836 I jxcore-log: 
,08-12 16:46:53.373  3787  3836 I jxcore-log: # teardown
08-12 16:46:53.373  3787  3836 I jxcore-log: 
,08-12 16:46:53.434  3787  3836 I jxcore-log: ok 536 should not be in started state
08-12 16:46:53.434  3787  3836 I jxcore-log: 
,08-12 16:46:53.439  3787  3836 I jxcore-log: # setup
08-12 16:46:53.439  3787  3836 I jxcore-log: 
,08-12 16:46:53.506  3787  3836 I jxcore-log: ok 537 should be in started state
08-12 16:46:53.506  3787  3836 I jxcore-log: 
,08-12 16:46:53.514  3787  3836 I jxcore-log: # 159. #startUpdateAdvertisingAndListening should use different USN after every invocation
08-12 16:46:53.514  3787  3836 I jxcore-log: 
,08-12 16:46:53.623  3787  3836 I jxcore-log: ok 538 USN should have changed from the first one
08-12 16:46:53.623  3787  3836 I jxcore-log: 
,08-12 16:46:53.630  3787  3836 I jxcore-log: ok 539 when receiving the second byebye, the first USN should be already set
08-12 16:46:53.630  3787  3836 I jxcore-log: 
,08-12 16:46:53.634  3787  3836 I jxcore-log: # teardown
08-12 16:46:53.634  3787  3836 I jxcore-log: 
,08-12 16:46:53.705  3787  3836 I jxcore-log: ok 540 should not be in started state
08-12 16:46:53.705  3787  3836 I jxcore-log: 
,08-12 16:46:53.710  3787  3836 I jxcore-log: # setup
08-12 16:46:53.710  3787  3836 I jxcore-log: 
,08-12 16:46:53.760  3787  3836 I jxcore-log: ok 541 should be in started state
08-12 16:46:53.760  3787  3836 I jxcore-log: 
,08-12 16:46:53.764  3787  3836 I jxcore-log: # 160. messages with invalid location or USN should be ignored
08-12 16:46:53.764  3787  3836 I jxcore-log: 
,08-12 16:46:53.837  3787  3836 I jxcore-log: WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
08-12 16:46:53.837  3787  3836 I jxcore-log: 
,08-12 16:46:53.838  3787  3836 I jxcore-log: ok 542 should not have emitted with invalid port
08-12 16:46:53.838  3787  3836 I jxcore-log: 
08-12 16:46:53.840  3787  3836 I jxcore-log: WARN thaliWifiInfrastructure: Received an invalid USN value: 
08-12 16:46:53.840  3787  3836 I jxcore-log: 
08-12 16:46:53.840  3787  3836 I jxcore-log: ok 543 should not have emitted with invalid USN
08-12 16:46:53.840  3787  3836 I jxcore-log: 
,08-12 16:46:53.842  3787  3836 I jxcore-log: # teardown
08-12 16:46:53.842  3787  3836 I jxcore-log: 
,08-12 16:46:53.899  3787  3836 I jxcore-log: ok 544 should not be in started state
08-12 16:46:53.899  3787  3836 I jxcore-log: 
,08-12 16:46:53.901  3787  3836 I jxcore-log: # setup
08-12 16:46:53.901  3787  3836 I jxcore-log: 
,08-12 16:46:53.938  3787  3836 I jxcore-log: ok 545 should be in started state
08-12 16:46:53.938  3787  3836 I jxcore-log: 
,08-12 16:46:53.940  3787  3836 I jxcore-log: # 161. verify that Thali-specific messages are filtered correctly
08-12 16:46:53.940  3787  3836 I jxcore-log: 
,08-12 16:46:54.064  3787  3836 I jxcore-log: ok 546 irrelevant messages should be ignored
08-12 16:46:54.064  3787  3836 I jxcore-log: 
,08-12 16:46:54.067  3787  3836 I jxcore-log: ok 547 relevant messages should not be ignored
08-12 16:46:54.067  3787  3836 I jxcore-log: 
,08-12 16:46:54.069  3787  3836 I jxcore-log: ok 548 messages from this device should be ignored
08-12 16:46:54.069  3787  3836 I jxcore-log: 
,08-12 16:46:54.074  3787  3836 I jxcore-log: # teardown
08-12 16:46:54.074  3787  3836 I jxcore-log: 
,08-12 16:46:54.123  3787  3836 I jxcore-log: ok 549 should not be in started state
08-12 16:46:54.123  3787  3836 I jxcore-log: 
,08-12 16:46:54.129  3787  3836 I jxcore-log: # setup
08-12 16:46:54.129  3787  3836 I jxcore-log: 
,08-12 16:46:54.173  3787  3836 I jxcore-log: ok 550 should be in started state
08-12 16:46:54.173  3787  3836 I jxcore-log: 
,08-12 16:46:54.175  3787  3836 I jxcore-log: # 162. #startListeningForAdvertisements should fail if start not called
08-12 16:46:54.175  3787  3836 I jxcore-log: 
,08-12 16:46:54.246  3787  3836 I jxcore-log: ok 551 specific error should be returned
08-12 16:46:54.246  3787  3836 I jxcore-log: 
,08-12 16:46:54.248  3787  3836 I jxcore-log: # teardown
08-12 16:46:54.248  3787  3836 I jxcore-log: 
,08-12 16:46:54.306  3787  3836 I jxcore-log: ok 552 should not be in started state
08-12 16:46:54.306  3787  3836 I jxcore-log: 
,08-12 16:46:54.308  3787  3836 I jxcore-log: # setup
08-12 16:46:54.308  3787  3836 I jxcore-log: 
,08-12 16:46:54.366  3787  3836 I jxcore-log: ok 553 should be in started state
08-12 16:46:54.366  3787  3836 I jxcore-log: 
,08-12 16:46:54.368  3787  3836 I jxcore-log: # 163. #startUpdateAdvertisingAndListening should fail if start not called
08-12 16:46:54.368  3787  3836 I jxcore-log: 
,08-12 16:46:54.438  3787  3836 I jxcore-log: ok 554 specific error should be returned
08-12 16:46:54.438  3787  3836 I jxcore-log: 
,08-12 16:46:54.444  3787  3836 I jxcore-log: # teardown
08-12 16:46:54.444  3787  3836 I jxcore-log: 
,08-12 16:46:54.479  3787  3836 I jxcore-log: ok 555 should not be in started state
08-12 16:46:54.479  3787  3836 I jxcore-log: 
,08-12 16:46:54.481  3787  3836 I jxcore-log: # setup
08-12 16:46:54.481  3787  3836 I jxcore-log: 
,08-12 16:46:54.567  3787  3836 I jxcore-log: ok 556 should be in started state
08-12 16:46:54.567  3787  3836 I jxcore-log: 
,08-12 16:46:54.572  3787  3836 I jxcore-log: # 164. #start should fail if called twice in a row
08-12 16:46:54.572  3787  3836 I jxcore-log: 
,08-12 16:46:54.694  3787  3836 I jxcore-log: ok 557 specific error should be received
08-12 16:46:54.694  3787  3836 I jxcore-log: 
,08-12 16:46:54.701  3787  3836 I jxcore-log: # teardown
08-12 16:46:54.701  3787  3836 I jxcore-log: 
,08-12 16:46:54.735  3787  3836 I jxcore-log: ok 558 should not be in started state
08-12 16:46:54.735  3787  3836 I jxcore-log: 
,08-12 16:46:54.737  3787  3836 I jxcore-log: # setup
08-12 16:46:54.737  3787  3836 I jxcore-log: 
,08-12 16:46:54.806  3787  3836 I jxcore-log: ok 559 should be in started state
08-12 16:46:54.806  3787  3836 I jxcore-log: 
,08-12 16:46:54.809  3787  3836 I jxcore-log: # 165. should not be started after stop is called
08-12 16:46:54.809  3787  3836 I jxcore-log: 
,08-12 16:46:54.858  3787  3836 I jxcore-log: ok 560 should not be started
08-12 16:46:54.858  3787  3836 I jxcore-log: 
,08-12 16:46:54.859  3787  3836 I jxcore-log: ok 561 should not be listening
08-12 16:46:54.859  3787  3836 I jxcore-log: 
,08-12 16:46:54.860  3787  3836 I jxcore-log: ok 562 should not target listening
08-12 16:46:54.860  3787  3836 I jxcore-log: 
08-12 16:46:54.861  3787  3836 I jxcore-log: ok 563 should not be advertising
08-12 16:46:54.861  3787  3836 I jxcore-log: 
,08-12 16:46:54.862  3787  3836 I jxcore-log: ok 564 should not target advertising
08-12 16:46:54.862  3787  3836 I jxcore-log: 
,08-12 16:46:54.865  3787  3836 I jxcore-log: # teardown
08-12 16:46:54.865  3787  3836 I jxcore-log: 
,08-12 16:46:54.938  3787  3836 I jxcore-log: ok 565 should not be in started state
08-12 16:46:54.938  3787  3836 I jxcore-log: 
,08-12 16:46:54.943  3787  3836 I jxcore-log: # setup
08-12 16:46:54.943  3787  3836 I jxcore-log: 
,08-12 16:46:55.001  3787  3836 I jxcore-log: ok 566 should be in started state
08-12 16:46:55.001  3787  3836 I jxcore-log: 
,08-12 16:46:55.006  3787  3836 I jxcore-log: # 166. #startUpdateAdvertisingAndListening should fail invalid router has been passed
08-12 16:46:55.006  3787  3836 I jxcore-log: 
,08-12 16:46:55.056  3787  3836 I jxcore-log: ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
08-12 16:46:55.056  3787  3836 I jxcore-log: 
,08-12 16:46:55.058  3787  3836 I jxcore-log: ok 567 specific error should be received
08-12 16:46:55.058  3787  3836 I jxcore-log: 
,08-12 16:46:55.061  3787  3836 I jxcore-log: # teardown
08-12 16:46:55.061  3787  3836 I jxcore-log: 
,08-12 16:46:55.129  3787  3836 I jxcore-log: ok 568 should not be in started state
08-12 16:46:55.129  3787  3836 I jxcore-log: 
,08-12 16:46:55.148  3787  3836 I jxcore-log: # setup
08-12 16:46:55.148  3787  3836 I jxcore-log: 
,08-12 16:46:55.211  3787  3836 I jxcore-log: ok 569 should be in started state
08-12 16:46:55.211  3787  3836 I jxcore-log: 
,08-12 16:46:55.215  3787  3836 I jxcore-log: # 167. #startUpdateAdvertisingAndListening should fail if router server starting fails
08-12 16:46:55.215  3787  3836 I jxcore-log: 
,08-12 16:46:55.290  3787  3836 I jxcore-log: ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
08-12 16:46:55.290  3787  3836 I jxcore-log: 
,08-12 16:46:55.292  3787  3836 I jxcore-log: ok 570 specific error expected
08-12 16:46:55.292  3787  3836 I jxcore-log: 
,08-12 16:46:55.295  3787  3836 I jxcore-log: # teardown
08-12 16:46:55.295  3787  3836 I jxcore-log: 
,08-12 16:46:55.344  3787  3836 I jxcore-log: ok 571 should not be in started state
08-12 16:46:55.344  3787  3836 I jxcore-log: 
,08-12 16:46:55.348  3787  3836 I jxcore-log: # setup
08-12 16:46:55.348  3787  3836 I jxcore-log: 
,08-12 16:46:55.389  3787  3836 I jxcore-log: ok 572 should be in started state
08-12 16:46:55.389  3787  3836 I jxcore-log: 
,08-12 16:46:55.391  3787  3836 I jxcore-log: # 168. #startUpdateAdvertisingAndListening should start hosting given router object
08-12 16:46:55.391  3787  3836 I jxcore-log: 
,08-12 16:46:55.526  3787  3836 I jxcore-log: ok 573 server should respond with code 200
08-12 16:46:55.526  3787  3836 I jxcore-log: 
,08-12 16:46:55.533  3787  3836 I jxcore-log: # teardown
08-12 16:46:55.533  3787  3836 I jxcore-log: 
,08-12 16:46:55.628  3787  3836 I jxcore-log: ok 574 should not be in started state
08-12 16:46:55.628  3787  3836 I jxcore-log: 
,08-12 16:46:55.634  3787  3836 I jxcore-log: # setup
08-12 16:46:55.634  3787  3836 I jxcore-log: 
,08-12 16:46:55.682  3787  3836 I jxcore-log: ok 575 should be in started state
08-12 16:46:55.682  3787  3836 I jxcore-log: 
,08-12 16:46:55.686  3787  3836 I jxcore-log: # 169. #startUpdateAdvertisingAndListening bad psk should be rejected object
08-12 16:46:55.686  3787  3836 I jxcore-log: 
,08-12 16:46:55.809  3787  3836 I jxcore-log: ok 576 Connection should be rejected
08-12 16:46:55.809  3787  3836 I jxcore-log: 
,08-12 16:46:55.814  3787  3836 I jxcore-log: # teardown
08-12 16:46:55.814  3787  3836 I jxcore-log: 
,08-12 16:46:55.909  3787  3836 I jxcore-log: ok 577 should not be in started state
08-12 16:46:55.909  3787  3836 I jxcore-log: 
,08-12 16:46:55.915  3787  3836 I jxcore-log: # setup
08-12 16:46:55.915  3787  3836 I jxcore-log: 
,08-12 16:46:55.963  3787  3836 I jxcore-log: ok 578 should be in started state
08-12 16:46:55.963  3787  3836 I jxcore-log: 
,08-12 16:46:55.967  3787  3836 I jxcore-log: # 170. #stop can be called multiple times in a row
08-12 16:46:55.967  3787  3836 I jxcore-log: 
,08-12 16:46:56.011  3787  3836 I jxcore-log: ok 579 should be in stopped state
08-12 16:46:56.011  3787  3836 I jxcore-log: 
,08-12 16:46:56.014  3787  3836 I jxcore-log: ok 580 should still be in stopped state
08-12 16:46:56.014  3787  3836 I jxcore-log: 
,08-12 16:46:56.017  3787  3836 I jxcore-log: # teardown
08-12 16:46:56.017  3787  3836 I jxcore-log: 
,08-12 16:46:56.061  3787  3836 I jxcore-log: ok 581 should not be in started state
08-12 16:46:56.061  3787  3836 I jxcore-log: 
,08-12 16:46:56.064  3787  3836 I jxcore-log: # setup
08-12 16:46:56.064  3787  3836 I jxcore-log: 
,08-12 16:46:56.108  3787  3836 I jxcore-log: ok 582 should be in started state
08-12 16:46:56.108  3787  3836 I jxcore-log: 
,08-12 16:46:56.111  3787  3836 I jxcore-log: # 171. #startListeningForAdvertisements can be called multiple times in a row
08-12 16:46:56.111  3787  3836 I jxcore-log: 
,08-12 16:46:56.169  3787  3836 I jxcore-log: ok 583 should be in listening state
08-12 16:46:56.169  3787  3836 I jxcore-log: 
,08-12 16:46:56.172  3787  3836 I jxcore-log: ok 584 should still be in listening state
08-12 16:46:56.172  3787  3836 I jxcore-log: 
,08-12 16:46:56.175  3787  3836 I jxcore-log: # teardown
08-12 16:46:56.175  3787  3836 I jxcore-log: 
,08-12 16:46:56.230  3787  3836 I jxcore-log: ok 585 should not be in started state
08-12 16:46:56.230  3787  3836 I jxcore-log: 
,08-12 16:46:56.233  3787  3836 I jxcore-log: # setup
08-12 16:46:56.233  3787  3836 I jxcore-log: 
,08-12 16:46:56.307  3787  3836 I jxcore-log: ok 586 should be in started state
08-12 16:46:56.307  3787  3836 I jxcore-log: 
,08-12 16:46:56.313  3787  3836 I jxcore-log: # 172. #stopListeningForAdvertisements can be called multiple times in a row
08-12 16:46:56.313  3787  3836 I jxcore-log: 
,08-12 16:46:56.357  3787  3836 I jxcore-log: ok 587 should not be in listening state
08-12 16:46:56.357  3787  3836 I jxcore-log: 
,08-12 16:46:56.359  3787  3836 I jxcore-log: ok 588 should still not be in listening state
08-12 16:46:56.359  3787  3836 I jxcore-log: 
,08-12 16:46:56.360  3787  3836 I jxcore-log: # teardown
08-12 16:46:56.360  3787  3836 I jxcore-log: 
,08-12 16:46:56.434  3787  3836 I jxcore-log: ok 589 should not be in started state
08-12 16:46:56.434  3787  3836 I jxcore-log: 
,08-12 16:46:56.441  3787  3836 I jxcore-log: # setup
08-12 16:46:56.441  3787  3836 I jxcore-log: 
,08-12 16:46:56.527  3787  3836 I jxcore-log: ok 590 should be in started state
08-12 16:46:56.527  3787  3836 I jxcore-log: 
,08-12 16:46:56.529  3787  3836 I jxcore-log: # 173. #stopAdvertisingAndListening can be called multiple times in a row
08-12 16:46:56.529  3787  3836 I jxcore-log: 
,08-12 16:46:56.564  3787  3836 I jxcore-log: ok 591 should not be in advertising state
08-12 16:46:56.564  3787  3836 I jxcore-log: 
,08-12 16:46:56.565  3787  3836 I jxcore-log: ok 592 should still not be in advertising state
08-12 16:46:56.565  3787  3836 I jxcore-log: 
,08-12 16:46:56.567  3787  3836 I jxcore-log: # teardown
08-12 16:46:56.567  3787  3836 I jxcore-log: 
,08-12 16:46:56.632  3787  3836 I jxcore-log: ok 593 should not be in started state
08-12 16:46:56.632  3787  3836 I jxcore-log: 
,08-12 16:46:56.639  3787  3836 I jxcore-log: # setup
08-12 16:46:56.639  3787  3836 I jxcore-log: 
,08-12 16:46:56.679  3787  3836 I jxcore-log: ok 594 should be in started state
08-12 16:46:56.679  3787  3836 I jxcore-log: 
,08-12 16:46:56.681  3787  3836 I jxcore-log: # 174. functions are run from a queue in the right order
08-12 16:46:56.681  3787  3836 I jxcore-log: 
,08-12 16:46:56.764  3787  3836 I jxcore-log: ok 595 call order must match
08-12 16:46:56.764  3787  3836 I jxcore-log: 
,08-12 16:46:56.767  3787  3836 I jxcore-log: # teardown
08-12 16:46:56.767  3787  3836 I jxcore-log: 
,08-12 16:46:56.864  3787  3836 I jxcore-log: ok 596 should not be in started state
08-12 16:46:56.864  3787  3836 I jxcore-log: 
,08-12 16:46:56.870  3787  3836 I jxcore-log: # setup
08-12 16:46:56.870  3787  3836 I jxcore-log: 
,08-12 16:46:56.913  3787  3836 I jxcore-log: ok 597 should be in started state
08-12 16:46:56.913  3787  3836 I jxcore-log: 
,08-12 16:46:56.915  3787  3836 I jxcore-log: # 175. does not get peer changes from self
08-12 16:46:56.915  3787  3836 I jxcore-log: 
,08-12 16:46:58.008  3787  3836 I jxcore-log: ok 598 USN must have changed again
08-12 16:46:58.008  3787  3836 I jxcore-log: 
,08-12 16:46:59.006  3787  3836 I jxcore-log: # teardown
08-12 16:46:59.006  3787  3836 I jxcore-log: 
,08-12 16:46:59.114  3787  3836 I jxcore-log: ok 599 should not be in started state
08-12 16:46:59.114  3787  3836 I jxcore-log: 
,08-12 16:46:59.117  3787  3836 I jxcore-log: # setup
08-12 16:46:59.117  3787  3836 I jxcore-log: 
,08-12 16:46:59.177  3787  3836 I jxcore-log: # 176. #ThaliPeerPoolDefault - single action
08-12 16:46:59.177  3787  3836 I jxcore-log: 
,08-12 16:46:59.236  3787  3836 I jxcore-log: ok 600 is an agent
08-12 16:46:59.236  3787  3836 I jxcore-log: 
,08-12 16:46:59.237  3787  3836 I jxcore-log: ok 601 enqueue is fine
08-12 16:46:59.237  3787  3836 I jxcore-log: 
,08-12 16:46:59.238  3787  3836 I jxcore-log: ok 602 Everything should be off the queue
08-12 16:46:59.238  3787  3836 I jxcore-log: 
08-12 16:46:59.240  3787  3836 I jxcore-log: # teardown
08-12 16:46:59.240  3787  3836 I jxcore-log: 
,08-12 16:46:59.303  3787  3836 I jxcore-log: # setup
08-12 16:46:59.303  3787  3836 I jxcore-log: 
,08-12 16:46:59.369  3787  3836 I jxcore-log: # 177. #ThaliPeerPoolDefault - multiple actions
08-12 16:46:59.369  3787  3836 I jxcore-log: 
,08-12 16:46:59.426  3787  3836 I jxcore-log: ok 603 is an agent
08-12 16:46:59.426  3787  3836 I jxcore-log: 
,08-12 16:46:59.429  3787  3836 I jxcore-log: ok 604 first enqueue is fine
08-12 16:46:59.429  3787  3836 I jxcore-log: 
,08-12 16:46:59.431  3787  3836 I jxcore-log: ok 605 is an agent
08-12 16:46:59.431  3787  3836 I jxcore-log: 
,08-12 16:46:59.434  3787  3836 I jxcore-log: ok 606 second enqueue is fine
08-12 16:46:59.434  3787  3836 I jxcore-log: 
,08-12 16:46:59.435  3787  3836 I jxcore-log: ok 607 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
08-12 16:46:59.435  3787  3836 I jxcore-log: 
,08-12 16:46:59.436  3787  3836 I jxcore-log: ok 608 Queue is empty
08-12 16:46:59.436  3787  3836 I jxcore-log: 
,08-12 16:46:59.438  3787  3836 I jxcore-log: # teardown
08-12 16:46:59.438  3787  3836 I jxcore-log: 
,08-12 16:46:59.478  3787  3836 I jxcore-log: # setup
08-12 16:46:59.478  3787  3836 I jxcore-log: 
,08-12 16:46:59.529  3787  3836 I jxcore-log: # 178. #ThaliPeerPoolDefault - PSK Pool works
08-12 16:46:59.529  3787  3836 I jxcore-log: 
,08-12 16:46:59.625  3787  3836 I jxcore-log: ok 609 is an agent
08-12 16:46:59.625  3787  3836 I jxcore-log: 
,08-12 16:46:59.628  3787  3836 I jxcore-log: ok 610 good enqueue
08-12 16:46:59.628  3787  3836 I jxcore-log: 
,08-12 16:46:59.666  3787  3836 I jxcore-log: ok 611 Identity should match
08-12 16:46:59.666  3787  3836 I jxcore-log: 
,08-12 16:46:59.691  3787  3836 I jxcore-log: ok 612 Got expected response
08-12 16:46:59.691  3787  3836 I jxcore-log: 
,08-12 16:46:59.692  3787  3836 I jxcore-log: ok 613 Got psk call back
08-12 16:46:59.692  3787  3836 I jxcore-log: 
,08-12 16:46:59.695  3787  3836 I jxcore-log: # teardown
08-12 16:46:59.695  3787  3836 I jxcore-log: 
,08-12 16:46:59.730  3787  3836 I jxcore-log: # setup
08-12 16:46:59.730  3787  3836 I jxcore-log: 
,08-12 16:46:59.785  3787  3836 I jxcore-log: # 179. #ThaliPeerPoolDefault - stop
08-12 16:46:59.785  3787  3836 I jxcore-log: 
,08-12 16:46:59.831  3787  3836 I jxcore-log: ok 614 is an agent
08-12 16:46:59.831  3787  3836 I jxcore-log: 
,08-12 16:46:59.833  3787  3836 I jxcore-log: ok 615 enqueue worked
08-12 16:46:59.833  3787  3836 I jxcore-log: 
,08-12 16:46:59.834  3787  3836 I jxcore-log: ok 616 is an agent
08-12 16:46:59.834  3787  3836 I jxcore-log: 
,08-12 16:46:59.835  3787  3836 I jxcore-log: ok 617 enqueue 2 worked
08-12 16:46:59.835  3787  3836 I jxcore-log: 
,08-12 16:46:59.838  3787  3836 I jxcore-log: ok 618 start action is killed
08-12 16:46:59.838  3787  3836 I jxcore-log: 
,08-12 16:46:59.839  3787  3836 I jxcore-log: ok 619 killed action is still killed
08-12 16:46:59.839  3787  3836 I jxcore-log: 
,08-12 16:46:59.840  3787  3836 I jxcore-log: ok 620 inQueue is empty
08-12 16:46:59.840  3787  3836 I jxcore-log: 
08-12 16:46:59.844  3787  3836 I jxcore-log: ok 621 Make sure we won enqueue after stopping
08-12 16:46:59.844  3787  3836 I jxcore-log: 
,08-12 16:46:59.848  3787  3836 I jxcore-log: # teardown
08-12 16:46:59.848  3787  3836 I jxcore-log: 
,08-12 16:46:59.980  3787  3836 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 16:46:59.980  3787  3836 I jxcore-log: 
,08-12 16:47:00.662  4099  4099 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-12 16:47:00.667  4099  4099 D AndroidRuntime: CheckJNI is OFF
,08-12 16:47:00.710  4099  4099 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 16:47:00.756  4099  4099 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 16:47:00.779  4099  4099 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 16:47:00.796   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-12 16:47:00.796   871   884 I ActivityManager: Killing 3787:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-12 16:47:00.931   871   894 W PackageSettings: Skipping PackageSetting{bf37ad com.example.hello/10273} due to missing metadata
,08-12 16:47:00.960   871  1312 D WifiService: Client connection lost with reason: 4
,08-12 16:47:00.961   871  1376 I WindowState: WIN DEATH: Window{255e468 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 16:47:00.961   871   882 D GraphicsStats: Buffer count: 2
,08-12 16:47:00.966   871   894 I art     : Starting a blocking GC Explicit
,08-12 16:47:01.009   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-12 16:47:01.009   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-12 16:47:01.009   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-12 16:47:01.009   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-12 16:47:01.009   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 16:47:01.009   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 16:47:01.009   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 16:47:01.009   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-12 16:47:01.010   871   884 I ActivityManager:   Force finishing activity ActivityRecord{be7aa69 u0 com.test.thalitest/.MainActivity t2}
,08-12 16:47:01.016   871  2144 W ActivityManager: Spurious death for ProcessRecord{29dfb1 0:com.test.thalitest/u0a0}, curProc for 3787: null
,08-12 16:47:01.036   871   894 I art     : Explicit concurrent mark sweep GC freed 23198(1870KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 794us total 69.575ms
,08-12 16:47:01.059   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 16:47:01.062  4099  4099 I art     : System.exit called, status: 0
,08-12 16:47:01.062  4099  4099 I AndroidRuntime: VM exiting with result code 0.
,08-12 16:47:01.068   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-12 16:47:01.089   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-12 16:47:01.094  2697  2697 D BluetoothMapAppObserver: onReceive
,08-12 16:47:01.094  2697  2697 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-12 16:47:01.097   871  1302 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 16:47:01.098  2056  2278 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 16:47:01.103  3656  3656 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-12 16:47:01.103  1865  1865 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-12 16:47:01.115  1937  1937 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 16:47:01.119  1865  4111 I Keyboard.Facilitator.DecoderInitializer: run()
,08-12 16:47:01.124  1865  4111 I Decoder : createOrResetDecoder
,08-12 16:47:01.161  3486  4114 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-12 16:47:01.164   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 16:47:01.171  1513  1513 I ConfigService: onCreate
,08-12 16:47:01.192  1513  1513 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-12 16:47:01.192  1513  1513 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-12 16:47:01.198  1865  4111 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-12 16:47:01.213  1513  1513 E SQLiteLog: (1034) os_unix.c:29052: (30) full_fsync(/data/user/0/com.google.android.gms/databases/ns.db-journal) - 
,08-12 16:47:01.219  1513  1513 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
08-12 16:47:01.220  1513  1513 E AndroidRuntime: FATAL EXCEPTION: main
08-12 16:47:01.220  1513  1513 E AndroidRuntime: Process: com.google.process.gapps, PID: 1513
08-12 16:47:01.220  1513  1513 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 1034)
08-12 16:47:01.220  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 16:47:01.220  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 16:47:01.220  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 16:47:01.220  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 16:47:01.220  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 16:47:01.220  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:264)
08-12 16:47:01.220  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
08-12 16:47:01.220  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:170)
08-12 16:47:01.220  1513  1513 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 16:47:01.220  1513  1513 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 16:47:01.220  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 16:47:01.220  1513  1513 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 16:47:01.220  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 16:47:01.220  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-12 16:47:01.223  1865  4111 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-12 16:47:01.225  1513  1513 I Process : Sending signal. PID: 1513 SIG: 9
,08-12 16:47:01.225   871  4119 E DropBoxManagerService: Can't write: system_app_crash
08-12 16:47:01.225   871  4119 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-12 16:47:01.225   871  4119 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 16:47:01.225   871  4119 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 16:47:01.225   871  4119 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 16:47:01.225   871  4119 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 16:47:01.225   871  4119 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 16:47:01.225   871  4119 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 16:47:01.225   871  4119 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 16:47:01.225   871  4119 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 16:47:01.225   871  4119 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 16:47:01.225   871  4119 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 16:47:01.225   871  4119 E DropBoxManagerService: 	... 5 more
,08-12 16:47:01.238  1865  4111 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-12 16:47:01.238  1865  4111 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-12 16:47:01.240  1865  4111 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-12 16:47:01.240  1865  4111 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-12 16:47:01.241  1865  4111 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-12 16:47:01.241  1865  4111 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-12 16:47:01.242  1865  4111 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-12 16:47:01.243  1865  4111 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-12 16:47:01.243  1865  4111 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-12 16:47:01.243  1865  4111 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-12 16:47:01.243  1865  4111 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-12 16:47:01.243  1865  4111 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-12 16:47:01.249  3486  4114 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-12 16:47:01.251  3486  4114 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-12 16:47:01.251  3486  4114 E AndroidRuntime: Process: android.process.acore, PID: 3486
08-12 16:47:01.251  3486  4114 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 16:47:01.251  3486  4114 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 16:47:01.254  3486  4114 I Process : Sending signal. PID: 3486 SIG: 9
,08-12 16:47:01.254   871  4121 E DropBoxManagerService: Can't write: system_app_crash
08-12 16:47:01.254   871  4121 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-12 16:47:01.254   871  4121 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 16:47:01.254   871  4121 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 16:47:01.254   871  4121 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 16:47:01.254   871  4121 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 16:47:01.254   871  4121 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 16:47:01.254   871  4121 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 16:47:01.254   871  4121 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 16:47:01.254   871  4121 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 16:47:01.254   871  4121 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 16:47:01.254   871  4121 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 16:47:01.254   871  4121 E DropBoxManagerService: 	... 5 more
,08-12 16:47:01.274  1956  2034 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-12 16:47:01.275  1722  2422 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 260)
,08-12 16:47:01.275  1722  2422 W GmsClient: service died
,08-12 16:47:01.275  1722  1722 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-12 16:47:01.276  1722  1722 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-12 16:47:01.278   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-12 16:47:01.279   871   883 E PackageManager: Failed to write settings, restoring backup
08-12 16:47:01.279   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-12 16:47:01.279   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-12 16:47:01.279   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-12 16:47:01.279   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-12 16:47:01.279   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-12 16:47:01.279   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 16:47:01.279   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 16:47:01.279   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 16:47:01.281   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-12 16:47:01.281   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 16:47:01.281   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 16:47:01.281   871   884 E DropBoxManagerService: 	... 13 more
,08-12 16:47:01.283   871  1312 D WifiService: Client connection lost with reason: 4
,08-12 16:47:01.301   871  1950 I ActivityManager: Start proc 4124:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-12 16:47:01.301  1956  2034 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-12 16:47:01.301  1956  2034 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1956
08-12 16:47:01.301  1956  2034 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 16:47:01.301  1956  2034 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 16:47:01.301  1956  2034 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 16:47:01.301  1956  2034 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 16:47:01.301  1956  2034 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 16:47:01.301  1956  2034 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 16:47:01.301  1956  2034 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-12 16:47:01.301  1956  2034 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-12 16:47:01.301  1956  2034 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 16:47:01.301  1956  2034 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 16:47:01.301  1956  2034 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 16:47:01.301  1956  2034 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 16:47:01.304  1722  1722 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-12 16:47:01.304  1722  1722 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-12 16:47:01.304   871  1939 I ActivityManager: Process com.google.process.gapps (pid 1513) has died
,08-12 16:47:01.305   871  1939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-12 16:47:01.305   871  1939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
,08-12 16:47:01.305   871  1939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
08-12 16:47:01.306   871  2144 I ActivityManager: Process android.process.acore (pid 3486) has died
,08-12 16:47:01.307   871  2144 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30998ms
,08-12 16:47:01.311   871  4129 E DropBoxManagerService: Can't write: system_app_crash
08-12 16:47:01.311   871  4129 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-12 16:47:01.311   871  4129 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 16:47:01.311   871  4129 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 16:47:01.311   871  4129 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 16:47:01.311   871  4129 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 16:47:01.311   871  4129 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 16:47:01.311   871  4129 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 16:47:01.311   871  4129 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 16:47:01.311   871  4129 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 16:47:01.311   871  4129 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 16:47:01.311   871  4129 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 16:47:01.311   871  4129 E DropBoxManagerService: 	... 5 more
,08-12 16:47:01.314   871  1944 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-12 16:47:01.320  1956  2034 I Process : Sending signal. PID: 1956 SIG: 9
,08-12 16:47:01.339   871  1989 I ActivityManager: Start proc 4138:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-12 16:47:01.342  1722  1722 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-12 16:47:01.356   277   277 E lowmemorykiller: Error writing /proc/1956/oom_score_adj; errno=22
,08-12 16:47:01.359  2007  4136 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-12 16:47:01.361  1722  4144 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 16:47:01.396  1722  4144 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-12 16:47:01.396  1722  4144 E AndroidRuntime: Process: com.google.android.gms, PID: 1722
08-12 16:47:01.396  1722  4144 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 16:47:01.396  1722  4144 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-12 16:47:01.400   871  4153 E DropBoxManagerService: Can't write: system_app_crash
08-12 16:47:01.400   871  4153 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-12 16:47:01.400   871  4153 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 16:47:01.400   871  4153 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 16:47:01.400   871  4153 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 16:47:01.400   871  4153 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 16:47:01.400   871  4153 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 16:47:01.400   871  4153 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 16:47:01.400   871  4153 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 16:47:01.400   871  4153 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 16:47:01.400   871  4153 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 16:47:01.400   871  4153 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 16:47:01.400   871  4153 E DropBoxManagerService: 	... 5 more
08-12 16:47:01.401  1722  4144 I Process : Sending signal. PID: 1722 SIG: 9
08-12 16:47:01.423   277   277 E lowmemorykiller: Error writing /proc/1722/oom_score_adj; errno=22
,08-12 16:47:01.432  2007  4136 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 16:47:01.435  4138  4138 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-12 16:47:01.442  2007  4136 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,08-12 16:47:01.442  2007  4136 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-12 16:47:01.442  2007  4136 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2007
08-12 16:47:01.442  2007  4136 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	,at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 16:47:01.442  2007  4136 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 16:47:01.444   871  2146 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
,08-12 16:47:01.444   871  2146 I ActivityManager: Killing 2007:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
,08-12 16:47:01.445   871  4155 E DropBoxManagerService: Can't write: system_app_crash
08-12 16:47:01.445   871  4155 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-12 16:47:01.445   871  4155 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 16:47:01.445   871  4155 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 16:47:01.445   871  4155 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 16:47:01.445   871  4155 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 16:47:01.445   871  4155 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 16:47:01.445   871  4155 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 16:47:01.445   871  4155 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 16:47:01.445   871  4155 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 16:47:01.445   871  4155 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 16:47:01.445   871  4155 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 16:47:01.445   871  4155 E DropBoxManagerService: 	... 5 more
,08-12 16:47:01.450   871  1939 D GraphicsStats: Buffer count: 1
,08-12 16:47:01.451   871  1376 I WindowState: WIN DEATH: Window{b51ac41 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-12 16:47:01.492  4138  4138 I MultiDex: VM with version 2.1.0 has multidex support
,08-12 16:47:01.492  4138  4138 I MultiDex: install
08-12 16:47:01.492  4138  4138 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 16:47:01.540   871  1919 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@cab70b6)
,08-12 16:47:01.540   871  1314 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 16:47:01.541   871  1314 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 16:47:01.559   871  1312 D WifiService: Client connection lost with reason: 4
,08-12 16:47:01.563   871  1939 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1956) has died
,08-12 16:47:01.563   871  1939 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-12 16:47:01.568  4138  4138 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-12 16:47:01.568   871  1989 I ActivityManager: Process com.google.android.gms (pid 1722) has died
08-12 16:47:01.569   871  1989 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 1000ms
08-12 16:47:01.569   871  1989 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
,08-12 16:47:01.571   871  2143 W ActivityManager: Spurious death for ProcessRecord{bd2434d 0:com.google.android.googlequicksearchbox:search/u0a28}, curProc for 2007: null
,08-12 16:47:01.575  4138  4138 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-12 16:47:01.578  4138  4138 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 16:47:01.578  4138  4138 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 16:47:01.579  4138  4138 D AndroidRuntime: Shutting down VM
08-12 16:47:01.579  4138  4138 E AndroidRuntime: FATAL EXCEPTION: main
08-12 16:47:01.579  4138  4138 E AndroidRuntime: Process: com.google.process.gapps, PID: 4138
08-12 16:47:01.579  4138  4138 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvid,er: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 16:47:01.579  4138  4138 E AndroidRuntime: 	... 10 more
08-12 16:47:01.586   871   881 I ActivityManager: Start proc 4157:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
08-12 16:47:01.590   871  1402 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
08-12 16:47:01.591   871  1402 I ActivityManager: Killing 4138:com.google.process.gapps/u0a11 (adj 0): crash
08-12 16:47:01.593   871  4167 E DropBoxManagerService: Can't write: system_app_crash
08-12 16:47:01.593   871  4167 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-12 16:47:01.593   871  4167 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 16:47:01.593   871  4167 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 16:47:01.593   871  4167 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 16:47:01.593   871  4167 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 16:47:01.593   871  4167 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 16:47:01.593   871  4167 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 16:47:01.593   871  4167 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 16:47:01.593   871  4167 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 16:47:01.593   871  4167 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 16:47:01.593   871  4167 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 16:47:01.593   871  4167 E DropBoxManagerService: 	... 5 more

```
