#### Test 82894682da71698_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-13 00:05:27.437  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 00:05:27.447  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 00:05:27.450  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 00:05:27.492  1509  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-13 00:05:27.492  1509  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 00:05:27.492  1509  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 00:05:27.492  1509  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-13 00:05:27.510  3537  3537 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-13 00:05:27.511  3537  3537 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 00:05:27.511  3537  3537 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-13 00:05:29.306  3818  3818 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 00:05:29.311  3818  3818 D AndroidRuntime: CheckJNI is OFF
09-13 00:05:29.357  3818  3818 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 00:05:29.412  3818  3818 I Radio-JNI: register_android_hardware_Radio DONE
09-13 00:05:29.435  3818  3818 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-13 00:05:29.440   874  2000 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 00:05:29.481  2053  3170 W SearchService: Abort, client detached.
09-13 00:05:29.488  3818  3818 D AndroidRuntime: Shutting down VM
09-13 00:05:29.489  2053  2053 I HotwordDetector: Closing mic
09-13 00:05:29.490  2053  2344 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a353ab8
09-13 00:05:29.490  2053  2349 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-13 00:05:29.505   874  1983 I ActivityManager: Start proc 3827:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 00:05:29.541   377  2351 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 00:05:29.542   377  2351 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-13 00:05:29.546   377  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 00:05:29.548  2053  2348 I MicroRecognitionRnrImpl: Detection finished
09-13 00:05:29.548  2053  2347 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-13 00:05:29.593  3827  3827 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 00:05:29.617  3827  3827 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 00:05:29.626  3827  3827 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6463-6467)
09-13 00:05:29.626  3827  3827 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 00:05:29.644  3827  3827 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e9934a5}
09-13 00:05:29.644  3827  3827 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 00:05:29.645  3827  3827 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 00:05:29.652  3827  3827 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 00:05:29.654  3827  3827 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 00:05:29.697  3827  3827 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 00:05:29.713  3827  3827 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 00:05:29.713  3827  3827 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 00:05:29.713  3827  3827 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 00:05:29.713  3827  3827 I Adreno  : Build Date                       : 10/20/15
09-13 00:05:29.713  3827  3827 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 00:05:29.713  3827  3827 I Adreno  : Local Branch                     : M14
09-13 00:05:29.713  3827  3827 I Adreno  : Remote Branch                    : 
09-13 00:05:29.713  3827  3827 I Adreno  : Remote Branch                    : 
09-13 00:05:29.713  3827  3827 I Adreno  : Reconstruct Branch               : 
,09-13 00:05:29.768   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@745152b:true
,09-13 00:05:29.810  3827  3827 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 00:05:29.823  3827  3827 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-13 00:05:29.880  3827  3865 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 00:05:29.888  3827  3852 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-13 00:05:29.913  3827  3865 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 00:05:29.972   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +484ms
,09-13 00:05:29.973  1883  1883 I Keyboard.Facilitator: onFinishInput()
,09-13 00:05:30.034  3827  3827 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3827
,09-13 00:05:30.130  3827  3827 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 00:05:30.307   874  2028 I ActivityManager: Killing 2978:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-13 00:05:30.315  3827  3868 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1681983184
,09-13 00:05:30.319  3827  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 00:05:30.319  3827  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 00:05:30.319  3827  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 00:05:30.319  3827  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 00:05:30.319  3827  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 00:05:30.319  3827  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80db160 added. We now have 1 listener(s)
09-13 00:05:30.322  3827  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-13 00:05:30.324  3827  3868 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 00:05:30.325  3827  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 00:05:30.325  3827  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-13 00:05:30.330  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d510bf added. We now have 1 listener(s)
09-13 00:05:30.330  3827  3868 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:05:30.334   874  1308 D WifiService: New client listening to asynchronous messages
09-13 00:05:30.334  3827  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 00:05:30.334  3827  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 00:05:30.335  3827  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 00:05:30.335  3827  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 00:05:30.335  3827  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 00:05:30.354   874  2028 I ActivityManager: Killing 3232:com.google.android.gm/u0a78 (adj 15): empty #18
,09-13 00:05:30.435  3827  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:05:30.435  3827  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-13 00:05:30.440  3827  3868 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 00:05:30.441  3827  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:05:30.441  3827  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:30.441  3827  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:30.441  3827  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:30.441  3827  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:30.441  3827  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:30.441  3827  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:30.441  3827  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:30.441  3827  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 00:05:30.441  3827  3868 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-13 00:05:30.442  3827  3868 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 00:05:30.516  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:30.526  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:30.528  3827  3827 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 00:05:31.477  3827  3877 W jxcore-log: Initializing JXcore engine
,09-13 00:05:31.477  3827  3877 W jxcore-log: JXcore engine is ready
,09-13 00:05:31.516  3877  3877 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8951 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-13 00:05:31.516  3877  3877 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11852]" dev="sockfs" ino=11852 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-13 00:05:31.516  3877  3877 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 00:05:31.516  3877  3877 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26893]" dev="sockfs" ino=26893 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-13 00:05:31.532  3827  3877 W jxcore-log: Starting JXcore engine
,09-13 00:05:31.646  3827  3877 W jxcore-log: Platform android
09-13 00:05:31.646  3827  3877 W jxcore-log: 
09-13 00:05:31.646  3827  3877 W jxcore-log: Process ARCH arm
09-13 00:05:31.646  3827  3877 W jxcore-log: 
,09-13 00:05:31.914  3827  3877 I jxcore-log: JXcore Cordova bridge is ready!
09-13 00:05:31.914  3827  3877 I jxcore-log: 
,09-13 00:05:31.915  3827  3877 W jxcore-log: JXcore engine is started
,09-13 00:05:31.929  3827  3868 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 00:05:31.934  3827  3827 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 00:05:33.315   874  1854 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 00:05:35.403   874  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 00:05:39.626  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 00:05:39.627  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 00:05:39.644  1509  2078 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 00:05:39.644  1509  2078 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 00:05:39.644  1509  2078 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 00:05:39.644  1509  2078 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 00:05:39.655  3574  3886 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 00:05:39.655  3574  3886 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at jdm.a(PG:82)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at jcs.o(PG:406)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at jcn.a(PG:1379)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at jcs.i(PG:143)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at blb.a(PG:3937)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at czp.a(PG:18188)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at czp.a(PG:9081)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at czq.run(PG:1686)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 00:05:39.655  3574  3886 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at jdj.a(PG:4091)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at jdj.a(PG:1125)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at jdm.a(PG:77)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	... 12 more
09-13 00:05:39.655  3574  3886 E HttpOperation: Caused by: faj: BadAuthentication
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at fal.a(PG:38)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	at jdj.a(PG:4089)
09-13 00:05:39.655  3574  3886 E HttpOperation: 	... 14 more
,09-13 00:05:39.680  1509  2975 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 00:05:39.680  1509  2975 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 00:05:39.680  1509  2975 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 00:05:39.680  1509  2975 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 00:05:39.694  3574  3886 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 00:05:39.694  3574  3886 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at jdm.a(PG:82)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at jcs.o(PG:406)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at jcn.a(PG:1379)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at jcs.i(PG:143)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at hec.a(PG:42)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at hee.a(PG:102)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at czr.a(PG:65)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at kka.a(PG:108)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at czp.a(PG:19176)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at czp.a(PG:9081)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at czq.run(PG:1686)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 00:05:39.694  3574  3886 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at jdj.a(PG:4091)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at jdj.a(PG:1125)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at jdm.a(PG:77)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	... 15 more
09-13 00:05:39.694  3574  3886 E HttpOperation: Caused by: faj: BadAuthentication
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at fal.a(PG:38)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	at jdj.a(PG:4089)
09-13 00:05:39.694  3574  3886 E HttpOperation: 	... 17 more
,09-13 00:05:39.694  3574  3886 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 00:05:39.694  3574  3886 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at hec.a(PG:42)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at hee.a(PG:102)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at czr.a(PG:65)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at kka.a(PG:108)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	... 15 more
09-13 00:05:39.694  3574  3886 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at fal.a(PG:38)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 00:05:39.694  3574  3886 E ExperimentLoader: 	... 17 more
,09-13 00:05:39.773   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 126092, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-13 00:05:41.964  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 00:05:41.964  3827  3877 I jxcore-log: 
,09-13 00:05:41.966  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 00:05:41.966  3827  3877 I jxcore-log: 
,09-13 00:05:41.973  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:05:41.973  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:41.973  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:41.973  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:41.973  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:41.973  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:41.973  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:41.973  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:41.976  3827  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 00:05:41.978  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 00:05:41.978  3827  3877 I jxcore-log: 
,09-13 00:05:41.980  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 00:05:41.980  3827  3877 I jxcore-log: 
,09-13 00:05:42.482  3827  3877 D executeNativeTests: Running unit tests
,09-13 00:05:42.540  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:05:42.540  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 added. We now have 2 listener(s)
,09-13 00:05:42.541  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 00:05:42.541  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:05:42.541  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 00:05:42.541  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:05:42.541  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e added. We now have 2 listener(s)
,09-13 00:05:42.541  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:05:42.543  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 00:05:42.545  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:05:42.560  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:05:42.560  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:42.560  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:42.560  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:42.560  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:42.560  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:42.560  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:42.560  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:42.563  3827  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:42.563  3827  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 00:05:42.565  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 00:05:42.567  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 00:05:42.567  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 00:05:42.568  3827  3877 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 00:05:42.569  3827  3877 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-13 00:05:42.569  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 00:05:42.569  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 00:05:42.569  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 00:05:42.569  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.570  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.570  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:42.570  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.570  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.570  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:05:42.570  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:05:42.570  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 removed from the list
09-13 00:05:42.570  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.570  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e removed from the list
09-13 00:05:42.571  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:42.571  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.571  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.571  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.571  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.578  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.578  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:42.578  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.578  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.580  3827  3877 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 00:05:42.580  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.581  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.581  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:42.581  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.581  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: ,release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.581  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.581  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.581  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.581  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.584  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:42.585  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.585  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.585  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.585  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.585  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.587  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.587  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:42.587  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.587  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 00:05:42.592  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 00:05:42.593  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 00:05:42.593  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 00:05:42.593  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 00:05:42.593  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 00:05:42.593  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 00:05:42.593  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 00:05:42.593  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 00:05:42.593  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 00:05:42.593  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 00:05:42.593  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 00:05:42.593  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 00:05:42.593  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 00:05:42.593  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 00:05:42.593  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 00:05:42.593  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.593  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.593  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:42.593  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.593  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.594  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.594  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.594  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.594  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.594  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.594  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.594  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.594  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.594  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.595  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.595  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:42.595  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.595  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.595  3827  3877 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 00:05:42.597  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:05:42.601  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:05:42.601  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:42.601  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:42.601  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:42.601  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:42.601  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:42.601  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:42.601  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:05:42.604  3827  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:42.604  3827  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:05:42.605  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:05:42.605  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:05:42.605  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 00:05:42.605  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:05:42.605  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 00:05:42.619  3827  3877 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 00:05:42.619  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 00:05:42.621  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:42.623  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 00:05:42.624  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:42.625  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 00:05:42.625  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 00:05:42.628  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-13 00:05:42.630  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 00:05:42.630  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 00:05:42.630  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 00:05:42.631  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 00:05:42.632  3827  3877 D BluetoothAdapter: STATE_ON
09-13 00:05:42.635  2696  2707 D BtGatt.GattService: registerClient() - UUID=0421ae0e-45eb-4644-ae8d-a7ba9276dd8c
09-13 00:05:42.636  2696  2717 D BtGatt.GattService: onClientRegistered() - UUID=0421ae0e-45eb-4644-ae8d-a7ba9276dd8c, clientIf=5
09-13 00:05:42.637  3827  3839 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 00:05:42.638  2696  2865 D BtGatt.GattService: start scan with filters
09-13 00:05:42.641  2696  2721 D BtGatt.ScanManager: handling starting scan
09-13 00:05:42.641  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 00:05:42.642  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 00:05:42.642  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 00:05:42.642  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 00:05:42.643  2696  2721 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
09-13 00:05:42.644  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 00:05:42.645  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 00:05:42.645  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 00:05:42.647  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-13 00:05:42.650  2696  2717 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 00:05:42.651  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:05:42.651  2696  2721 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 00:05:42.651  3827  3877 I io.jxcore.node.ConnectionHelper: start: OK
09-13 00:05:42.654  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.654  3827  3877 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 00:05:42.654  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.654  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 00:05:42.654  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.655  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 00:05:42.655  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 00:05:42.655  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 00:05:42.655  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 00:05:42.655  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 00:05:42.656  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 00:05:42.656  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 00:05:42.656  2696  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 00:05:42.657  3827  3877 D BluetoothAdapter: STATE_ON
09-13 00:05:42.657  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:05:42.657  2696  2721 D BtGatt.ScanManager: Starting BLE batch scan
09-13 00:05:42.657  2696  2721 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 00:05:42.657  2696  2708 D BtGatt.GattService: stopScan() - queue size =1
09-13 00:05:42.658  2696  2707 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 00:05:42.658  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 00:05:42.659  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 00:05:42.659  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 00:05:42.659  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-13 00:05:42.659  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 00:05:42.660  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:05:42.660  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 00:05:42.660  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 00:05:42.661  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 00:05:42.661  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:05:42.664  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:05:42.664  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:05:42.664  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 00:05:42.665  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:05:42.666  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.666  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:05:42.666  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.666  2696  2717 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 00:05:42.667  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 00:05:42.666  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.667  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.667  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.667  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.669  3827  3877 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 00:05:42.672  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:05:42.673  2696  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 00:05:42.673  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 00:05:42.675  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:05:42.675  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:42.675  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:42.675  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:42.675  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:42.675  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:42.675  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:42.675  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:42.676  3827  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 00:05:42.677  3827  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:05:42.677  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:05:42.677  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 00:05:42.677  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 00:05:42.677  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:05:42.677  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 00:05:42.680  3827  3877 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 00:05:42.680  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 00:05:42.681  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:42.682  2696  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 00:05:42.682  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:05:42.682  2696  2721 D BtGatt.ScanManager: stopping BLe Batch
,09-13 00:05:42.684  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:42.684  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 00:05:42.684  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 00:05:42.685  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 00:05:42.688  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 00:05:42.688  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 00:05:42.688  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 00:05:42.688  2696  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 00:05:42.688  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 00:05:42.688  3827  3877 D BluetoothAdapter: STATE_ON
09-13 00:05:42.688  2696  2721 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 00:05:42.690  2696  2708 D BtGatt.GattService: registerClient() - UUID=de88922d-6303-431c-8feb-942abd39ab0c
09-13 00:05:42.690  2696  2717 D BtGatt.GattService: onClientRegistered() - UUID=de88922d-6303-431c-8feb-942abd39ab0c, clientIf=5
,09-13 00:05:42.691  3827  3838 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 00:05:42.691  2696  2707 D BtGatt.GattService: start scan with filters
,09-13 00:05:42.694  2696  2717 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 00:05:42.694  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:05:42.694  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 00:05:42.694  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 00:05:42.694  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 00:05:42.695  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 00:05:42.696  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 00:05:42.696  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 00:05:42.696  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 00:05:42.696  2696  2721 D BtGatt.ScanManager: handling starting scan
,09-13 00:05:42.697  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 00:05:42.699  3827  3877 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 00:05:42.701  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.701  3827  3877 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 00:05:42.701  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 00:05:42.701  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 00:05:42.701  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.701  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 00:05:42.701  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 00:05:42.701  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 00:05:42.701  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 00:05:42.701  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 00:05:42.701  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 00:05:42.701  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 00:05:42.702  3827  3877 D BluetoothAdapter: STATE_ON
09-13 00:05:42.702  2696  2865 D BtGatt.GattService: stopScan() - queue size =1
09-13 00:05:42.702  2696  2717 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 00:05:42.703  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 00:05:42.703  2696  2708 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 00:05:42.703  2696  2721 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 00:05:42.703  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:05:42.703  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 00:05:42.703  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 00:05:42.703  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 00:05:42.703  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 00:05:42.704  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 00:05:42.704  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 00:05:42.704  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 00:05:42.704  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 00:05:42.705  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:05:42.705  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 00:05:42.706  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:05:42.706  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 00:05:42.706  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.706  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.706  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:05:42.706  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.706  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 00:05:42.706  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
,09-13 00:05:42.706  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.706  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.706  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.706  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.707  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.707  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:42.707  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.707  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
,09-13 00:05:42.707  3827  3877 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 00:05:42.708  2696  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 00:05:42.708  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:05:42.708  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:05:42.709  2696  2721 D BtGatt.ScanManager: Starting BLE batch scan
09-13 00:05:42.709  2696  2721 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 00:05:42.711  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:05:42.711  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:42.711  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:42.711  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:42.711  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:42.711  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:42.711  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:42.711  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:42.712  3827  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:42.713  3827  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:05:42.714  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:05:42.714  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:42.714  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:05:42.714  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 00:05:42.715  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:05:42.715  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 00:05:42.716  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:42.719  3827  3877 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 00:05:42.719  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 00:05:42.719  2696  2717 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 00:05:42.720  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:05:42.721  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 00:05:42.722  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 00:05:42.722  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 00:05:42.725  2696  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 00:05:42.725  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 00:05:42.727  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 00:05:42.727  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 00:05:42.727  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 00:05:42.728  3827  3877 D BluetoothAdapter: STATE_ON
,09-13 00:05:42.732  2696  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 00:05:42.732  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 00:05:42.732  2696  2721 D BtGatt.ScanManager: stopping BLe Batch
09-13 00:05:42.732  2696  2708 D BtGatt.GattService: registerClient() - UUID=be8b3f8e-861c-4e12-8b5a-1ed1b27ec053
,09-13 00:05:42.733  2696  2717 D BtGatt.GattService: onClientRegistered() - UUID=be8b3f8e-861c-4e12-8b5a-1ed1b27ec053, clientIf=5
09-13 00:05:42.733  3827  3838 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 00:05:42.733  2696  2707 D BtGatt.GattService: start scan with filters
,09-13 00:05:42.735  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 00:05:42.736  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 00:05:42.736  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 00:05:42.736  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 00:05:42.737  2696  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 00:05:42.737  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:05:42.737  2696  2721 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 00:05:42.739  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 00:05:42.739  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 00:05:42.740  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 00:05:42.742  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 00:05:42.743  2696  2717 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 00:05:42.743  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:05:42.744  2696  2721 D BtGatt.ScanManager: handling starting scan
,09-13 00:05:42.745  3827  3877 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 00:05:42.745  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.745  3827  3877 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 00:05:42.745  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.745  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 00:05:42.746  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.746  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 00:05:42.746  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 00:05:42.746  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 00:05:42.746  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 00:05:42.746  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 00:05:42.746  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 00:05:42.746  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 00:05:42.747  3827  3877 D BluetoothAdapter: STATE_ON
,09-13 00:05:42.748  2696  2708 D BtGatt.GattService: stopScan() - queue size =1
09-13 00:05:42.749  2696  2707 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 00:05:42.749  2696  2717 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 00:05:42.749  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:05:42.749  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:05:42.749  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 00:05:42.750  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 00:05:42.750  2696  2721 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 00:05:42.750  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 00:05:42.750  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 00:05:42.751  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:05:42.751  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 00:05:42.751  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 00:05:42.751  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 00:05:42.751  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:05:42.752  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:05:42.752  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:05:42.752  3827  3877 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 00:05:42.752  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.752  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:42.753  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.753  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 00:05:42.753  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.753  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:05:42.753  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.753  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 00:05:42.753  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.753  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.753  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.753  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.753  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.753  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.754  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.754  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:42.754  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.754  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.754  3827  3877 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 00:05:42.755  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:05:42.755  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.755  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:42.755  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.755  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.755  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.755  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.755  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.755  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.755  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.755  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.755  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.755  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.755  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.756  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.756  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:42.756  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.756  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.757  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 00:05:42.757  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:05:42.757  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.757  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:42.757  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.757  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.757  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.757  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
,09-13 00:05:42.757  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.757  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
,09-13 00:05:42.757  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.757  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.757  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.757  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.757  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.758  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.758  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:42.758  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.758  2696  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 00:05:42.758  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.758  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:05:42.759  2696  2721 D BtGatt.ScanManager: Starting BLE batch scan
09-13 00:05:42.759  3827  3877 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-13 00:05:42.759  2696  2721 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 00:05:42.759  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:05:42.759  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.761  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 00:05:42.761  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:05:42.761  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.761  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.761  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list,
09-13 00:05:42.761  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.761  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
,09-13 00:05:42.761  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.761  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 00:05:42.761  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.761  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.761  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.762  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 00:05:42.762  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:05:42.762  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.762  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.762  3827  3877 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 00:05:42.762  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.762  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.762  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 00:05:42.763  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.763  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.763  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.763  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.763  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.763  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
,09-13 00:05:42.763  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.763  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.763  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.763  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.763  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.763  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.764  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:05:42.764  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.764  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.764  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 00:05:42.764  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 00:05:42.764  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 00:05:42.764  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 00:05:42.764  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 00:05:42.764  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 00:05:42.764  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.765  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.765  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 00:05:42.765  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.765  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.765  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.765  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.765  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.765  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
,09-13 00:05:42.765  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.765  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.765  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.765  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.765  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.766  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.766  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:42.766  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.766  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.767  3827  3877 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 00:05:42.767  3827  3877 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 00:05:42.767  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 00:05:42.769  3827  3877 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 00:05:42.769  3827  3877 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
,09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-13 00:05:42.770  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 00:05:42.771  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 00:05:42.771  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-13 00:05:42.771  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 00:05:42.771  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 00:05:42.771  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-13 00:05:42.771  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-13 00:05:42.771  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 00:05:42.771  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-13 00:05:42.771  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-13 00:05:42.771  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-13 00:05:42.771  3827  3877 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 00:05:42.771  3827  3877 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 00:05:42.771  3827  3877 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 00:05:42.771  3827  3877 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 00:05:42.772  3827  3877 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-13 00:05:42.772  3827  3877 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 00:05:42.772  3827  3877 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 00:05:42.772  3827  3877 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 00:05:42.772  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-13 00:05:42.775  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-13 00:05:42.775  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 00:05:42.775  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 00:05:42.776  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-13 00:05:42.776  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 00:05:42.776  3827  3877 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 00:05:42.776  3827  3877 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 00:05:42.776  3827  3877 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 00:05:42.777  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.777  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 00:05:42.777  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:42.777  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.777  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.777  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.777  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 00:05:42.778  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
,09-13 00:05:42.778  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.778  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.778  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.778  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 00:05:42.778  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.778  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.778  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.779  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.779  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:05:42.779  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.779  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.780  3827  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
09-13 00:05:42.781  3827  3877 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-13 00:05:42.781  3827  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
,09-13 00:05:42.781  3827  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
09-13 00:05:42.781  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.781  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.781  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 00:05:42.781  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.781  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.781  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.781  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
,09-13 00:05:42.781  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 00:05:42.782  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.782  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 00:05:42.782  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.782  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.782  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.782  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.782  2696  2717 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 00:05:42.782  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:05:42.782  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.782  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:42.782  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.782  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.783  3827  3877 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 00:05:42.783  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.783  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.783  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:42.783  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.783  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.783  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.783  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.783  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.784  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.784  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.784  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.784  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.784  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.784  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.784  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.784  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:42.784  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.784  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.785  3827  3877 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 00:05:42.785  3827  3877 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 00:05:42.785  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnection,Thread: 1 outgoing connection(s) left
09-13 00:05:42.785  3827  3877 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 00:05:42.785  3827  3877 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 00:05:42.785  3827  3877 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 00:05:42.785  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 00:05:42.785  3827  3877 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 00:05:42.785  3827  3877 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 00:05:42.785  3827  3877 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 00:05:42.786  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 00:05:42.786  3827  3877 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 00:05:42.786  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.786  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.786  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:42.786  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.786  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.786  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.786  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.786  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.786  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.786  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.786  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.786  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.786  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.786  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.787  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.787  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:42.787  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.787  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.787  2696  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 00:05:42.787  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:05:42.787  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.787  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.787  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.787  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
,09-13 00:05:42.787  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.788  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.788  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.788  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.788  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.788  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.788  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.788  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.788  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.788  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.788  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
,09-13 00:05:42.788  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.788  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.788  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:42.788  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.788  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.788  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.788  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.789  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.789  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.789  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.789  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.789  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.789  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.789  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.789  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.789  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:05:42.789  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.790  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.790  3827  3877 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 00:05:42.791  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:05:42.791  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 00:05:42.792  3827  3877 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 00:05:42.792  3827  3877 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 00:05:42.792  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 00:05:42.792  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 00:05:42.792  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 00:05:42.792  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.792  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 00:05:42.792  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 00:05:42.792  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 00:05:42.792  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.792  3827  3877 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 00:05:42.793  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 00:05:42.793  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.793  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.793  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 00:05:42.793  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 00:05:42.793  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 00:05:42.793  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.793  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.794  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:05:42.794  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:05:42.794  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:05:42.794  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:05:42.794  2696  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 00:05:42.794  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:05:42.794  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.794  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:05:42.794  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 00:05:42.794  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-13 00:05:42.794  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.794  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.794  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.794  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.794  2696  2721 D BtGatt.ScanManager: stopping BLe Batch
09-13 00:05:42.795  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.795  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.795  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.795  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.795  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-13 00:05:42.795  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 00:05:42.795  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.795  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.795  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:05:42.795  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-13 00:05:42.795  3827  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 00:05:42.796  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list,
09-13 00:05:42.796  3827  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 00:05:42.796  3827  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 00:05:42.797  3827  3877 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 00:05:42.797  3827  3877 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-13 00:05:42.797  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 00:05:42.797  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 00:05:42.797  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.797  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.797  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:42.797  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:05:42.797  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 00:05:42.797  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.798  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.798  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.798  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list,
09-13 00:05:42.798  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.798  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.798  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.798  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.798  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.798  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.799  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:42.799  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.799  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.800  2696  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 00:05:42.801  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:05:42.801  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.801  2696  2721 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 00:05:42.801  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.801  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:42.802  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.802  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.802  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.802  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.802  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 00:05:42.802  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.802  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:42.802  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:42.802  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.802  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.802  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.803  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 00:05:42.803  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:42.803  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.803  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
,09-13 00:05:42.804  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:42.804  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:42.804  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:42.804  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:42.804  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.804  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:42.804  3827  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbb94a9 not in the list
09-13 00:05:42.804  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.804  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
,09-13 00:05:42.804  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop,
09-13 00:05:42.804  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.804  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.804  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:42.804  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:42.805  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:42.805  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-13 00:05:42.805  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:42.805  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dffa2e not in the list
09-13 00:05:42.806  3827  3877 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 00:05:42.806  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left,
09-13 00:05:42.806  3827  3877 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 00:05:42.806  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 00:05:42.806  3827  3877 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 00:05:42.806  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 00:05:42.806  2696  2717 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 00:05:42.807  2696  2717 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 00:05:42.808  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 00:05:42.808  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 00:05:42.808  3827  3877 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 00:05:42.808  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-13 00:05:42.808  3827  3877 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 00:05:42.808  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-13 00:05:42.808  3827  3877 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2,
09-13 00:05:42.808  3827  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 00:05:42.809  3827  3877 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-13 00:05:42.809  3827  3877 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 00:05:42.809  3827  3877 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id,
09-13 00:05:42.809  3827  3877 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 00:05:42.809  3827  3877 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 00:05:42.809  3827  3877 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 00:05:42.810  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:05:42.810  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a394560 added. We now have 2 listener(s)
09-13 00:05:42.810  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:05:42.811  3827  3877 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 00:05:42.811   874  1698 D WifiService: setWifiEnabled: true pid=3827, uid=10000
,09-13 00:05:42.811   874  1698 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 00:05:42.812  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:05:42.812  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5c5fa19 added. We now have 3 listener(s)
09-13 00:05:42.812  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:05:42.817  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:05:42.817  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fd54ade added. We now have 4 listener(s)
09-13 00:05:42.817  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:05:42.818  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,09-13 00:05:42.818  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@54b4bf added. We now have 5 listener(s)
,09-13 00:05:42.818  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:05:42.820   874  1983 D WifiService: setWifiEnabled: false pid=3827, uid=10000
09-13 00:05:42.820   874  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 00:05:42.824  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:05:42.824  2696  2712 D BluetoothAdapterState: Current state: ON, message: 23
09-13 00:05:42.824  2696  2712 D BluetoothAdapterProperties: Setting state to 13
09-13 00:05:42.824  2696  2712 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 00:05:42.825  2696  2712 D BluetoothAdapterProperties: onBluetoothDisable(),
09-13 00:05:42.826  2696  2712 I BluetoothAdapterState: Entering PendingCommandState
09-13 00:05:42.826  2696  2696 D BluetoothMapService: onReceive
09-13 00:05:42.826  2696  2696 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:05:42.826  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:42.827  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
,09-13 00:05:42.827  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:42.827  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:42.827  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
09-13 00:05:42.827  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:42.827  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:42.827  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:42.827  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:05:42.827  2696  2696 D BluetoothMapService: STATE_TURNING_OFF
09-13 00:05:42.827  2696  2696 D BluetoothMapService: MAP Service closeService in
09-13 00:05:42.827  2696  2696 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 00:05:42.827  2696  2696 D ObexServerSockets0: shutdown(block = true)
09-13 00:05:42.827  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:42.827  3827  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 00:05:42.827  2696  2696 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 00:05:42.828  3827  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 00:05:42.828  2696  2696 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 00:05:42.828  2696  2890 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 00:05:42.828  2696  2862 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 00:05:42.828  2696  2891 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 00:05:42.829  2696  2696 I BtOppRfcommListener: stopping Accept Thread
09-13 00:05:42.829  2696  3460 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 00:05:42.829  2696  3460 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 00:05:42.830  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:42.831  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:42.833  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:42.834  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:42.834  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:42.834  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:42.834  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:42.834  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:42.834  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:42.834  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:42.834  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:05:42.834  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:42.834  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 00:05:42.836  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:42.841   874   887 I ActivityManager: Start proc 3896:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-13 00:05:42.842  2696  2717 D BluetoothAdapterProperties: Scan Mode:20
09-13 00:05:42.842  2696  2712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-13 00:05:42.844  2696  2696 D HeadsetService: Received stop request...Stopping profile...
,09-13 00:05:42.849  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:42.849  1354  2089 D BluetoothHeadset: Proxy object disconnected
,09-13 00:05:42.850  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1,
09-13 00:05:42.850   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 00:05:42.850   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 00:05:42.850   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 00:05:42.852  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:42.853   874  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 00:05:42.853   874  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-13 00:05:42.853   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 00:05:42.853   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 00:05:42.855  1970  1984 D BluetoothHeadset: Proxy object disconnected
09-13 00:05:42.856  2696  2696 D A2dpService: Received stop request...Stopping profile...
09-13 00:05:42.857  2696  2871 D A2dpStateMachine: Exit Disconnected: -1,
,09-13 00:05:42.857   874   874 D BluetoothA2dp: Proxy object disconnected
09-13 00:05:42.858   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-13 00:05:42.859   874  1858 D DhcpClient: Clearing IP address
09-13 00:05:42.859  1354  1354 D HeadsetProfile: Bluetooth service disconnected
09-13 00:05:42.860  1354  1354 D BluetoothA2dp: Proxy object disconnected
09-13 00:05:42.860  2696  2696 D HidService: Received stop request...Stopping profile...
09-13 00:05:42.860  2696  2696 D HidService: Stopping Bluetooth HidService
09-13 00:05:42.860  1354  1354 D BluetoothInputDevice: Proxy object disconnected
09-13 00:05:42.860  1354  1354 D HidProfile: Bluetooth service disconnected
09-13 00:05:42.861   373   872 D CommandListener: Setting iface cfg
09-13 00:05:42.862   874  1862 D DhcpClient: Receive thread stopped
09-13 00:05:42.862  1509  2435 V NativeCrypto: Read error: ssl=0x9abe8200: I/O error during system call, Connection timed out
,09-13 00:05:42.867  1509  2435 V NativeCrypto: SSL shutdown failed: ssl=0x9abe8200: I/O error during system call, Broken pipe
09-13 00:05:42.870   874  1698 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-13 00:05:42.870   874  1852 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-13 00:05:42.871  2696  2696 V BluetoothAdapterState: isTurningOff()=true
09-13 00:05:42.871  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-13 00:05:42.871  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:42.871  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:05:42.871  2696  2696 D HealthService: Received stop request...Stopping profile...
09-13 00:05:42.873   874  1852 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-13 00:05:42.874  2696  2696 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 00:05:42.874   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-13 00:05:42.874  2696  2696 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object,
09-13 00:05:42.874   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-13 00:05:42.874  2696  2822 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 00:05:42.874  2696  2822 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 00:05:42.874  2696  2822 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 00:05:42.874  2696  2696 D PanService: Received stop request...Stopping profile...
09-13 00:05:42.875   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 00:05:42.875  2696  2717 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-13 00:05:42.875  2696  2717 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-13 00:05:42.876  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 00:05:42.876  1354  1354 D PanProfile: Bluetooth service disconnected
,09-13 00:05:42.876  2696  2696 D BluetoothMapService: Received stop request...Stopping profile...
,09-13 00:05:42.876  2696  2696 D BluetoothMapService: stop()
09-13 00:05:42.879  2696  2696 D BluetoothMapAppObserver: deinitObservers()
09-13 00:05:42.879  2696  2696 D BluetoothMapAppObserver: removeReceiver()
09-13 00:05:42.882   874  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-13 00:05:42.883   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 00:05:42.887   405   405 E Parcel  : Reading a NULL string not supported here.
09-13 00:05:42.888   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-13 00:05:42.888   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-13 00:05:42.888   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-13 00:05:42.890  2696  2696 V BluetoothAdapterState: isTurningOff()=true
09-13 00:05:42.890  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-13 00:05:42.890  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:42.890  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:05:42.892  2696  2822 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 00:05:42.892  2696  2822 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 00:05:42.892  2696  2822 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 00:05:42.892  2696  2822 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-13 00:05:42.892  2696  2822 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 00:05:42.892  2696  2822 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 00:05:42.892  2696  2717 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-13 00:05:42.893  2696  2696 V BluetoothAdapterState: isTurningOff()=true
09-13 00:05:42.893  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-13 00:05:42.893  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 00:05:42.893  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 00:05:42.893   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 00:05:42.895  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:42.895  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:42.895  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:42.895  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:42.895  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:42.895  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:42.895  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:42.895  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:42.895  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:42.895  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:42.895  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:05:42.897   874  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-13 00:05:42.899  2696  2696 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-13 00:05:42.899  2696  2717 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 00:05:42.899  2696  2696 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-13 00:05:42.899  2696  2696 V BluetoothAdapterState: isTurningOff()=true
,09-13 00:05:42.899  2696  2696 V BluetoothAdapterState: isTurningOn()=false
,09-13 00:05:42.899  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 00:05:42.900  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:42.900  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:42.900  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:42.900  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:42.900  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:42.900  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:42.900  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:42.900  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:42.900  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:05:42.901  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:42.901  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:05:42.902  1354  1354 D BluetoothMap: Proxy object disconnected
09-13 00:05:42.902  1354  1354 D MapProfile: Bluetooth service disconnected
09-13 00:05:42.902   874  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-13 00:05:42.900  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:05:42.904  2696  2696 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-13 00:05:42.904  2696  2717 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 00:05:42.904  2696  2696 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 00:05:42.904  2696  2696 V BluetoothAdapterState: isTurningOff()=true
09-13 00:05:42.905  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-13 00:05:42.905  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:42.905  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:05:42.905  2696  2696 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 00:05:42.906  2696  2696 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 00:05:42.910  2696  2696 D BluetoothMapService: MAP Service closeService in
09-13 00:05:42.910  2696  2696 V BluetoothAdapterState: isTurningOff()=true
09-13 00:05:42.910  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-13 00:05:42.910  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:42.910  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:05:42.910  2696  2712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 00:05:42.910  2696  2712 D BluetoothAdapterProperties: Setting state to 15
09-13 00:05:42.910  2696  2712 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-13 00:05:42.910  2696  2712 I BluetoothAdapterState: Entering BleOnState
09-13 00:05:42.911  2696  2696 D BluetoothMapService: cleanup()
09-13 00:05:42.911  2696  2696 D BluetoothMapService: MAP Service closeService in
09-13 00:05:42.912  1897  2323 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 00:05:42.912  1354  1371 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:05:42.912  1354  1370 D BluetoothMap: onBluetoothStateChange: up=false
09-13 00:05:42.912  1354  2089 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 00:05:42.915   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:05:42.915  1970  1981 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 00:05:42.917  1354  1370 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 00:05:42.917   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:05:42.917   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 00:05:42.917   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:05:42.917  1354  1371 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 00:05:42.918  1354  2089 D BluetoothPan: onBluetoothStateChange on: false
09-13 00:05:42.919  2696  2712 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 00:05:42.919  2696  2712 D BluetoothAdapterProperties: Setting state to 16
09-13 00:05:42.919  2696  2712 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-13 00:05:42.920  2696  2712 D BluetoothAdapterProperties: onBleDisable
09-13 00:05:42.920  2696  2712 I BluetoothAdapterState: Entering PendingCommandState
09-13 00:05:42.921  2696  2714 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 00:05:42.921  2696  2717 D BluetoothAdapterProperties: Scan Mode:20
,09-13 00:05:42.921  2696  2822 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-13 00:05:42.921  2696  2822 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 00:05:42.925  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:42.926  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:42.926  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:42.926  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:42.926  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:42.926  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:42.926  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:42.926  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:42.926  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:05:42.928  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:42.928  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:42.928  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:42.928  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:42.928  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:42.928  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:42.928  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:42.928  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:42.928  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:05:42.929  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:42.930  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:42.940  3896  3896 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-13 00:05:42.943   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-13 00:05:42.949   874   883 I art     : Background partial concurrent mark sweep GC freed 48241(2MB) AllocSpace objects, 14(356KB) LOS objects, 33% free, 29MB/44MB, paused 958us total 104.168ms
09-13 00:05:42.961  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 00:05:42.962   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-13 00:05:42.963   874  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-13 00:05:42.963   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 00:05:42.968   874   891 D Tethering: MasterInitialState.processMessage what=3
09-13 00:05:42.969  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:42.970  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:42.970  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 00:05:42.972  3411  3411 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a1ff619 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-13 00:05:42.973  2053  2053 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-13 00:05:42.980   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e1bc51:true
,09-13 00:05:42.986   874  2000 I ActivityManager: Start proc 3915:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-13 00:05:42.995  3896  3896 D LocalBluetoothProfileManager: Adding local MAP profile
,09-13 00:05:42.997  3896  3896 D BluetoothMap: Create BluetoothMap proxy object
,09-13 00:05:43.002  3896  3896 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-13 00:05:43.014   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-13 00:05:43.015   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 00:05:43.015  3915  3915 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-13 00:05:43.018  3896  3896 D DockEventReceiver: finishStartingService: stopping service
,09-13 00:05:43.025   874  2028 I ActivityManager: Killing 2273:com.google.android.talk/u0a61 (adj 15): empty #17
,09-13 00:05:43.122  2696  2717 I bt_hci  : shut_down
,09-13 00:05:43.122  2696  2722 D bt_hwcfg: hw_epilog_process
,09-13 00:05:43.131  2696  2722 I bt_vendor: low_power_mode_cb
,09-13 00:05:43.153  2696  2722 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-13 00:05:43.153  2696  2722 I bt_vendor: epilog_cb
,09-13 00:05:43.153  2696  2722 I bt_hci  : epilog_finished_callback
,09-13 00:05:43.158  2696  2717 I bt_hci_h4: hal_close
09-13 00:05:43.159  2696  2717 I bt_userial_vendor: device fd = 51 close
,09-13 00:05:43.187  3915  3915 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 00:05:43.187  3915  3915 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 00:05:43.187  3915  3915 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 00:05:43.187  3915  3915 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 00:05:43.187  3915  3915 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.r.k.d(PG:583)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 00:05:43.187  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 00:05:43.188  3915  3915 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 00:05:43.188  3915  3915 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 00:05:43.188  3915  3915 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 00:05:43.188  3915  3915 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 00:05:43.219   874  1994 I ActivityManager: Start proc 3946:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
09-13 00:05:43.221   874  1994 I ActivityManager: Killing 3593:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-13 00:05:43.278  2696  2714 D bt_stack_manager: event_shut_down_stack finished.
09-13 00:05:43.279  2696  2712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 00:05:43.280  2696  2712 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 00:05:43.280  2696  2696 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 00:05:43.282  2696  2696 D BtGatt.GattService: Received stop request...Stopping profile...
,09-13 00:05:43.282  2696  2696 D BtGatt.GattService: stop()
09-13 00:05:43.282  2696  2696 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 00:05:43.286  2696  2696 V BluetoothAdapterState: isTurningOff()=false
,09-13 00:05:43.286  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-13 00:05:43.286  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:43.287  2696  2696 V BluetoothAdapterState: isBleTurningOff()=true
09-13 00:05:43.287  2696  2712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 00:05:43.287  2696  2712 D BluetoothAdapterProperties: Setting state to 10
,09-13 00:05:43.287  2696  2712 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-13 00:05:43.288  2696  2712 I BluetoothAdapterState: Entering OffState
,09-13 00:05:43.288  3946  3946 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
09-13 00:05:43.288   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-13 00:05:43.295  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 00:05:43.319  2696  2696 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 00:05:43.319  2696  2696 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 00:05:43.319  2696  2714 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 00:05:43.321  2696  2714 D bt_stack_manager: event_clean_up_stack finished.
,09-13 00:05:43.321  2696  2696 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 00:05:43.331  2696  2696 I art     : System.exit called, status: 0
,09-13 00:05:43.332  2696  2696 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 00:05:43.388   874  2152 I ActivityManager: Process com.android.bluetooth (pid 2696) has died
,09-13 00:05:43.492  3946  3965 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-13 00:05:43.492  3946  3965 I Babel_SMS: MmsConfig.loadMmsSettings
09-13 00:05:43.493  3946  3965 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-13 00:05:43.493  3946  3965 I Babel_SMS: MmsConfig.loadFromDatabase
,09-13 00:05:43.533  3946  3965 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-13 00:05:43.533  3946  3965 I Babel_SMS: MmsConfig.loadFromResources
09-13 00:05:43.534  3946  3965 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-13 00:05:43.535  3946  3965 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-13 00:05:43.598  3946  3946 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 00:05:43.602  3946  3946 I Babel_Crash: startup - clean
,09-13 00:05:43.683  3946  3946 I Babel_telephony: TeleModule.launchCompleted
,09-13 00:05:43.688   874  2008 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-13 00:05:43.696  3946  3946 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-13 00:05:43.702  3946  3946 W Babel   : BAM#gBA: invalid account id: -1
09-13 00:05:43.702  3946  3946 W Babel   : BAM#gBA: invalid account id: -1
09-13 00:05:43.702  3946  3946 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-13 00:05:43.732   874  2153 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-13 00:05:43.733  3946  3972 I Babel   : deleted: false for 0
,09-13 00:05:43.819   874   885 I ActivityManager: Start proc 3974:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-13 00:05:43.865  3946  3946 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 00:05:43.884  3974  3974 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-13 00:05:43.936  3915  3937 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-13 00:05:43.971  3946  3946 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-13 00:05:43.995  3946  3946 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 00:05:44.011  3946  3946 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 00:05:44.022  3974  3974 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-13 00:05:44.026  3946  3946 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 00:05:44.037  3946  3946 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 00:05:44.074  3946  3946 I vclib   : onServiceConnected
,09-13 00:05:44.076  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 00:05:44.122   874   885 I ActivityManager: Start proc 3999:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-13 00:05:44.126  3896  3896 D DockEventReceiver: finishStartingService: stopping service
09-13 00:05:44.129   874  1983 I ActivityManager: Killing 3411:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-13 00:05:44.138   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2037e8f:true
,09-13 00:05:44.244  3999  3999 D AdapterServiceConfig: Adding HeadsetService
,09-13 00:05:44.244  3999  3999 D AdapterServiceConfig: Adding A2dpService
,09-13 00:05:44.244  3999  3999 D AdapterServiceConfig: Adding HidService
,09-13 00:05:44.244  3999  3999 D AdapterServiceConfig: Adding HealthService
,09-13 00:05:44.244  3999  3999 D AdapterServiceConfig: Adding PanService
,09-13 00:05:44.244  3999  3999 D AdapterServiceConfig: Adding GattService
,09-13 00:05:44.245  3999  3999 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 00:05:44.247   874   884 I ActivityManager: Killing 3477:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-13 00:05:44.277  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:05:44.306  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 00:05:44.312  1717  1717 D SystemUpdateService: onCreate
,09-13 00:05:44.317  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 00:05:44.326  1717  4011 I SystemUpdateService: active receiver: enabled
,09-13 00:05:44.336  1717  4011 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 00:05:44.338  1717  4011 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 00:05:44.338  1717  4011 I SystemUpdateService: now status is 0 (complete)
,09-13 00:05:44.342  1717  4011 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-13 00:05:44.342  1717  4011 I SystemUpdateService: file has been verified
09-13 00:05:44.342  1717  4011 I SystemUpdateService: OTA package size = 12249756
09-13 00:05:44.342  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 00:05:44.344  1717  2410 I iu.UploadsManager: num queued entries: 0
,09-13 00:05:44.345  1717  2410 I iu.UploadsManager: num updated entries: 0
,09-13 00:05:44.348  1717  4011 I SystemUpdateService: showing system update notification
,09-13 00:05:44.350  1717  2410 I iu.SyncManager: NEXT; no task
,09-13 00:05:44.364  1717  1717 D SystemUpdateService: onDestroy
,09-13 00:05:44.365  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 00:05:44.367  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 00:05:44.380   874   885 I ActivityManager: Start proc 4013:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-13 00:05:44.428  4013  4013 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-13 00:05:44.431  4013  4013 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:05:44.443  4013  4013 D SprintDMHelper: simOperator: 
09-13 00:05:44.443  4013  4013 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 00:05:44.461   874  1983 I ActivityManager: Start proc 4025:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-13 00:05:44.461   874  1983 I ActivityManager: Killing 3520:android.process.acore/u0a5 (adj 15): empty #17
,09-13 00:05:44.596   874  1983 I ActivityManager: Start proc 4040:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-13 00:05:44.601  3946  4039 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-13 00:05:44.609   874  1523 I ActivityManager: Killing 3682:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-13 00:05:44.673  4040  4040 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-13 00:05:44.728  4040  4040 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 00:05:44.728  4040  4040 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 00:05:44.728  4040  4040 I GAv4    :   adb logcat -s GAv4
,09-13 00:05:44.748  4040  4040 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 00:05:44.757  4040  4040 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 00:05:44.785  4040  4057 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 00:05:44.902  4040  4040 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-13 00:05:44.940  4040  4040 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 00:05:44.956  4040  4040 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 1789-1797)
,09-13 00:05:44.956  4040  4040 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 00:05:44.967  4040  4040 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c7d9789}
,09-13 00:05:44.967  4040  4040 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 00:05:44.967  4040  4040 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 00:05:44.983  4040  4040 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-13 00:05:44.986  4040  4040 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 00:05:45.005  4040  4040 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 00:05:45.018  4040  4040 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 00:05:45.018  4040  4040 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 00:05:45.018  4040  4040 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 00:05:45.018  4040  4040 I Adreno  : Build Date                       : 10/20/15
09-13 00:05:45.018  4040  4040 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 00:05:45.018  4040  4040 I Adreno  : Local Branch                     : M14
,09-13 00:05:45.018  4040  4040 I Adreno  : Remote Branch                    : 
09-13 00:05:45.018  4040  4040 I Adreno  : Remote Branch                    : 
09-13 00:05:45.018  4040  4040 I Adreno  : Reconstruct Branch               : 
,09-13 00:05:45.086  4040  4040 I NSApplication: Starting up...
,09-13 00:05:45.109  4040  4086 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 00:05:45.116   874   884 I ActivityManager: Start proc 4091:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-13 00:05:45.118   874   884 I ActivityManager: Killing 3697:com.android.musicfx/u0a18 (adj 15): empty #17
,09-13 00:05:45.199  4091  4091 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-13 00:05:45.386   874  1991 I ActivityManager: Killing 2118:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-13 00:05:45.830   874  1994 D WifiService: setWifiEnabled: true pid=3827, uid=10000
09-13 00:05:45.831   874  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 00:05:45.843   874  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-13 00:05:45.853  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:45.854  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:45.854  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:45.854  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:45.854  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:45.854  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:45.854  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:45.854  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:45.854  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:05:45.854  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:45.855  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:05:45.859  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:45.859  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:45.859  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:45.859  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:45.859  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:45.859  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:45.859  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:45.859  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:45.859  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:05:45.859  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:45.860  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:05:45.878   874  1307 D WifiConfigStore: loaded 0 passpoint configs
,09-13 00:05:45.880   874  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 00:05:45.881   874  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 00:05:45.882   874  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 00:05:45.882   874  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-13 00:05:45.883   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 00:05:45.883   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 00:05:45.895   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-13 00:05:45.895   874  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=11.38 rxSuccessRate=17.00 delta 1000 -> 994
,09-13 00:05:45.897   373   872 D CommandListener: Setting iface cfg
,09-13 00:05:45.898   874  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-13 00:05:45.898   874  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 00:05:45.905   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 00:05:45.905   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 00:05:45.906   874  1306 D WifiNative-HAL: p2pGetDeviceAddress
09-13 00:05:45.907   874  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 00:05:45.914   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 00:05:45.972   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 00:05:45.976  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 00:05:46.398  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 00:05:46.444  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 00:05:46.445  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 00:05:46.454   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 00:05:46.469   874  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 00:05:46.470   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 00:05:46.470   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 00:05:46.496   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 00:05:46.519   373   872 D CommandListener: Setting iface cfg
,09-13 00:05:46.525   874  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,09-13 00:05:46.547   874  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-13 00:05:46.554   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 00:05:46.571   874  4114 D DhcpClient: Receive thread started
,09-13 00:05:46.653   874  1307 E native  : do suspend false
,09-13 00:05:46.671   874  1858 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 00:05:46.684   874  4114 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172688, domain null
,09-13 00:05:46.685   874  1858 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172688 seconds
,09-13 00:05:46.691   874  1858 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 00:05:46.704   874  4114 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 00:05:46.706   874  1858 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 00:05:46.710   373   872 D CommandListener: Setting iface cfg
,09-13 00:05:46.721   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 00:05:46.725   874  1858 D DhcpClient: Scheduling renewal in 86399s
,09-13 00:05:46.737   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 00:05:46.740   874  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 00:05:46.740   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 00:05:46.741   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 00:05:46.743   874  1309 D ConnectivityService: Adding iface wlan0 to network 101
,09-13 00:05:46.759   874  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 00:05:46.824   874  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 00:05:46.824   874  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-13 00:05:46.825   874  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-13 00:05:46.826   874  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-13 00:05:46.827   874  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-13 00:05:46.833   874  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 00:05:46.838   874  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-13 00:05:46.838   874  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-13 00:05:46.838   874  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-13 00:05:46.838   874  1309 D ConnectivityService:    accepting network in place of null
09-13 00:05:46.839   874  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 00:05:46.846   874  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-13 00:05:46.846   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 00:05:46.852   874  4113 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133694, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 00:05:46.870   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 00:05:46.898   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 00:05:46.903   874  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 00:05:46.903   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:05:46.905   874  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-13 00:05:46.907   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-13 00:05:46.922   874  4112 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
09-13 00:05:46.925  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:46.925  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:46.925  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:46.925  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:46.925  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:46.925  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:46.925  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:46.925  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:46.925  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:46.925  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:46.925  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:46.928  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:46.928  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:46.928  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:46.928  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:46.928  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:46.928  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:46.928  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:46.928  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:46.928  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:46.928  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:46.928  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 00:05:46.934  2053  2053 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-13 00:05:46.935  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 00:05:46.938  1717  1717 D SystemUpdateService: onCreate
,09-13 00:05:46.940  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 00:05:46.944  1717  4125 I SystemUpdateService: active receiver: enabled
,09-13 00:05:46.950  1717  4125 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 00:05:46.952  1717  4125 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 00:05:46.952  1717  4125 I SystemUpdateService: now status is 0 (complete)
,09-13 00:05:46.952  1717  4125 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 00:05:46.953  1717  4125 I SystemUpdateService: file has been verified
09-13 00:05:46.953  1717  4125 I SystemUpdateService: OTA package size = 12249756
,09-13 00:05:46.955  1717  4125 I SystemUpdateService: showing system update notification
,09-13 00:05:46.961  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 00:05:46.963  1717  2410 I iu.UploadsManager: num queued entries: 0
,09-13 00:05:46.964  1717  2410 I iu.UploadsManager: num updated entries: 0
,09-13 00:05:46.964  1717  2410 I iu.SyncManager: NEXT; no task
,09-13 00:05:46.973  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 00:05:46.974  1717  4129 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-13 00:05:46.974  1717  4129 W BaseAppContext: Using Auth Proxy for data requests.
09-13 00:05:46.974  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 00:05:46.976  1717  4129 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 00:05:46.977  1717  1717 D SystemUpdateService: onDestroy
09-13 00:05:46.977  4013  4013 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:05:46.983  4013  4013 D SprintDMHelper: simOperator: 
09-13 00:05:46.983  4013  4013 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 00:05:46.989  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 00:05:46.991  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 00:05:47.006   874  4112 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 22:05:46 GMT], X-Android-Received-Millis=[1473717947006], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473717946962]}
,09-13 00:05:47.007   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 00:05:47.007   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-13 00:05:47.008   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 00:05:47.009   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 00:05:47.029  1509  2975 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 00:05:47.030  1509  2975 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 00:05:47.030  1509  2975 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 00:05:47.030  1509  2975 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 00:05:47.048  1717  4129 E MDM     : [175] SitrepService.a: Error sending sitrep.
,09-13 00:05:47.112  3946  4131 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 00:05:47.905   874  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 00:05:47.999  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 00:05:48.060  1509  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 00:05:48.061  1509  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 00:05:48.061  1509  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 00:05:48.062  1509  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 00:05:48.107  3537  3537 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 00:05:48.107  3537  3537 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 00:05:48.107  3537  3537 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-13 00:05:48.840   874  2152 D WifiService: setWifiEnabled: false pid=3827, uid=10000
,09-13 00:05:48.840   874  2152 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 00:05:48.870   874   884 I ActivityManager: Killing 3721:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-13 00:05:48.875  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 00:05:48.882   874  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 00:05:48.882   874  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-13 00:05:48.882   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 00:05:48.883   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 00:05:48.904   874  1858 D DhcpClient: Clearing IP address
,09-13 00:05:48.904   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 00:05:48.909   373   872 D CommandListener: Setting iface cfg
,09-13 00:05:48.919  1509  4138 V NativeCrypto: Read error: ssl=0x9a9f6600: I/O error during system call, Connection timed out
,09-13 00:05:48.921  1509  4138 V NativeCrypto: SSL shutdown failed: ssl=0x9a9f6600: I/O error during system call, Broken pipe
,09-13 00:05:48.922   874  4114 D DhcpClient: Receive thread stopped
,09-13 00:05:48.927   874  1994 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-13 00:05:48.928   874  4112 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,09-13 00:05:48.929   874  4112 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-13 00:05:48.929   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
09-13 00:05:48.929   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 00:05:48.931   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 00:05:48.987   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-13 00:05:48.987   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-13 00:05:48.992   874  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-13 00:05:48.993   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 00:05:48.993   405   405 E Parcel  : Reading a NULL string not supported here.
,09-13 00:05:48.996   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 00:05:49.008   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 00:05:49.011   874  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-13 00:05:49.019  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:49.019  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:49.019  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:49.019  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:49.019  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:49.019  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:49.019  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:49.019  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:49.019  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:05:49.020  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:49.020  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:05:49.021   874  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-13 00:05:49.021  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:49.021  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:49.021  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:49.021  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:49.021  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:49.021  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:49.021  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:49.021  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:49.021  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:05:49.021  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:49.021  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:05:49.026  1897  2323 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 00:05:49.056   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 00:05:49.089   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 00:05:49.090   874  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 00:05:49.090   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:05:49.094   874   891 D Tethering: MasterInitialState.processMessage what=3
09-13 00:05:49.097  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:49.097  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:49.097  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:49.097  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:49.097  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:49.097  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:49.097  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:49.097  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:49.097  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:05:49.098  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:49.098  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:49.098  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:49.098  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:49.098  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:49.098  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:49.098  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:49.098  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:49.098  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:05:49.108  2053  2053 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-13 00:05:49.111  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 00:05:49.114  1717  1717 D SystemUpdateService: onCreate
09-13 00:05:49.116  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 00:05:49.123  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 00:05:49.128  1717  2410 I iu.UploadsManager: num queued entries: 0
,09-13 00:05:49.128  1717  2410 I iu.UploadsManager: num updated entries: 0
09-13 00:05:49.129  1717  2410 I iu.SyncManager: NEXT; no task
,09-13 00:05:49.131  1717  4150 I SystemUpdateService: active receiver: enabled
,09-13 00:05:49.133  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 00:05:49.135  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 00:05:49.137  4013  4013 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:05:49.141  4013  4013 D SprintDMHelper: simOperator: 
,09-13 00:05:49.141  4013  4013 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 00:05:49.164  1717  4150 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 00:05:49.168  3946  4154 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-13 00:05:49.169   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-13 00:05:49.171   874  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 00:05:49.171   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 00:05:49.174  1717  4150 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 00:05:49.175  1717  4150 I SystemUpdateService: now status is 0 (complete)
09-13 00:05:49.175  1717  4150 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 00:05:49.175  1717  4150 I SystemUpdateService: file has been verified
09-13 00:05:49.175  1717  4150 I SystemUpdateService: OTA package size = 12249756
,09-13 00:05:49.178  1717  4150 I SystemUpdateService: showing system update notification
,09-13 00:05:49.187  1717  1717 D SystemUpdateService: onDestroy
,09-13 00:05:51.893   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ae801c3:true
,09-13 00:05:51.893  3999  3999 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 00:05:51.899  3999  3999 I bt_bluedroid: init
,09-13 00:05:51.900  3999  4156 I BluetoothAdapterState: Entering OffState
,09-13 00:05:51.905  3999  4157 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 00:05:51.905  3999  4157 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 00:05:51.905  3999  4157 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-13 00:05:51.906  3999  4157 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 00:05:51.908  3999  3999 I bt_bluedroid: get_profile_interface socket
,09-13 00:05:51.911  3999  3999 I bt_bluedroid: get_profile_interface sdp
,09-13 00:05:51.913  3999  4160 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 00:05:51.915  3999  4010 I bt_bluedroid: config_hci_snoop_log
,09-13 00:05:51.917   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 00:05:51.917  3999  4160 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 00:05:51.926  3999  4156 D BluetoothAdapterState: Current state: OFF, message: 0
09-13 00:05:51.927  3999  4156 D BluetoothAdapterProperties: Setting state to 14
,09-13 00:05:51.927  3999  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 00:05:51.932  3999  4156 D BluetoothBondStateMachine: make
,09-13 00:05:51.938  3999  4162 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 00:05:51.944  3999  4156 I BluetoothAdapterState: Entering PendingCommandState
,09-13 00:05:51.945  3999  3999 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 00:05:51.949  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
,09-13 00:05:51.950  3999  3999 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 00:05:51.951  3999  3999 D BtGatt.GattService: Received start request. Starting profile...
09-13 00:05:51.951  3999  3999 D BtGatt.GattService: start()
09-13 00:05:51.951  3999  3999 I bt_bluedroid: get_profile_interface gatt
,09-13 00:05:51.953  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
09-13 00:05:51.953  3999  3999 D BtGatt.AdvertiseManager: advertise manager created
,09-13 00:05:51.964  3999  3999 V BluetoothAdapterState: isTurningOff()=false
,09-13 00:05:51.965  3999  3999 V BluetoothAdapterState: isTurningOn()=false
09-13 00:05:51.965  3999  3999 V BluetoothAdapterState: isBleTurningOn()=true
09-13 00:05:51.965  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 00:05:51.966  3999  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-13 00:05:51.967  3999  4156 I bt_bluedroid: enable
09-13 00:05:51.967  3999  4157 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-13 00:05:51.968  3999  4157 I bt_hci  : start_up
,09-13 00:05:51.986  3999  4157 I bt_vendor: alloc value 0xb3979189
,09-13 00:05:51.986  3999  4157 I bt_vendor: init
09-13 00:05:51.986  3999  4157 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-13 00:05:51.986  3999  4157 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 00:05:52.094  3999  4157 D bt_hci  : start_up starting async portion
,09-13 00:05:52.094  3999  4165 I bt_hci  : event_finish_startup
09-13 00:05:52.095  3999  4165 I bt_hci_h4: hal_open
09-13 00:05:52.095  3999  4165 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 00:05:52.108  3999  4165 I bt_userial_vendor: device fd = 51 open
,09-13 00:05:52.135  3999  4165 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 00:05:52.168  3999  4165 D bt_hwcfg: Chipset BCM4354A2
09-13 00:05:52.168  3999  4165 D bt_hwcfg: Target name = [BCM4354A2]
09-13 00:05:52.169  3999  4165 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 00:05:52.829  3999  4165 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-13 00:05:52.830  3999  4165 D bt_hwcfg: Settlement delay -- 100 ms
09-13 00:05:52.831  3999  4165 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 00:05:52.947  3999  4165 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-13 00:05:52.948  3999  4165 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 00:05:52.978  3999  4165 I bt_hwcfg: vendor lib fwcfg completed
,09-13 00:05:52.978  3999  4165 I bt_vendor: firmware callback
,09-13 00:05:52.978  3999  4165 I bt_hci  : firmware_config_callback
,09-13 00:05:52.992  3999  4169 I bt_btu  : btu_task pending for preload complete event
,09-13 00:05:52.992  3999  4169 I bt_btu_task: Bluetooth chip preload is complete
09-13 00:05:52.992  3999  4169 I bt_btu  : btu_task received preload complete event
,09-13 00:05:53.003  3999  4169 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 00:05:53.003  3999  4169 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-13 00:05:53.003  3999  4169 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 00:05:53.004  3999  4169 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 00:05:53.004  3999  4169 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 00:05:53.004  3999  4169 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 00:05:53.004  3999  4169 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 00:05:53.005  3999  4169 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 00:05:53.005  3999  4169 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 00:05:53.005  3999  4169 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 00:05:53.005  3999  4169 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 00:05:53.006  3999  4169 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 00:05:53.006  3999  4169 I         : BTE_InitTraceLevels -- TRC_SMP
,09-13 00:05:53.006  3999  4169 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 00:05:53.007  3999  4169 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 00:05:53.138  3999  4169 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f6d9d
,09-13 00:05:53.138  3999  4169 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f6d9d 
,09-13 00:05:53.158  3999  4160 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-13 00:05:53.160  3999  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 00:05:53.161  3999  4160 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 00:05:53.165  3999  4160 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 00:05:53.168  3999  4160 D BluetoothAdapterProperties: Scan Mode:20
,09-13 00:05:53.169  3999  4160 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 00:05:53.169  3999  4160 D bt_hci  : do_postload posting postload work item
,09-13 00:05:53.169  3999  4165 I bt_hci  : event_postload
,09-13 00:05:53.169  3999  4165 I bt_vendor: sco_config_cb
,09-13 00:05:53.169  3999  4165 I bt_hci  : sco_config_callback postload finished.
09-13 00:05:53.173  3999  4160 D bt_bte_conf: Device ID record 1 : primary
,09-13 00:05:53.173  3999  4160 D bt_bte_conf:   vendorId            = 000f
09-13 00:05:53.173  3999  4160 D bt_bte_conf:   vendorIdSource      = 0001
09-13 00:05:53.174  3999  4160 D bt_bte_conf:   product             = 1200
,09-13 00:05:53.174  3999  4160 D bt_bte_conf:   version             = 1436
,09-13 00:05:53.174  3999  4160 D bt_bte_conf:   clientExecutableURL = 
09-13 00:05:53.174  3999  4160 D bt_bte_conf:   serviceDescription  = 
09-13 00:05:53.174  3999  4160 D bt_bte_conf:   documentationURL    = 
,09-13 00:05:53.175  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:53.175  3999  4160 D bt_bte_conf: bte_load_did_conf no section named DID2.,
09-13 00:05:53.175  3999  4157 D bt_stack_manager: event_start_up_stack finished
,09-13 00:05:53.177  3999  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-13 00:05:53.178  3999  4156 D BluetoothAdapterProperties: Setting state to 15
,09-13 00:05:53.178  3999  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15,
09-13 00:05:53.179  3999  4165 I bt_vendor: low_power_mode_cb
09-13 00:05:53.179  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:53.180  3999  4156 I BluetoothAdapterState: Entering BleOnState
09-13 00:05:53.183  3999  4156 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-13 00:05:53.183  3999  4156 D BluetoothAdapterProperties: Setting state to 11
,09-13 00:05:53.183  3999  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-13 00:05:53.189  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
09-13 00:05:53.191  3999  3999 D HeadsetService: Received start request. Starting profile...
09-13 00:05:53.192  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:53.193  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:53.194  3999  3999 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 00:05:53.195  3999  3999 D HeadsetStateMachine: make
,09-13 00:05:53.204  3999  4156 I BluetoothAdapterState: Entering PendingCommandState
09-13 00:05:53.210  3999  3999 D HeadsetStateMachine: max_hf_connections = 1
09-13 00:05:53.210  3999  3999 I bt_bluedroid: get_profile_interface handsfree,
09-13 00:05:53.210  3999  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 00:05:53.210  3999  4160 E bt_btif : btif_hf_upstreams_evt: Invalid index -1,
09-13 00:05:53.215  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
,09-13 00:05:53.216  3999  3999 D A2dpService: Received start request. Starting profile...
,09-13 00:05:53.216  3999  3999 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 00:05:53.217  3999  3999 I bt_bluedroid: get_profile_interface avrcp
,09-13 00:05:53.224  3999  3999 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 00:05:53.224  3999  3999 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 00:05:53.224  3999  3999 D A2dpStateMachine: make
,09-13 00:05:53.226  3999  3999 I bt_bluedroid: get_profile_interface a2dp
,09-13 00:05:53.226  3999  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 00:05:53.227  3999  4178 D A2dpStateMachine: Enter Disconnected: -2
,09-13 00:05:53.228  3999  3999 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 00:05:53.228  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
09-13 00:05:53.229  3999  3999 D HidService: Received start request. Starting profile...
,09-13 00:05:53.230  3999  3999 I bt_bluedroid: get_profile_interface hidhost
09-13 00:05:53.230  3999  4160 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d83e5
09-13 00:05:53.230  3999  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-13 00:05:53.230  3999  3999 D HidService: setHidService(): set to: null
09-13 00:05:53.230  3896  3896 D BluetoothInputDevice: Proxy object connected
,09-13 00:05:53.230  3999  3999 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 00:05:53.231  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
09-13 00:05:53.231  3896  3896 D HidProfile: Bluetooth service connected
,09-13 00:05:53.232  3999  3999 D HealthService: Received start request. Starting profile...
,09-13 00:05:53.233  3999  3999 I bt_bluedroid: get_profile_interface health
,09-13 00:05:53.233  3999  3999 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 00:05:53.234  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
,09-13 00:05:53.235  3999  3999 D PanService: Received start request. Starting profile...
,09-13 00:05:53.235  3999  3999 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 00:05:53.235  3999  3999 I bt_bluedroid: get_profile_interface pan
09-13 00:05:53.235  3896  3896 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 00:05:53.236  3999  4160 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 00:05:53.237  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
,09-13 00:05:53.238  3896  3896 D PanProfile: Bluetooth service connected
,09-13 00:05:53.239  3999  3999 D BluetoothMapService: Received start request. Starting profile...
09-13 00:05:53.239  3999  3999 D BluetoothMapService: start()
09-13 00:05:53.239  3896  3896 D BluetoothMap: Proxy object connected
,09-13 00:05:53.240  3896  3896 D MapProfile: Bluetooth service connected
09-13 00:05:53.240  3896  3896 D BluetoothMap: getConnectedDevices()
,09-13 00:05:53.241  3999  3999 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 00:05:53.241  3896  3896 D BluetoothMap: Bluetooth is Not enabled
09-13 00:05:53.242  3999  3999 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-13 00:05:53.242  3999  3999 D BluetoothMapAppObserver: createReceiver()
,09-13 00:05:53.243  3999  3999 D BluetoothMapAppObserver: initObservers()
09-13 00:05:53.243  3999  3999 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 00:05:53.250  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:05:53.251  3999  4175 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-13 00:05:53.252  3999  3999 V BluetoothAdapterState: isTurningOff()=false
09-13 00:05:53.252  3999  3999 V BluetoothAdapterState: isTurningOn()=true
,09-13 00:05:53.252  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:53.252  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 00:05:53.253  3999  3999 V BluetoothAdapterState: isTurningOff()=false
09-13 00:05:53.253  3999  3999 V BluetoothAdapterState: isTurningOn()=true
,09-13 00:05:53.253  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:53.253  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:05:53.253  3999  3999 V BluetoothAdapterState: isTurningOff()=false
09-13 00:05:53.254  3999  3999 V BluetoothAdapterState: isTurningOn()=true
09-13 00:05:53.254  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:53.254  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:05:53.254  3999  3999 V BluetoothAdapterState: isTurningOff()=false
,09-13 00:05:53.254  3999  3999 V BluetoothAdapterState: isTurningOn()=true
,09-13 00:05:53.254  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:53.254  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 00:05:53.254  3999  3999 V BluetoothAdapterState: isTurningOff()=false
,09-13 00:05:53.254  3999  3999 V BluetoothAdapterState: isTurningOn()=true
09-13 00:05:53.254  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false,
09-13 00:05:53.254  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:05:53.254  3999  3999 V BluetoothAdapterState: isTurningOff()=false
09-13 00:05:53.254  3999  3999 V BluetoothAdapterState: isTurningOn()=true
09-13 00:05:53.255  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:53.255  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 00:05:53.255  3999  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-13 00:05:53.255  3999  4156 D BluetoothAdapterProperties: ScanMode =  20
09-13 00:05:53.255  3999  4156 D BluetoothAdapterProperties: State =  11
,09-13 00:05:53.255  3999  4156 D BluetoothAdapterProperties: Setting state to 12
,09-13 00:05:53.255  3999  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 00:05:53.256  1354  2089 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 00:05:53.256  1354  1370 D BluetoothMap: onBluetoothStateChange: up=true
09-13 00:05:53.256  3999  4160 D BluetoothAdapterProperties: Scan Mode:21
09-13 00:05:53.256  3999  4160 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 00:05:53.257  3999  4156 I BluetoothAdapterState: Entering OnState
09-13 00:05:53.259  1354  1354 D BluetoothMap: Proxy object connected
09-13 00:05:53.259  1354  1354 D MapProfile: Bluetooth service connected
09-13 00:05:53.259  1354  1354 D BluetoothMap: getConnectedDevices()
,09-13 00:05:53.259  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:53.259  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:53.259  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:53.259  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:53.259  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:53.259  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:53.259  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:53.259  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:05:53.262  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:05:53.262  1354  2089 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 00:05:53.265  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:53.265  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:53.265  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:53.265  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:53.265  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:53.265  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:53.265  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:53.265  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:05:53.266  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:05:53.267   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 00:05:53.267  1354  1354 D BluetoothA2dp: Proxy object connected
09-13 00:05:53.267  3896  3908 D BluetoothMap: onBluetoothStateChange: up=true
09-13 00:05:53.268  3999  3999 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 00:05:53.268  3896  3906 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 00:05:53.268  3999  3999 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-13 00:05:53.269  3896  3908 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 00:05:53.270  3999  3999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:05:53.270  1970  2312 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 00:05:53.271  1354  1370 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 00:05:53.271  3999  3999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:05:53.272  3999  3999 D ObexServerSockets: Succeed to create listening sockets 
,09-13 00:05:53.272  3999  3999 D ObexServerSockets0: startAccept()
,09-13 00:05:53.272  3999  3999 D ObexServerSockets0: prepareForNewConnect()
,09-13 00:05:53.273  1354  1354 D BluetoothInputDevice: Proxy object connected
09-13 00:05:53.273  3896  3906 D BluetoothPan: onBluetoothStateChange on: true
,09-13 00:05:53.273  1354  1354 D HidProfile: Bluetooth service connected
09-13 00:05:53.273   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 00:05:53.273   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 00:05:53.273   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 00:05:53.273   874   874 D BluetoothA2dp: Proxy object connected
09-13 00:05:53.273  1354  1370 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 00:05:53.275  1354  1371 D BluetoothPan: onBluetoothStateChange on: true
09-13 00:05:53.276  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 00:05:53.276  1354  1354 D PanProfile: Bluetooth service connected
09-13 00:05:53.276  3999  3999 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 00:05:53.276  3999  3999 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 00:05:53.277  3999  4184 D ObexServerSockets0: Accepting socket connection...
,09-13 00:05:53.277   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-13 00:05:53.279  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:53.280  3999  4185 D ObexServerSockets0: Accepting socket connection...
09-13 00:05:53.279  3999  3999 D BluetoothMapService: onReceive
,09-13 00:05:53.280  3999  3999 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:05:53.280  3999  3999 D BluetoothMapService: STATE_ON
09-13 00:05:53.280  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:53.281  3896  3896 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-13 00:05:53.286  3896  3896 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-13 00:05:53.293  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 00:05:53.295  3896  3896 D BluetoothA2dp: Proxy object connected
,09-13 00:05:53.299  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:05:53.302  3896  3896 D DockEventReceiver: finishStartingService: stopping service
,09-13 00:05:53.308  3896  3896 D BluetoothPbap: Proxy object connected
,09-13 00:05:53.308  1354  1354 D BluetoothPbap: Proxy object connected
,09-13 00:05:53.308  1354  1354 D PbapServerProfile: Bluetooth service connected
,09-13 00:05:53.308  3896  3896 D PbapServerProfile: Bluetooth service connected
,09-13 00:05:53.308  3999  3999 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 00:05:53.308  3999  3999 D ObexServerSockets0: prepareForNewConnect()
,09-13 00:05:53.317  3999  4190 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 00:05:53.332  3999  4194 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 00:05:53.333  3999  4194 I BtOppRfcommListener: Accept thread started.
,09-13 00:05:53.359  1354  1371 D BluetoothHeadset: Proxy object connected
,09-13 00:05:53.359  1354  1354 D HeadsetProfile: Bluetooth service connected
,09-13 00:05:53.359   874   874 D BluetoothHeadset: Proxy object connected
09-13 00:05:53.359   874   874 D BluetoothHeadset: Proxy object connected
,09-13 00:05:53.360   874   874 D BluetoothHeadset: Proxy object connected
09-13 00:05:53.360  1970  1984 D BluetoothHeadset: Proxy object connected
,09-13 00:05:53.368   874   891 D BluetoothHeadset: Proxy object connected
,09-13 00:05:53.371  1970  2136 D BluetoothHeadset: Proxy object connected
,09-13 00:05:53.373   874   891 D BluetoothHeadset: Proxy object connected
,09-13 00:05:53.374   874   891 D BluetoothHeadset: Proxy object connected
,09-13 00:05:53.389  3896  3908 D BluetoothHeadset: Proxy object connected
,09-13 00:05:53.392  3896  3896 D HeadsetProfile: Bluetooth service connected
,09-13 00:05:54.843   874  1309 D ConnectivityService: handlePromptUnvalidated 101
,09-13 00:05:54.856  3999  4156 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 00:05:54.856  3999  4156 D BluetoothAdapterProperties: Setting state to 13
09-13 00:05:54.857  3999  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 00:05:54.857  3999  4156 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 00:05:54.858  3999  4156 I BluetoothAdapterState: Entering PendingCommandState
09-13 00:05:54.861  3999  4160 D BluetoothAdapterProperties: Scan Mode:20
09-13 00:05:54.861  3999  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-13 00:05:54.865  3999  3999 D BluetoothMapService: onReceive
,09-13 00:05:54.865  3999  3999 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:54.866  3999  3999 D BluetoothMapService: STATE_TURNING_OFF
,09-13 00:05:54.866  3999  3999 D BluetoothMapService: MAP Service closeService in
,09-13 00:05:54.867  3999  3999 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 00:05:54.867  3999  3999 D ObexServerSockets0: shutdown(block = true)
09-13 00:05:54.867  3999  4184 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-13 00:05:54.869  3999  3999 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 00:05:54.869  3999  4185 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-13 00:05:54.870  3999  3999 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-13 00:05:54.870  3999  3999 I BtOppRfcommListener: stopping Accept Thread
09-13 00:05:54.876  3999  4194 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 00:05:54.870  3999  4172 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-13 00:05:54.876  3999  4194 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 00:05:54.870  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:54.876  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:54.876  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:54.876  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:54.876  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:54.876  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:54.876  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:54.876  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:54.876  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:05:54.879  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:54.879  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:05:54.883  3999  3999 D HeadsetService: Received stop request...Stopping profile...
09-13 00:05:54.884  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 00:05:54.887  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:54.887  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:54.887  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:54.887  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:54.887  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:54.887  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:54.887  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:54.887  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:54.887  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:05:54.887  1354  2089 D BluetoothHeadset: Proxy object disconnected
09-13 00:05:54.887  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:54.887   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 00:05:54.888  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:05:54.888   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 00:05:54.889  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:54.890  3896  3908 D BluetoothHeadset: Proxy object disconnected
09-13 00:05:54.890   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 00:05:54.891  1970  1981 D BluetoothHeadset: Proxy object disconnected
09-13 00:05:54.891  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:54.892  3999  3999 D A2dpService: Received stop request...Stopping profile...
09-13 00:05:54.892  3999  4178 D A2dpStateMachine: Exit Disconnected: -1
09-13 00:05:54.895   874   874 D BluetoothA2dp: Proxy object disconnected
09-13 00:05:54.897  3999  3999 D HidService: Received stop request...Stopping profile...
09-13 00:05:54.897  3999  3999 D HidService: Stopping Bluetooth HidService
09-13 00:05:54.898  3896  3896 D HeadsetProfile: Bluetooth service disconnected
09-13 00:05:54.899  1354  1354 D HeadsetProfile: Bluetooth service disconnected
09-13 00:05:54.899  1354  1354 D BluetoothA2dp: Proxy object disconnected
09-13 00:05:54.899  1354  1354 D BluetoothInputDevice: Proxy object disconnected
09-13 00:05:54.899  1354  1354 D HidProfile: Bluetooth service disconnected
09-13 00:05:54.900  3999  3999 D HealthService: Received stop request...Stopping profile...
,09-13 00:05:54.902  3999  3999 V BluetoothAdapterState: isTurningOff()=true
,09-13 00:05:54.902  3999  3999 V BluetoothAdapterState: isTurningOn()=false
,09-13 00:05:54.903  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:54.903  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:05:54.904  3896  3896 D DockEventReceiver: finishStartingService: stopping service
09-13 00:05:54.904  3999  3999 D PanService: Received stop request...Stopping profile...
09-13 00:05:54.906  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 00:05:54.906  1354  1354 D PanProfile: Bluetooth service disconnected
,09-13 00:05:54.906  3896  3896 D BluetoothA2dp: Proxy object disconnected
,09-13 00:05:54.906  3896  3896 D BluetoothInputDevice: Proxy object disconnected
,09-13 00:05:54.907  3896  3896 D HidProfile: Bluetooth service disconnected
,09-13 00:05:54.907  3999  3999 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 00:05:54.907  3999  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 00:05:54.907  3999  4169 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 00:05:54.908  3999  4169 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 00:05:54.908  3999  4169 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 00:05:54.908  3999  4160 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-13 00:05:54.909  3999  3999 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 00:05:54.909  3999  3999 V BluetoothAdapterState: isTurningOff()=true
09-13 00:05:54.909  3999  3999 V BluetoothAdapterState: isTurningOn()=false
,09-13 00:05:54.910  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:54.910  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:05:54.910  3999  3999 D BluetoothMapService: Received stop request...Stopping profile...
,09-13 00:05:54.910  3999  3999 D BluetoothMapService: stop()
,09-13 00:05:54.910  3896  3896 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 00:05:54.911  3896  3896 D PanProfile: Bluetooth service disconnected
09-13 00:05:54.911  3999  3999 D BluetoothMapAppObserver: deinitObservers()
,09-13 00:05:54.911  3999  3999 D BluetoothMapAppObserver: removeReceiver()
09-13 00:05:54.912  1354  1354 D BluetoothMap: Proxy object disconnected
09-13 00:05:54.912  1354  1354 D MapProfile: Bluetooth service disconnected
,09-13 00:05:54.912  3896  3896 D BluetoothMap: Proxy object disconnected
09-13 00:05:54.912  3896  3896 D MapProfile: Bluetooth service disconnected
,09-13 00:05:54.913  3999  4169 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 00:05:54.914  3999  4169 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 00:05:54.914  3999  4169 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 00:05:54.914  3999  4169 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 00:05:54.914  3999  4169 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 00:05:54.914  3999  4169 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 00:05:54.914  3999  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 00:05:54.916  3999  3999 V BluetoothAdapterState: isTurningOff()=true
,09-13 00:05:54.916  3999  3999 V BluetoothAdapterState: isTurningOn()=false
09-13 00:05:54.916  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:54.916  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 00:05:54.916  3999  3999 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 00:05:54.916  3999  3999 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 00:05:54.917  3999  3999 V BluetoothAdapterState: isTurningOff()=true
09-13 00:05:54.917  3999  3999 V BluetoothAdapterState: isTurningOn()=false
09-13 00:05:54.917  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:54.917  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:05:54.917  3999  3999 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-13 00:05:54.917  3999  3999 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 00:05:54.917  3999  4160 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 00:05:54.917  3999  4160 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 00:05:54.917  3999  3999 V BluetoothAdapterState: isTurningOff()=true
09-13 00:05:54.917  3999  3999 V BluetoothAdapterState: isTurningOn()=false
09-13 00:05:54.917  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 00:05:54.918  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:05:54.918  3999  3999 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 00:05:54.918  3999  3999 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 00:05:54.918  3999  3999 D BluetoothMapService: MAP Service closeService in
09-13 00:05:54.919  3999  3999 V BluetoothAdapterState: isTurningOff()=true
09-13 00:05:54.919  3999  3999 V BluetoothAdapterState: isTurningOn()=false
09-13 00:05:54.919  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:05:54.919  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 00:05:54.919  3999  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 00:05:54.919  3999  4156 D BluetoothAdapterProperties: Setting state to 15
09-13 00:05:54.919  3999  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 00:05:54.920  3999  4156 I BluetoothAdapterState: Entering BleOnState
09-13 00:05:54.919  3999  3999 D BluetoothMapService: cleanup()
09-13 00:05:54.920  3999  3999 D BluetoothMapService: MAP Service closeService in
09-13 00:05:54.920  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:05:54.920  1354  2089 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:05:54.922  1354  1371 D BluetoothMap: onBluetoothStateChange: up=false
09-13 00:05:54.923  1354  1354 D BluetoothPbap: Proxy object disconnected
09-13 00:05:54.923  1354  1354 D PbapServerProfile: Bluetooth service disconnected
09-13 00:05:54.925  1354  1370 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 00:05:54.926  3896  3896 D BluetoothPbap: Proxy object disconnected
09-13 00:05:54.926  3896  3896 D PbapServerProfile: Bluetooth service disconnected
,09-13 00:05:54.926   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:05:54.927  3896  3906 D BluetoothMap: onBluetoothStateChange: up=false
09-13 00:05:54.931  3896  3908 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 00:05:54.932  3896  3906 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 00:05:54.932  3896  3908 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 00:05:54.932  1970  2312 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:05:54.933  3896  3906 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:05:54.933  1354  2089 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 00:05:54.937  3896  3908 D BluetoothPan: onBluetoothStateChange on: false
,09-13 00:05:54.940   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false,
09-13 00:05:54.940   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 00:05:54.942   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 00:05:54.942  1354  1371 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 00:05:54.943  1354  1370 D BluetoothPan: onBluetoothStateChange on: false
,09-13 00:05:54.945  3999  4156 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 00:05:54.945  3999  4156 D BluetoothAdapterProperties: Setting state to 16
09-13 00:05:54.945  3999  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-13 00:05:54.946  3999  4156 D BluetoothAdapterProperties: onBleDisable
09-13 00:05:54.946  3999  4156 I BluetoothAdapterState: Entering PendingCommandState
,09-13 00:05:54.948  3999  4157 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-13 00:05:54.950  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:54.950  3999  4169 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 00:05:54.950  3999  4160 D BluetoothAdapterProperties: Scan Mode:20
09-13 00:05:54.950  3999  4169 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 00:05:54.952  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:54.952  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 00:05:54.953  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:54.955  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:54.956  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:05:54.957  3896  3896 D DockEventReceiver: finishStartingService: stopping service
,09-13 00:05:55.151  3999  4160 I bt_hci  : shut_down
,09-13 00:05:55.173  3999  4165 D bt_hwcfg: hw_epilog_process
,09-13 00:05:55.173  3999  4165 I bt_vendor: low_power_mode_cb
,09-13 00:05:55.196  3999  4165 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 00:05:55.196  3999  4165 I bt_vendor: epilog_cb
09-13 00:05:55.196  3999  4165 I bt_hci  : epilog_finished_callback
,09-13 00:05:55.203  3999  4160 I bt_hci_h4: hal_close
,09-13 00:05:55.205  3999  4160 I bt_userial_vendor: device fd = 51 close
,09-13 00:05:55.322  3999  4157 D bt_stack_manager: event_shut_down_stack finished.
,09-13 00:05:55.323  3999  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 00:05:55.330  3999  4156 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 00:05:55.330  3999  3999 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 00:05:55.332  3999  3999 D BtGatt.GattService: Received stop request...Stopping profile...
,09-13 00:05:55.334  3999  3999 D BtGatt.GattService: stop()
,09-13 00:05:55.334  3999  3999 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 00:05:55.342  3999  3999 V BluetoothAdapterState: isTurningOff()=false
,09-13 00:05:55.343  3999  3999 V BluetoothAdapterState: isTurningOn()=false
09-13 00:05:55.343  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 00:05:55.343  3999  3999 V BluetoothAdapterState: isBleTurningOff()=true
,09-13 00:05:55.344  3999  4156 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-13 00:05:55.345  3999  4156 D BluetoothAdapterProperties: Setting state to 10
09-13 00:05:55.345  3999  4156 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-13 00:05:55.347  3999  4156 I BluetoothAdapterState: Entering OffState
,09-13 00:05:55.349   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-13 00:05:55.380  3999  3999 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 00:05:55.380  3999  3999 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 00:05:55.381  3999  4157 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 00:05:55.390  3999  4157 D bt_stack_manager: event_clean_up_stack finished.
,09-13 00:05:55.390  3999  3999 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 00:05:55.395  3999  3999 I art     : System.exit called, status: 0
,09-13 00:05:55.395  3999  3999 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 00:05:55.439   874  1698 I ActivityManager: Process com.android.bluetooth (pid 3999) has died
,09-13 00:05:57.854  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 00:05:57.854  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:00.862  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:06:00.862  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a331ed5 added. We now have 6 listener(s)
09-13 00:06:00.863  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:06:00.868  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:06:00.869  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8e736ea added. We now have 7 listener(s)
09-13 00:06:00.869  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:00.870  3827  3877 I System.out: IsBluetoothEnabled
,09-13 00:06:00.883  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:00.936   874   891 I ActivityManager: Start proc 4204:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 00:06:01.072  4204  4204 D AdapterServiceConfig: Adding HeadsetService
,09-13 00:06:01.072  4204  4204 D AdapterServiceConfig: Adding A2dpService
,09-13 00:06:01.073  4204  4204 D AdapterServiceConfig: Adding HidService
09-13 00:06:01.074  4204  4204 D AdapterServiceConfig: Adding HealthService
,09-13 00:06:01.074  4204  4204 D AdapterServiceConfig: Adding PanService
,09-13 00:06:01.075  4204  4204 D AdapterServiceConfig: Adding GattService
,09-13 00:06:01.076  4204  4204 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 00:06:01.104   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fb66594:true
,09-13 00:06:01.104  4204  4204 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 00:06:01.117  4204  4204 I bt_bluedroid: init
,09-13 00:06:01.117  4204  4216 I BluetoothAdapterState: Entering OffState
,09-13 00:06:01.121  4204  4217 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 00:06:01.121  4204  4217 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-13 00:06:01.121  4204  4217 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 00:06:01.121  4204  4217 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 00:06:01.122  4204  4204 I bt_bluedroid: get_profile_interface socket
,09-13 00:06:01.129  4204  4220 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 00:06:01.129  4204  4204 I bt_bluedroid: get_profile_interface sdp
,09-13 00:06:01.135  4204  4220 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 00:06:01.138  4204  4215 I bt_bluedroid: config_hci_snoop_log
09-13 00:06:01.141   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 00:06:01.152  4204  4216 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 00:06:01.152  4204  4216 D BluetoothAdapterProperties: Setting state to 14
09-13 00:06:01.153  4204  4216 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 00:06:01.159  4204  4216 D BluetoothBondStateMachine: make
,09-13 00:06:01.167  4204  4221 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 00:06:01.178  4204  4216 I BluetoothAdapterState: Entering PendingCommandState
,09-13 00:06:01.181  4204  4204 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 00:06:01.192  4204  4204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
,09-13 00:06:01.194  4204  4204 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 00:06:01.196  4204  4204 D BtGatt.GattService: Received start request. Starting profile...
,09-13 00:06:01.197  4204  4204 D BtGatt.GattService: start()
,09-13 00:06:01.197  4204  4204 I bt_bluedroid: get_profile_interface gatt
,09-13 00:06:01.199  4204  4204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
09-13 00:06:01.200  4204  4204 D BtGatt.AdvertiseManager: advertise manager created
,09-13 00:06:01.212  4204  4204 V BluetoothAdapterState: isTurningOff()=false
,09-13 00:06:01.213  4204  4204 V BluetoothAdapterState: isTurningOn()=false
09-13 00:06:01.213  4204  4204 V BluetoothAdapterState: isBleTurningOn()=true
,09-13 00:06:01.213  4204  4204 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:06:01.215  4204  4216 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-13 00:06:01.216  4204  4216 I bt_bluedroid: enable
,09-13 00:06:01.216  4204  4217 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-13 00:06:01.217  4204  4217 I bt_hci  : start_up
,09-13 00:06:01.225  4204  4217 I bt_vendor: alloc value 0xb39f0189
09-13 00:06:01.225  4204  4217 I bt_vendor: init
,09-13 00:06:01.226  4204  4217 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 00:06:01.226  4204  4217 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 00:06:01.332  4204  4217 D bt_hci  : start_up starting async portion
09-13 00:06:01.333  4204  4224 I bt_hci  : event_finish_startup
,09-13 00:06:01.333  4204  4224 I bt_hci_h4: hal_open
09-13 00:06:01.334  4204  4224 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 00:06:01.343  4204  4224 I bt_userial_vendor: device fd = 51 open
,09-13 00:06:01.376  4204  4224 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 00:06:01.408  4204  4224 D bt_hwcfg: Chipset BCM4354A2
,09-13 00:06:01.408  4204  4224 D bt_hwcfg: Target name = [BCM4354A2]
09-13 00:06:01.409  4204  4224 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 00:06:02.092  4204  4224 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 00:06:02.093  4204  4224 D bt_hwcfg: Settlement delay -- 100 ms
09-13 00:06:02.094  4204  4224 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 00:06:02.211  4204  4224 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 00:06:02.212  4204  4224 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 00:06:02.241  4204  4224 I bt_hwcfg: vendor lib fwcfg completed
,09-13 00:06:02.241  4204  4224 I bt_vendor: firmware callback
,09-13 00:06:02.242  4204  4224 I bt_hci  : firmware_config_callback
,09-13 00:06:02.253  4204  4227 I bt_btu  : btu_task pending for preload complete event
,09-13 00:06:02.254  4204  4227 I bt_btu_task: Bluetooth chip preload is complete
09-13 00:06:02.254  4204  4227 I bt_btu  : btu_task received preload complete event
,09-13 00:06:02.266  4204  4227 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 00:06:02.266  4204  4227 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 00:06:02.267  4204  4227 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 00:06:02.267  4204  4227 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-13 00:06:02.267  4204  4227 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 00:06:02.268  4204  4227 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 00:06:02.268  4204  4227 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 00:06:02.268  4204  4227 I         : BTE_InitTraceLevels -- TRC_BTM
,09-13 00:06:02.268  4204  4227 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 00:06:02.269  4204  4227 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 00:06:02.269  4204  4227 I         : BTE_InitTraceLevels -- TRC_SDP
,09-13 00:06:02.269  4204  4227 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 00:06:02.269  4204  4227 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 00:06:02.270  4204  4227 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 00:06:02.270  4204  4227 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 00:06:02.406  4204  4227 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb396dd9d
,09-13 00:06:02.407  4204  4227 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb396dd9d 
,09-13 00:06:02.431  4204  4220 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 00:06:02.433  4204  4220 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 00:06:02.435  4204  4220 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 00:06:02.439  4204  4220 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 00:06:02.444  4204  4220 D BluetoothAdapterProperties: Scan Mode:20
,09-13 00:06:02.445  4204  4220 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 00:06:02.446  4204  4220 D bt_hci  : do_postload posting postload work item
,09-13 00:06:02.446  4204  4224 I bt_hci  : event_postload
09-13 00:06:02.446  4204  4224 I bt_vendor: sco_config_cb
09-13 00:06:02.446  4204  4224 I bt_hci  : sco_config_callback postload finished.
,09-13 00:06:02.450  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:02.451  4204  4224 I bt_vendor: low_power_mode_cb
,09-13 00:06:02.451  4204  4220 D bt_bte_conf: Device ID record 1 : primary
,09-13 00:06:02.452  4204  4220 D bt_bte_conf:   vendorId            = 000f
,09-13 00:06:02.452  4204  4220 D bt_bte_conf:   vendorIdSource      = 0001
09-13 00:06:02.452  4204  4220 D bt_bte_conf:   product             = 1200
09-13 00:06:02.452  4204  4220 D bt_bte_conf:   version             = 1436
,09-13 00:06:02.453  4204  4220 D bt_bte_conf:   clientExecutableURL = 
09-13 00:06:02.453  4204  4220 D bt_bte_conf:   serviceDescription  = 
09-13 00:06:02.453  4204  4220 D bt_bte_conf:   documentationURL    = 
,09-13 00:06:02.453  4204  4220 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 00:06:02.454  4204  4217 D bt_stack_manager: event_start_up_stack finished
09-13 00:06:02.454  4204  4216 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-13 00:06:02.454  4204  4216 D BluetoothAdapterProperties: Setting state to 15
09-13 00:06:02.455  4204  4216 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 00:06:02.455  4204  4216 I BluetoothAdapterState: Entering BleOnState
,09-13 00:06:02.458  4204  4216 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-13 00:06:02.458  4204  4216 D BluetoothAdapterProperties: Setting state to 11
,09-13 00:06:02.458  4204  4216 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-13 00:06:02.463  4204  4204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
09-13 00:06:02.467  4204  4204 D HeadsetService: Received start request. Starting profile...
09-13 00:06:02.467  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:02.471  4204  4204 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 00:06:02.471  4204  4204 D HeadsetStateMachine: make
,09-13 00:06:02.479  4204  4216 I BluetoothAdapterState: Entering PendingCommandState
,09-13 00:06:02.484  4204  4204 D HeadsetStateMachine: max_hf_connections = 1
,09-13 00:06:02.484  4204  4204 I bt_bluedroid: get_profile_interface handsfree
09-13 00:06:02.485  4204  4220 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 00:06:02.485  4204  4220 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-13 00:06:02.490  4204  4204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
09-13 00:06:02.491  4204  4204 D A2dpService: Received start request. Starting profile...
,09-13 00:06:02.491  4204  4204 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 00:06:02.492  4204  4204 I bt_bluedroid: get_profile_interface avrcp
,09-13 00:06:02.500  4204  4204 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 00:06:02.500  4204  4204 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 00:06:02.500  4204  4204 D A2dpStateMachine: make
,09-13 00:06:02.502  4204  4204 I bt_bluedroid: get_profile_interface a2dp
,09-13 00:06:02.503  4204  4220 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 00:06:02.506  4204  4236 D A2dpStateMachine: Enter Disconnected: -2
,09-13 00:06:02.507  4204  4204 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 00:06:02.509  4204  4204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
09-13 00:06:02.509  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:06:02.510  4204  4204 D HidService: Received start request. Starting profile...
,09-13 00:06:02.510  4204  4204 I bt_bluedroid: get_profile_interface hidhost
09-13 00:06:02.510  4204  4220 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb394f3e5
,09-13 00:06:02.510  4204  4220 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-13 00:06:02.510  4204  4204 D HidService: setHidService(): set to: null
09-13 00:06:02.511  4204  4204 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-13 00:06:02.512  4204  4204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
09-13 00:06:02.513  4204  4204 D HealthService: Received start request. Starting profile...
,09-13 00:06:02.514  4204  4204 I bt_bluedroid: get_profile_interface health
,09-13 00:06:02.515  4204  4204 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-13 00:06:02.516  4204  4204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
,09-13 00:06:02.516  4204  4204 D PanService: Received start request. Starting profile...
09-13 00:06:02.516  4204  4204 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 00:06:02.516  4204  4204 I bt_bluedroid: get_profile_interface pan
,09-13 00:06:02.517  4204  4220 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 00:06:02.520  4204  4204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
,09-13 00:06:02.521  4204  4204 D BluetoothMapService: Received start request. Starting profile...
,09-13 00:06:02.521  4204  4204 D BluetoothMapService: start()
,09-13 00:06:02.524  4204  4204 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 00:06:02.525  4204  4204 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-13 00:06:02.525  4204  4204 D BluetoothMapAppObserver: createReceiver()
,09-13 00:06:02.526  4204  4204 D BluetoothMapAppObserver: initObservers()
,09-13 00:06:02.527  4204  4204 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 00:06:02.535  4204  4204 V BluetoothAdapterState: isTurningOff()=false
,09-13 00:06:02.536  4204  4204 V BluetoothAdapterState: isTurningOn()=true
09-13 00:06:02.536  4204  4204 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:06:02.536  4204  4234 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-13 00:06:02.536  4204  4204 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:06:02.538  4204  4204 V BluetoothAdapterState: isTurningOff()=false,
09-13 00:06:02.538  4204  4204 V BluetoothAdapterState: isTurningOn()=true
09-13 00:06:02.538  4204  4204 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:06:02.538  4204  4204 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 00:06:02.538  4204  4204 V BluetoothAdapterState: isTurningOff()=false
,09-13 00:06:02.538  4204  4204 V BluetoothAdapterState: isTurningOn()=true
09-13 00:06:02.538  4204  4204 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:06:02.538  4204  4204 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 00:06:02.539  4204  4204 V BluetoothAdapterState: isTurningOff()=false
09-13 00:06:02.539  4204  4204 V BluetoothAdapterState: isTurningOn()=true
09-13 00:06:02.539  4204  4204 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 00:06:02.539  4204  4204 V BluetoothAdapterState: isBleTurningOff()=false
09-13 00:06:02.540  4204  4204 V BluetoothAdapterState: isTurningOff()=false
09-13 00:06:02.540  4204  4204 V BluetoothAdapterState: isTurningOn()=true
,09-13 00:06:02.541  4204  4204 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:06:02.541  4204  4204 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 00:06:02.541  4204  4204 V BluetoothAdapterState: isTurningOff()=false
,09-13 00:06:02.542  4204  4204 V BluetoothAdapterState: isTurningOn()=true
09-13 00:06:02.542  4204  4204 V BluetoothAdapterState: isBleTurningOn()=false
09-13 00:06:02.542  4204  4204 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 00:06:02.542  4204  4216 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 00:06:02.542  4204  4216 D BluetoothAdapterProperties: ScanMode =  20
09-13 00:06:02.542  4204  4216 D BluetoothAdapterProperties: State =  11
09-13 00:06:02.547  4204  4220 D BluetoothAdapterProperties: Scan Mode:21
09-13 00:06:02.547  4204  4220 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 00:06:02.547  4204  4216 D BluetoothAdapterProperties: Setting state to 12
09-13 00:06:02.547  4204  4216 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 00:06:02.547  1354  1371 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 00:06:02.548  1354  1370 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 00:06:02.548  4204  4216 I BluetoothAdapterState: Entering OnState
,09-13 00:06:02.550  1354  2089 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 00:06:02.551  1354  1354 D BluetoothMap: Proxy object connected
,09-13 00:06:02.551  1354  1354 D MapProfile: Bluetooth service connected
09-13 00:06:02.551  1354  1354 D BluetoothMap: getConnectedDevices(),
,09-13 00:06:02.552  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:02.552  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:02.552  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:02.552  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:06:02.552  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:02.552  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:02.552  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:02.552  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:02.553   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 00:06:02.553  3896  3908 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 00:06:02.554  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:06:02.555  1354  1354 D BluetoothA2dp: Proxy object connected
09-13 00:06:02.556  3896  3906 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 00:06:02.556  3896  3896 D BluetoothMap: Proxy object connected
,09-13 00:06:02.556  4204  4204 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 00:06:02.556  3896  3896 D MapProfile: Bluetooth service connected
09-13 00:06:02.556  3896  3896 D BluetoothMap: getConnectedDevices()
,09-13 00:06:02.556  4204  4204 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-13 00:06:02.557  3896  3908 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 00:06:02.558  4204  4204 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 00:06:02.559  3896  3906 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 00:06:02.561  4204  4204 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:06:02.562  1970  2312 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 00:06:02.562  3896  3896 D BluetoothA2dp: Proxy object connected
,09-13 00:06:02.562  4204  4204 D ObexServerSockets: Succeed to create listening sockets 
09-13 00:06:02.563  4204  4204 D ObexServerSockets0: startAccept()
09-13 00:06:02.563  4204  4204 D ObexServerSockets0: prepareForNewConnect()
09-13 00:06:02.563  3896  3908 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 00:06:02.563  1354  1370 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 00:06:02.566  3896  3906 D BluetoothPan: onBluetoothStateChange on: true
,09-13 00:06:02.566  4204  4204 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-13 00:06:02.566  4204  4204 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 00:06:02.568  3896  3896 D BluetoothInputDevice: Proxy object connected
,09-13 00:06:02.568  3896  3896 D HidProfile: Bluetooth service connected
,09-13 00:06:02.568  1354  1354 D BluetoothInputDevice: Proxy object connected
,09-13 00:06:02.568  1354  1354 D HidProfile: Bluetooth service connected
09-13 00:06:02.569   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 00:06:02.569   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 00:06:02.569   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 00:06:02.569   874   874 D BluetoothA2dp: Proxy object connected
09-13 00:06:02.570  1354  1371 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 00:06:02.570  4204  4244 D ObexServerSockets0: Accepting socket connection...
09-13 00:06:02.572  1354  1370 D BluetoothPan: onBluetoothStateChange on: true
09-13 00:06:02.572  4204  4243 D ObexServerSockets0: Accepting socket connection...
09-13 00:06:02.573  3896  3896 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 00:06:02.573  3896  3896 D PanProfile: Bluetooth service connected
09-13 00:06:02.574  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 00:06:02.574  1354  1354 D PanProfile: Bluetooth service connected
09-13 00:06:02.575   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 00:06:02.577  4204  4204 D BluetoothMapService: onReceive
09-13 00:06:02.577  4204  4204 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:02.577  4204  4204 D BluetoothMapService: STATE_ON
,09-13 00:06:02.578  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:02.583  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 00:06:02.589  3896  3896 D DockEventReceiver: finishStartingService: stopping service
,09-13 00:06:02.592  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:06:02.608  1354  1354 D BluetoothPbap: Proxy object connected
09-13 00:06:02.608  3896  3896 D BluetoothPbap: Proxy object connected
,09-13 00:06:02.608  3896  3896 D PbapServerProfile: Bluetooth service connected
09-13 00:06:02.608  1354  1354 D PbapServerProfile: Bluetooth service connected
,09-13 00:06:02.617  4204  4204 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 00:06:02.617  4204  4204 D ObexServerSockets0: prepareForNewConnect()
,09-13 00:06:02.623  4204  4248 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 00:06:02.645  4204  4252 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 00:06:02.646  4204  4252 I BtOppRfcommListener: Accept thread started.
,09-13 00:06:02.650  1354  2089 D BluetoothHeadset: Proxy object connected
,09-13 00:06:02.650  1354  1354 D HeadsetProfile: Bluetooth service connected
09-13 00:06:02.650   874   874 D BluetoothHeadset: Proxy object connected
,09-13 00:06:02.650   874   874 D BluetoothHeadset: Proxy object connected
,09-13 00:06:02.651  3896  3906 D BluetoothHeadset: Proxy object connected
09-13 00:06:02.651   874   874 D BluetoothHeadset: Proxy object connected
09-13 00:06:02.652  1970  1984 D BluetoothHeadset: Proxy object connected
09-13 00:06:02.652  3896  3896 D HeadsetProfile: Bluetooth service connected
,09-13 00:06:02.655   874   891 D BluetoothHeadset: Proxy object connected
,09-13 00:06:02.664  1970  2136 D BluetoothHeadset: Proxy object connected
,09-13 00:06:02.665  3896  3908 D BluetoothHeadset: Proxy object connected
,09-13 00:06:02.665  3896  3896 D HeadsetProfile: Bluetooth service connected
,09-13 00:06:02.670   874   891 D BluetoothHeadset: Proxy object connected
,09-13 00:06:02.670   874   891 D BluetoothHeadset: Proxy object connected
,09-13 00:06:02.907  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:02.907  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:02.907  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:02.907  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:06:02.907  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:02.907  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:02.907  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:02.907  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:02.913  3827  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:06:02.916  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:06:02.917  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29dddb added. We now have 8 listener(s)
,09-13 00:06:02.917  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:06:02.923   874  2008 D WifiService: setWifiEnabled: false pid=3827, uid=10000
,09-13 00:06:02.924   874  2008 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 00:06:02.936  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:02.937   874  1698 D WifiService: setWifiEnabled: true pid=3827, uid=10000
,09-13 00:06:02.938   874  1698 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 00:06:02.953   874  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-13 00:06:02.973  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:02.973  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:02.973  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:02.973  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:02.973  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:02.973  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:02.973  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:02.973  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:02.975  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:06:02.996   874  1307 D WifiConfigStore: loaded 0 passpoint configs
,09-13 00:06:02.999   874  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 00:06:03.001   874  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 00:06:03.003   874  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 00:06:03.004   874  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-13 00:06:03.004   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 00:06:03.005   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 00:06:03.025   874  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.23 rxSuccessRate=0.31 delta 1000 -> 1000
,09-13 00:06:03.026   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 00:06:03.028   373   872 D CommandListener: Setting iface cfg
,09-13 00:06:03.029   874  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-13 00:06:03.030   874  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 00:06:03.036   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 00:06:03.036   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 00:06:03.044   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 00:06:03.102   874  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 00:06:03.103   874  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 00:06:03.148   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 00:06:03.150  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 00:06:03.491   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-13 00:06:03.500  1883  1883 I Keyboard.Facilitator: onFinishInput()
,09-13 00:06:03.507   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 00:06:03.507   874   894 I Adreno  : Build Date                       : 10/20/15
09-13 00:06:03.507   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 00:06:03.507   874   894 I Adreno  : Local Branch                     : M14
09-13 00:06:03.507   874   894 I Adreno  : Remote Branch                    : 
09-13 00:06:03.507   874   894 I Adreno  : Remote Branch                    : 
09-13 00:06:03.507   874   894 I Adreno  : Reconstruct Branch               : 
,09-13 00:06:03.552   280  2368 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (392 us)
,09-13 00:06:03.631  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 00:06:03.678  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 00:06:03.682  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 00:06:03.684   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 00:06:03.690   874  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 00:06:03.691   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 00:06:03.691   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 00:06:03.710   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 00:06:03.716   373   872 D CommandListener: Setting iface cfg
,09-13 00:06:03.718   874  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,09-13 00:06:03.733   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 00:06:03.733   874  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-13 00:06:03.736   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 00:06:03.769   874  4261 D DhcpClient: Receive thread started
,09-13 00:06:03.853   874  1307 E native  : do suspend false
,09-13 00:06:03.873   874  1858 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 00:06:03.892   874  4261 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-13 00:06:03.893   874  1858 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-13 00:06:03.900   874  1858 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 00:06:03.914   874  4261 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 00:06:03.916   874  1858 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 00:06:03.926   373   872 D CommandListener: Setting iface cfg
,09-13 00:06:03.937   874  1858 D DhcpClient: Scheduling renewal in 86399s
,09-13 00:06:03.938   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 00:06:03.948   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 00:06:03.950   874  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 00:06:03.950   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 00:06:03.952   874  1309 D ConnectivityService: Adding iface wlan0 to network 102
09-13 00:06:03.953   874  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 00:06:03.972  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:03.972  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:03.972  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:03.972  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:03.972  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:03.972  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:03.972  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:03.972  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:03.976  3827  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:06:03.980  3827  3877 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 00:06:03.981  3827  3877 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 00:06:03.983  3827  3877 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f3839a3 Bundle[{}]
,09-13 00:06:03.984  3827  3877 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 00:06:03.984  3827  3877 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 00:06:03.985  3827  3877 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 00:06:03.985  3827  3877 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 00:06:03.986  3827  3877 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-13 00:06:03.988  3827  3877 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 00:06:03.992  3827  3877 I System.out: Running OutgoingSocketThread
,09-13 00:06:03.993  3827  4264 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 423)
09-13 00:06:03.994  3827  4264 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45218
09-13 00:06:03.994  3827  4264 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 00:06:04.005   874  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 00:06:04.005   874  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-13 00:06:04.006   874  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-13 00:06:04.007   874  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-13 00:06:04.008   874  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-13 00:06:04.018   874  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 00:06:04.023   874  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-13 00:06:04.023   874  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-13 00:06:04.023   874  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-13 00:06:04.023   874  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-13 00:06:04.023   874  1309 D ConnectivityService:    accepting network in place of null
09-13 00:06:04.024   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 00:06:04.024   874  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 00:06:04.033   874  4260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=150875, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 00:06:04.059   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 00:06:04.099   874  4259 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-13 00:06:04.100   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 00:06:04.107   874  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-13 00:06:04.107   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 00:06:04.110   874   891 D Tethering: MasterInitialState.processMessage what=3
09-13 00:06:04.113   874  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-13 00:06:04.129  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:04.129  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:04.129  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:04.129  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:04.129  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:04.129  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:04.129  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:06:04.129  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:06:04.132  2053  2053 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-13 00:06:04.142  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 00:06:04.155  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 00:06:04.166   874  4259 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 22:06:04 GMT], X-Android-Received-Millis=[1473717964164], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473717964142]}
,09-13 00:06:04.167  3827  3827 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-13 00:06:04.167  3827  3827 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 00:06:04.196   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-13 00:06:04.198   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 00:06:04.198   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-13 00:06:04.198   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 00:06:04.200  3827  3827 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f3839a3 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@5ce6078, 16908290=android.view.AbsSavedState$1@5ce6078}, android:focusedViewId=100}]}]
,09-13 00:06:04.200  3827  3827 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-13 00:06:04.200  3827  3827 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 00:06:04.201  3827  3827 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 00:06:04.207   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 00:06:04.208   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
09-13 00:06:04.212   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-13 00:06:04.212   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
09-13 00:06:04.212   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-13 00:06:04.219  1717  1717 D SystemUpdateService: onCreate
,09-13 00:06:04.226  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-13 00:06:04.230   874   883 I art     : Background partial concurrent mark sweep GC freed 52375(3MB) AllocSpace objects, 22(824KB) LOS objects, 33% free, 29MB/43MB, paused 6.478ms total 99.532ms
,09-13 00:06:04.246  1717  4273 I SystemUpdateService: active receiver: enabled
,09-13 00:06:04.252  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-13 00:06:04.254  1717  2410 I iu.UploadsManager: num queued entries: 0
09-13 00:06:04.254  1717  2410 I iu.UploadsManager: num updated entries: 0
,09-13 00:06:04.259  1717  4273 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 00:06:04.263  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 00:06:04.265  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 00:06:04.268  4013  4013 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:06:04.270  1717  4276 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-13 00:06:04.270  1717  4276 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 00:06:04.273  1717  4276 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 00:06:04.275  4013  4013 D SprintDMHelper: simOperator: 
,09-13 00:06:04.275  4013  4013 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 00:06:04.276  1717  4273 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 00:06:04.284  1717  4273 I SystemUpdateService: now status is 0 (complete)
09-13 00:06:04.285  1717  4273 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 00:06:04.285  1717  4273 I SystemUpdateService: file has been verified
,09-13 00:06:04.289  1717  4273 I SystemUpdateService: OTA package size = 12249756
,09-13 00:06:04.290  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 00:06:04.291  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 00:06:04.310  1717  2410 I iu.SyncManager: NEXT; no task
,09-13 00:06:04.319  1717  4273 I SystemUpdateService: showing system update notification
,09-13 00:06:04.351  1717  1717 D SystemUpdateService: onDestroy
,09-13 00:06:04.358  1509  2977 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 00:06:04.358  1509  2977 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 00:06:04.358  1509  2977 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 00:06:04.359  1509  2977 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 00:06:04.374  1717  4276 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-13 00:06:04.407  3946  4278 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 00:06:04.445   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 00:06:04.449   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-13 00:06:04.452   874  1333 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,09-13 00:06:04.455   874   894 I DreamManagerService: Entering dreamland.
,09-13 00:06:04.457   874   894 I PowerManagerService: Dozing...
09-13 00:06:04.459   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-13 00:06:04.513   377  1279 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-13 00:06:04.513   377  1279 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-13 00:06:04.516   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 00:06:04.521   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 00:06:04.526   874  1307 E native  : do suspend false
,09-13 00:06:04.532   874  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 00:06:04.533  1954  4285 D NfcService: Discovery configuration equal, not updating.
,09-13 00:06:04.552   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 00:06:04.557   874  1307 E native  : do suspend true
,09-13 00:06:04.646   377  1315 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-13 00:06:04.647   377  1315 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-13 00:06:04.995  3827  3877 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 424)
,09-13 00:06:04.996  3827  3877 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 424)
,09-13 00:06:05.006  3827  3877 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 429)
,09-13 00:06:05.009  3827  3877 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-13 00:06:05.009  3827  3877 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,09-13 00:06:05.017  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 00:06:05.017  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f13d351 added. We now have 2 listener(s)
,09-13 00:06:05.023  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 00:06:05.023  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:06:05.023  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:05.024  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:05.024  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@779d7b6 added. We now have 9 listener(s)
09-13 00:06:05.025  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:06:05.026  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 00:06:05.029  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:06:05.038  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:05.038  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:05.038  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:05.038  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:05.038  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:05.038  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:05.038  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:06:05.038  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:06:05.042  3827  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 00:06:05.042  3827  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:06:05.042  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:06:05.042  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc50c24 added. We now have 3 listener(s)
,09-13 00:06:05.044  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 00:06:05.044  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:06:05.044  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:05.045  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:05.045  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e71538d added. We now have 10 listener(s)
09-13 00:06:05.045  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:05.045  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:05.046  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:05.046  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 00:06:05.046  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:06:05.046  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:06:05.046  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:06:05.046  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:06:05.046  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f13d351 removed from the list
09-13 00:06:05.046  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 00:06:05.046  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@779d7b6 removed from the list
09-13 00:06:05.056  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:05.056  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 00:06:05.056  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:05.057  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:05.057  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:05.058  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:05.058  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:05.058  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:05.058  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@779d7b6 not in the list
09-13 00:06:05.058  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:06:05.059  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:05.062  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:06:05.062  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 00:06:05.062  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 00:06:05.063  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e71538d removed from the list
,09-13 00:06:05.063  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:06:05.063  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:05.063  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:05.063  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 00:06:05.063  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc50c24 removed from the list
09-13 00:06:05.064  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:05.065  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:06:05.065  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c3b942 added. We now have 2 listener(s)
09-13 00:06:05.069  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 00:06:05.070  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:06:05.070  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:05.070  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:05.070  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d42d53 added. We now have 9 listener(s)
09-13 00:06:05.071  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:05.071  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 00:06:05.075  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:06:05.082  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:05.082  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:05.082  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:05.082  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:05.082  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:05.082  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:05.082  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:06:05.082  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:06:05.085  3827  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 00:06:05.086  3827  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:06:05.086  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:06:05.086  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac9b89 added. We now have 3 listener(s)
,09-13 00:06:05.088  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 00:06:05.089  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:06:05.089  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:05.089  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:05.089  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:06:05.089  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d8278e added. We now have 10 listener(s)
,09-13 00:06:05.089  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:05.090  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:06:05.090  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:06:05.090  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 00:06:05.090  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:06:05.090  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 00:06:05.092  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:05.094  3827  3877 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 00:06:05.095  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 00:06:05.103  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 00:06:05.104  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 00:06:05.105  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 00:06:05.107   874  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-13 00:06:05.110  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 00:06:05.110  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 00:06:05.110  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 00:06:05.111  3827  3877 D BluetoothAdapter: STATE_ON
,09-13 00:06:05.115  4204  4233 D BtGatt.GattService: registerClient() - UUID=1f3ca3be-04c4-41c6-a44a-bfeb7003c31c
,09-13 00:06:05.116  4204  4220 D BtGatt.GattService: onClientRegistered() - UUID=1f3ca3be-04c4-41c6-a44a-bfeb7003c31c, clientIf=5
,09-13 00:06:05.117  3827  3838 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 00:06:05.118  4204  4215 D BtGatt.GattService: start scan with filters
,09-13 00:06:05.122  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 00:06:05.123  4204  4223 D BtGatt.ScanManager: handling starting scan
,09-13 00:06:05.123  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 00:06:05.123  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 00:06:05.123  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 00:06:05.125  4204  4223 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d36407
,09-13 00:06:05.127  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 00:06:05.128  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 00:06:05.128  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 00:06:05.130  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 00:06:05.132  4204  4220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 00:06:05.132  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 00:06:05.133  4204  4223 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 00:06:05.134  3827  3877 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 00:06:05.135  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 00:06:05.135  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 00:06:05.135  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:06:05.135  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 00:06:05.135  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 00:06:05.135  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 00:06:05.135  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 00:06:05.135  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 00:06:05.136  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 00:06:05.136  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 00:06:05.137  3827  3877 D BluetoothAdapter: STATE_ON
,09-13 00:06:05.137  4204  4215 D BtGatt.GattService: stopScan() - queue size =1
,09-13 00:06:05.138  4204  4241 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 00:06:05.139  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 00:06:05.139  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 00:06:05.139  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 00:06:05.139  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
,09-13 00:06:05.139  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 00:06:05.141  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,09-13 00:06:05.141  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 00:06:05.141  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 00:06:05.141  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 00:06:05.142  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:06:05.143  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 00:06:05.143  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:06:05.143  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 00:06:05.147  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:06:05.147  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:05.147  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:05.147  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:06:05.147  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:06:05.147  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:06:05.147  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 00:06:05.148  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c3b942 removed from the list
09-13 00:06:05.148  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 00:06:05.148  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d42d53 removed from the list
,09-13 00:06:05.148  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 00:06:05.148  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:05.148  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:05.149  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:05.150  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:05.150  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:06:05.150  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:05.150  4204  4220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 00:06:05.150  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 00:06:05.150  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d42d53 not in the list
,09-13 00:06:05.150  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:05.150  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:05.151  4204  4223 D BtGatt.ScanManager: Starting BLE batch scan
09-13 00:06:05.151  4204  4223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
09-13 00:06:05.152  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:06:05.152  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 00:06:05.152  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 00:06:05.153  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d8278e removed from the list
09-13 00:06:05.153  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,09-13 00:06:05.153  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:05.153  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:05.153  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 00:06:05.153  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac9b89 removed from the list
,09-13 00:06:05.154  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 00:06:05.154  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b32e9a added. We now have 2 listener(s)
,09-13 00:06:05.157  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 00:06:05.157  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 00:06:05.157  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 00:06:05.158  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:06:05.158  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e99f3cb added. We now have 9 listener(s)
09-13 00:06:05.158  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:05.158  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 00:06:05.161  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:06:05.163  4204  4220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 00:06:05.163  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,09-13 00:06:05.167  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:05.167  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:05.167  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:05.167  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:05.167  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:05.167  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:05.167  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:06:05.167  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:06:05.170  4204  4220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 00:06:05.170  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 00:06:05.171  3827  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 00:06:05.171  3827  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 00:06:05.173  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 00:06:05.174  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:05.174  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1f32c1 added. We now have 3 listener(s)
,09-13 00:06:05.177  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:05.178  4204  4220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 00:06:05.178  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:06:05.178  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 00:06:05.178  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 00:06:05.178  4204  4223 D BtGatt.ScanManager: stopping BLe Batch
09-13 00:06:05.179  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:05.179  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:05.179  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3059a66 added. We now have 10 listener(s)
09-13 00:06:05.179  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:06:05.179  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:06:05.180  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:06:05.180  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:06:05.180  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 00:06:05.180  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:05.180  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 00:06:05.183  3827  3877 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 00:06:05.183  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 00:06:05.187  4204  4220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 00:06:05.187  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:06:05.187  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 00:06:05.187  4204  4223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 00:06:05.188  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 00:06:05.188  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 00:06:05.192  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 00:06:05.192  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 00:06:05.192  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 00:06:05.193  3827  3877 D BluetoothAdapter: STATE_ON
09-13 00:06:05.193  4204  4220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 00:06:05.194  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 00:06:05.196  4204  4241 D BtGatt.GattService: registerClient() - UUID=3b3b0560-57cf-4b91-8283-82431b238ee4
09-13 00:06:05.196  4204  4220 D BtGatt.GattService: onClientRegistered() - UUID=3b3b0560-57cf-4b91-8283-82431b238ee4, clientIf=5
09-13 00:06:05.197  3827  3839 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 00:06:05.197  4204  4214 D BtGatt.GattService: start scan with filters
,09-13 00:06:05.202  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 00:06:05.203  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 00:06:05.203  4204  4223 D BtGatt.ScanManager: handling starting scan
,09-13 00:06:05.203  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 00:06:05.203  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 00:06:05.210  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 00:06:05.210  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 00:06:05.211  4204  4220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 00:06:05.211  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:06:05.210  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 00:06:05.212  4204  4223 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 00:06:05.216  4204  4220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 00:06:05.216  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:06:05.216  4204  4223 D BtGatt.ScanManager: Starting BLE batch scan
09-13 00:06:05.216  4204  4223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 00:06:05.217  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 00:06:05.227  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 00:06:05.227  3827  3877 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 00:06:05.228  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:06:05.228  4204  4220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 00:06:05.228  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:05.228  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 00:06:05.228  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:05.229  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:05.229  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:06:05.230  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 00:06:05.230  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:06:05.230  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b32e9a removed from the list
,09-13 00:06:05.230  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:05.231  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e99f3cb removed from the list
09-13 00:06:05.231  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 00:06:05.231  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:06:05.232  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:05.232  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-13 00:06:05.232  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:06:05.232  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:06:05.233  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:05.233  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:05.233  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 00:06:05.233  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e99f3cb not in the list
09-13 00:06:05.233  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 00:06:05.233  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 00:06:05.233  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 00:06:05.234  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 00:06:05.234  4204  4220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 00:06:05.234  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:06:05.234  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 00:06:05.234  3827  3877 D BluetoothAdapter: STATE_ON
09-13 00:06:05.235  4204  4215 D BtGatt.GattService: stopScan() - queue size =1
,09-13 00:06:05.235  4204  4241 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 00:06:05.235  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:05.235  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 00:06:05.235  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 00:06:05.236  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 00:06:05.236  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 00:06:05.237  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 00:06:05.237  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 00:06:05.237  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 00:06:05.237  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 00:06:05.237  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:05.238  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 00:06:05.239  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:06:05.239  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:06:05.239  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:05.239  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:05.239  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 00:06:05.239  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3059a66 removed from the list
09-13 00:06:05.239  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:05.239  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:05.239  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:05.239  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:06:05.239  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1f32c1 removed from the list
09-13 00:06:05.240  4204  4220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 00:06:05.240  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:06:05.240  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:06:05.240  4204  4223 D BtGatt.ScanManager: stopping BLe Batch
09-13 00:06:05.240  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c0f6f2 added. We now have 2 listener(s)
,09-13 00:06:05.242  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 00:06:05.242  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:06:05.242  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:05.242  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:05.242  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5931143 added. We now have 9 listener(s)
09-13 00:06:05.242  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:05.243  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 00:06:05.244  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:06:05.246  4204  4220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 00:06:05.246  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:06:05.247  4204  4223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 00:06:05.248  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:05.248  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:05.248  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:05.248  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:05.248  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:05.248  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:05.248  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:06:05.248  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:06:05.250  3827  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 00:06:05.250  3827  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:06:05.250  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 00:06:05.250  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f678f9 added. We now have 3 listener(s)
,09-13 00:06:05.252  4204  4220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 00:06:05.252  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:06:05.252  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 00:06:05.252  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-13 00:06:05.252  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 00:06:05.252  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:06:05.252  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@663903e added. We now have 10 listener(s)
09-13 00:06:05.253  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:05.253  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 00:06:05.253  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:06:05.253  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 00:06:05.253  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:05.253  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:05.253  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 00:06:05.255  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:05.256  3827  3877 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 00:06:05.256  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 00:06:05.259  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 00:06:05.260  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 00:06:05.260  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 00:06:05.262  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 00:06:05.262  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 00:06:05.262  3827  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 00:06:05.263  3827  3877 D BluetoothAdapter: STATE_ON
,09-13 00:06:05.264  4204  4215 D BtGatt.GattService: registerClient() - UUID=00c66d36-3cd3-410d-b829-5daa94ffe10f
09-13 00:06:05.265  4204  4220 D BtGatt.GattService: onClientRegistered() - UUID=00c66d36-3cd3-410d-b829-5daa94ffe10f, clientIf=5
,09-13 00:06:05.265  3827  3839 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 00:06:05.265  4204  4214 D BtGatt.GattService: start scan with filters
,09-13 00:06:05.268  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 00:06:05.268  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 00:06:05.268  4204  4223 D BtGatt.ScanManager: handling starting scan
09-13 00:06:05.268  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 00:06:05.268  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 00:06:05.270  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 00:06:05.270  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 00:06:05.270  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 00:06:05.272  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 00:06:05.274  4204  4220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 00:06:05.274  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 00:06:05.274  4204  4223 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 00:06:05.276  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:06:05.276  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:05.276  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:05.276  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:05.276  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:05.276  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 00:06:05.276  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 00:06:05.277  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c0f6f2 removed from the list
09-13 00:06:05.277  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:05.277  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5931143 removed from the list
09-13 00:06:05.277  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:05.277  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:06:05.277  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:05.277  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-13 00:06:05.277  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:05.277  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:06:05.278  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:05.278  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:05.278  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:05.278  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5931143 not in the list
,09-13 00:06:05.279  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 00:06:05.279  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 00:06:05.279  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 00:06:05.279  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 00:06:05.279  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 00:06:05.279  4204  4220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 00:06:05.279  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:06:05.279  4204  4223 D BtGatt.ScanManager: Starting BLE batch scan
09-13 00:06:05.279  4204  4223 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 00:06:05.279  3827  3877 D BluetoothAdapter: STATE_ON
09-13 00:06:05.280  4204  4215 D BtGatt.GattService: stopScan() - queue size =1
,09-13 00:06:05.280  4204  4241 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 00:06:05.280  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:05.280  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 00:06:05.281  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 00:06:05.281  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 00:06:05.281  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 00:06:05.282  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:06:05.282  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 00:06:05.282  3827  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 00:06:05.282  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 00:06:05.283  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:05.283  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:05.284  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 00:06:05.284  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:05.284  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:06:05.284  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@663903e removed from the list
09-13 00:06:05.284  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:06:05.284  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:06:05.284  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:06:05.284  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:05.284  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:06:05.284  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f678f9 removed from the list
09-13 00:06:05.284  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:06:05.285  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 00:06:05.285  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d04724a added. We now have 2 listener(s)
09-13 00:06:05.286  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 00:06:05.286  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:06:05.286  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:05.286  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:05.287  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f365bb added. We now have 9 listener(s)
,09-13 00:06:05.287  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:05.287  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 00:06:05.289  4204  4220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 00:06:05.289  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:06:05.289  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:06:05.293  3827  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:05.293  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:05.293  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:05.293  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:05.293  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:05.293  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:06:05.293  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:06:05.293  3827  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:06:05.294  4204  4220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 00:06:05.294  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 00:06:05.295  3827  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 00:06:05.295  3827  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 00:06:05.295  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 00:06:05.295  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d394e31 added. We now have 3 listener(s)
09-13 00:06:05.297  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 00:06:05.297  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 00:06:05.297  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:05.298  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:05.298  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:06:05.298  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21f6916 added. We now have 10 listener(s)
,09-13 00:06:05.298  3827  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:06:05.298  3827  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:06:05.298  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:05.298  3827  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:05.298  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:06:05.298  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:06:05.298  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:06:05.298  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:06:05.299  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d04724a removed from the list
,09-13 00:06:05.299  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:05.299  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f365bb removed from the list
,09-13 00:06:05.299  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:05.299  4204  4220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 00:06:05.299  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:06:05.299  3827  3877 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:05.299  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:05.299  4204  4223 D BtGatt.ScanManager: stopping BLe Batch
,09-13 00:06:05.300  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:06:05.300  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:05.301  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 00:06:05.301  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:05.301  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 00:06:05.301  3827  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f365bb not in the list
09-13 00:06:05.301  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:05.301  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:05.302  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:06:05.302  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 00:06:05.302  3827  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:05.302  3827  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21f6916 removed from the list
09-13 00:06:05.302  3827  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:05.302  3827  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:05.302  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:05.302  3827  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 00:06:05.302  3827  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d394e31 removed from the list
09-13 00:06:05.303  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 00:06:05.303  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 00:06:05.304  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 00:06:05.304  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:06:05.304  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-13 00:06:05.304  3827  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:05.305  4204  4220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 00:06:05.305  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:06:05.305  4204  4223 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 00:06:05.309  3827  4289 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: My test thread name)
,09-13 00:06:05.309  3827  4289 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: My test thread name)
09-13 00:06:05.309  3827  4289 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-13 00:06:05.310  4204  4220 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 00:06:05.310  4204  4220 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 00:06:05.311  3827  4290 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name)
09-13 00:06:05.311  3827  4290 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: My test thread name)
09-13 00:06:05.311  3827  4290 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-13 00:06:05.312  3827  3877 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-13 00:06:05.313  3827  3877 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-13 00:06:05.313  3827  3877 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-13 00:06:05.313  3827  3877 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-13 00:06:05.313  3827  3877 D com.test.thalitest.ThaliTestRunner: Total duration: 22774 ms
09-13 00:06:05.314  3827  3877 I jxcore-log: *Native tests were executed*
09-13 00:06:05.314  3827  3877 I jxcore-log: 
,09-13 00:06:05.314  3827  3877 I jxcore-log: Total number of executed tests:  80
09-13 00:06:05.314  3827  3877 I jxcore-log: 
09-13 00:06:05.315  3827  3877 I jxcore-log: Number of passed tests:  80
09-13 00:06:05.315  3827  3877 I jxcore-log: 
09-13 00:06:05.315  3827  3877 I jxcore-log: Number of failed tests:  0
09-13 00:06:05.315  3827  3877 I jxcore-log: 
09-13 00:06:05.315  3827  3877 I jxcore-log: Number of ignored tests:  0
09-13 00:06:05.315  3827  3877 I jxcore-log: 
09-13 00:06:05.315  3827  3877 I jxcore-log: Total duration:  22774
09-13 00:06:05.315  3827  3877 I jxcore-log: 
09-13 00:06:05.316  3827  3877 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 00:06:05.316  3827  3877 I jxcore-log: 
,09-13 00:06:05.318  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.318  3827  3877 I jxcore-log: 
09-13 00:06:05.321  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.321  3827  3877 I jxcore-log: 
09-13 00:06:05.322  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.322  3827  3877 I jxcore-log: 
09-13 00:06:05.323  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.323  3827  3877 I jxcore-log: 
09-13 00:06:05.323  3827  3827 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 00:06:05.324  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.324  3827  3877 I jxcore-log: 
09-13 00:06:05.325  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.325  3827  3877 I jxcore-log: 
,09-13 00:06:05.327  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.327  3827  3877 I jxcore-log: 
09-13 00:06:05.329  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:06:05.329  3827  3877 I jxcore-log: 
09-13 00:06:05.329  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:06:05.329  3827  3877 I jxcore-log: 
09-13 00:06:05.330  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 00:06:05.330  3827  3877 I jxcore-log: 
09-13 00:06:05.331  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 00:06:05.331  3827  3877 I jxcore-log: 
09-13 00:06:05.332  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 00:06:05.332  3827  3877 I jxcore-log: 
09-13 00:06:05.332  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.332  3827  3877 I jxcore-log: 
09-13 00:06:05.333  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.333  3827  3877 I jxcore-log: 
09-13 00:06:05.334  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:06:05.334  3827  3877 I jxcore-log: 
,09-13 00:06:05.334  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:06:05.334  3827  3877 I jxcore-log: 
09-13 00:06:05.335  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 00:06:05.335  3827  3877 I jxcore-log: 
,09-13 00:06:05.336  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 00:06:05.336  3827  3877 I jxcore-log: 
,09-13 00:06:05.336  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:06:05.336  3827  3877 I jxcore-log: 
09-13 00:06:05.337  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:06:05.337  3827  3877 I jxcore-log: 
09-13 00:06:05.337  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 00:06:05.337  3827  3877 I jxcore-log: 
,09-13 00:06:05.338  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 00:06:05.338  3827  3877 I jxcore-log: 
09-13 00:06:05.338  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 00:06:05.338  3827  3877 I jxcore-log: 
,09-13 00:06:05.339  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 00:06:05.339  3827  3877 I jxcore-log: 
,09-13 00:06:05.339  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.339  3827  3877 I jxcore-log: 
,09-13 00:06:05.340  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.340  3827  3877 I jxcore-log: 
09-13 00:06:05.341  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.341  3827  3877 I jxcore-log: 
,09-13 00:06:05.342  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.342  3827  3877 I jxcore-log: 
09-13 00:06:05.342  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.342  3827  3877 I jxcore-log: 
,09-13 00:06:05.343  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:05.343  3827  3877 I jxcore-log: 
,09-13 00:06:05.644  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 00:06:05.646  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 00:06:05.646  3827  3877 I jxcore-log: 
,09-13 00:06:05.739  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 00:06:05.742  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 00:06:05.742  3827  3877 I jxcore-log: 
,09-13 00:06:05.785  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 00:06:05.788  3827  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 00:06:05.788  3827  3877 I jxcore-log: 
,09-13 00:06:06.040  4291  4291 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-13 00:06:06.045  4291  4291 D AndroidRuntime: CheckJNI is OFF
,09-13 00:06:06.089  4291  4291 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-13 00:06:06.137  4291  4291 I Radio-JNI: register_android_hardware_Radio DONE
,09-13 00:06:06.159  4291  4291 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 00:06:06.170   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-13 00:06:06.170   874   887 I ActivityManager: Killing 3827:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-13 00:06:06.276   874   897 W PackageSettings: Skipping PackageSetting{85bddd8 com.example.hello/10273} due to missing metadata
,09-13 00:06:06.287   874  1991 I WindowState: WIN DEATH: Window{ed99f1b u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 00:06:06.289   874  1308 D WifiService: Client connection lost with reason: 4
,09-13 00:06:06.289   874  2028 D GraphicsStats: Buffer count: 2
,09-13 00:06:06.315   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-13 00:06:06.315   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-13 00:06:06.316   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-13 00:06:06.316   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-13 00:06:06.316   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:06.316   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:06:06.316   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 00:06:06.316   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-13 00:06:06.317   874   887 I ActivityManager:   Force finishing activity ActivityRecord{2482740 u0 com.test.thalitest/.MainActivity t4},
,09-13 00:06:06.325   874   897 I art     : Starting a blocking GC Explicit
,09-13 00:06:06.330   874  1994 W ActivityManager: Spurious death for ProcessRecord{23e714 0:com.test.thalitest/u0a0}, curProc for 3827: null
,09-13 00:06:06.366   874   897 I art     : Explicit concurrent mark sweep GC freed 27390(1673KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 684us total 40.716ms
,09-13 00:06:06.398   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-13 00:06:06.402  4291  4291 I art     : System.exit called, status: 0
,09-13 00:06:06.402  4291  4291 I AndroidRuntime: VM exiting with result code 0.
,09-13 00:06:06.406   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-13 00:06:06.440   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-13 00:06:06.447  1883  1883 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-13 00:06:06.448  4204  4204 D BluetoothMapAppObserver: onReceive
09-13 00:06:06.448  4204  4204 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-13 00:06:06.451   874  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 00:06:06.453  1897  2289 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 00:06:06.459  3668  3668 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-13 00:06:06.462  1883  4302 I Keyboard.Facilitator.DecoderInitializer: run()
,09-13 00:06:06.476  1883  4302 I Decoder : createOrResetDecoder
,09-13 00:06:06.493  1970  1970 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-13 00:06:06.496   874   884 I ActivityManager: Start proc 4305:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-13 00:06:06.508  1509  1509 I ConfigService: onCreate
,09-13 00:06:06.534  1883  4302 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-13 00:06:06.539  4305  4305 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-13 00:06:06.560   874  1699 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3827 uid 10000
,09-13 00:06:06.561  1883  1883 I Keyboard.Facilitator: onFinishInput()
,09-13 00:06:06.578   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-13 00:06:06.584  4305  4305 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-13 00:06:06.586   874  1334 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,09-13 00:06:06.586   874  1334 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
09-13 00:06:06.586   874  1334 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
09-13 00:06:06.586   874  1334 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
,09-13 00:06:06.586   874  1334 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
09-13 00:06:06.586   874  1334 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
09-13 00:06:06.586   874  1334 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
09-13 00:06:06.586   874  1334 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
,09-13 00:06:06.586   874  1334 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
09-13 00:06:06.586   874  1334 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
09-13 00:06:06.586   874  1334 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
,09-13 00:06:06.586   874  1334 W System.err: 	... 4 more
09-13 00:06:06.586   874  1334 D skia    : ------- write threw an exception
,09-13 00:06:06.593  1883  4302 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-13 00:06:06.595  1883  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-13 00:06:06.595  1883  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-13 00:06:06.598  1883  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-13 00:06:06.598  1883  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-13 00:06:06.598  1985  2083 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-13 00:06:06.599  1883  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-13 00:06:06.599  1883  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-13 00:06:06.601  1883  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-13 00:06:06.601   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-13 00:06:06.601  1883  4302 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-13 00:06:06.601  1883  4302 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-13 00:06:06.601  1883  4302 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-13 00:06:06.601  1883  4302 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-13 00:06:06.601  1883  4302 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-13 00:06:06.602   874   886 E PackageManager: Failed to write settings, restoring backup
09-13 00:06:06.602   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-13 00:06:06.602   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-13 00:06:06.602   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-13 00:06:06.602   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-13 00:06:06.602   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-13 00:06:06.602   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:06.602   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:06:06.602   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 00:06:06.606   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-13 00:06:06.606   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 00:06:06.606   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 00:06:06.606   874   887 E DropBoxManagerService: 	... 13 more
,09-13 00:06:06.615   874  2152 I ActivityManager: Start proc 4322:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-13 00:06:06.615  1985  2083 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-13 00:06:06.615  1985  2083 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1985
09-13 00:06:06.615  1985  2083 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 00:06:06.615  1985  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 00:06:06.615  1985  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 00:06:06.615  1985  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 00:06:06.615  1985  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 00:06:06.615  1985  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 00:06:06.615  1985  2083 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-13 00:06:06.615  1985  2083 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-13 00:06:06.615  1985  2083 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 00:06:06.615  1985  2083 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 00:06:06.615  1985  2083 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:06:06.615  1985  2083 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 00:06:06.618   874  4327 E DropBoxManagerService: Can't write: system_app_crash
09-13 00:06:06.618   874  4327 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-13 00:06:06.618   874  4327 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 00:06:06.618   874  4327 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 00:06:06.618   874  4327 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 00:06:06.618   874  4327 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 00:06:06.618   874  4327 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 00:06:06.618   874  4327 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 00:06:06.618   874  4327 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 00:06:06.618   874  4327 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 00:06:06.618   874  4327 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 00:06:06.618   874  4327 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 00:06:06.618   874  4327 E DropBoxManagerService: 	... 5 more
,09-13 00:06:06.618   874  2153 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 00:06:06.648  1985  2083 I Process : Sending signal. PID: 1985 SIG: 9
,09-13 00:06:06.670  4305  4336 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-13 00:06:06.671   874  2152 I ActivityManager: Start proc 4337:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-13 00:06:06.703  4337  4337 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-13 00:06:06.710  4305  4336 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:06:06.710  4305  4336 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 00:06:06.718  4305  4336 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-13 00:06:06.718  4305  4336 E AndroidRuntime: Process: android.process.acore, PID: 4305
09-13 00:06:06.718  4305  4336 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:06:06.718  4305  4336 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 00:06:06.721   874  4350 E DropBoxManagerService: Can't write: system_app_crash
09-13 00:06:06.721   874  4350 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-13 00:06:06.721   874  4350 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 00:06:06.721   874  4350 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 00:06:06.721   874  4350 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 00:06:06.721   874  4350 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerServ,ice.java:211)
09-13 00:06:06.721   874  4350 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 00:06:06.721   874  4350 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 00:06:06.721   874  4350 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 00:06:06.721   874  4350 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 00:06:06.721   874  4350 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 00:06:06.721   874  4350 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 00:06:06.721   874  4350 E DropBoxManagerService: 	... 5 more
,09-13 00:06:06.730  4305  4336 I Process : Sending signal. PID: 4305 SIG: 9
,09-13 00:06:06.745  1509  1509 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-13 00:06:06.747  1509  1509 D AndroidRuntime: Shutting down VM
,09-13 00:06:06.749  1509  1509 E AndroidRuntime: FATAL EXCEPTION: main
09-13 00:06:06.749  1509  1509 E AndroidRuntime: Process: com.google.process.gapps, PID: 1509
09-13 00:06:06.749  1509  1509 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-13 00:06:06.749  1509  1509 E AndroidRuntime: 	... 8 more
,09-13 00:06:06.754   874  4355 E DropBoxManagerService: Can't write: system_app_crash
09-13 00:06:06.754   874  4355 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-13 00:06:06.754   874  4355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 00:06:06.754   874  4355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 00:06:06.754   874  4355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 00:06:06.754   874  4355 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 00:06:06.754   874  4355 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 00:06:06.754   874  4355 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 00:06:06.754   874  4355 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 00:06:06.754   874  4355 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 00:06:06.754   874  4355 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 00:06:06.754   874  4355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 00:06:06.754   874  4355 E DropBoxManagerService: 	... 5 more
,09-13 00:06:06.756  1509  1509 I Process : Sending signal. PID: 1509 SIG: 9
,09-13 00:06:06.759   874  1983 I WindowState: WIN DEATH: Window{e510e3a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-13 00:06:06.759   874  2008 D GraphicsStats: Buffer count: 1
,09-13 00:06:06.770   874   885 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1985) has died
,09-13 00:06:06.771   874   885 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-13 00:06:06.773   874   885 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-13 00:06:06.779   278   278 E lowmemorykiller: Error writing /proc/4305/oom_score_adj; errno=22
,09-13 00:06:06.796   874   887 I ActivityManager: Start proc 4357:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 00:06:06.798   874  1308 D WifiService: Client connection lost with reason: 4
,09-13 00:06:06.803   874  2000 I ActivityManager: Process com.google.process.gapps (pid 1509) has died
,09-13 00:06:06.803   874  2000 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,09-13 00:06:06.803   874  2000 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 11000ms
,09-13 00:06:06.804   874  2000 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
,09-13 00:06:06.804   874  2000 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
09-13 00:06:06.805   278   278 E lowmemorykiller: Error writing /proc/4305/oom_score_adj; errno=22
09-13 00:06:06.807   278   278 E lowmemorykiller: Error writing /proc/4305/oom_score_adj; errno=22
09-13 00:06:06.825   874  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 15 -> obsolete
09-13 00:06:06.831  1717  1717 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-13 00:06:06.843   874  2158 I ActivityManager: Start proc 4369:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,09-13 00:06:06.859  4357  4357 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 00:06:06.859  4357  4357 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 00:06:06.859  4357  4357 D AndroidRuntime: Shutting down VM
,09-13 00:06:06.869  4357  4357 E AndroidRuntime: FATAL EXCEPTION: main
09-13 00:06:06.869  4357  4357 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4357
09-13 00:06:06.869  4357  4357 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 00:06:06.869  4357  4357 E AndroidRuntime: 	... 10 more
09-13 00:06:06.872   874  2028 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 00:06:06.872   874  4382 E DropBoxManagerService: Can't write: system_app_crash
09-13 00:06:06.872   874  4382 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-13 00:06:06.872   874  4382 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 00:06:06.872   874  4382 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 00:06:06.872   874  4382 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 00:06:06.872   874  4382 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 00:06:06.872   874  4382 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 00:06:06.872   874  4382 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 00:06:06.872   874  4382 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 00:06:06.872   874  4382 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 00:06:06.872   874  4382 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 00:06:06.872   874  4382 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 00:06:06.872   874  4382 E DropBoxManagerService: 	... 5 more
09-13 00:06:06.876  4357  4357 I Process : Sending signal. PID: 4357 SIG: 9
09-13 00:06:06.878  4369  4369 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,09-13 00:06:06.883  4369  4369 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,09-13 00:06:06.885   874  1392 I ActivityManager: Process android.process.acore (pid 4305) has died
,09-13 00:06:06.885   874  1392 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 00:06:06.886  4369  4369 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 00:06:06.886  4369  4369 D AndroidRuntime: Shutting down VM
,09-13 00:06:06.886  4369  4369 E AndroidRuntime: FATAL EXCEPTION: main
09-13 00:06:06.886  4369  4369 E AndroidRuntime: Process: com.google.process.gapps, PID: 4369
09-13 00:06:06.886  4369  4369 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.content,.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 00:06:06.886  4369  4369 E AndroidRuntime: 	... 10 more
09-13 00:06:06.889  4369  4369 I Process : Sending signal. PID: 4369 SIG: 9
09-13 00:06:06.890   874  4384 E DropBoxManagerService: Can't write: system_app_crash
09-13 00:06:06.890   874  4384 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
09-13 00:06:06.890   874  4384 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 00:06:06.890   874  4384 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 00:06:06.890   874  4384 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 00:06:06.890   874  4384 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 00:06:06.890   874  4384 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 00:06:06.890   874  4384 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 00:06:06.890   874  4384 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 00:06:06.890   874  4384 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 00:06:06.890   874  4384 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 00:06:06.890   874  4384 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 00:06:06.890   874  4384 E DropBoxManagerService: 	... 5 more
09-13 00:06:06.897  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-13 00:06:06.897  1717  1717 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded,
09-13 00:06:06.900  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-13 00:06:06.900  1717  1717 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-13 00:06:06.905   874   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4357) has died
09-13 00:06:06.906   874   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-13 00:06:06.911  1717  4386 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error

```
