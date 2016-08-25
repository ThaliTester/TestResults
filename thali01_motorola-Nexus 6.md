#### Test 797638306764640_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-25 15:24:50.694  1585  1585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 15:24:50.704  1585  1585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 15:24:50.710  1585  1585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 15:24:50.776  1585  2178 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-25 15:24:50.777  1585  2178 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 15:24:50.777  1585  2178 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 15:24:50.777  1585  2178 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-25 15:24:50.840  3511  3511 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-25 15:24:50.841  3511  3511 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 15:24:50.841  3511  3511 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
08-25 15:24:51.491  3778  3778 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-25 15:24:51.496  3778  3778 D AndroidRuntime: CheckJNI is OFF
08-25 15:24:51.532  3778  3778 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-25 15:24:51.574  3778  3778 I Radio-JNI: register_android_hardware_Radio DONE
08-25 15:24:51.594  3778  3778 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 15:24:51.600   874  1875 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 15:24:51.650  2018  2031 W SearchService: Abort, client detached.
08-25 15:24:51.659  2018  2330 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e2c760e
08-25 15:24:51.659  2018  2343 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-25 15:24:51.660  2018  2018 I HotwordDetector: Closing mic
08-25 15:24:51.670  3778  3778 D AndroidRuntime: Shutting down VM
08-25 15:24:51.720   874  1958 I ActivityManager: Start proc 3787:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-25 15:24:51.721   376  2345 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-25 15:24:51.723   376  2345 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-25 15:24:51.733   376  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-25 15:24:51.735  2018  2342 I MicroRecognitionRnrImpl: Detection finished
08-25 15:24:51.736  2018  2337 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-25 15:24:51.798  3787  3787 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-25 15:24:51.820  3787  3787 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-25 15:24:51.829  3787  3787 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 349-353)
08-25 15:24:51.830  3787  3787 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 15:24:51.877  3787  3787 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bfa0ae3}
08-25 15:24:51.877  3787  3787 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 15:24:51.878  3787  3787 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 15:24:51.883  3787  3787 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-25 15:24:51.884  3787  3787 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 15:24:51.923  3787  3787 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 15:24:51.948  3787  3787 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 15:24:51.948  3787  3787 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 15:24:51.948  3787  3787 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 15:24:51.948  3787  3787 I Adreno  : Build Date                       : 10/20/15
08-25 15:24:51.948  3787  3787 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 15:24:51.948  3787  3787 I Adreno  : Local Branch                     : M14
08-25 15:24:51.948  3787  3787 I Adreno  : Remote Branch                    : 
08-25 15:24:51.948  3787  3787 I Adreno  : Remote Branch                    : 
08-25 15:24:51.948  3787  3787 I Adreno  : Reconstruct Branch               : 
,08-25 15:24:52.032   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e69d2d6:true
,08-25 15:24:52.114  3787  3787 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-25 15:24:52.145  3787  3787 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-25 15:24:52.229  3787  3825 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-25 15:24:52.256  3787  3812 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-25 15:24:52.289  3787  3825 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 15:24:52.405   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +719ms
,08-25 15:24:52.417  1895  1895 I Keyboard.Facilitator: onFinishInput()
,08-25 15:24:52.528   874  1875 I ActivityManager: Killing 3216:com.google.android.gm/u0a78 (adj 15): empty #17
,08-25 15:24:52.565  3787  3787 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3787
,08-25 15:24:52.571   874  1875 I ActivityManager: Killing 3091:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-25 15:24:52.747  3787  3787 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 15:24:52.886  3787  3827 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1697973968
,08-25 15:24:52.913  3787  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 15:24:52.913  3787  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 15:24:52.913  3787  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 15:24:52.913  3787  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 15:24:52.913  3787  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 15:24:52.914  3787  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@492a5f7 added. We now have 1 listener(s)
,08-25 15:24:52.921  3787  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-25 15:24:52.929  3787  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 15:24:52.939  3787  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 15:24:52.939  3787  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-25 15:24:52.948  3787  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2fe382 added. We now have 1 listener(s)
,08-25 15:24:52.949  3787  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:24:52.954   874  1315 D WifiService: New client listening to asynchronous messages
08-25 15:24:52.954  3787  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 15:24:52.954  3787  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 15:24:52.954  3787  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 15:24:52.954  3787  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-25 15:24:52.954  3787  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-25 15:24:52.956  3787  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:24:52.957  3787  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-25 15:24:52.963  3787  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-25 15:24:52.963  3787  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:24:52.963  3787  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:24:52.963  3787  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:24:52.963  3787  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:24:52.963  3787  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:24:52.963  3787  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:24:52.963  3787  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:24:52.963  3787  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:24:52.963  3787  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-25 15:24:52.963  3787  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 15:24:52.964  3787  3827 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 15:24:53.082  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:53.088  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:53.091  3787  3787 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 15:24:53.449  3787  3794 I art     : Background sticky concurrent mark sweep GC freed 69062(6MB) AllocSpace objects, 18(1604KB) LOS objects, 29% free, 23MB/32MB, paused 802us total 111.992ms
,08-25 15:24:54.240  3787  3836 W jxcore-log: Initializing JXcore engine
,08-25 15:24:54.240  3787  3836 W jxcore-log: JXcore engine is ready
,08-25 15:24:54.287  3836  3836 W Thread-326: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-25 15:24:54.287  3836  3836 W Thread-326: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11852]" dev="sockfs" ino=11852 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-25 15:24:54.287  3836  3836 W Thread-326: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-25 15:24:54.287  3836  3836 W Thread-326: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[24357]" dev="sockfs" ino=24357 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-25 15:24:54.305  3787  3836 W jxcore-log: Starting JXcore engine
,08-25 15:24:54.387  3787  3836 W jxcore-log: Platform android
08-25 15:24:54.387  3787  3836 W jxcore-log: 
,08-25 15:24:54.387  3787  3836 W jxcore-log: Process ARCH arm
08-25 15:24:54.387  3787  3836 W jxcore-log: 
,08-25 15:24:54.582  3787  3836 I jxcore-log: JXcore Cordova bridge is ready!
08-25 15:24:54.582  3787  3836 I jxcore-log: 
,08-25 15:24:54.583  3787  3836 W jxcore-log: JXcore engine is started
,08-25 15:24:54.596  3787  3827 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 15:24:54.601  3787  3787 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 15:24:55.536   874  1314 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-25 15:24:57.393  1585  1585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 15:24:57.398  1585  1585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 15:24:57.441  1585  2889 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 15:24:57.441  1585  2889 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-25 15:24:57.441  1585  2889 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 15:24:57.442  1585  2889 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 15:24:57.471  3552  3845 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-25 15:24:57.471  3552  3845 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at jdm.a(PG:82)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at jcs.o(PG:406)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at jcn.a(PG:1379)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at jcs.i(PG:143)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at blb.a(PG:3937)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at czp.a(PG:18188)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at czp.a(PG:9081)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at czq.run(PG:1686)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 15:24:57.471  3552  3845 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at jdj.a(PG:4091)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at jdj.a(PG:1125)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at jdm.a(PG:77)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	... 12 more
08-25 15:24:57.471  3552  3845 E HttpOperation: Caused by: faj: BadAuthentication
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at fal.a(PG:38)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	at jdj.a(PG:4089)
08-25 15:24:57.471  3552  3845 E HttpOperation: 	... 14 more
,08-25 15:24:57.521  1585  2178 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 15:24:57.521  1585  2178 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 15:24:57.521  1585  2178 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 15:24:57.522  1585  2178 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 15:24:57.539  3552  3845 E HttpOperation: [getmobileexperiments] Unexpected exception
08-25 15:24:57.539  3552  3845 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at jdm.a(PG:82)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at jcs.o(PG:406)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at jcn.a(PG:1379)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at jcs.i(PG:143)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at hec.a(PG:42)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at hee.a(PG:102)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at czr.a(PG:65)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at kka.a(PG:108)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at czp.a(PG:19176)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at czp.a(PG:9081)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at czq.run(PG:1686)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 15:24:57.539  3552  3845 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at jdj.a(PG:4091)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at jdj.a(PG:1125)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at jdm.a(PG:77)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	... 15 more
08-25 15:24:57.539  3552  3845 E HttpOperation: Caused by: faj: BadAuthentication
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at fal.a(PG:38)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	at jdj.a(PG:4089)
08-25 15:24:57.539  3552  3845 E HttpOperation: 	... 17 more
,08-25 15:24:57.540  3552  3845 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-25 15:24:57.540  3552  3845 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at jdm.a(PG:82)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at jcs.o(PG:406)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at jcn.a(PG:1379)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at jcs.i(PG:143)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at hec.a(PG:42)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at hee.a(PG:102)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at czr.a(PG:65)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at kka.a(PG:108)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at czp.a(PG:19176)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at czp.a(PG:9081)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at czq.run(PG:1686)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at jdj.a(PG:4091)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at jdj.a(PG:1125)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at jdm.a(PG:77)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	... 15 more
08-25 15:24:57.540  3552  3845 E ExperimentLoader: Caused by: faj: BadAuthentication
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at fal.a(PG:38)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	at jdj.a(PG:4089)
08-25 15:24:57.540  3552  3845 E ExperimentLoader: 	... 17 more
,08-25 15:24:57.620   874  2236 D NetlinkSocketObserver: NeighborEvent{elapsedMs=126143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 15:24:57.626   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 125619, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-25 15:25:04.451  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 15:25:04.451  3787  3836 I jxcore-log: 
,08-25 15:25:04.454  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 15:25:04.454  3787  3836 I jxcore-log: 
,08-25 15:25:04.465  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:25:04.465  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:04.465  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:04.465  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:04.465  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:04.465  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:04.465  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:04.465  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:25:04.471  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:25:04.473  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 15:25:04.473  3787  3836 I jxcore-log: 
,08-25 15:25:04.475  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 15:25:04.475  3787  3836 I jxcore-log: 
,08-25 15:25:04.959  3787  3836 D executeNativeTests: Running unit tests
,08-25 15:25:05.021  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 15:25:05.021  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 added. We now have 2 listener(s)
,08-25 15:25:05.022  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 15:25:05.023  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 15:25:05.023  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 15:25:05.023  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 15:25:05.023  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 added. We now have 2 listener(s)
08-25 15:25:05.023  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:25:05.023  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 15:25:05.030  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:25:05.042  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:25:05.042  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:05.042  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:05.042  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:05.042  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:05.042  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:05.042  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:05.042  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:25:05.049  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:25:05.050  3787  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 15:25:05.053  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:05.056  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 15:25:05.058  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 15:25:05.058  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 15:25:05.059  3787  3836 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-25 15:25:05.059  3787  3836 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 15:25:05.059  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-25 15:25:05.060  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 15:25:05.060  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 15:25:05.060  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.060  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 15:25:05.060  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.063  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.063  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.063  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 15:25:05.063  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 15:25:05.063  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 removed from the list
08-25 15:25:05.063  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:25:05.063  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 removed from the list
08-25 15:25:05.060  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-25 15:25:05.064  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.064  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:05.066  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:25:05.066  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.067  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.067  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-25 15:25:05.067  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.067  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
,08-25 15:25:05.069  3787  3836 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 15:25:05.070  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:25:05.070  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.070  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.070  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 15:25:05.070  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.070  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:05.070  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.070  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.070  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.070  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.070  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.070  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.070  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.071  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.072  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 15:25:05.072  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.072  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.072  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.079  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 15:25:05.079  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 15:25:05.079  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 15:25:05.079  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 15:25:05.079  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-25 15:25:05.079  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 15:25:05.079  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 15:25:05.080  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 15:25:05.081  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 15:25:05.081  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 15:25:05.081  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 15:25:05.081  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-25 15:25:05.081  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.081  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.081  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.081  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.081  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.081  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.081  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.081  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:25:05.081  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.081  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.081  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.082  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.082  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.082  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.083  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.083  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.084  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.084  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.084  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 15:25:05.086  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:25:05.094  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:25:05.094  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:05.094  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:05.094  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:05.094  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:05.094  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:05.094  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:05.094  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:25:05.097  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:25:05.097  3787  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:25:05.097  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:25:05.098  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 15:25:05.098  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:25:05.098  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:25:05.098  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 15:25:05.106  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:05.106  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 15:25:05.107  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 15:25:05.109  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:05.115  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 15:25:05.117  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 15:25:05.117  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 15:25:05.120  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-25 15:25:05.124  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-25 15:25:05.124  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 15:25:05.124  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 15:25:05.126  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 15:25:05.128  3787  3836 D BluetoothAdapter: STATE_ON
,08-25 15:25:05.135  2689  2702 D BtGatt.GattService: registerClient() - UUID=003bdee4-6dc2-43a7-bc11-92eb0a8bb7b5
,08-25 15:25:05.136  2689  2710 D BtGatt.GattService: onClientRegistered() - UUID=003bdee4-6dc2-43a7-bc11-92eb0a8bb7b5, clientIf=5
,08-25 15:25:05.138  3787  3829 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 15:25:05.139  2689  2896 D BtGatt.GattService: start scan with filters
,08-25 15:25:05.142  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 15:25:05.142  2689  2716 D BtGatt.ScanManager: handling starting scan
08-25 15:25:05.142  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 15:25:05.142  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 15:25:05.142  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 15:25:05.145  2689  2716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
,08-25 15:25:05.146  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 15:25:05.146  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 15:25:05.146  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 15:25:05.147  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 15:25:05.151  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 15:25:05.154  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:25:05.154  3787  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 15:25:05.154  2689  2710 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 15:25:05.154  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 15:25:05.155  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 15:25:05.154  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:05.155  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.155  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 15:25:05.155  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 15:25:05.155  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 15:25:05.155  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-25 15:25:05.155  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 15:25:05.156  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 15:25:05.156  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 15:25:05.156  2689  2716 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 15:25:05.157  3787  3836 D BluetoothAdapter: STATE_ON
,08-25 15:25:05.158  2689  2702 D BtGatt.GattService: stopScan() - queue size =1
,08-25 15:25:05.161  2689  2702 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 15:25:05.162  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 15:25:05.162  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 15:25:05.162  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 15:25:05.163  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 15:25:05.163  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 15:25:05.164  2689  2710 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 15:25:05.164  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:05.164  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 15:25:05.165  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 15:25:05.165  2689  2716 D BtGatt.ScanManager: Starting BLE batch scan
08-25 15:25:05.169  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 15:25:05.169  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 15:25:05.169  2689  2716 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 15:25:05.171  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 15:25:05.172  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 15:25:05.173  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:25:05.173  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:25:05.173  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.173  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:25:05.173  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:25:05.173  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.173  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:25:05.173  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.173  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.173  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.174  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 15:25:05.175  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:25:05.182  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:25:05.182  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:05.182  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:05.182  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:05.182  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:05.182  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:05.182  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:05.182  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:25:05.184  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:25:05.184  3787  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 15:25:05.185  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 15:25:05.186  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 15:25:05.186  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:05.186  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:25:05.186  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:25:05.186  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 15:25:05.187  2689  2710 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 15:25:05.187  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:05.188  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:05.192  2689  2710 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 15:25:05.192  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:05.193  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 15:25:05.193  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 15:25:05.199  2689  2710 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 15:25:05.199  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:05.199  2689  2716 D BtGatt.ScanManager: stopping BLe Batch
,08-25 15:25:05.201  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,08-25 15:25:05.202  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 15:25:05.203  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 15:25:05.206  2689  2710 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 15:25:05.206  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:05.206  2689  2716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 15:25:05.207  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 15:25:05.208  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 15:25:05.208  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 15:25:05.208  3787  3836 D BluetoothAdapter: STATE_ON
,08-25 15:25:05.211  2689  2700 D BtGatt.GattService: registerClient() - UUID=cfbbf0e2-35bd-4b0b-bd3a-22b642981c87
,08-25 15:25:05.212  2689  2710 D BtGatt.GattService: onClientRegistered() - UUID=cfbbf0e2-35bd-4b0b-bd3a-22b642981c87, clientIf=5
,08-25 15:25:05.212  2689  2710 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 15:25:05.212  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:05.212  3787  3829 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 15:25:05.212  2689  2702 D BtGatt.GattService: start scan with filters
,08-25 15:25:05.216  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 15:25:05.216  2689  2716 D BtGatt.ScanManager: handling starting scan
,08-25 15:25:05.217  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
08-25 15:25:05.218  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 15:25:05.218  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 15:25:05.224  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 15:25:05.224  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 15:25:05.224  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 15:25:05.226  2689  2710 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 15:25:05.226  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:05.226  2689  2716 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 15:25:05.228  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 15:25:05.234  2689  2710 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 15:25:05.234  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK,
08-25 15:25:05.234  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:05.234  2689  2716 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 15:25:05.234  2689  2716 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 15:25:05.237  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:25:05.238  3787  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
08-25 15:25:05.238  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 15:25:05.238  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 15:25:05.238  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.238  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 15:25:05.238  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 15:25:05.238  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 15:25:05.238  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 15:25:05.238  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 15:25:05.238  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 15:25:05.238  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 15:25:05.239  3787  3836 D BluetoothAdapter: STATE_ON
,08-25 15:25:05.239  2689  2700 D BtGatt.GattService: stopScan() - queue size =1
,08-25 15:25:05.240  2689  2702 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 15:25:05.240  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 15:25:05.240  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 15:25:05.240  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 15:25:05.240  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 15:25:05.240  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 15:25:05.241  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-25 15:25:05.241  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 15:25:05.241  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 15:25:05.241  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 15:25:05.242  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 15:25:05.242  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.242  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 15:25:05.242  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.242  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:25:05.242  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:25:05.243  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
,08-25 15:25:05.243  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:25:05.243  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.243  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
,08-25 15:25:05.243  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.243  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.243  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.243  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.244  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 15:25:05.244  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 15:25:05.244  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.244  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list,
08-25 15:25:05.244  3787  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 15:25:05.246  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:25:05.249  2689  2710 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 15:25:05.249  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:05.249  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:25:05.249  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:05.249  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-25 15:25:05.249  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:05.249  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:05.249  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:05.249  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:05.249  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:25:05.251  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:25:05.251  3787  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 15:25:05.251  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:25:05.251  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 15:25:05.252  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:25:05.252  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-25 15:25:05.252  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 15:25:05.254  2689  2710 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 15:25:05.254  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:05.254  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:05.255  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 15:25:05.255  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 15:25:05.257  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:05.259  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 15:25:05.259  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 15:25:05.260  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 15:25:05.261  2689  2710 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 15:25:05.261  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:05.261  2689  2716 D BtGatt.ScanManager: stopping BLe Batch
,08-25 15:25:05.262  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 15:25:05.262  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 15:25:05.262  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 15:25:05.263  3787  3836 D BluetoothAdapter: STATE_ON
08-25 15:25:05.264  2689  2896 D BtGatt.GattService: registerClient() - UUID=60962571-3ee5-4839-9d8a-ad492f99033c
,08-25 15:25:05.264  2689  2710 D BtGatt.GattService: onClientRegistered() - UUID=60962571-3ee5-4839-9d8a-ad492f99033c, clientIf=5
08-25 15:25:05.265  3787  3829 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 15:25:05.265  2689  2897 D BtGatt.GattService: start scan with filters
08-25 15:25:05.267  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 15:25:05.267  2689  2710 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 15:25:05.267  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:05.267  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 15:25:05.267  2689  2716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 15:25:05.267  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 15:25:05.267  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 15:25:05.269  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 15:25:05.269  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 15:25:05.269  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 15:25:05.270  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 15:25:05.272  3787  3836 I io.jxcore.node.ConnectionHelper: start: OK
08-25 15:25:05.272  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.272  3787  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 15:25:05.272  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.272  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 15:25:05.272  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.272  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 15:25:05.272  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 15:25:05.273  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 15:25:05.273  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 15:25:05.273  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 15:25:05.273  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 15:25:05.273  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 15:25:05.273  3787  3836 D BluetoothAdapter: STATE_ON
,08-25 15:25:05.274  2689  2897 D BtGatt.GattService: stopScan() - queue size =0
08-25 15:25:05.274  2689  2702 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 15:25:05.274  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:25:05.274  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 15:25:05.274  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 15:25:05.274  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 15:25:05.274  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 15:25:05.275  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:25:05.275  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 15:25:05.275  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 15:25:05.275  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 15:25:05.276  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:25:05.276  2689  2710 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 15:25:05.276  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:05.277  2689  2716 D BtGatt.ScanManager: handling starting scan
,08-25 15:25:05.277  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:25:05.277  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:25:05.277  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 15:25:05.278  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.278  3787  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 15:25:05.279  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.279  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.280  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 15:25:05.280  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.280  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:25:05.280  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
,08-25 15:25:05.281  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:25:05.281  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.281  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 15:25:05.281  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:05.282  2689  2710 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 15:25:05.282  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:05.282  2689  2716 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 15:25:05.283  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:25:05.283  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.285  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.285  2689  2710 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 15:25:05.286  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:05.286  2689  2716 D BtGatt.ScanManager: Starting BLE batch scan
08-25 15:25:05.286  2689  2716 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 15:25:05.285  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.286  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:25:05.286  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.287  3787  3836 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 15:25:05.288  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.288  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.288  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 15:25:05.289  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.289  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.289  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.289  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.290  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.290  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
,08-25 15:25:05.290  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.290  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.291  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.291  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.291  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:05.293  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 15:25:05.293  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.293  2689  2710 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 15:25:05.293  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.293  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:05.293  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.295  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-25 15:25:05.295  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:25:05.295  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 15:25:05.295  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 15:25:05.295  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 15:25:05.295  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.295  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-25 15:25:05.296  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
,08-25 15:25:05.296  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:25:05.296  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.296  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 15:25:05.296  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:25:05.296  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:05.296  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:25:05.296  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-25 15:25:05.297  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 15:25:05.297  2689  2710 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 15:25:05.297  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:05.297  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.297  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:25:05.297  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.298  3787  3836 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 15:25:05.298  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.298  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.298  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.298  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.299  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:25:05.299  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.299  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.299  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.299  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.299  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.299  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.299  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.299  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.299  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.300  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.300  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.300  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.300  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.301  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 15:25:05.301  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.301  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.301  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.301  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.301  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.301  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.301  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.301  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.302  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.302  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.302  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.302  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.302  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:,25:05.302  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.302  2689  2710 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 15:25:05.302  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:05.303  2689  2716 D BtGatt.ScanManager: stopping BLe Batch
08-25 15:25:05.303  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.303  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.303  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.303  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.303  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 15:25:05.304  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 15:25:05.304  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 15:25:05.304  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 15:25:05.304  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 15:25:05.304  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 15:25:05.304  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.304  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.304  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.304  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.305  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.305  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.305  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.305  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.305  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.305  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.305  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.305  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.305  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.305  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.307  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.308  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.308  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.308  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.308  3787  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 15:25:05.308  3787  3836 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 15:25:05.309  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 15:25:05.312  2689  2710 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 15:25:05.313  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:05.313  2689  2716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 15:25:05.315  3787  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 15:25:05.316  3787  3836 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 15:25:05.316  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 15:25:05.316  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 15:25:05.316  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 15:25:05.316  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 15:25:05.316  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 15:25:05.316  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 15:25:05.316  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 15:25:05.316  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 15:25:05.316  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 15:25:05.316  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 15:25:05.316  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 15:25:05.317  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 15:25:05.318  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 15:25:05.318  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 15:25:05.318  3787  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 15:25:05.318  3787  3836 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 15:25:05.318  3787  3836 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 15:25:05.318  3787  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 15:25:05.318  3787  3836 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 15:25:05.318  3787  3836 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 15:25:05.318  3787  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 15:25:05.318  3787  3836 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 15:25:05.318  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 15:25:05.322  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 15:25:05.323  2689  2710 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 15:25:05.323  2689  2710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:05.323  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 15:25:05.323  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 15:25:05.324  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 15:25:05.324  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 15:25:05.324  3787  3836 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 15:25:05.324  3787  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 15:25:05.324  3787  3836 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 15:25:05.325  3787  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 390)
08-25 15:25:05.325  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.325  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.325  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.325  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.325  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.325  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.325  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 15:25:05.327  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.327  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.327  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.327  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.327  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.327  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.327  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.327  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.327  3787  3851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:25:05.328  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.328  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.328  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.328  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.328  3787  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 390
08-25 15:25:05.328  3787  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 390)
08-25 15:25:05.329  3787  3836 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 15:25:05.329  3787  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 390)
08-25 15:25:05.329  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.329  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.329  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.329  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.329  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.329  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.329  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.330  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.330  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.330  3787  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 390)
08-25 15:25:05.330  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.330  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.330  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.330  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.330  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.331  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.331  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.331  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.331  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.331  3787  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 15:25:05.331  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.331  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.332  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.332  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.332  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.332  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.332  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.332  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.332  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.332  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.332  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.332  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.332  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.332  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.333  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.333  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.333  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.333  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.334  3787  3836 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 15:25:05.334  3787  3836 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 15:25:05.334  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 15:25:05.334  3787  3836 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 15:25:05.334  3787  3836 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 15:25:05.334  3787  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 15:25:05.334  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 15:25:05.334  3787  3836 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 15:25:05.334  3787  3836 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 15:25:05.334  3787  3836 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 15:25:05.335  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 15:25:05.335  3787  3836 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 15:25:05.335  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.335  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.335  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.335  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.335  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.335  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.335  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.335  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.335  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.335  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.335  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.335  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.335  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.335  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.336  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.336  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.336  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.336  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.337  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.337  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.337  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.337  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.337  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.337  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.337  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.337  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.337  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.337  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.337  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.337  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.338  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.338  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.338  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.338  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.338  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.338  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.338  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.338  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.338  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.338  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.338  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.338  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.338  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.338  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.338  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:05.338  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.338  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.339  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.339  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.339  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.339  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.340  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 15:25:05.341  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:25:05.341  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 15:25:05.342  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 15:25:05.342  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 15:25:05.342  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 15:25:05.342  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 15:25:05.342  3787  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 15:25:05.342  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.343  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 15:25:05.343  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 15:25:05.343  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 15:25:05.343  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.343  3787  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 15:25:05.343  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.343  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.343  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 15:25:05.343  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 15:25:05.343  3787  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 15:25:05.343  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 15:25:05.343  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.343  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.344  3787  3853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:25:05.344  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:25:05.344  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.344  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:25:05.344  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.344  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:25:05.344  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:25:05.344  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.344  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.344  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.344  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.344  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.345  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.345  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.345  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.345  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.345  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.345  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.345  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.345  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.345  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.346  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.346  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.346  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.347  3787  3836 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 15:25:05.347  3787  3836 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 15:25:05.347  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 15:25:05.347  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 15:25:05.347  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.347  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.347  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.347  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.347  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.347  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.347  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.347  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.347  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.347  3787  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 15:25:05.347  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.347  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.347  3787  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 15:25:05.347  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.347  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.348  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.348  3787  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 15:25:05.348  3787  3787 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 15:25:05.350  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.350  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.350  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.350  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.353  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.353  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.353  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.354  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.354  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.354  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.354  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.354  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.354  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.354  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.354  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.354  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.354  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.354  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.355  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.355  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.355  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.355  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.356  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:05.356  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:05.356  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:05.356  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:05.356  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.356  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.356  3787  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2459107 not in the list
08-25 15:25:05.356  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.356  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.356  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:05.356  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.356  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.356  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:05.356  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:05.357  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:05.357  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:05.357  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:05.357  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c391234 not in the list
08-25 15:25:05.358  3787  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 15:25:05.358  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 15:25:05.358  3787  3836 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 15:25:05.358  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 15:25:05.358  3787  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 15:25:05.358  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 15:25:05.360  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 15:25:05.360  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 15:25:05.360  3787  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 15:25:05.360  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 15:25:05.360  3787  3836 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 15:25:05.360  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 15:25:05.360  3787  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 15:25:05.360  3787  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 15:25:05.361  3787  3836 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 15:25:05.361  3787  3836 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 15:25:05.361  3787  3836 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 15:25:05.361  3787  3836 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 15:25:05.361  3787  3836 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 15:25:05.361  3787  3836 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 15:25:05.362  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:05.362  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9b211f6 added. We now have 2 listener(s)
08-25 15:25:05.362  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:05.364  3787  3836 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 15:25:05.364   874  1977 D WifiService: setWifiEnabled: true pid=3787, uid=10000
08-25 15:25:05.364   874  1977 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 15:25:05.365  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:05.365  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxco,re.node.ConnectivityMonitorTest$DiscoveryManagerMock@c8ec9f7 added. We now have 3 listener(s)
08-25 15:25:05.365  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:05.369  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:05.369  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@65f7064 added. We now have 4 listener(s)
08-25 15:25:05.369  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:05.371  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:05.371  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c3982cd added. We now have 5 listener(s)
08-25 15:25:05.371  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:05.372   874  1959 D WifiService: setWifiEnabled: false pid=3787, uid=10000
08-25 15:25:05.372   874  1959 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 15:25:05.377  2689  2706 D BluetoothAdapterState: Current state: ON, message: 23
08-25 15:25:05.377  2689  2706 D BluetoothAdapterProperties: Setting state to 13
08-25 15:25:05.377  2689  2706 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 15:25:05.378  2689  2706 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 15:25:05.381  2689  2689 D BluetoothMapService: onReceive
08-25 15:25:05.381  2689  2689 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:25:05.381  2689  2689 D BluetoothMapService: STATE_TURNING_OFF
08-25 15:25:05.381  2689  2689 D BluetoothMapService: MAP Service closeService in
08-25 15:25:05.381  2689  2706 I BluetoothAdapterState: Entering PendingCommandState
08-25 15:25:05.381  2689  2689 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 15:25:05.381  2689  2689 D ObexServerSockets0: shutdown(block = true)
08-25 15:25:05.382  2689  2689 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 15:25:05.382  2689  2905 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 15:25:05.382  2689  2689 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 15:25:05.382  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:25:05.383  2689  2885 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-25 15:25:05.383  2689  2906 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-25 15:25:05.384  2689  2689 I BtOppRfcommListener: stopping Accept Thread
08-25 15:25:05.384  2689  3445 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-25 15:25:05.385  2689  3445 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 15:25:05.388  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:05.388  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:25:05.388  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:05.388  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:05.388  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:05.388  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:05.388  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:05.388  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:05.388  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:25:05.388  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:05.388  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:05.389  3787  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:25:05.390  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:05.392  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:05.393  1485  1485 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 15:25:05.394  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 15:25:05.394  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:05.394  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:05.394  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:05.394  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:05.394  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:05.394  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:05.394  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:05.394  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:25:05.395  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:05.395  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:05.395   874  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 15:25:05.395   874  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 15:25:05.395   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 15:25:05.395   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 15:25:05.398  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:05.403   874  2237 D DhcpClient: Clearing IP address
,08-25 15:25:05.404   372   872 D CommandListener: Setting iface cfg
,08-25 15:25:05.405   874   887 I ActivityManager: Start proc 3856:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-25 15:25:05.406   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-25 15:25:05.407  2689  2710 D BluetoothAdapterProperties: Scan Mode:20
,08-25 15:25:05.407  2689  2706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-25 15:25:05.409  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:05.409  1585  2560 V NativeCrypto: Read error: ssl=0x9b26de00: I/O error during system call, Connection timed out
08-25 15:25:05.410  1585  2560 V NativeCrypto: SSL shutdown failed: ssl=0x9b26de00: I/O error during system call, Broken pipe
,08-25 15:25:05.412   874  1977 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-25 15:25:05.413  2689  2689 D HeadsetService: Received stop request...Stopping profile...
,08-25 15:25:05.413   874  2233 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-25 15:25:05.417  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:05.417   874  2233 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-25 15:25:05.418   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,08-25 15:25:05.418   874  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-25 15:25:05.419   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 15:25:05.421   874   874 D BluetoothHeadset: Proxy object disconnected
,08-25 15:25:05.421   874   874 D BluetoothHeadset: Proxy object disconnected
08-25 15:25:05.421  2689  2689 D A2dpService: Received stop request...Stopping profile...
,08-25 15:25:05.421  1357  1368 D BluetoothHeadset: Proxy object disconnected
08-25 15:25:05.421  1357  1357 D HeadsetProfile: Bluetooth service disconnected,
,08-25 15:25:05.421  2689  2900 D A2dpStateMachine: Exit Disconnected: -1
,08-25 15:25:05.422  1953  1974 D BluetoothHeadset: Proxy object disconnected
,08-25 15:25:05.423   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-25 15:25:05.423   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-25 15:25:05.425  1357  1357 D BluetoothA2dp: Proxy object disconnected
08-25 15:25:05.425  2689  2689 D HidService: Received stop request...Stopping profile...
08-25 15:25:05.425  2689  2689 D HidService: Stopping Bluetooth HidService
08-25 15:25:05.425   471   471 E Parcel  : Reading a NULL string not supported here.
08-25 15:25:05.425   874   874 D BluetoothHeadset: Proxy object disconnected
08-25 15:25:05.426   874   874 D BluetoothA2dp: Proxy object disconnected
08-25 15:25:05.427  1357  1357 D BluetoothInputDevice: Proxy object disconnected
08-25 15:25:05.427  1357  1357 D HidProfile: Bluetooth service disconnected
08-25 15:25:05.427   874  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 15:25:05.427  2689  2689 V BluetoothAdapterState: isTurningOff()=true
08-25 15:25:05.428  2689  2689 V BluetoothAdapterState: isTurningOn()=false
08-25 15:25:05.428  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:05.428   874  1314 D WifiStateMachine: Start Disconnecting Watchdog 1
08-25 15:25:05.428  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:05.428  2689  2689 D HealthService: Received stop request...Stopping profile...
08-25 15:25:05.429   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 15:25:05.429   874  2242 D DhcpClient: Receive thread stopped
08-25 15:25:05.430  2689  2689 D PanService: Received stop request...Stopping profile...
08-25 15:25:05.431  2689  2689 D BluetoothMapService: Received stop request...Stopping profile...
08-25 15:25:05.431  2689  2689 D BluetoothMapService: stop()
08-25 15:25:05.431  2689  2689 D BluetoothMapAppObserver: deinitObservers()
08-25 15:25:05.431  2689  2689 D BluetoothMapAppObserver: removeReceiver()
08-25 15:25:05.436  2689  2689 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 15:25:05.436  2689  2689 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 15:25:05.436  2689  2710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-25 15:25:05.436  2689  2857 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 15:25:05.436  2689  2689 V BluetoothAdapterState: isTurningOff()=true
08-25 15:25:05.436  2689  2857 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 15:25:05.436  2689  2689 V BluetoothAdapterState: isTurningOn()=false
08-25 15:25:05.436  2689  2857 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 15:25:05.436  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:05.436  2689  2710 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-25 15:25:05.436  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:05.437  2689  2689 V BluetoothAdapterState: isTurningOff()=true
08-25 15:25:05.437  2689  2689 V BluetoothAdapterState: isTurningOn()=false
08-25 15:25:05.437  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:05.437  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:05.438  2689  2689 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 15:25:05.438  2689  2689 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 15:25:05.438  2689  2689 V BluetoothAdapterState: isTurningOff()=true
08-25 15:25:05.438  2689  2689 V BluetoothAdapterState: isTurningOn()=false
08-25 15:25:05.438  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:05.438  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:05.438  2689  2689 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 15:25:05.438  2689  2710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 15:25:05.438  2689  2857 D bt_bta_sys_main: bta_sys_stop_timer exp,ected alarm was not in bta alarm hash map.
08-25 15:25:05.438  2689  2710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 15:25:05.438  2689  2857 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 15:25:05.438  2689  2710 E bt_btif : L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:25:05.438  2689  2857 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:25:05.438  2689  2857 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:25:05.438  2689  2857 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:25:05.438  2689  2689 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 15:25:05.438  2689  2857 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:25:05.439  2689  2689 V BluetoothAdapterState: isTurningOff()=true
08-25 15:25:05.439  2689  2689 V BluetoothAdapterState: isTurningOn()=false
08-25 15:25:05.439  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:05.439  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:05.439  2689  2689 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 15:25:05.440  2689  2689 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 15:25:05.440  2689  2689 D BluetoothMapService: MAP Service closeService in
08-25 15:25:05.441  2689  2689 V BluetoothAdapterState: isTurningOff()=true
08-25 15:25:05.441  2689  2689 V BluetoothAdapterState: isTurningOn()=false
08-25 15:25:05.441  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:05.441  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:05.441  2689  2706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 15:25:05.441  2689  2706 D BluetoothAdapterProperties: Setting state to 15
08-25 15:25:05.441  2689  2706 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 15:25:05.442  1357  2045 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 15:25:05.442   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 15:25:05.442   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:25:05.442  1357  1368 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 15:25:05.442  2689  2706 I BluetoothAdapterState: Entering BleOnState
08-25 15:25:05.443   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:25:05.443  1357  1374 D BluetoothPan: onBluetoothStateChange on: false
08-25 15:25:05.443  1357  2045 D BluetoothMap: onBluetoothStateChange: up=false
08-25 15:25:05.444   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false,
08-25 15:25:05.444  1357  1368 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:25:05.446  2689  2689 D BluetoothMapService: cleanup()
08-25 15:25:05.446  1357  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 15:25:05.446  2689  2689 D BluetoothMapService: MAP Service closeService in,
08-25 15:25:05.448  1953  1974 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:25:05.448  2689  2706 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 15:25:05.448  2689  2706 D BluetoothAdapterProperties: Setting state to 16,
08-25 15:25:05.448  2689  2706 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-25 15:25:05.449  2689  2706 D BluetoothAdapterProperties: onBleDisable
08-25 15:25:05.449  2689  2706 I BluetoothAdapterState: Entering PendingCommandState
,08-25 15:25:05.450  2689  2707 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-25 15:25:05.452  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:05.452  2689  2710 D BluetoothAdapterProperties: Scan Mode:20
,08-25 15:25:05.452  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:05.452  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:05.452  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:05.452  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:05.452  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:05.452  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
08-25 15:25:05.452  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:05.452  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:05.452  2689  2857 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-25 15:25:05.452  2689  2857 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 15:25:05.452  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:05.452  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:25:05.454  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 15:25:05.454  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:05.454  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:05.454  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:05.454  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:05.454  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:05.454  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:05.454  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:05.454  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:05.455  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:05.455  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:25:05.456  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:05.457  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:05.468   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 15:25:05.477  3856  3856 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-25 15:25:05.486  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 15:25:05.489   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 15:25:05.490  1585  1585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:25:05.490   874  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 15:25:05.491   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-25 15:25:05.491   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-25 15:25:05.492   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-25 15:25:05.496  3393  3393 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@492a5f7 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-25 15:25:05.497  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:05.498  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:05.503   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cf015d:true
,08-25 15:25:05.510   874  1977 I ActivityManager: Start proc 3875:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-25 15:25:05.521  3856  3856 D LocalBluetoothProfileManager: Adding local MAP profile
,08-25 15:25:05.524  3856  3856 D BluetoothMap: Create BluetoothMap proxy object
,08-25 15:25:05.538  3875  3875 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-25 15:25:05.540   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-25 15:25:05.540   874  1316 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-25 15:25:05.540   874  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 15:25:05.542   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 15:25:05.543  2181  2291 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:25:05.544  3856  3856 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-25 15:25:05.545  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:05.545  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:05.545  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:05.545  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:05.545  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:05.545  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:05.545  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:05.545  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:05.545  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:05.545  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:05.545  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:05.546   874  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 15:25:05.546  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:05.547  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:05.547  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:05.547  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:05.547  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:05.547  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:05.547  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:05.547  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:05.547  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:05.547  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:05.547  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:05.561  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:25:05.568   874  2046 I ActivityManager: Killing 2987:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-25 15:25:05.653  2689  2710 I bt_hci  : shut_down
,08-25 15:25:05.654  2689  2718 D bt_hwcfg: hw_epilog_process
,08-25 15:25:05.655  2689  2718 I bt_vendor: low_power_mode_cb
,08-25 15:25:05.686  2689  2718 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 15:25:05.686  2689  2718 I bt_vendor: epilog_cb
,08-25 15:25:05.686  2689  2718 I bt_hci  : epilog_finished_callback
,08-25 15:25:05.693  2689  2710 I bt_hci_h4: hal_close
,08-25 15:25:05.694  2689  2710 I bt_userial_vendor: device fd = 51 close
,08-25 15:25:05.730  3875  3875 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 15:25:05.730  3875  3875 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 15:25:05.730  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 15:25:05.731  3875  3875 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 15:25:05.731  3875  3875 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 15:25:05.731  3875  3875 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.r.k.d(PG:583)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 15:25:05.731  3875  3875 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 15:25:05.731  3875  3875 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 15:25:05.731  3875  3875 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 15:25:05.731  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 15:25:05.741  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 15:25:05.751  1585  1585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:25:05.765  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:25:05.769  1745  1745 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 15:25:05.775  1745  1745 D SystemUpdateService: onCreate
,08-25 15:25:05.783  1745  1745 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 15:25:05.788  1745  3909 I SystemUpdateService: active receiver: enabled
,08-25 15:25:05.796  1745  1745 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 15:25:05.800  1745  2537 I iu.UploadsManager: num queued entries: 0
,08-25 15:25:05.801  1745  2537 I iu.UploadsManager: num updated entries: 0
,08-25 15:25:05.803  1745  1745 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 15:25:05.805  1745  1745 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 15:25:05.807  1745  2537 I iu.SyncManager: NEXT; no task
,08-25 15:25:05.813  1745  3909 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 15:25:05.820  1745  3909 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 15:25:05.821  1745  3909 I SystemUpdateService: now status is 0 (complete)
,08-25 15:25:05.821  1745  3909 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-25 15:25:05.822  1745  3909 I SystemUpdateService: file has been verified
,08-25 15:25:05.823  1745  3909 I SystemUpdateService: OTA package size = 12249756
,08-25 15:25:05.827   874  1982 I ActivityManager: Start proc 3911:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-25 15:25:05.830  1745  3909 I SystemUpdateService: showing system update notification
,08-25 15:25:05.834  2689  2707 D bt_stack_manager: event_shut_down_stack finished.
,08-25 15:25:05.834  2689  2706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 15:25:05.839  2689  2706 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 15:25:05.839  2689  2689 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 15:25:05.840  2689  2689 D BtGatt.GattService: Received stop request...Stopping profile...
,08-25 15:25:05.840  2689  2689 D BtGatt.GattService: stop()
,08-25 15:25:05.840  2689  2689 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 15:25:05.843  2689  2689 V BluetoothAdapterState: isTurningOff()=false
08-25 15:25:05.843  2689  2689 V BluetoothAdapterState: isTurningOn()=false
08-25 15:25:05.843  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:05.843  2689  2689 V BluetoothAdapterState: isBleTurningOff()=true
08-25 15:25:05.844  2689  2706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-25 15:25:05.844  2689  2706 D BluetoothAdapterProperties: Setting state to 10
08-25 15:25:05.844  2689  2706 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-25 15:25:05.845  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 15:25:05.846  2689  2706 I BluetoothAdapterState: Entering OffState
,08-25 15:25:05.846   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-25 15:25:05.863  2689  2689 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 15:25:05.864  2689  2689 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-25 15:25:05.864  2689  2689 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 15:25:05.865  2689  2707 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 15:25:05.867  2689  2707 D bt_stack_manager: event_clean_up_stack finished.
,08-25 15:25:05.870  2689  2689 I art     : System.exit called, status: 0
,08-25 15:25:05.870  2689  2689 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 15:25:05.886  1745  1745 D SystemUpdateService: onDestroy
,08-25 15:25:05.889   874  2047 I ActivityManager: Killing 3393:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-25 15:25:05.905  3911  3911 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-25 15:25:05.909  3911  3911 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:25:05.923  3911  3911 D SprintDMHelper: simOperator: 
08-25 15:25:05.923  3911  3911 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 15:25:05.998   874  1403 I ActivityManager: Process com.android.bluetooth (pid 2689) has died
,08-25 15:25:06.007  3875  3898 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-25 15:25:06.023   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@389a383:true
,08-25 15:25:06.066   874  2047 I ActivityManager: Start proc 3926:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-25 15:25:06.173  2471  3941 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-25 15:25:06.195   874  1958 I ActivityManager: Start proc 3942:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-25 15:25:06.198   874   885 I ActivityManager: Killing 3466:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-25 15:25:06.272  3942  3942 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-25 15:25:06.334  3942  3942 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 15:25:06.334  3942  3942 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 15:25:06.334  3942  3942 I GAv4    :   adb logcat -s GAv4
,08-25 15:25:06.353  3942  3942 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-25 15:25:06.359  3942  3942 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-25 15:25:06.377  3942  3959 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 15:25:06.504  3942  3942 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-25 15:25:06.541  3942  3942 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-25 15:25:06.549  3942  3942 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5070-5073)
,08-25 15:25:06.555  3942  3942 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 15:25:06.569  3942  3942 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {382fae7}
,08-25 15:25:06.570  3942  3942 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 15:25:06.570  3942  3942 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 15:25:06.579  3942  3942 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-25 15:25:06.581  3942  3942 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 15:25:06.596  3942  3942 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 15:25:06.608  3942  3942 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 15:25:06.608  3942  3942 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 15:25:06.608  3942  3942 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 15:25:06.608  3942  3942 I Adreno  : Build Date                       : 10/20/15
08-25 15:25:06.608  3942  3942 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 15:25:06.608  3942  3942 I Adreno  : Local Branch                     : M14
08-25 15:25:06.608  3942  3942 I Adreno  : Remote Branch                    : 
08-25 15:25:06.608  3942  3942 I Adreno  : Remote Branch                    : 
08-25 15:25:06.608  3942  3942 I Adreno  : Reconstruct Branch               : 
,08-25 15:25:06.676  3942  3942 I NSApplication: Starting up...
,08-25 15:25:06.685  3942  3988 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-25 15:25:06.719   874  1958 I ActivityManager: Start proc 3993:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-25 15:25:06.720   874  1958 I ActivityManager: Killing 3196:android.process.acore/u0a5 (adj 15): empty #17
,08-25 15:25:06.789  3993  3993 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-25 15:25:06.972   874  1959 I ActivityManager: Killing 3643:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-25 15:25:06.994  3552  3561 W art     : Suspending all threads took: 7.959ms
,08-25 15:25:07.064   874  3112 I ActivityManager: Start proc 4007:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-25 15:25:07.098  4007  4007 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-25 15:25:07.144  4007  4007 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-25 15:25:07.159   874  1403 I ActivityManager: Killing 3660:com.android.musicfx/u0a18 (adj 15): empty #17
,08-25 15:25:08.391   874  1875 D WifiService: setWifiEnabled: true pid=3787, uid=10000
,08-25 15:25:08.392   874  1875 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
,08-25 15:25:08.406   874  1314 D WifiConfigStore: Loading config and enabling all networks 
08-25 15:25:08.412  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:08.412  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:08.412  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:08.412  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:08.412  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:08.412  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:08.412  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:08.412  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:08.412  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:08.412  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:08.413  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:25:08.414  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:08.414  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:08.414  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:08.414  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:08.414  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:08.414  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:08.414  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:08.414  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:08.414  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:08.414  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:08.414  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:08.451   874  1314 D WifiConfigStore: loaded 0 passpoint configs,
08-25 15:25:08.452   874  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 15:25:08.453   874  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-25 15:25:08.454   874  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 15:25:08.454   874  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-25 15:25:08.454   874  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-25 15:25:08.454   874  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 15:25:08.470   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 15:25:08.473   372   872 D CommandListener: Setting iface cfg
,08-25 15:25:08.477   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
08-25 15:25:08.478   874  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-25 15:25:08.478   874  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 15:25:08.488   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 15:25:08.491   874  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 15:25:08.493   874  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 15:25:10.016   874  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=1.20 rxSuccessRate=1.64 delta 1000 -> 1000
,08-25 15:25:10.019   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-25 15:25:10.019   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 15:25:10.041   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 15:25:10.122   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 15:25:10.124  1485  1485 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 15:25:10.558  1485  1485 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 15:25:10.604  1485  1485 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 15:25:10.604  1485  1485 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 15:25:10.613   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 15:25:10.620   874  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-25 15:25:10.620   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 15:25:10.621   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 15:25:10.636   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 15:25:10.647   372   872 D CommandListener: Setting iface cfg
,08-25 15:25:10.649   874  1314 D WifiStateMachine: Start Dhcp Watchdog 2
,08-25 15:25:10.656   874  4043 D DhcpClient: Receive thread started
,08-25 15:25:10.659   874  1316 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-25 15:25:10.664   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 15:25:10.750   874  1314 E native  : do suspend false
,08-25 15:25:10.767   874  2237 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 15:25:10.780   874  4043 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-25 15:25:10.781   874  2237 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-25 15:25:10.784   874  2237 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 15:25:10.797   874  4043 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 15:25:10.798   874  2237 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 15:25:10.802   372   872 D CommandListener: Setting iface cfg
,08-25 15:25:10.807   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 15:25:10.813   874  2237 D DhcpClient: Scheduling renewal in 86399s
,08-25 15:25:10.819   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 15:25:10.820   874  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 15:25:10.820   874  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 15:25:10.821   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 15:25:10.824   874  1316 D ConnectivityService: Adding iface wlan0 to network 101
08-25 15:25:10.836   874  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 15:25:10.877   874  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 15:25:10.877   874  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-25 15:25:10.878   874  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-25 15:25:10.879   874  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101,
08-25 15:25:10.880   874  1316 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-25 15:25:10.890   874  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 15:25:10.896   874  1316 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-25 15:25:10.896   874  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-25 15:25:10.896   874  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-25 15:25:10.896   874  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-25 15:25:10.896   874  1316 D ConnectivityService:    accepting network in place of null
08-25 15:25:10.897   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 15:25:10.897   874  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 15:25:10.915   874  4042 D NetlinkSocketObserver: NeighborEvent{elapsedMs=139438, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 15:25:10.947   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 15:25:10.983   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 15:25:10.988   874  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 15:25:10.988   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 15:25:10.989   874  4041 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.198.142,2a00:1450:4001:80d::200e
,08-25 15:25:10.991   874   891 D Tethering: MasterInitialState.processMessage what=3
08-25 15:25:10.990   874  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-25 15:25:11.006  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:11.007  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:11.007  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:11.007  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:11.007  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:11.007  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:11.007  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:11.007  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:11.007  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:25:11.007  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:11.007  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:11.009  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 15:25:11.009  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:11.009  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:11.009  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:11.009  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:11.009  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:11.009  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:11.009  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:11.009  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:25:11.010  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:11.010  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:25:11.022  1745  1745 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 15:25:11.024  1745  1745 D SystemUpdateService: onCreate
,08-25 15:25:11.028  1745  1745 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 15:25:11.035  1745  4053 I SystemUpdateService: active receiver: enabled
,08-25 15:25:11.039  1745  4053 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 15:25:11.041  1745  4053 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
08-25 15:25:11.042  1745  4053 I SystemUpdateService: now status is 0 (complete)
08-25 15:25:11.042  1745  4053 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 15:25:11.042  1745  4053 I SystemUpdateService: file has been verified
08-25 15:25:11.042  1745  4053 I SystemUpdateService: OTA package size = 12249756
,08-25 15:25:11.045  1745  4053 I SystemUpdateService: showing system update notification
,08-25 15:25:11.053  1745  1745 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 15:25:11.055  1745  2537 I iu.UploadsManager: num queued entries: 0
,08-25 15:25:11.055  1745  2537 I iu.UploadsManager: num updated entries: 0
08-25 15:25:11.056  1745  2537 I iu.SyncManager: NEXT; no task
,08-25 15:25:11.058  1745  4057 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-25 15:25:11.058  1745  4057 W BaseAppContext: Using Auth Proxy for data requests.
08-25 15:25:11.059  1745  4057 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
08-25 15:25:11.060  1745  1745 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 15:25:11.061  1745  1745 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 15:25:11.064  3911  3911 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:25:11.065  1745  1745 D SystemUpdateService: onDestroy
,08-25 15:25:11.070  3911  3911 D SprintDMHelper: simOperator: 
,08-25 15:25:11.070  3911  3911 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-25 15:25:11.070  1585  1585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 15:25:11.072  1585  1585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 15:25:11.073   874  4041 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 13:25:11 GMT], X-Android-Received-Millis=[1472131511071], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472131511042]}
,08-25 15:25:11.075   874  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-25 15:25:11.076   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-25 15:25:11.076   874  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 15:25:11.077   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 15:25:11.115  1585  1596 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 15:25:11.115  1585  1596 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-25 15:25:11.115  1585  1596 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 15:25:11.115  1585  1596 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 15:25:11.129  1745  4057 E MDM     : [175] SitrepService.a: Error sending sitrep.
,08-25 15:25:11.185  2471  4060 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 15:25:11.188   874  1959 I ActivityManager: Killing 2255:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-25 15:25:11.398   874  1958 D WifiService: setWifiEnabled: false pid=3787, uid=10000
,08-25 15:25:11.398   874  1958 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 15:25:11.418  1485  1485 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 15:25:11.420   874  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-25 15:25:11.420   874  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 15:25:11.420   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 15:25:11.421   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 15:25:11.431   874  2237 D DhcpClient: Clearing IP address
,08-25 15:25:11.432   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-25 15:25:11.434   372   872 D CommandListener: Setting iface cfg
,08-25 15:25:11.436  1585  4065 V NativeCrypto: Read error: ssl=0x9b085a00: I/O error during system call, Connection timed out
,08-25 15:25:11.437  1585  4065 V NativeCrypto: SSL shutdown failed: ssl=0x9b085a00: I/O error during system call, Broken pipe
,08-25 15:25:11.439   874  3112 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-25 15:25:11.440   874  4041 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-25 15:25:11.441   874  4041 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.198.142,2a00:1450:4001:80d::200e
,08-25 15:25:11.444   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 15:25:11.444   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-25 15:25:11.449   874  4043 D DhcpClient: Receive thread stopped
08-25 15:25:11.450   874  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-25 15:25:11.450   471   471 E Parcel  : Reading a NULL string not supported here.
08-25 15:25:11.452   874  1314 D WifiStateMachine: Start Disconnecting Watchdog 2
08-25 15:25:11.453   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 15:25:11.460   874  4041 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:80d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-25 15:25:11.479   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 15:25:11.501   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 15:25:11.502   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-25 15:25:11.502   874  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 15:25:11.502   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:25:11.505   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-25 15:25:11.506  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 15:25:11.507  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:11.507  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:11.507  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:11.507  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:11.507  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:11.507  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:11.507  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:11.507  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:11.507  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:11.507  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:25:11.508  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 15:25:11.508  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:11.508  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:11.508  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:11.508  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:11.508  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:11.508  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:11.508  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:11.508  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:11.508  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:11.508  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:11.511   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 15:25:11.515  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:11.515  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:11.515  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:11.515  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:11.515  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:11.515  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:11.515  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:11.515  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:11.515  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:11.515  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 15:25:11.515  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:11.516  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:11.516  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:11.516  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:11.516  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:11.516  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:11.516  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:11.516  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:11.516  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:11.516  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:11.516  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 15:25:11.516  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:25:11.519   874  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 15:25:11.521  2181  2291 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 15:25:11.522  1745  1745 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 15:25:11.526  1745  1745 D SystemUpdateService: onCreate
,08-25 15:25:11.530  1745  1745 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-25 15:25:11.537  1745  1745 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 15:25:11.543  1745  2537 I iu.UploadsManager: num queued entries: 0
,08-25 15:25:11.543  1745  2537 I iu.UploadsManager: num updated entries: 0
,08-25 15:25:11.546  1745  1745 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 15:25:11.547  1745  1745 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 15:25:11.549  3911  3911 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:25:11.553  3911  3911 D SprintDMHelper: simOperator: 
,08-25 15:25:11.553  3911  3911 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 15:25:11.569  1745  4074 I SystemUpdateService: active receiver: enabled
,08-25 15:25:11.575   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-25 15:25:11.575  1745  2537 I iu.SyncManager: NEXT; no task
,08-25 15:25:11.576   874  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 15:25:11.584  2471  4078 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-25 15:25:11.587  1745  4074 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 15:25:11.596  1745  4074 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 15:25:11.596  1745  4074 I SystemUpdateService: now status is 0 (complete)
,08-25 15:25:11.596  1745  4074 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 15:25:11.596  1745  4074 I SystemUpdateService: file has been verified
,08-25 15:25:11.598  1745  4074 I SystemUpdateService: OTA package size = 12249756
,08-25 15:25:11.604  1745  4074 I SystemUpdateService: showing system update notification
,08-25 15:25:11.621  1745  1745 D SystemUpdateService: onDestroy
,08-25 15:25:11.642  1585  1585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 15:25:11.671  1585  1596 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-25 15:25:11.671  1585  1596 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-25 15:25:11.671  1585  1596 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 15:25:11.671  1585  1596 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 15:25:11.699  3511  3511 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-25 15:25:11.699  3511  3511 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 15:25:11.700  3511  3511 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-25 15:25:11.989   874  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-25 15:25:14.452   874   891 I ActivityManager: Start proc 4081:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-25 15:25:14.587  4081  4081 D AdapterServiceConfig: Adding HeadsetService
,08-25 15:25:14.588  4081  4081 D AdapterServiceConfig: Adding A2dpService
,08-25 15:25:14.588  4081  4081 D AdapterServiceConfig: Adding HidService
,08-25 15:25:14.588  4081  4081 D AdapterServiceConfig: Adding HealthService
,08-25 15:25:14.589  4081  4081 D AdapterServiceConfig: Adding PanService
,08-25 15:25:14.589  4081  4081 D AdapterServiceConfig: Adding GattService
,08-25 15:25:14.589  4081  4081 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 15:25:14.598   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8108311:true
,08-25 15:25:14.599  4081  4081 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 15:25:14.604  4081  4081 I bt_bluedroid: init
08-25 15:25:14.604  4081  4093 I BluetoothAdapterState: Entering OffState
,08-25 15:25:14.605  4081  4094 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 15:25:14.605  4081  4094 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 15:25:14.605  4081  4094 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-25 15:25:14.606  4081  4094 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 15:25:14.606  4081  4081 I bt_bluedroid: get_profile_interface socket
,08-25 15:25:14.608  4081  4097 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 15:25:14.609  4081  4097 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 15:25:14.610  4081  4081 I bt_bluedroid: get_profile_interface sdp
,08-25 15:25:14.612  4081  4092 I bt_bluedroid: config_hci_snoop_log
,08-25 15:25:14.613   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 15:25:14.616  4081  4093 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 15:25:14.616  4081  4093 D BluetoothAdapterProperties: Setting state to 14
,08-25 15:25:14.617  4081  4093 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 15:25:14.618  4081  4093 D BluetoothBondStateMachine: make
,08-25 15:25:14.619  4081  4098 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 15:25:14.622  4081  4093 I BluetoothAdapterState: Entering PendingCommandState
,08-25 15:25:14.623  4081  4081 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 15:25:14.626  4081  4081 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
,08-25 15:25:14.627  4081  4081 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 15:25:14.628  4081  4081 D BtGatt.GattService: Received start request. Starting profile...
08-25 15:25:14.628  4081  4081 D BtGatt.GattService: start()
,08-25 15:25:14.628  4081  4081 I bt_bluedroid: get_profile_interface gatt
,08-25 15:25:14.629  4081  4081 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
,08-25 15:25:14.629  4081  4081 D BtGatt.AdvertiseManager: advertise manager created
,08-25 15:25:14.634  4081  4081 V BluetoothAdapterState: isTurningOff()=false
,08-25 15:25:14.634  4081  4081 V BluetoothAdapterState: isTurningOn()=false
,08-25 15:25:14.634  4081  4081 V BluetoothAdapterState: isBleTurningOn()=true
,08-25 15:25:14.634  4081  4081 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 15:25:14.635  4081  4093 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-25 15:25:14.635  4081  4093 I bt_bluedroid: enable
,08-25 15:25:14.635  4081  4094 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-25 15:25:14.636  4081  4094 I bt_hci  : start_up
,08-25 15:25:14.643  4081  4094 I bt_vendor: alloc value 0xb39b9189
,08-25 15:25:14.643  4081  4094 I bt_vendor: init
,08-25 15:25:14.643  4081  4094 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-25 15:25:14.643  4081  4094 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 15:25:14.750  4081  4094 D bt_hci  : start_up starting async portion
,08-25 15:25:14.750  4081  4101 I bt_hci  : event_finish_startup
08-25 15:25:14.750  4081  4101 I bt_hci_h4: hal_open
,08-25 15:25:14.751  4081  4101 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 15:25:14.757  4081  4101 I bt_userial_vendor: device fd = 51 open
,08-25 15:25:14.793  4081  4101 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 15:25:14.825  4081  4101 D bt_hwcfg: Chipset BCM4354A2
,08-25 15:25:14.825  4081  4101 D bt_hwcfg: Target name = [BCM4354A2]
08-25 15:25:14.826  4081  4101 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 15:25:15.510  4081  4101 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 15:25:15.512  4081  4101 D bt_hwcfg: Settlement delay -- 100 ms
,08-25 15:25:15.512  4081  4101 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 15:25:15.629  4081  4101 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 15:25:15.630  4081  4101 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 15:25:15.659  4081  4101 I bt_hwcfg: vendor lib fwcfg completed
08-25 15:25:15.660  4081  4101 I bt_vendor: firmware callback
08-25 15:25:15.660  4081  4101 I bt_hci  : firmware_config_callback
,08-25 15:25:15.671  4081  4105 I bt_btu  : btu_task pending for preload complete event
,08-25 15:25:15.671  4081  4105 I bt_btu_task: Bluetooth chip preload is complete
,08-25 15:25:15.671  4081  4105 I bt_btu  : btu_task received preload complete event
,08-25 15:25:15.683  4081  4105 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 15:25:15.683  4081  4105 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 15:25:15.684  4081  4105 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 15:25:15.684  4081  4105 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 15:25:15.684  4081  4105 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 15:25:15.685  4081  4105 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 15:25:15.685  4081  4105 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 15:25:15.686  4081  4105 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 15:25:15.686  4081  4105 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 15:25:15.686  4081  4105 I         : BTE_InitTraceLevels -- TRC_PAN
,08-25 15:25:15.687  4081  4105 I         : BTE_InitTraceLevels -- TRC_SDP
,08-25 15:25:15.687  4081  4105 I         : BTE_InitTraceLevels -- TRC_GATT
,08-25 15:25:15.687  4081  4105 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 15:25:15.687  4081  4105 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-25 15:25:15.688  4081  4105 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 15:25:15.824  4081  4105 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
08-25 15:25:15.825  4081  4105 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,08-25 15:25:15.835  4081  4097 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 15:25:15.837  4081  4097 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 15:25:15.838  4081  4097 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 15:25:15.842  4081  4097 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 15:25:15.846  4081  4097 D BluetoothAdapterProperties: Scan Mode:20
,08-25 15:25:15.847  4081  4097 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 15:25:15.848  4081  4097 D bt_hci  : do_postload posting postload work item
,08-25 15:25:15.849  4081  4101 I bt_hci  : event_postload
,08-25 15:25:15.849  4081  4101 I bt_vendor: sco_config_cb
08-25 15:25:15.849  4081  4101 I bt_hci  : sco_config_callback postload finished.
,08-25 15:25:15.852  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:15.855  4081  4097 D bt_bte_conf: Device ID record 1 : primary
,08-25 15:25:15.856  4081  4097 D bt_bte_conf:   vendorId            = 000f
,08-25 15:25:15.856  4081  4097 D bt_bte_conf:   vendorIdSource      = 0001
,08-25 15:25:15.857  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:15.857  4081  4097 D bt_bte_conf:   product             = 1200
08-25 15:25:15.858  4081  4097 D bt_bte_conf:   version             = 1436
08-25 15:25:15.858  4081  4097 D bt_bte_conf:   clientExecutableURL = 
08-25 15:25:15.859  4081  4097 D bt_bte_conf:   serviceDescription  = 
08-25 15:25:15.859  4081  4097 D bt_bte_conf:   documentationURL    = 
08-25 15:25:15.859  4081  4101 I bt_vendor: low_power_mode_cb
08-25 15:25:15.859  4081  4097 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 15:25:15.860  4081  4094 D bt_stack_manager: event_start_up_stack finished
08-25 15:25:15.861  4081  4093 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 15:25:15.862  4081  4093 D BluetoothAdapterProperties: Setting state to 15
08-25 15:25:15.862  4081  4093 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-25 15:25:15.864  4081  4093 I BluetoothAdapterState: Entering BleOnState
,08-25 15:25:15.867  4081  4093 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-25 15:25:15.868  4081  4093 D BluetoothAdapterProperties: Setting state to 11
,08-25 15:25:15.868  4081  4093 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 15:25:15.878  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:15.881  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:15.886  1585  1585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:25:15.889  4081  4081 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
08-25 15:25:15.890  4081  4081 D HeadsetService: Received start request. Starting profile...
,08-25 15:25:15.892  4081  4081 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-25 15:25:15.893  4081  4081 D HeadsetStateMachine: make
,08-25 15:25:15.897  4081  4093 I BluetoothAdapterState: Entering PendingCommandState
,08-25 15:25:15.902  4081  4081 D HeadsetStateMachine: max_hf_connections = 1
,08-25 15:25:15.902  4081  4081 I bt_bluedroid: get_profile_interface handsfree
08-25 15:25:15.902  4081  4097 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-25 15:25:15.902  4081  4097 E bt_btif : btif_hf_upstreams_evt: Invalid index 1024
,08-25 15:25:15.906  4081  4081 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
,08-25 15:25:15.907  4081  4081 D A2dpService: Received start request. Starting profile...
08-25 15:25:15.907  4081  4081 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 15:25:15.908  4081  4081 I bt_bluedroid: get_profile_interface avrcp
,08-25 15:25:15.913  4081  4081 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 15:25:15.914  4081  4081 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 15:25:15.914  4081  4081 D A2dpStateMachine: make
,08-25 15:25:15.915  4081  4081 I bt_bluedroid: get_profile_interface a2dp
,08-25 15:25:15.915  4081  4097 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 15:25:15.917  4081  4115 D A2dpStateMachine: Enter Disconnected: -2
,08-25 15:25:15.920  4081  4081 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 15:25:15.921  4081  4081 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
08-25 15:25:15.922  4081  4081 D HidService: Received start request. Starting profile...
08-25 15:25:15.923  4081  4081 I bt_bluedroid: get_profile_interface hidhost
,08-25 15:25:15.923  4081  4097 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
08-25 15:25:15.923  4081  4097 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-25 15:25:15.923  4081  4081 D HidService: setHidService(): set to: null
08-25 15:25:15.924  4081  4081 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 15:25:15.924  3856  3856 D BluetoothInputDevice: Proxy object connected
08-25 15:25:15.925  4081  4081 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
,08-25 15:25:15.925  4081  4081 D HealthService: Received start request. Starting profile...
,08-25 15:25:15.927  4081  4081 I bt_bluedroid: get_profile_interface health
,08-25 15:25:15.928  3856  3856 D HidProfile: Bluetooth service connected
,08-25 15:25:15.929  4081  4081 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 15:25:15.929  4081  4081 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
,08-25 15:25:15.930  4081  4081 D PanService: Received start request. Starting profile...
,08-25 15:25:15.931  4081  4081 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-25 15:25:15.931  4081  4081 I bt_bluedroid: get_profile_interface pan
,08-25 15:25:15.931  4081  4097 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 15:25:15.931  3856  3856 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 15:25:15.932  3856  3856 D PanProfile: Bluetooth service connected
08-25 15:25:15.934  4081  4081 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
08-25 15:25:15.935  4081  4081 D BluetoothMapService: Received start request. Starting profile...
08-25 15:25:15.935  4081  4081 D BluetoothMapService: start()
08-25 15:25:15.936  3856  3856 D BluetoothMap: Proxy object connected
08-25 15:25:15.936  3856  3856 D MapProfile: Bluetooth service connected
08-25 15:25:15.937  3856  3856 D BluetoothMap: getConnectedDevices()
08-25 15:25:15.937  4081  4081 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-25 15:25:15.937  3856  3856 D BluetoothMap: Bluetooth is Not enabled
08-25 15:25:15.938  4081  4081 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-25 15:25:15.938  4081  4081 D BluetoothMapAppObserver: createReceiver()
,08-25 15:25:15.939  4081  4081 D BluetoothMapAppObserver: initObservers()
,08-25 15:25:15.939  4081  4081 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 15:25:15.947  4081  4081 V BluetoothAdapterState: isTurningOff()=false
,08-25 15:25:15.947  4081  4081 V BluetoothAdapterState: isTurningOn()=true
08-25 15:25:15.947  4081  4081 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:15.947  4081  4081 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 15:25:15.949  4081  4081 V BluetoothAdapterState: isTurningOff()=false
,08-25 15:25:15.949  4081  4081 V BluetoothAdapterState: isTurningOn()=true
08-25 15:25:15.949  4081  4081 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:15.949  4081  4113 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 15:25:15.949  4081  4081 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:15.950  4081  4081 V BluetoothAdapterState: isTurningOff()=false
,08-25 15:25:15.950  4081  4081 V BluetoothAdapterState: isTurningOn()=true
08-25 15:25:15.950  4081  4081 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:15.950  4081  4081 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:15.950  4081  4081 V BluetoothAdapterState: isTurningOff()=false
08-25 15:25:15.950  4081  4081 V BluetoothAdapterState: isTurningOn()=true
08-25 15:25:15.950  4081  4081 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 15:25:15.950  4081  4081 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:15.950  4081  4081 V BluetoothAdapterState: isTurningOff()=false
08-25 15:25:15.950  4081  4081 V BluetoothAdapterState: isTurningOn()=true
08-25 15:25:15.951  4081  4081 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 15:25:15.951  4081  4081 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:15.951  4081  4081 V BluetoothAdapterState: isTurningOff()=false
08-25 15:25:15.951  4081  4081 V BluetoothAdapterState: isTurningOn()=true
08-25 15:25:15.951  4081  4081 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:15.951  4081  4081 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 15:25:15.951  4081  4093 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 15:25:15.952  4081  4093 D BluetoothAdapterProperties: ScanMode =  20
08-25 15:25:15.952  4081  4093 D BluetoothAdapterProperties: State =  11
,08-25 15:25:15.955  4081  4097 D BluetoothAdapterProperties: Scan Mode:21
,08-25 15:25:15.956  4081  4097 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 15:25:15.956  4081  4093 D BluetoothAdapterProperties: Setting state to 12
08-25 15:25:15.956  4081  4093 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 15:25:15.957  4081  4093 I BluetoothAdapterState: Entering OnState
,08-25 15:25:15.957  3856  3869 D BluetoothMap: onBluetoothStateChange: up=true
08-25 15:25:15.957  3856  3867 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 15:25:15.957  1357  1368 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 15:25:15.959  1357  1357 D BluetoothInputDevice: Proxy object connected
08-25 15:25:15.960  1357  1357 D HidProfile: Bluetooth service connected
08-25 15:25:15.960   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 15:25:15.960  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:15.960  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:15.960  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:15.960  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:15.960  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:15.960  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:15.960  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:15.960  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:15.961   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 15:25:15.961  1357  1374 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 15:25:15.962   874   874 D BluetoothA2dp: Proxy object connected
,08-25 15:25:15.963  3856  3869 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 15:25:15.964  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:25:15.964   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 15:25:15.964  1357  2045 D BluetoothPan: onBluetoothStateChange on: true
08-25 15:25:15.966  4081  4081 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 15:25:15.967  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:15.967  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:15.967  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:15.967  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:15.967  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:15.967  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:15.967  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:15.967  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:15.968  4081  4081 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-25 15:25:15.969  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:25:15.969  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 15:25:15.969  1357  1357 D PanProfile: Bluetooth service connected
08-25 15:25:15.969  3856  3867 D BluetoothPan: onBluetoothStateChange on: true
08-25 15:25:15.970  1357  1374 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 15:25:15.970  4081  4081 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 15:25:15.972  1357  1357 D BluetoothMap: Proxy object connected
08-25 15:25:15.972  1357  1357 D MapProfile: Bluetooth service connected
08-25 15:25:15.973  1357  1357 D BluetoothMap: getConnectedDevices()
08-25 15:25:15.973  4081  4081 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 15:25:15.973   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 15:25:15.974  1357  2045 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 15:25:15.974  4081  4081 D ObexServerSockets: Succeed to create listening sockets 
08-25 15:25:15.974  4081  4081 D ObexServerSockets0: startAccept()
,08-25 15:25:15.974  4081  4081 D ObexServerSockets0: prepareForNewConnect()
08-25 15:25:15.975  1357  1368 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 15:25:15.976  4081  4081 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-25 15:25:15.976  4081  4081 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 15:25:15.977  1357  1357 D BluetoothA2dp: Proxy object connected
08-25 15:25:15.977  1953  1974 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 15:25:15.978  4081  4121 D ObexServerSockets0: Accepting socket connection...
,08-25 15:25:15.978  4081  4122 D ObexServerSockets0: Accepting socket connection...
08-25 15:25:15.980   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 15:25:15.981  4081  4081 D BluetoothMapService: onReceive
,08-25 15:25:15.981  4081  4081 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:25:15.981  4081  4081 D BluetoothMapService: STATE_ON
08-25 15:25:15.983  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:15.984  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:15.986  3856  3856 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-25 15:25:15.990  3856  3856 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-25 15:25:15.996  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 15:25:15.998  3856  3856 D BluetoothA2dp: Proxy object connected
,08-25 15:25:16.003  1585  1585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:25:16.009  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:25:16.011  4081  4081 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 15:25:16.011  1357  1357 D BluetoothPbap: Proxy object connected
08-25 15:25:16.011  4081  4081 D ObexServerSockets0: prepareForNewConnect()
08-25 15:25:16.011  1357  1357 D PbapServerProfile: Bluetooth service connected
,08-25 15:25:16.013  3856  3856 D BluetoothPbap: Proxy object connected
,08-25 15:25:16.013  3856  3856 D PbapServerProfile: Bluetooth service connected
,08-25 15:25:16.027  4081  4126 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 15:25:16.050  4081  4130 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 15:25:16.053  4081  4130 I BtOppRfcommListener: Accept thread started.
,08-25 15:25:16.064   874   874 D BluetoothHeadset: Proxy object connected
,08-25 15:25:16.064   874   874 D BluetoothHeadset: Proxy object connected
,08-25 15:25:16.065   874   891 D BluetoothHeadset: Proxy object connected
,08-25 15:25:16.065  1357  1368 D BluetoothHeadset: Proxy object connected
,08-25 15:25:16.065  1357  1357 D HeadsetProfile: Bluetooth service connected
08-25 15:25:16.066  1953  2148 D BluetoothHeadset: Proxy object connected
,08-25 15:25:16.067   874   874 D BluetoothHeadset: Proxy object connected
,08-25 15:25:16.073   874   891 D BluetoothHeadset: Proxy object connected
,08-25 15:25:16.075  1357  2045 D BluetoothHeadset: Proxy object connected
,08-25 15:25:16.075  1357  1357 D HeadsetProfile: Bluetooth service connected
,08-25 15:25:16.078  1953  2109 D BluetoothHeadset: Proxy object connected
,08-25 15:25:16.093  3856  3869 D BluetoothHeadset: Proxy object connected
,08-25 15:25:16.094  3856  3856 D HeadsetProfile: Bluetooth service connected
,08-25 15:25:17.416  4081  4093 D BluetoothAdapterState: Current state: ON, message: 23
,08-25 15:25:17.417  4081  4093 D BluetoothAdapterProperties: Setting state to 13
,08-25 15:25:17.417  4081  4093 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 15:25:17.419  4081  4093 D BluetoothAdapterProperties: onBluetoothDisable()
,08-25 15:25:17.427  4081  4081 D BluetoothMapService: onReceive
08-25 15:25:17.427  4081  4081 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:17.427  4081  4081 D BluetoothMapService: STATE_TURNING_OFF
08-25 15:25:17.428  4081  4081 D BluetoothMapService: MAP Service closeService in
08-25 15:25:17.428  4081  4081 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 15:25:17.428  4081  4081 D ObexServerSockets0: shutdown(block = true)
08-25 15:25:17.430  4081  4081 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 15:25:17.431  4081  4121 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 15:25:17.431  4081  4122 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-25 15:25:17.434  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:17.434  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:17.434  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:17.434  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:17.434  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:17.434  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:17.434  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:17.434  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:17.434  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:17.435  4081  4107 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-25 15:25:17.435  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:17.435  4081  4081 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 15:25:17.435  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:25:17.435  4081  4093 I BluetoothAdapterState: Entering PendingCommandState
08-25 15:25:17.435  4081  4081 I BtOppRfcommListener: stopping Accept Thread
08-25 15:25:17.437  4081  4130 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 15:25:17.437  4081  4130 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 15:25:17.438  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:17.438  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:17.438  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:17.438  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:17.438  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:17.438  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:17.438  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:17.438  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:17.438  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:17.440  3787  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:17.440  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:25:17.443  4081  4097 D BluetoothAdapterProperties: Scan Mode:20
08-25 15:25:17.443  4081  4093 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-25 15:25:17.447  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 15:25:17.448  4081  4081 D HeadsetService: Received stop request...Stopping profile...
,08-25 15:25:17.449  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:17.450  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:17.452   874   874 D BluetoothHeadset: Proxy object disconnected
08-25 15:25:17.453   874   874 D BluetoothHeadset: Proxy object disconnected
,08-25 15:25:17.453  1357  2045 D BluetoothHeadset: Proxy object disconnected
08-25 15:25:17.453  4081  4081 D A2dpService: Received stop request...Stopping profile...
08-25 15:25:17.454  1953  2109 D BluetoothHeadset: Proxy object disconnected
,08-25 15:25:17.454  4081  4115 D A2dpStateMachine: Exit Disconnected: -1
08-25 15:25:17.454  3856  3869 D BluetoothHeadset: Proxy object disconnected
08-25 15:25:17.454   874   874 D BluetoothHeadset: Proxy object disconnected
,08-25 15:25:17.456   874   874 D BluetoothA2dp: Proxy object disconnected
,08-25 15:25:17.457  4081  4081 D HidService: Received stop request...Stopping profile...
08-25 15:25:17.457  4081  4081 D HidService: Stopping Bluetooth HidService
,08-25 15:25:17.459  4081  4081 V BluetoothAdapterState: isTurningOff()=true
,08-25 15:25:17.459  4081  4081 V BluetoothAdapterState: isTurningOn()=false
,08-25 15:25:17.459  4081  4081 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 15:25:17.459  4081  4081 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 15:25:17.460  1357  1357 D HeadsetProfile: Bluetooth service disconnected
,08-25 15:25:17.461  1357  1357 D BluetoothA2dp: Proxy object disconnected
08-25 15:25:17.461  1357  1357 D BluetoothInputDevice: Proxy object disconnected
08-25 15:25:17.461  4081  4081 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-25 15:25:17.461  1357  1357 D HidProfile: Bluetooth service disconnected
,08-25 15:25:17.461  4081  4097 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-25 15:25:17.461  4081  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 15:25:17.461  4081  4081 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 15:25:17.461  4081  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 15:25:17.461  4081  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 15:25:17.461  4081  4097 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-25 15:25:17.462  4081  4081 V BluetoothAdapterState: isTurningOff()=true
08-25 15:25:17.462  4081  4081 V BluetoothAdapterState: isTurningOn()=false
,08-25 15:25:17.462  4081  4081 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:17.462  4081  4081 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:17.463  4081  4081 D HealthService: Received stop request...Stopping profile...
08-25 15:25:17.465  3856  3856 D DockEventReceiver: finishStartingService: stopping service
08-25 15:25:17.466  3856  3856 D HeadsetProfile: Bluetooth service disconnected
,08-25 15:25:17.467  1585  1585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 15:25:17.467  3856  3856 D BluetoothA2dp: Proxy object disconnected
08-25 15:25:17.468  4081  4097 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-25 15:25:17.468  4081  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 15:25:17.468  3856  3856 D BluetoothInputDevice: Proxy object disconnected
08-25 15:25:17.468  3856  3856 D HidProfile: Bluetooth service disconnected
08-25 15:25:17.468  4081  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 15:25:17.468  4081  4105 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 15:25:17.468  4081  4105 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:25:17.468  4081  4105 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 15:25:17.469  4081  4105 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:25:17.470  4081  4081 D PanService: Received stop request...Stopping profile...
,08-25 15:25:17.476  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 15:25:17.476  1357  1357 D PanProfile: Bluetooth service disconnected
08-25 15:25:17.476  4081  4081 V BluetoothAdapterState: isTurningOff()=true
08-25 15:25:17.476  4081  4081 V BluetoothAdapterState: isTurningOn()=false
08-25 15:25:17.476  4081  4081 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:17.476  4081  4081 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:17.476  3856  3856 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 15:25:17.477  3856  3856 D PanProfile: Bluetooth service disconnected
08-25 15:25:17.477  4081  4081 D BluetoothMapService: Received stop request...Stopping profile...
08-25 15:25:17.477  4081  4081 D BluetoothMapService: stop()
08-25 15:25:17.477  4081  4081 D BluetoothMapAppObserver: deinitObservers()
08-25 15:25:17.477  4081  4081 D BluetoothMapAppObserver: removeReceiver()
08-25 15:25:17.479  1357  1357 D BluetoothMap: Proxy object disconnected
08-25 15:25:17.479  1357  1357 D MapProfile: Bluetooth service disconnected
08-25 15:25:17.479  4081  4081 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 15:25:17.479  4081  4081 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 15:25:17.479  4081  4097 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 15:25:17.479  4081  4081 V BluetoothAdapterState: isTurningOff()=true
,08-25 15:25:17.479  3856  3856 D BluetoothMap: Proxy object disconnected
08-25 15:25:17.479  4081  4081 V BluetoothAdapterState: isTurningOn()=false
,08-25 15:25:17.480  3856  3856 D MapProfile: Bluetooth service disconnected
08-25 15:25:17.480  4081  4081 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:17.480  4081  4081 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:17.480  4081  4081 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 15:25:17.480  4081  4097 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-25 15:25:17.480  4081  4081 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 15:25:17.481  3856  3856 D BluetoothPbap: Proxy object disconnected
08-25 15:25:17.482  3856  3856 D PbapServerProfile: Bluetooth service disconnected
08-25 15:25:17.482  1357  1357 D BluetoothPbap: Proxy object disconnected
08-25 15:25:17.483  1357  1357 D PbapServerProfile: Bluetooth service disconnected
,08-25 15:25:17.483  4081  4081 V BluetoothAdapterState: isTurningOff()=true
08-25 15:25:17.483  4081  4081 V BluetoothAdapterState: isTurningOn()=false
08-25 15:25:17.483  4081  4081 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:17.483  4081  4081 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 15:25:17.485  4081  4081 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-25 15:25:17.486  4081  4081 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-25 15:25:17.487  4081  4081 D BluetoothMapService: MAP Service closeService in
08-25 15:25:17.488  4081  4081 V BluetoothAdapterState: isTurningOff()=true
08-25 15:25:17.488  4081  4081 V BluetoothAdapterState: isTurningOn()=false
,08-25 15:25:17.488  4081  4081 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:17.488  4081  4081 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 15:25:17.488  4081  4081 D BluetoothMapService: cleanup()
08-25 15:25:17.488  4081  4081 D BluetoothMapService: MAP Service closeService in
08-25 15:25:17.488  4081  4093 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 15:25:17.488  4081  4093 D BluetoothAdapterProperties: Setting state to 15
,08-25 15:25:17.488  4081  4093 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 15:25:17.489  4081  4093 I BluetoothAdapterState: Entering BleOnState
08-25 15:25:17.490  3856  3869 D BluetoothMap: onBluetoothStateChange: up=false
08-25 15:25:17.491  3856  3867 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 15:25:17.492  1357  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 15:25:17.492   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 15:25:17.492   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:25:17.493  1357  1368 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 15:25:17.494  3856  3869 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 15:25:17.494  3856  3867 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 15:25:17.495   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 15:25:17.495  1357  2045 D BluetoothPan: onBluetoothStateChange on: false
08-25 15:25:17.496  3856  3869 D BluetoothPan: onBluetoothStateChange on: false
,08-25 15:25:17.497  1357  1374 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 15:25:17.497  3856  3867 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 15:25:17.498   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:25:17.498  1357  1368 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:25:17.498  1357  2045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 15:25:17.499  1953  1967 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 15:25:17.499  4081  4093 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 15:25:17.499  4081  4093 D BluetoothAdapterProperties: Setting state to 16
08-25 15:25:17.499  4081  4093 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-25 15:25:17.500  4081  4093 D BluetoothAdapterProperties: onBleDisable
08-25 15:25:17.501  4081  4094 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-25 15:25:17.503  4081  4105 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-25 15:25:17.503  4081  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 15:25:17.504  4081  4093 I BluetoothAdapterState: Entering PendingCommandState
08-25 15:25:17.504  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:17.505  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:17.506  4081  4097 D BluetoothAdapterProperties: Scan Mode:20
08-25 15:25:17.507  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:17.509  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:17.509  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 15:25:17.515  1585  1585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:25:17.519  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:25:17.704  4081  4097 I bt_hci  : shut_down
,08-25 15:25:17.728  4081  4101 I bt_vendor: low_power_mode_cb
,08-25 15:25:17.734  4081  4101 D bt_hwcfg: hw_epilog_process
,08-25 15:25:17.742  4081  4101 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 15:25:17.742  4081  4101 I bt_vendor: epilog_cb
,08-25 15:25:17.742  4081  4101 I bt_hci  : epilog_finished_callback
,08-25 15:25:17.749  4081  4097 I bt_hci_h4: hal_close
,08-25 15:25:17.751  4081  4097 I bt_userial_vendor: device fd = 51 close
,08-25 15:25:17.870  4081  4094 D bt_stack_manager: event_shut_down_stack finished.
,08-25 15:25:17.872  4081  4093 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 15:25:17.879  4081  4093 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 15:25:17.880  4081  4081 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 15:25:17.881  4081  4081 D BtGatt.GattService: Received stop request...Stopping profile...
,08-25 15:25:17.881  4081  4081 D BtGatt.GattService: stop()
08-25 15:25:17.882  4081  4081 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 15:25:17.886  4081  4081 V BluetoothAdapterState: isTurningOff()=false
,08-25 15:25:17.886  4081  4081 V BluetoothAdapterState: isTurningOn()=false
08-25 15:25:17.887  4081  4081 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:17.887  4081  4081 V BluetoothAdapterState: isBleTurningOff()=true
08-25 15:25:17.888  4081  4093 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-25 15:25:17.888  4081  4093 D BluetoothAdapterProperties: Setting state to 10
08-25 15:25:17.888  4081  4093 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-25 15:25:17.890  4081  4093 I BluetoothAdapterState: Entering OffState
,08-25 15:25:17.891   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 15:25:17.906  4081  4081 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 15:25:17.906  4081  4081 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 15:25:17.906  4081  4081 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 15:25:17.908  4081  4094 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 15:25:17.912  4081  4094 D bt_stack_manager: event_clean_up_stack finished.
,08-25 15:25:17.914  4081  4081 I art     : System.exit called, status: 0
,08-25 15:25:17.914  4081  4081 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 15:25:17.957   874  3112 I ActivityManager: Process com.android.bluetooth (pid 4081) has died
,08-25 15:25:18.903   874  1316 D ConnectivityService: handlePromptUnvalidated 101
,08-25 15:25:20.413  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 15:25:20.413  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:21.734   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-25 15:25:21.742  1895  1895 I Keyboard.Facilitator: onFinishInput()
,08-25 15:25:21.750   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 15:25:21.750   874   894 I Adreno  : Build Date                       : 10/20/15
08-25 15:25:21.750   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 15:25:21.750   874   894 I Adreno  : Local Branch                     : M14
08-25 15:25:21.750   874   894 I Adreno  : Remote Branch                    : 
08-25 15:25:21.750   874   894 I Adreno  : Remote Branch                    : 
08-25 15:25:21.750   874   894 I Adreno  : Reconstruct Branch               : 
,08-25 15:25:21.791   280   361 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (319 us)
,08-25 15:25:22.479  3787  3787 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-25 15:25:22.480  3787  3787 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 15:25:22.514   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-25 15:25:22.519  3787  3787 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@77da4d1 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@fdc0e93, 16908290=android.view.AbsSavedState$1@fdc0e93}, android:focusedViewId=100}]}]
,08-25 15:25:22.520  3787  3787 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-25 15:25:22.522   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
08-25 15:25:22.522  3787  3787 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 15:25:22.522  3787  3787 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-25 15:25:22.533   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-25 15:25:22.533   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-25 15:25:22.549   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-25 15:25:22.781   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-25 15:25:22.787   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-25 15:25:22.788   874  1337 D SurfaceControl: Excessive delay in setPowerMode(): 255ms
,08-25 15:25:22.791   874   894 I DreamManagerService: Entering dreamland.
,08-25 15:25:22.793   874   894 I PowerManagerService: Dozing...
,08-25 15:25:22.794   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-25 15:25:22.843   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-25 15:25:22.843   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-25 15:25:22.856   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
08-25 15:25:22.859   874  1314 E native  : do suspend false
08-25 15:25:22.864  1938  4142 D NfcService: Discovery configuration equal, not updating.
08-25 15:25:22.893   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
08-25 15:25:22.896   874  1314 E native  : do suspend true
,08-25 15:25:22.980   376  1286 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-25 15:25:22.980   376  1286 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-25 15:25:23.421  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 15:25:23.422  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5d52ed0 added. We now have 6 listener(s)
08-25 15:25:23.422  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:25:23.426  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 15:25:23.426  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e87ec9 added. We now have 7 listener(s)
08-25 15:25:23.427  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:25:23.428  3787  3836 I System.out: IsBluetoothEnabled
,08-25 15:25:23.440  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:23.492   874   891 I ActivityManager: Start proc 4148:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-25 15:25:23.620  4148  4148 D AdapterServiceConfig: Adding HeadsetService
,08-25 15:25:23.620  4148  4148 D AdapterServiceConfig: Adding A2dpService
08-25 15:25:23.620  4148  4148 D AdapterServiceConfig: Adding HidService
08-25 15:25:23.621  4148  4148 D AdapterServiceConfig: Adding HealthService
,08-25 15:25:23.621  4148  4148 D AdapterServiceConfig: Adding PanService
08-25 15:25:23.622  4148  4148 D AdapterServiceConfig: Adding GattService
08-25 15:25:23.622  4148  4148 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 15:25:23.638   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2262109:true
08-25 15:25:23.639  4148  4148 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 15:25:23.644  4148  4148 I bt_bluedroid: init
,08-25 15:25:23.645  4148  4160 I BluetoothAdapterState: Entering OffState
,08-25 15:25:23.650  4148  4161 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 15:25:23.651  4148  4161 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 15:25:23.651  4148  4161 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 15:25:23.652  4148  4161 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 15:25:23.653  4148  4148 I bt_bluedroid: get_profile_interface socket
,08-25 15:25:23.656  4148  4148 I bt_bluedroid: get_profile_interface sdp
,08-25 15:25:23.660  4148  4164 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-25 15:25:23.661  4148  4159 I bt_bluedroid: config_hci_snoop_log
,08-25 15:25:23.663  4148  4164 D BluetoothAdapterProperties: Name is: Nexus 6
08-25 15:25:23.664   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 15:25:23.673  4148  4160 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 15:25:23.673  4148  4160 D BluetoothAdapterProperties: Setting state to 14
08-25 15:25:23.674  4148  4160 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 15:25:23.678  4148  4160 D BluetoothBondStateMachine: make
,08-25 15:25:23.684  4148  4165 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 15:25:23.693  4148  4160 I BluetoothAdapterState: Entering PendingCommandState
,08-25 15:25:23.694  4148  4148 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 15:25:23.701  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
,08-25 15:25:23.703  4148  4148 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 15:25:23.704  4148  4148 D BtGatt.GattService: Received start request. Starting profile...
,08-25 15:25:23.705  4148  4148 D BtGatt.GattService: start()
,08-25 15:25:23.706  4148  4148 I bt_bluedroid: get_profile_interface gatt
,08-25 15:25:23.708  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
08-25 15:25:23.708  4148  4148 D BtGatt.AdvertiseManager: advertise manager created
,08-25 15:25:23.724  4148  4148 V BluetoothAdapterState: isTurningOff()=false
,08-25 15:25:23.724  4148  4148 V BluetoothAdapterState: isTurningOn()=false
,08-25 15:25:23.725  4148  4148 V BluetoothAdapterState: isBleTurningOn()=true
08-25 15:25:23.725  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 15:25:23.729  4148  4160 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-25 15:25:23.730  4148  4160 I bt_bluedroid: enable
,08-25 15:25:23.730  4148  4161 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-25 15:25:23.731  4148  4161 I bt_hci  : start_up
,08-25 15:25:23.752  4148  4161 I bt_vendor: alloc value 0xb39b9189
,08-25 15:25:23.752  4148  4161 I bt_vendor: init
08-25 15:25:23.752  4148  4161 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-25 15:25:23.752  4148  4161 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 15:25:23.861  4148  4161 D bt_hci  : start_up starting async portion
,08-25 15:25:23.862  4148  4168 I bt_hci  : event_finish_startup
08-25 15:25:23.862  4148  4168 I bt_hci_h4: hal_open
,08-25 15:25:23.863  4148  4168 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 15:25:23.873  4148  4168 I bt_userial_vendor: device fd = 51 open
,08-25 15:25:23.904  4148  4168 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 15:25:23.935  4148  4168 D bt_hwcfg: Chipset BCM4354A2
,08-25 15:25:23.935  4148  4168 D bt_hwcfg: Target name = [BCM4354A2]
08-25 15:25:23.936  4148  4168 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 15:25:24.594  4148  4168 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 15:25:24.595  4148  4168 D bt_hwcfg: Settlement delay -- 100 ms
,08-25 15:25:24.596  4148  4168 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 15:25:24.712  4148  4168 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 15:25:24.714  4148  4168 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 15:25:24.743  4148  4168 I bt_hwcfg: vendor lib fwcfg completed
,08-25 15:25:24.743  4148  4168 I bt_vendor: firmware callback
,08-25 15:25:24.743  4148  4168 I bt_hci  : firmware_config_callback
,08-25 15:25:24.754  4148  4170 I bt_btu  : btu_task pending for preload complete event
,08-25 15:25:24.754  4148  4170 I bt_btu_task: Bluetooth chip preload is complete
08-25 15:25:24.754  4148  4170 I bt_btu  : btu_task received preload complete event
,08-25 15:25:24.766  4148  4170 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 15:25:24.766  4148  4170 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 15:25:24.766  4148  4170 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 15:25:24.767  4148  4170 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 15:25:24.767  4148  4170 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 15:25:24.767  4148  4170 I         : BTE_InitTraceLevels -- TRC_A2D
,08-25 15:25:24.768  4148  4170 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 15:25:24.769  4148  4170 I         : BTE_InitTraceLevels -- TRC_BTM
,08-25 15:25:24.769  4148  4170 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 15:25:24.770  4148  4170 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 15:25:24.770  4148  4170 I         : BTE_InitTraceLevels -- TRC_SDP
,08-25 15:25:24.771  4148  4170 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 15:25:24.772  4148  4170 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 15:25:24.772  4148  4170 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 15:25:24.772  4148  4170 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 15:25:24.913  4148  4170 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
,08-25 15:25:24.913  4148  4170 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,08-25 15:25:24.923  4148  4164 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-25 15:25:24.925  4148  4164 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 15:25:24.925  4148  4164 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 15:25:24.932  4148  4164 D BluetoothAdapterProperties: Name is: Nexus 6
08-25 15:25:24.936  4148  4164 D BluetoothAdapterProperties: Scan Mode:20
,08-25 15:25:24.936  4148  4164 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 15:25:24.941  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:24.941  4148  4164 D bt_hci  : do_postload posting postload work item
,08-25 15:25:24.941  4148  4168 I bt_hci  : event_postload
,08-25 15:25:24.942  4148  4168 I bt_vendor: sco_config_cb
08-25 15:25:24.942  4148  4168 I bt_hci  : sco_config_callback postload finished.
08-25 15:25:24.945  4148  4164 D bt_bte_conf: Device ID record 1 : primary
08-25 15:25:24.945  4148  4164 D bt_bte_conf:   vendorId            = 000f
08-25 15:25:24.945  4148  4164 D bt_bte_conf:   vendorIdSource      = 0001
08-25 15:25:24.946  4148  4164 D bt_bte_conf:   product             = 1200
,08-25 15:25:24.946  4148  4164 D bt_bte_conf:   version             = 1436
08-25 15:25:24.946  4148  4164 D bt_bte_conf:   clientExecutableURL = 
08-25 15:25:24.946  4148  4164 D bt_bte_conf:   serviceDescription  = 
08-25 15:25:24.946  4148  4164 D bt_bte_conf:   documentationURL    = 
08-25 15:25:24.946  4148  4164 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 15:25:24.947  4148  4161 D bt_stack_manager: event_start_up_stack finished
,08-25 15:25:24.948  4148  4160 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 15:25:24.949  4148  4168 I bt_vendor: low_power_mode_cb
08-25 15:25:24.949  4148  4160 D BluetoothAdapterProperties: Setting state to 15
08-25 15:25:24.949  4148  4160 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-25 15:25:24.951  4148  4160 I BluetoothAdapterState: Entering BleOnState
,08-25 15:25:24.957  4148  4160 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-25 15:25:24.957  4148  4160 D BluetoothAdapterProperties: Setting state to 11
08-25 15:25:24.958  4148  4160 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 15:25:24.967  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:24.971  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
,08-25 15:25:24.973  4148  4148 D HeadsetService: Received start request. Starting profile...
,08-25 15:25:24.977  4148  4160 I BluetoothAdapterState: Entering PendingCommandState
,08-25 15:25:24.979  4148  4148 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-25 15:25:24.980  4148  4148 D HeadsetStateMachine: make
,08-25 15:25:24.989  4148  4148 D HeadsetStateMachine: max_hf_connections = 1
08-25 15:25:24.989  4148  4148 I bt_bluedroid: get_profile_interface handsfree
,08-25 15:25:24.989  4148  4164 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-25 15:25:24.992  4148  4164 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-25 15:25:24.994  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
08-25 15:25:24.995  1585  1585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:25:24.995  4148  4148 D A2dpService: Received start request. Starting profile...
,08-25 15:25:24.996  4148  4148 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 15:25:24.996  4148  4148 I bt_bluedroid: get_profile_interface avrcp
,08-25 15:25:25.003  4148  4148 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 15:25:25.003  4148  4148 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 15:25:25.003  4148  4148 D A2dpStateMachine: make
,08-25 15:25:25.004  4148  4148 I bt_bluedroid: get_profile_interface a2dp
,08-25 15:25:25.005  4148  4164 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 15:25:25.008  4148  4179 D A2dpStateMachine: Enter Disconnected: -2
,08-25 15:25:25.009  4148  4148 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 15:25:25.010  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
,08-25 15:25:25.010  4148  4148 D HidService: Received start request. Starting profile...
,08-25 15:25:25.011  4148  4148 I bt_bluedroid: get_profile_interface hidhost
,08-25 15:25:25.011  4148  4148 D HidService: setHidService(): set to: null
08-25 15:25:25.011  4148  4164 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
08-25 15:25:25.011  4148  4164 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-25 15:25:25.011  4148  4148 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 15:25:25.012  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
08-25 15:25:25.013  4148  4148 D HealthService: Received start request. Starting profile...
,08-25 15:25:25.014  4148  4148 I bt_bluedroid: get_profile_interface health
,08-25 15:25:25.015  4148  4148 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 15:25:25.015  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
,08-25 15:25:25.016  4148  4148 D PanService: Received start request. Starting profile...
08-25 15:25:25.017  4148  4148 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-25 15:25:25.017  4148  4148 I bt_bluedroid: get_profile_interface pan
08-25 15:25:25.017  4148  4164 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 15:25:25.020  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
,08-25 15:25:25.021  4148  4148 D BluetoothMapService: Received start request. Starting profile...
,08-25 15:25:25.021  4148  4148 D BluetoothMapService: start()
,08-25 15:25:25.024  4148  4148 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 15:25:25.025  4148  4148 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-25 15:25:25.025  4148  4148 D BluetoothMapAppObserver: createReceiver()
,08-25 15:25:25.026  4148  4148 D BluetoothMapAppObserver: initObservers()
08-25 15:25:25.026  4148  4148 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 15:25:25.036  4148  4148 V BluetoothAdapterState: isTurningOff()=false
,08-25 15:25:25.036  4148  4148 V BluetoothAdapterState: isTurningOn()=true
08-25 15:25:25.037  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:25.037  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 15:25:25.039  4148  4177 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 15:25:25.040  4148  4148 V BluetoothAdapterState: isTurningOff()=false
08-25 15:25:25.040  4148  4148 V BluetoothAdapterState: isTurningOn()=true
,08-25 15:25:25.040  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 15:25:25.041  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:25.041  4148  4148 V BluetoothAdapterState: isTurningOff()=false
08-25 15:25:25.041  4148  4148 V BluetoothAdapterState: isTurningOn()=true
08-25 15:25:25.041  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:25.041  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 15:25:25.041  4148  4148 V BluetoothAdapterState: isTurningOff()=false
08-25 15:25:25.041  4148  4148 V BluetoothAdapterState: isTurningOn()=true
08-25 15:25:25.041  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
08-25 15:25:25.041  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 15:25:25.042  4148  4148 V BluetoothAdapterState: isTurningOff()=false
08-25 15:25:25.042  4148  4148 V BluetoothAdapterState: isTurningOn()=true
08-25 15:25:25.042  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 15:25:25.042  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:25.042  4148  4148 V BluetoothAdapterState: isTurningOff()=false
08-25 15:25:25.043  4148  4148 V BluetoothAdapterState: isTurningOn()=true
,08-25 15:25:25.043  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 15:25:25.043  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
08-25 15:25:25.044  4148  4160 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-25 15:25:25.044  4148  4160 D BluetoothAdapterProperties: ScanMode =  20
08-25 15:25:25.044  4148  4160 D BluetoothAdapterProperties: State =  11
08-25 15:25:25.045  4148  4160 D BluetoothAdapterProperties: Setting state to 12
,08-25 15:25:25.045  4148  4160 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 15:25:25.046  4148  4160 I BluetoothAdapterState: Entering OnState
08-25 15:25:25.046  3856  3867 D BluetoothMap: onBluetoothStateChange: up=true
08-25 15:25:25.047  4148  4164 D BluetoothAdapterProperties: Scan Mode:21
,08-25 15:25:25.047  4148  4164 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 15:25:25.049  3856  4138 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 15:25:25.051  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:25.051  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:25.051  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:25.051  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:25.051  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:25.051  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:25.051  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:25.051  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:25.053  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:25:25.054  1357  1374 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 15:25:25.055  3856  3856 D BluetoothMap: Proxy object connected
,08-25 15:25:25.055  3856  3856 D MapProfile: Bluetooth service connected
08-25 15:25:25.055  3856  3856 D BluetoothMap: getConnectedDevices()
08-25 15:25:25.055  4148  4148 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 15:25:25.056  1357  1357 D BluetoothInputDevice: Proxy object connected
,08-25 15:25:25.056  1357  1357 D HidProfile: Bluetooth service connected
08-25 15:25:25.056   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 15:25:25.056  4148  4148 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-25 15:25:25.057   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 15:25:25.057  1357  1368 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 15:25:25.059  4148  4148 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:25:25.059  3856  3869 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 15:25:25.062  4148  4148 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:25:25.062  3856  4138 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 15:25:25.064  4148  4148 D ObexServerSockets: Succeed to create listening sockets 
08-25 15:25:25.064  4148  4148 D ObexServerSockets0: startAccept()
08-25 15:25:25.064  4148  4148 D ObexServerSockets0: prepareForNewConnect()
08-25 15:25:25.065   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 15:25:25.066  1357  1374 D BluetoothPan: onBluetoothStateChange on: true
,08-25 15:25:25.068  4148  4148 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-25 15:25:25.068  4148  4148 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-25 15:25:25.068  3856  3856 D BluetoothInputDevice: Proxy object connected
08-25 15:25:25.068  3856  3856 D HidProfile: Bluetooth service connected
08-25 15:25:25.068  4148  4185 D ObexServerSockets0: Accepting socket connection...
08-25 15:25:25.069  3856  3867 D BluetoothPan: onBluetoothStateChange on: true
,08-25 15:25:25.070   874   874 D BluetoothA2dp: Proxy object connected
,08-25 15:25:25.071  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 15:25:25.071  1357  1357 D PanProfile: Bluetooth service connected
08-25 15:25:25.072  4148  4186 D ObexServerSockets0: Accepting socket connection...
08-25 15:25:25.072  1357  1368 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 15:25:25.074  3856  3869 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 15:25:25.074  1357  1357 D BluetoothMap: Proxy object connected
08-25 15:25:25.075  1357  1357 D MapProfile: Bluetooth service connected
08-25 15:25:25.075  1357  1357 D BluetoothMap: getConnectedDevices()
,08-25 15:25:25.075   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 15:25:25.075  3856  3856 D BluetoothA2dp: Proxy object connected
08-25 15:25:25.075  1357  2045 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 15:25:25.076  1357  1368 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 15:25:25.078  1953  2109 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 15:25:25.078  1357  1357 D BluetoothA2dp: Proxy object connected
,08-25 15:25:25.079  3856  3856 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 15:25:25.080  3856  3856 D PanProfile: Bluetooth service connected
,08-25 15:25:25.081   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 15:25:25.084  4148  4148 D BluetoothMapService: onReceive
,08-25 15:25:25.084  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:25.084  4148  4148 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:25.084  4148  4148 D BluetoothMapService: STATE_ON
,08-25 15:25:25.089  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 15:25:25.096  1585  1585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:25:25.098  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:25:25.105  3856  3856 D BluetoothPbap: Proxy object connected
08-25 15:25:25.105  3856  3856 D PbapServerProfile: Bluetooth service connected
,08-25 15:25:25.109  1357  1357 D BluetoothPbap: Proxy object connected
08-25 15:25:25.110  1357  1357 D PbapServerProfile: Bluetooth service connected
,08-25 15:25:25.111  4148  4148 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 15:25:25.111  4148  4148 D ObexServerSockets0: prepareForNewConnect()
,08-25 15:25:25.115  4148  4190 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 15:25:25.129  4148  4194 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 15:25:25.130  4148  4194 I BtOppRfcommListener: Accept thread started.
,08-25 15:25:25.158   874   874 D BluetoothHeadset: Proxy object connected
,08-25 15:25:25.158   874   874 D BluetoothHeadset: Proxy object connected
08-25 15:25:25.159  1357  1374 D BluetoothHeadset: Proxy object connected
,08-25 15:25:25.159  1357  1357 D HeadsetProfile: Bluetooth service connected
,08-25 15:25:25.159  1953  1967 D BluetoothHeadset: Proxy object connected
,08-25 15:25:25.160  3856  3867 D BluetoothHeadset: Proxy object connected
,08-25 15:25:25.160   874   874 D BluetoothHeadset: Proxy object connected
08-25 15:25:25.160  3856  3856 D HeadsetProfile: Bluetooth service connected
,08-25 15:25:25.166   874   891 D BluetoothHeadset: Proxy object connected
,08-25 15:25:25.175  3856  3869 D BluetoothHeadset: Proxy object connected
08-25 15:25:25.175  3856  3856 D HeadsetProfile: Bluetooth service connected
,08-25 15:25:25.175   874   891 D BluetoothHeadset: Proxy object connected
,08-25 15:25:25.177  1357  1368 D BluetoothHeadset: Proxy object connected
08-25 15:25:25.177  1357  1357 D HeadsetProfile: Bluetooth service connected
,08-25 15:25:25.179  1953  1974 D BluetoothHeadset: Proxy object connected
,08-25 15:25:25.464  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:25.464  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:25.464  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:25.464  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:25.464  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:25.464  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:25.464  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:25.464  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:25.470  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:25.474  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 15:25:25.475  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61569ce added. We now have 8 listener(s)
,08-25 15:25:25.475  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:25:25.483   874  3112 D WifiService: setWifiEnabled: false pid=3787, uid=10000
,08-25 15:25:25.484   874  3112 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 15:25:25.497  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:25.498   874   885 D WifiService: setWifiEnabled: true pid=3787, uid=10000
,08-25 15:25:25.498   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 15:25:25.512   874  1314 D WifiConfigStore: Loading config and enabling all networks 
,08-25 15:25:25.533  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:25.533  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:25.533  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:25.533  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:25.533  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:25.533  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:25.533  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:25.533  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:25.547  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:25.552   874  1314 D WifiConfigStore: loaded 0 passpoint configs
,08-25 15:25:25.553   874  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 15:25:25.554   874  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 15:25:25.555   874  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-25 15:25:25.555   874  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-25 15:25:25.555   874  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-25 15:25:25.555   874  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 15:25:25.568   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-25 15:25:25.569   372   872 D CommandListener: Setting iface cfg
08-25 15:25:25.569   874  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.20 rxSuccessRate=0.25 delta 1000 -> 1000
,08-25 15:25:25.570   874  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-25 15:25:25.570   874  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 15:25:25.572   874  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-25 15:25:25.627   874  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 15:25:25.628   874  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 15:25:25.631   874  1314 E native  : do suspend true
,08-25 15:25:25.666   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-25 15:25:25.666   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 15:25:25.673   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 15:25:25.710   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 15:25:25.711  1485  1485 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 15:25:26.150  1485  1485 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 15:25:26.189  1485  1485 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 15:25:26.190  1485  1485 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-25 15:25:26.191   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 15:25:26.204   874  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-25 15:25:26.204   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 15:25:26.204   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 15:25:26.225   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 15:25:26.238   372   872 D CommandListener: Setting iface cfg
08-25 15:25:26.238   874  1314 D WifiStateMachine: Start Dhcp Watchdog 3
,08-25 15:25:26.246   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 15:25:26.267   874  4203 D DhcpClient: Receive thread started
,08-25 15:25:26.351   874  1314 E native  : do suspend false
,08-25 15:25:26.371   874  2237 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 15:25:26.387   874  4203 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172784, domain null
,08-25 15:25:26.388   874  2237 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172784 seconds
08-25 15:25:26.391   874  2237 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 15:25:26.405   874  4203 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 15:25:26.406   874  2237 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 15:25:26.411   372   872 D CommandListener: Setting iface cfg
,08-25 15:25:26.422   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 15:25:26.423   874  2237 D DhcpClient: Scheduling renewal in 86399s
,08-25 15:25:26.425   874  1314 E native  : do suspend true
,08-25 15:25:26.442   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 15:25:26.445   874  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 15:25:26.447   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 15:25:26.449   874  1316 D ConnectivityService: Adding iface wlan0 to network 102
,08-25 15:25:26.456   874  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 15:25:26.510   874  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 15:25:26.510   874  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-25 15:25:26.513   874  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-25 15:25:26.515   874  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-25 15:25:26.517   874  1316 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-25 15:25:26.530  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:26.530  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:26.530  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:26.530  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:26.530  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:26.530  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:26.530  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:26.530  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:26.531   874  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-25 15:25:26.535  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:26.538   874  1316 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-25 15:25:26.538   874  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-25 15:25:26.538   874  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-25 15:25:26.539   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 15:25:26.539   874  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-25 15:25:26.539   874  1316 D ConnectivityService:    accepting network in place of null
08-25 15:25:26.541   874  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 15:25:26.547   874  4202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155071, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 15:25:26.550  3787  3836 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-25 15:25:26.551  3787  3836 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 15:25:26.553  3787  3836 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@77da4d1 Bundle[{}]
,08-25 15:25:26.554  3787  3836 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 15:25:26.554  3787  3836 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 15:25:26.555  3787  3836 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-25 15:25:26.556  3787  3836 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 15:25:26.556  3787  3836 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-25 15:25:26.557  3787  3836 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 15:25:26.561  3787  3836 I System.out: Running OutgoingSocketThread
,08-25 15:25:26.563  3787  4208 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 420)
,08-25 15:25:26.564  3787  4208 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49131
,08-25 15:25:26.564  3787  4208 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 15:25:26.584   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 15:25:26.615   874  4201 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.198.142,2a00:1450:4001:80e::200e
,08-25 15:25:26.616   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 15:25:26.629   874  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-25 15:25:26.629   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:25:26.636   874  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-25 15:25:26.637   874   891 D Tethering: MasterInitialState.processMessage what=3
08-25 15:25:26.655  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:26.655  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:26.655  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:26.655  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:26.655  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:26.655  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:26.655  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:26.655  3787  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:25:26.659  3787  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:25:26.668  1745  1745 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 15:25:26.673  1745  1745 D SystemUpdateService: onCreate
,08-25 15:25:26.678  1745  1745 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 15:25:26.685   874  4201 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 13:25:26 GMT], X-Android-Received-Millis=[1472131526685], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472131526659]}
,08-25 15:25:26.687   874  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 15:25:26.687   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-25 15:25:26.687   874  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 15:25:26.688   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 15:25:26.698  1745  4213 I SystemUpdateService: active receiver: enabled
,08-25 15:25:26.704  1745  1745 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 15:25:26.711  1745  2537 I iu.UploadsManager: num queued entries: 0
,08-25 15:25:26.711  1745  2537 I iu.UploadsManager: num updated entries: 0
08-25 15:25:26.712  1745  2537 I iu.SyncManager: NEXT; no task
,08-25 15:25:26.715  1745  4213 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 15:25:26.718  1745  1745 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 15:25:26.719  1745  1745 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 15:25:26.722  3911  3911 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:25:26.725  1745  4217 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-25 15:25:26.725  1745  4217 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 15:25:26.726  1745  4217 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 15:25:26.729  3911  3911 D SprintDMHelper: simOperator: 
08-25 15:25:26.729  3911  3911 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 15:25:26.736  1745  4213 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 15:25:26.737  1745  4213 I SystemUpdateService: now status is 0 (complete)
08-25 15:25:26.737  1745  4213 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 15:25:26.737  1745  4213 I SystemUpdateService: file has been verified
08-25 15:25:26.737  1745  4213 I SystemUpdateService: OTA package size = 12249756
,08-25 15:25:26.749  1585  1585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 15:25:26.751  1585  1585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 15:25:26.771  1745  4213 I SystemUpdateService: showing system update notification
,08-25 15:25:26.806  1745  1745 D SystemUpdateService: onDestroy
,08-25 15:25:26.816  1585  2091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 15:25:26.816  1585  2091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-25 15:25:26.816  1585  2091 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 15:25:26.816  1585  2091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 15:25:26.836  1745  4217 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-25 15:25:26.859  2471  4219 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 15:25:27.561  2181  2512 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-25 15:25:27.566  3787  3836 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 421)
,08-25 15:25:27.566  3787  3836 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 421)
,08-25 15:25:27.576  3787  3836 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 426)
,08-25 15:25:27.579  3787  3836 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-25 15:25:27.580  3787  3836 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 427)
,08-25 15:25:27.586  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 15:25:27.587  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af00ef added. We now have 2 listener(s)
,08-25 15:25:27.591  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 15:25:27.592  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:27.592  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 15:25:27.593  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 15:25:27.593  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a667fc added. We now have 9 listener(s)
08-25 15:25:27.593  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:27.595  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 15:25:27.602  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:25:27.615  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:25:27.615  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:27.615  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:27.615  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:27.615  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:27.615  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:27.615  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:27.615  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:25:27.620  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:25:27.621  3787  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:25:27.621  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:25:27.622  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2254da added. We now have 3 listener(s)
,08-25 15:25:27.627  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:27.630  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 15:25:27.630  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 15:25:27.631  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:27.631  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:27.632  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b14bd0b added. We now have 10 listener(s)
,08-25 15:25:27.632  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:25:27.634  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:27.634  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:27.634  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:27.634  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 15:25:27.635  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:27.635  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.636  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:25:27.636  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:27.637  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af00ef removed from the list
,08-25 15:25:27.637  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:27.637  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a667fc removed from the list
08-25 15:25:27.637  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:27.638  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:27.639  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.640  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:27.643  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:27.643  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:27.644  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:27.644  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a667fc not in the list
,08-25 15:25:27.644  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.644  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:27.647  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 15:25:27.647  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:27.647  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:27.648  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b14bd0b removed from the list
08-25 15:25:27.648  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 15:25:27.648  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.648  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:27.648  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:27.649  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2254da removed from the list
,08-25 15:25:27.651  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 15:25:27.651  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af007e8 added. We now have 2 listener(s)
,08-25 15:25:27.657  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 15:25:27.657  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:27.657  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:27.658  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:27.658  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3e01 added. We now have 9 listener(s)
,08-25 15:25:27.658  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:27.660  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 15:25:27.665  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:25:27.671  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:25:27.671  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:27.671  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:27.671  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:27.671  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:27.671  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:27.671  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:27.671  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:25:27.674  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:25:27.675  3787  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 15:25:27.675  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:25:27.675  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d01ee7 added. We now have 3 listener(s)
,08-25 15:25:27.677  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:27.679  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:27.680  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 15:25:27.680  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:27.680  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 15:25:27.681  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:27.681  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b1ba94 added. We now have 10 listener(s)
08-25 15:25:27.681  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:27.682  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:25:27.682  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 15:25:27.682  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:25:27.682  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:25:27.682  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 15:25:27.687  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 15:25:27.687  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 15:25:27.694  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 15:25:27.695  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 15:25:27.695  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 15:25:27.701  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 15:25:27.701  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 15:25:27.702  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 15:25:27.703  3787  3836 D BluetoothAdapter: STATE_ON
,08-25 15:25:27.708  4148  4175 D BtGatt.GattService: registerClient() - UUID=58ddd742-dd3b-4d1f-a27e-6a93533ff252
,08-25 15:25:27.710  4148  4164 D BtGatt.GattService: onClientRegistered() - UUID=58ddd742-dd3b-4d1f-a27e-6a93533ff252, clientIf=5
,08-25 15:25:27.712  3787  3829 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 15:25:27.714  4148  4184 D BtGatt.GattService: start scan with filters
,08-25 15:25:27.721  4148  4167 D BtGatt.ScanManager: handling starting scan
,08-25 15:25:27.723  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 15:25:27.723  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 15:25:27.723  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 15:25:27.723  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 15:25:27.726  4148  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61ad855
,08-25 15:25:27.729  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 15:25:27.730  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 15:25:27.730  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 15:25:27.733  4148  4164 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 15:25:27.733  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:27.734  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 15:25:27.735  4148  4167 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 15:25:27.741  3787  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 15:25:27.741  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:27.741  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 15:25:27.741  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.742  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 15:25:27.742  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 15:25:27.742  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 15:25:27.742  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 15:25:27.742  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 15:25:27.742  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 15:25:27.742  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 15:25:27.744  3787  3836 D BluetoothAdapter: STATE_ON
08-25 15:25:27.746  4148  4184 D BtGatt.GattService: stopScan() - queue size =1
08-25 15:25:27.747  4148  4158 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 15:25:27.747  4148  4164 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 15:25:27.747  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:27.748  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 15:25:27.748  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 15:25:27.748  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 15:25:27.748  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 15:25:27.748  4148  4167 D BtGatt.ScanManager: Starting BLE batch scan
08-25 15:25:27.748  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 15:25:27.748  4148  4167 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 15:25:27.751  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:25:27.751  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 15:25:27.752  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 15:25:27.752  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 15:25:27.755  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 15:25:27.758  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 15:25:27.759  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 15:25:27.759  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:25:27.761  4148  4164 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 15:25:27.762  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:27.762  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:27.762  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:27.762  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:27.762  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:27.762  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.763  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:25:27.763  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:27.763  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af007e8 removed from the list
08-25 15:25:27.763  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:27.763  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3e01 removed from the list
,08-25 15:25:27.763  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:27.763  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:27.765  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.765  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:27.767  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:27.767  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:27.767  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:27.767  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3e01 not in the list
08-25 15:25:27.767  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.768  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:27.768  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:27.768  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:27.769  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:27.769  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b1ba94 removed from the list
08-25 15:25:27.769  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:27.769  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:25:27.769  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:27.769  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:27.769  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d01ee7 removed from the list
08-25 15:25:27.770  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:25:27.770  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@839ec00 added. We now have 2 listener(s)
,08-25 15:25:27.772  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 15:25:27.772  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:27.772  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:27.772  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:27.773  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e91ac39 added. We now have 9 listener(s)
,08-25 15:25:27.773  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:27.773  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 15:25:27.776  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:25:27.780  4148  4164 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 15:25:27.780  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:27.782  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:25:27.782  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:27.782  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:27.782  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:27.782  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:27.782  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:27.782  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:27.782  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:25:27.784  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:27.784  3787  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 15:25:27.785  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 15:25:27.785  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4803df added. We now have 3 listener(s)
08-25 15:25:27.787  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:27.789  4148  4164 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 15:25:27.789  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:27.789  4148  4167 D BtGatt.ScanManager: stopping BLe Batch
08-25 15:25:27.790  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 15:25:27.790  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:27.790  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:27.791  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:27.791  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@651c82c added. We now have 10 listener(s)
08-25 15:25:27.791  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:27.791  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:25:27.792  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:25:27.792  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 15:25:27.792  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:27.792  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:25:27.792  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:25:27.792  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 15:25:27.796  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 15:25:27.796  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 15:25:27.798  4148  4164 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 15:25:27.798  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:27.798  4148  4167 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 15:25:27.803  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 15:25:27.803  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 15:25:27.803  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 15:25:27.807  4148  4164 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 15:25:27.807  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:27.808  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 15:25:27.808  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 15:25:27.808  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 15:25:27.809  3787  3836 D BluetoothAdapter: STATE_ON
,08-25 15:25:27.811  4148  4159 D BtGatt.GattService: registerClient() - UUID=1f8489b2-8f69-4d37-822b-f799c23192d3
08-25 15:25:27.812  4148  4164 D BtGatt.GattService: onClientRegistered() - UUID=1f8489b2-8f69-4d37-822b-f799c23192d3, clientIf=5
,08-25 15:25:27.812  3787  3829 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 15:25:27.812  4148  4175 D BtGatt.GattService: start scan with filters
,08-25 15:25:27.815  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 15:25:27.815  4148  4167 D BtGatt.ScanManager: handling starting scan
,08-25 15:25:27.815  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 15:25:27.815  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 15:25:27.815  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 15:25:27.819  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 15:25:27.819  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 15:25:27.819  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 15:25:27.821  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 15:25:27.821  4148  4164 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 15:25:27.822  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:27.822  4148  4167 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 15:25:27.824  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 15:25:27.825  3787  3836 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-25 15:25:27.825  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:27.825  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:27.825  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 15:25:27.826  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:27.826  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:25:27.826  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 15:25:27.826  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:27.826  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@839ec00 removed from the list
08-25 15:25:27.826  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:27.826  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e91ac39 removed from the list
08-25 15:25:27.826  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:27.826  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:25:27.827  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.827  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-25 15:25:27.827  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.827  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:25:27.829  4148  4164 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 15:25:27.829  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:27.829  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:27.829  4148  4167 D BtGatt.ScanManager: Starting BLE batch scan
08-25 15:25:27.829  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:27.829  4148  4167 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 15:25:27.829  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:27.829  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e91ac39 not in the list
08-25 15:25:27.829  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 15:25:27.830  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 15:25:27.830  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 15:25:27.830  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 15:25:27.830  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 15:25:27.831  3787  3836 D BluetoothAdapter: STATE_ON
,08-25 15:25:27.832  4148  4159 D BtGatt.GattService: stopScan() - queue size =1
08-25 15:25:27.833  4148  4175 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 15:25:27.834  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:25:27.834  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 15:25:27.834  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 15:25:27.834  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 15:25:27.834  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 15:25:27.836  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:25:27.836  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 15:25:27.836  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 15:25:27.836  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 15:25:27.837  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:27.838  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 15:25:27.838  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:25:27.838  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 15:25:27.839  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:27.839  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:27.839  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:25:27.839  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@651c82c removed from the list
08-25 15:25:27.839  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:27.839  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.839  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:27.839  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 15:25:27.840  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4803df removed from the list
08-25 15:25:27.841  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:25:27.841  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d293b18 added. We now have 2 listener(s)
08-25 15:25:27.841  4148  4164 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 15:25:27.841  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:27.843  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 15:25:27.843  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:27.843  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:27.843  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:27.843  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71fa971 added. We now have 9 listener(s)
08-25 15:25:27.843  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:27.844  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 15:25:27.848  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:25:27.848  4148  4164 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 15:25:27.848  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:27.854  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:25:27.854  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:27.854  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:27.854  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:27.854  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:27.854  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:27.854  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:27.854  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:25:27.856  4148  4164 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 15:25:27.856  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:27.857  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:27.857  3787  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:25:27.857  4148  4167 D BtGatt.ScanManager: stopping BLe Batch
,08-25 15:25:27.858  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 15:25:27.858  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7488fd7 added. We now have 3 listener(s)
08-25 15:25:27.859  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:27.860  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 15:25:27.860  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:27.860  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:27.861  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:27.861  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d02f0c4 added. We now have 10 listener(s)
08-25 15:25:27.861  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:25:27.861  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:25:27.861  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:27.861  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 15:25:27.862  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:25:27.862  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:25:27.862  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 15:25:27.865  4148  4164 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 15:25:27.865  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:27.865  4148  4167 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 15:25:27.869  3787  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 15:25:27.869  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
08-25 15:25:27.870  4148  4164 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 15:25:27.870  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:27.877  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 15:25:27.878  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 15:25:27.878  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 15:25:27.881  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 15:25:27.881  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 15:25:27.881  3787  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 15:25:27.882  3787  3836 D BluetoothAdapter: STATE_ON
,08-25 15:25:27.884  4148  4159 D BtGatt.GattService: registerClient() - UUID=5b33f3f7-e525-40a2-a809-d72ef167be44
,08-25 15:25:27.884  4148  4164 D BtGatt.GattService: onClientRegistered() - UUID=5b33f3f7-e525-40a2-a809-d72ef167be44, clientIf=5
08-25 15:25:27.884  3787  3829 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 15:25:27.885  4148  4175 D BtGatt.GattService: start scan with filters
,08-25 15:25:27.888  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 15:25:27.888  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 15:25:27.888  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 15:25:27.888  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 15:25:27.888  4148  4167 D BtGatt.ScanManager: handling starting scan
,08-25 15:25:27.890  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 15:25:27.891  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 15:25:27.891  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 15:25:27.893  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 15:25:27.897  4148  4164 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 15:25:27.897  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:27.897  4148  4167 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 15:25:27.897  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:27.897  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:27.898  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:27.898  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 15:25:27.898  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.898  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 15:25:27.898  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:27.898  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d293b18 removed from the list
08-25 15:25:27.898  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:25:27.898  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71fa971 removed from the list
08-25 15:25:27.898  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:27.898  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:25:27.899  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:25:27.899  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 15:25:27.899  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.899  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:25:27.900  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:27.901  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 15:25:27.901  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:27.901  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71fa971 not in the list
08-25 15:25:27.901  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 15:25:27.901  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 15:25:27.901  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 15:25:27.901  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 15:25:27.901  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 15:25:27.902  3787  3836 D BluetoothAdapter: STATE_ON
08-25 15:25:27.903  4148  4175 D BtGatt.GattService: stopScan() - queue size =1
08-25 15:25:27.904  4148  4184 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 15:25:27.904  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:25:27.904  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 15:25:27.905  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 15:25:27.905  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 15:25:27.905  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 15:25:27.906  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:25:27.906  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 15:25:27.906  3787  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 15:25:27.906  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 15:25:27.907  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:27.908  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 15:25:27.908  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 15:25:27.908  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:25:27.908  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:27.909  3787  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:25:27.909  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d02f0c4 removed from the list
08-25 15:25:27.909  3787  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:25:27.909  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:27.909  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.909  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:27.909  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:27.909  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7488fd7 removed from the list
,08-25 15:25:27.910  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:25:27.910  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a05530 added. We now have 2 listener(s)
,08-25 15:25:27.913  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 15:25:27.913  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:27.913  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 15:25:27.914  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:27.914  4148  4164 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 15:25:27.914  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:27.914  4148  4167 D BtGatt.ScanManager: Starting BLE batch scan
08-25 15:25:27.914  4148  4167 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 15:25:27.914  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25915a9 added. We now have 9 listener(s)
08-25 15:25:27.915  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:25:27.915  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 15:25:27.927  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:25:27.934  3787  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:25:27.934  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:27.934  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:27.934  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:27.934  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:27.934  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:27.934  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:27.934  3787  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:25:27.937  4148  4164 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 15:25:27.937  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:27.938  3787  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:25:27.938  3787  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:25:27.938  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:25:27.939  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85fa2cf added. We now have 3 listener(s)
,08-25 15:25:27.942  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:27.942  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 15:25:27.942  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:27.943  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:27.943  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:27.943  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d945c added. We now have 10 listener(s)
,08-25 15:25:27.943  3787  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:27.943  3787  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:27.944  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:27.944  3787  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:27.944  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:27.944  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:25:27.944  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:25:27.944  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:27.944  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a05530 removed from the list
08-25 15:25:27.944  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:27.945  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25915a9 removed from the list
08-25 15:25:27.945  3787  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:27.946  3787  3836 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:27.946  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:27.947  4148  4164 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 15:25:27.947  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:27.947  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.947  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:27.949  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:27.949  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:27.949  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:27.949  3787  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25915a9 not in the list
08-25 15:25:27.949  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.949  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:27.951  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:27.951  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 15:25:27.951  3787  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:27.951  3787  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d945c removed from the list
08-25 15:25:27.951  3787  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:27.951  3787  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:27.951  3787  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:27.951  3787  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 15:25:27.952  3787  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85fa2cf removed from the list
08-25 15:25:27.953  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 15:25:27.953  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-25 15:25:27.953  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-25 15:25:27.954  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:25:27.954  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 15:25:27.955  3787  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 15:25:27.957  4148  4164 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 15:25:27.957  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:27.958  4148  4167 D BtGatt.ScanManager: stopping BLe Batch
,08-25 15:25:27.964  3787  4226 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: My test thread name)
,08-25 15:25:27.964  3787  4226 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 434, thread name: My test thread name)
,08-25 15:25:27.964  3787  4226 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 434, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 15:25:27.965  4148  4164 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 15:25:27.965  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 15:25:27.965  4148  4167 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 15:25:27.966  3787  4227 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: My test thread name)
,08-25 15:25:27.967  3787  4227 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 436, thread name: My test thread name)
08-25 15:25:27.967  3787  4227 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 436, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 15:25:27.969  3787  3836 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 15:25:27.969  3787  3836 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 15:25:27.969  3787  3836 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 15:25:27.969  3787  3836 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-25 15:25:27.969  3787  3836 D com.test.thalitest.ThaliTestRunner: Total duration: 22949 ms
08-25 15:25:27.971  3787  3836 I jxcore-log: Total number of executed tests:  80
08-25 15:25:27.971  3787  3836 I jxcore-log: 
,08-25 15:25:27.971  3787  3836 I jxcore-log: Number of passed tests:  80
08-25 15:25:27.971  3787  3836 I jxcore-log: 
08-25 15:25:27.971  3787  3836 I jxcore-log: Number of failed tests:  0
08-25 15:25:27.971  3787  3836 I jxcore-log: 
08-25 15:25:27.972  3787  3836 I jxcore-log: Number of ignored tests:  0
08-25 15:25:27.972  3787  3836 I jxcore-log: 
08-25 15:25:27.972  3787  3836 I jxcore-log: Total duration:  22949
08-25 15:25:27.972  3787  3836 I jxcore-log: 
,08-25 15:25:27.973  4148  4164 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 15:25:27.973  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 15:25:27.973  3787  3836 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 15:25:27.973  3787  3836 I jxcore-log: 
08-25 15:25:27.978  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:27.978  3787  3836 I jxcore-log: 
,08-25 15:25:27.983  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:27.983  3787  3836 I jxcore-log: 
08-25 15:25:27.984  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:27.984  3787  3836 I jxcore-log: 
08-25 15:25:27.985  3787  3787 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 15:25:27.985  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:27.985  3787  3836 I jxcore-log: 
08-25 15:25:27.986  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:27.986  3787  3836 I jxcore-log: 
08-25 15:25:27.988  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:27.988  3787  3836 I jxcore-log: 
08-25 15:25:27.990  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:27.990  3787  3836 I jxcore-log: 
08-25 15:25:27.992  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 15:25:27.992  3787  3836 I jxcore-log: 
08-25 15:25:27.993  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 15:25:27.993  3787  3836 I jxcore-log: 
08-25 15:25:27.994  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:25:27.994  3787  3836 I jxcore-log: 
08-25 15:25:27.995  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:25:27.995  3787  3836 I jxcore-log: 
08-25 15:25:27.996  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 15:25:27.996  3787  3836 I jxcore-log: 
08-25 15:25:27.997  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 15:25:27.997  3787  3836 I jxcore-log: 
08-25 15:25:27.998  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 15:25:27.998  3787  3836 I jxcore-log: 
08-25 15:25:27.999  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:27.999  3787  3836 I jxcore-log: 
08-25 15:25:28.000  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:28.000  3787  3836 I jxcore-log: 
08-25 15:25:28.001  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 15:25:28.001  3787  3836 I jxcore-log: 
08-25 15:25:28.002  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 15:25:28.002  3787  3836 I jxcore-log: 
08-25 15:25:28.003  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:25:28.003  3787  3836 I jxcore-log: 
08-25 15:25:28.004  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:25:28.004  3787  3836 I jxcore-log: 
08-25 15:25:28.004  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 15:25:28.004  3787  3836 I jxcore-log: 
08-25 15:25:28.005  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 15:25:28.005  3787  3836 I jxcore-log: 
08-25 15:25:28.005  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:25:28.005  3787  3836 I jxcore-log: 
08-25 15:25:28.006  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:25:28.006  3787  3836 I jxcore-log: 
,08-25 15:25:28.007  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 15:25:28.007  3787  3836 I jxcore-log: 
08-25 15:25:28.007  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 15:25:28.007  3787  3836 I jxcore-log: 
,08-25 15:25:28.008  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 15:25:28.008  3787  3836 I jxcore-log: 
08-25 15:25:28.009  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 15:25:28.009  3787  3836 I jxcore-log: 
,08-25 15:25:28.009  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:28.009  3787  3836 I jxcore-log: 
,08-25 15:25:28.010  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:28.010  3787  3836 I jxcore-log: 
08-25 15:25:28.010  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:28.010  3787  3836 I jxcore-log: 
,08-25 15:25:28.011  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:28.011  3787  3836 I jxcore-log: 
,08-25 15:25:28.012  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:28.012  3787  3836 I jxcore-log: 
08-25 15:25:28.012  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:28.012  3787  3836 I jxcore-log: 
,08-25 15:25:28.260  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 15:25:28.263  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 15:25:28.263  3787  3836 I jxcore-log: 
,08-25 15:25:28.338  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 15:25:28.341  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 15:25:28.341  3787  3836 I jxcore-log: 
,08-25 15:25:28.409  3787  3787 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 15:25:28.412  3787  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 15:25:28.412  3787  3836 I jxcore-log: 
,08-25 15:25:28.627  4228  4228 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-25 15:25:28.632  4228  4228 D AndroidRuntime: CheckJNI is OFF
,08-25 15:25:28.675  4228  4228 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-25 15:25:28.722  4228  4228 I Radio-JNI: register_android_hardware_Radio DONE
,08-25 15:25:28.744  4228  4228 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 15:25:28.759   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-25 15:25:28.760   874   887 I ActivityManager: Killing 3787:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-25 15:25:28.861   874   897 W PackageSettings: Skipping PackageSetting{545e22e com.example.hello/10273} due to missing metadata
,08-25 15:25:28.885   874  2047 D GraphicsStats: Buffer count: 2
08-25 15:25:28.885   874  2047 I WindowState: WIN DEATH: Window{dfa9d86 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-25 15:25:28.887   874  1315 D WifiService: Client connection lost with reason: 4
,08-25 15:25:28.908   874   897 I art     : Starting a blocking GC Explicit
,08-25 15:25:28.922   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-25 15:25:28.922   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-25 15:25:28.926   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-25 15:25:28.926   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-25 15:25:28.926   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:28.926   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:28.926   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 15:25:28.926   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 15:25:28.927   874   887 I ActivityManager:   Force finishing activity ActivityRecord{65d8a6f u0 com.test.thalitest/.MainActivity t2}
08-25 15:25:28.932   874  1958 W ActivityManager: Spurious death for ProcessRecord{2a033ea 0:com.test.thalitest/u0a0}, curProc for 3787: null
,08-25 15:25:28.959   874   897 I art     : Explicit concurrent mark sweep GC freed 13735(960KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 818us total 49.768ms
,08-25 15:25:28.981   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-25 15:25:28.983  4228  4228 I art     : System.exit called, status: 0
,08-25 15:25:28.983  4228  4228 I AndroidRuntime: VM exiting with result code 0.
,08-25 15:25:28.987   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-25 15:25:29.004   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-25 15:25:29.016  4148  4148 D BluetoothMapAppObserver: onReceive
,08-25 15:25:29.016  4148  4148 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-25 15:25:29.018  1895  1895 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-25 15:25:29.019  2181  2235 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 15:25:29.022   874  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 15:25:29.027  3629  3629 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-25 15:25:29.031  1895  4240 I Keyboard.Facilitator.DecoderInitializer: run()
,08-25 15:25:29.033  1895  4240 I Decoder : createOrResetDecoder
,08-25 15:25:29.056  1953  1953 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-25 15:25:29.063   874  1958 I ActivityManager: Start proc 4242:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-25 15:25:29.075  1585  1585 I ConfigService: onCreate
,08-25 15:25:29.100  1895  4240 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-25 15:25:29.108   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 15:25:29.118  4242  4242 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-25 15:25:29.120  1969  2049 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-25 15:25:29.123   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-25 15:25:29.124   874   886 E PackageManager: Failed to write settings, restoring backup
08-25 15:25:29.124   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-25 15:25:29.124   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-25 15:25:29.124   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-25 15:25:29.124   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-25 15:25:29.124   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-25 15:25:29.124   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:29.124   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:29.124   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 15:25:29.131   874  1982 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3787 uid 10000
,08-25 15:25:29.133  1895  1895 I Keyboard.Facilitator: onFinishInput()
,08-25 15:25:29.134   874  1959 I ActivityManager: Start proc 4256:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-25 15:25:29.134  1969  2049 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-25 15:25:29.134  1969  2049 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1969
08-25 15:25:29.134  1969  2049 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 15:25:29.134  1969  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 15:25:29.134  1969  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 15:25:29.134  1969  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 15:25:29.134  1969  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 15:25:29.134  1969  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 15:25:29.134  1969  2049 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-25 15:25:29.134  1969  2049 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-25 15:25:29.134  1969  2049 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 15:25:29.134  1969  2049 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 15:25:29.134  1969  2049 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:29.134  1969  2049 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 15:25:29.135   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-25 15:25:29.135   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 15:25:29.135   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.,java:186)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 15:25:29.135   874   887 E DropBoxManagerService: 	... 13 more
,08-25 15:25:29.135  1895  4240 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-25 15:25:29.137   874  2047 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 15:25:29.137   874  4262 E DropBoxManagerService: Can't write: system_app_crash
08-25 15:25:29.137   874  4262 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-25 15:25:29.137   874  4262 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 15:25:29.137   874  4262 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 15:25:29.137   874  4262 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 15:25:29.137   874  4262 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 15:25:29.137   874  4262 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 15:25:29.137   874  4262 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 15:25:29.137   874  4262 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 15:25:29.137   874  4262 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 15:25:29.137   874  4262 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 15:25:29.137   874  4262 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 15:25:29.137   874  4262 E DropBoxManagerService: 	... 5 more
08-25 15:25:29.138  1895  4240 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-25 15:25:29.139  1895  4240 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-25 15:25:29.140  1969  2049 I Process : Sending signal. PID: 1969 SIG: 9
,08-25 15:25:29.148  1895  4240 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-25 15:25:29.148  1895  4240 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-25 15:25:29.148  1895  4240 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-25 15:25:29.148  1895  4240 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-25 15:25:29.157  1895  4240 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-25 15:25:29.157  1895  4240 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-25 15:25:29.158  1895  4240 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-25 15:25:29.158  1895  4240 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-25 15:25:29.158  1895  4240 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-25 15:25:29.158  1895  4240 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-25 15:25:29.187  4242  4242 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-25 15:25:29.190   874  1959 D GraphicsStats: Buffer count: 1
,08-25 15:25:29.190   874  3112 I WindowState: WIN DEATH: Window{b64da9e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-25 15:25:29.195   874   885 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1969) has died
08-25 15:25:29.196   874   885 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-25 15:25:29.197   874   885 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-25 15:25:29.204  4242  4270 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:29.204  4242  4270 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:29.205  4242  4270 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 15:25:29.212   874   887 I ActivityManager: Start proc 4272:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 15:25:29.229   874  1382 I ActivityManager: Start proc 4286:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-25 15:25:29.259  4242  4283 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-25 15:25:29.267  4272  4272 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 15:25:29.267  4272  4272 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 15:25:29.267  4272  4272 D AndroidRuntime: Shutting down VM
,08-25 15:25:29.273  4272  4272 E AndroidRuntime: FATAL EXCEPTION: main
08-25 15:25:29.273  4272  4272 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4272
08-25 15:25:29.273  4272  4272 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 15:25:29.273  4272  4272 E AndroidRuntime: 	... 10 more
,08-25 15:25:29.275   874  1403 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 15:25:29.276   874  4299 E DropBoxManagerService: Can't write: system_app_crash
08-25 15:25:29.276   874  4299 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-25 15:25:29.276   874  4299 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 15:25:29.276   874  4299 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 15:25:29.276   874  4299 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 15:25:29.276   874  4299 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 15:25:29.276   874  4299 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 15:25:29.276   874  4299 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 15:25:29.276   874  4299 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 15:25:29.276   874  4299 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 15:25:29.276   874  4299 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 15:25:29.276   874  4299 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 15:25:29.276   874  4299 E DropBoxManagerService: 	... 5 more
08-25 15:25:29.276  4272  4272 I Process : Sending signal. PID: 4272 SIG: 9
,08-25 15:25:29.296  4286  4286 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-25 15:25:29.310  1585  1585 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-25 15:25:29.311  1585  1585 D AndroidRuntime: Shutting down VM
,08-25 15:25:29.312  1585  1585 E AndroidRuntime: FATAL EXCEPTION: main
08-25 15:25:29.312  1585  1585 E AndroidRuntime: Process: com.google.process.gapps, PID: 1585
08-25 15:25:29.312  1585  1585 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-25 15:25:29.312  1585  1585 E AndroidRuntime: 	... 8 more
,08-25 15:25:29.315  1585  1585 I Process : Sending signal. PID: 1585 SIG: 9
,08-25 15:25:29.317   874  4303 E DropBoxManagerService: Can't write: system_app_crash
08-25 15:25:29.317   874  4303 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-25 15:25:29.317   874  4303 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 15:25:29.317   874  4303 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 15:25:29.317   874  4303 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 15:25:29.317   874  4303 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 15:25:29.317   874  4303 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 15:25:29.317   874  4303 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 15:25:29.317   874  4303 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 15:25:29.317   874  4303 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 15:25:29.317   874  4303 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 15:25:29.317   874  4303 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 15:25:29.317   874  4303 E DropBoxManagerService: 	... 5 more
,08-25 15:25:29.318  1745  4300 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-25 15:25:29.319  1745  4300 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-25 15:25:29.323   874  1959 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4272) has died
,08-25 15:25:29.325   874  1959 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-25 15:25:29.338   874   887 I ActivityManager: Start proc 4305:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 15:25:29.341   874  3112 I ActivityManager: Killing 3688:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-25 15:25:29.348  1745  4300 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-25 15:25:29.348  1745  4300 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-25 15:25:29.360  4242  4270 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-25 15:25:29.365   874  1315 D WifiService: Client connection lost with reason: 4
,08-25 15:25:29.373  4242  4283 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:29.373  4242  4283 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 15:25:29.374  4242  4283 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-25 15:25:29.374  4242  4283 E AndroidRuntime: Process: android.process.acore, PID: 4242
08-25 15:25:29.374  4242  4283 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:29.374  4242  4283 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 15:25:29.374  4242  4270 I Process : Sending signal. PID: 4242 SIG: 9
,08-25 15:25:29.410   874  1403 I ActivityManager: Process android.process.acore (pid 4242) has died
08-25 15:25:29.410   874  1403 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-25 15:25:29.412   874  2046 W ActivityManager: Can't find mystery application for Crash from pid=4242 uid=10005: android.os.BinderProxy@de574f1
,08-25 15:25:29.413   874  2046 E DropBoxManagerService: Can't write: system_server_crash
08-25 15:25:29.413   874  2046 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop90.tmp: open failed: EROFS (Read-only file system)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12127)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 15:25:29.413   874  2046 E DropBoxManagerService: 	... 11 more
,08-25 15:25:29.413   874  1959 I ActivityManager: Process com.google.process.gapps (pid 1585) has died
,08-25 15:25:29.414   874  1959 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,08-25 15:25:29.414   874  1959 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 10999ms
08-25 15:25:29.414   874  1959 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
,08-25 15:25:29.414   874  1959 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
08-25 15:25:29.424  1745  1745 W RocketImpressions: ClearcutLogger connection suspended: 1
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 15:25:29.438  4305  4305 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 15:25:29.439 , 4305  4305 D AndroidRuntime: Shutting down VM
08-25 15:25:29.444   874  2047 I ActivityManager: Start proc 4317:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-25 15:25:29.457  4305  4305 E AndroidRuntime: FATAL EXCEPTION: main
08-25 15:25:29.457  4305  4305 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4305
08-25 15:25:29.457  4305  4305 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 15:25:29.457  4305  4305 E AndroidRuntime: 	... 10 more
,08-25 15:25:29.459   874   884 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 15:25:29.460  4305  4305 I Process : Sending signal. PID: 4305 SIG: 9
08-25 15:25:29.462   874  4330 E DropBoxManagerService: Can't write: system_app_crash
08-25 15:25:29.462   874  4330 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-25 15:25:29.462   874  4330 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 15:25:29.462   874  4330 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 15:25:29.462   874  4330 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 15:25:29.462   874  4330 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 15:25:29.462   874  4330 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 15:25:29.462   874  4330 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 15:25:29.462   874  4330 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 15:25:29.462   874  4330 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 15:25:29.462   874  4330 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 15:25:29.462   874  4330 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 15:25:29.462   874  4330 E DropBoxManagerService: 	... 5 more
08-25 15:25:29.468  1745  1745 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-25 15:25:29.468  1745  1745 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded

```
